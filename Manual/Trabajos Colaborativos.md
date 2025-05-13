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
