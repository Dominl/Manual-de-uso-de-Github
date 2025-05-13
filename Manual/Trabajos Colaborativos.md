# Trabajos Colaborativos  
Para comenzar un trabajo colaborativo en GitHub primero se debe crear un repositorio y añadir a tus colaboradores. 
Se procede a clonar el repositorio en nuestro escritorio local 
<pre>  
<code class="language-bash">
$ cd desktop
#Clonación de repositorio 
$ git clone https://github.com/Dominl/Manual-de-uso-de-Github.git 
</code>  
</pre>
Se crea una rama para poder usar el Pull Requests
<pre>  
<code class="language-bash">
$ git checkout Dhalia
</code>  
</pre>
Ingresamos a nuestro repositorio para comenzar a realizar los cambios
<pre>  
<code class="language-bash">
$ cd 'Manual-de-uso-de-Github'
</code>  
</pre>
Es importante preparar los cambios del directorio y especificar las actualizaciones que se harán seguimiento con **git add  "archivo "** para preparar multiples archivos **git add .**.
Con **git log** se puede visualizar el historial de las confirmaciones realizadas en el repositorio.
Finalmente con **git commit -m "mensaje" se guarda los cambios programados  y se crea una nueva instancia.
Estos pasos son importantes para visualizar y acceder al historial de versiones de nuestro repositorio.

Para subir los cambios a GitHub usamos un push
<pre>  
<code class="language-bash">
$ git push origin Dhalia
</code>  
</pre>
> Nota: Es importante tener en cuenta, como se está realizando un trabajo colaborativo se debe ir actualizando la rama ante los posibles cambios realizados por el resto de colaboradores. Se debe cambiar la rama a principal **git checkout main** y actualizar **git pull origin main**

Antes de contribuir a nuestro al repositorio, nuestros cambios deben pasar por un Pull Requests.
## ¿Qué es un Pull Requests?
Cualquiera con acceso a la escritura de un repositorio, o que sea colaborador del mismo, puede usar un pull requests. Para acceder a esta acción es necesario crear una rama diferente del **main**.
> Nota: En caso de no contar con el acceso a la escritura o no ser colaborador, se puede crear un fork para trabajar con una "copia" del repositorio.

Pull request es una solicitud para que los cambios realizados del repositorio desde una rama nueva sean integrados a la rama principal. El hecho de que se tenga que pasar por una revisión garantiza que el repositorio contenga en trabajo final.
#### Creación de un Pull requests
1. Una vez que se suben los cambios a nuestra rama en Github, ubicamos la pestaña "Pull requests".
2. Seleccionar nuevo pull requests, se selecciona las ramas (main, mi-rama)  donde se compararan las modificaciones y creamos una pull requests.
3. Llegado a este paso podremos visualizar en la pestañas superiores: los archivos modificados, los commits realizados en el git, los chequest y la conversación.
4. Cuando se halla revisado los cambios nuevos y de no haber **conflictos** procedemos a fusionar las ramas en **mergen pull request**. 
5. Confirmar la fusión y por ultimo eliminamos la rama.
> Nota: Para prevenir conflictos lo mas adecuado es actualizar el repositorio con su última versión, **git pull origin main**.
#### Fusión de Ramas
Cuando fusionamos nuestra ramas se esta llevando todos los cambios realizados y historial a la rama principal (main)
![Fusión de ramas](https://github.com/Dominl/Manual-de-uso-de-Github/blob/main/Manual/Imagenes/fusionramas.png) 

Estas solicitudes facilidad colaboración y revisión de un condigo, permitiendo que todos los colaboradores revisen los cambios y se aprueben los que irán al repositorio final.
## ¿Qué es un Fork?
Cuando se quiere trabajar libremente o contribuir con el repositorio de otra persona, pero no estamos dentro de su circulo de colaboradores, se puede hacer uso de un fork, que consta de crear una "copia" del contenido original del repositorio.
> :eyes: Tener en cuenta: La visibilidad de los fork dependerá si el repositorio es publico, privado o de alguna organización.


Los cambios que realizados en el fork no afectaran al original. Si se quiere que los cambios que realizamos en el fork se visualicen en el repositorio original, se debe solicitar un pull requests.

### ¿Se realizaron cambios en el repositorio original?

Se debe abrir el fork del repositorio e ir a :arrows_counterclockwise: syn fork, se dará la opción de comparas los cambios que se realizaron, se realiza la sincronización que traerá los cambios del repositorio original a mi fork.

