![Lumetrio](./images/readme/Portada.png)
<h1 align="center">Práctico 7: Stash y Pop </a></h1>

Estudiante: Federico Gutierrez

<h2 align="center">📖 Documentación</h2>
Para terminar de entender todo lo que vimos de stash y pop lo mejor será que lo pongas en práctica.

Empezá por dejar limpio tu repositorio local. Con eso me refiero a hacer un commit con todos los cambios que tengas. Si estás en medio de una funcionalidad terminala, y luego volvé a esta parte.

Una vez que tengas el repositorio limio, modifica un archivo y guardalo.

Ahora, si intentas hacer un checkout a un commit anterior vas a ver que te salta un error:

<p style="color:red"> error: Your local changes to the following files would be overwritten by checkout: countries.php Please commit your changes or stash them before you switch branches Aborting </p>

Este error te esta diciendo que tenés cambios sin "commitear" en el archivo "countries.php" y que debes hacer un commit o un stash antes de realmente hacer el checkout.

Si ejecutas el comando
<p style="color:orange"> git stash </p>

y uff... todo volvió a la normalidad.

Luego de un stash podés hacer todos los checkouts que quieras, y cuando precises volver a lo que estabas haciendo, volvés al commit y la branch en la que estabas antes de comenzar con tus viajes y ejecutas el pop. Y listo, aquí no pasó nada.