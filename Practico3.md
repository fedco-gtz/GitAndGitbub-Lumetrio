![Lumetrio](./images/readme/Portada.png)
<h1 align="center">Práctico 3: Subir solo un archivo y usar git add.</a></h1>

Estudiante: Federico Gutierrez

<h2 align="center">📖 Documentación</h2>
<h3>¡Ahora hazlo vos mismo!</h3>

Empecemos por agregar todos los archivos modificados de nuestro proyecto. Para eso ya sabemos que podemos utilizar el comando: <p style="color:orange"> git add . </p>

Normalmente a los primeros commits de los proyectos se les pone el mensaje "Initial commit", así que hagamoslo. <p style="color:orange"> git commit -m "initial commit" </p>

Y listo! Ya tenemos nuestro primer commit. Peeeero... esto es solo en nuestro repositorio local! Si vamos a nuestro repositorio en github veremos que todo sigue igual.
Para subirlo tendremos que hacer un push.

<p style="color:orange"> git push </p>

Y probablemente te de un error! No desesperes. El primer push que hacemos nos pedirá que definamos cual es el remoto al que queremos subir el contenido, por eso debemos indicarle origin, y además la branch que será master. No sabés que es una branch aún, pero cuando termines este curso te prometo que entenderás todo lo que dice este comando:
<p style="color:orange"> git push -u origin master </p>

Ahora sí. Todo se subió correctamente. Actualizamos nuestro github y vemos que ahora está nuestro código! De ahora en más si querés hacer un push de más commits alcanza con que hagas

<p style="color:orange"> git push </p>

<h2 align="center">🛠️ Commiteá algo</h2>
Ahora es hora de que practiques. Te recomendamos que pruebes distintas cosas para entender como funcionan los commits, y si usas Visual Studio que estés atento a los distintos colores que toman los archivos. 

Por ejemplo, podés probar:

1. ¿Qué pasa si modifico un archivo y luego revierto los cambios que hice?
2. ¿Qué pasa si agrego una imagen?
3. ¿Qué pasa si elimino un archivo?
4. ¿Qué pasa si creo un archivo nuevo en mi proyecto?

Hace algunos commits y subilos, así en los proximos videos del curso tenés commits con los que practicar.