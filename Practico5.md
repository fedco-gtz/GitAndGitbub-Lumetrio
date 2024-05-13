![Lumetrio](./images/readme/Portada.png)
<h1 align="center">Práctico 5: Creando una nueva branch </a></h1>

Estudiante: Federico Gutierrez

<h2 align="center">📖 Documentación</h2>
Las branches siempre se crean a imagen y semejanza del commit en el que te encontrás actualmente. 
Por lo tanto, si queremos crear una branch a partir del estado actual del código podemos hacerlo simplemente ejecutando.

  <p style="color:orange"> git checkout -b nueva_branch </p>


Pero si queremos ir a un commit anterior y comenzar a programar algo a partir de ese momento en el código podemos hacer un checkout al commit correspondiente, y luego iniciar la branch nueva:

 <p style="color:orange"> git checkout identificador </p>
 <p style="color:orange"> git checkout -b nueva_branch </p>

<h2 align="center">🛠️ Agreguemos commits</h2>
Modifica el código en tu nueva branch y comenzá a hacer algunos commits para que se diferencie de la branch principal. No importa si haces modificaciones simples, simplemente hacelo para luego hacer un merge.

Recordá que para hacer un merge tendrás que "pararte" en la branch a la cual querés agregarle el código de la branch nueva, por lo que tendrías que hacer un checkout a la rama master. El comando es el mismo que usabamos para viajar entre commits, pero ahora escribimos el nombre de la branch en vez que el identificador del commit:

 <p style="color:orange"> git checkout master </p>

Las branches principales de los proyectos normalmente se llaman master o main.
Una vez que estás en la branch a la que le queres agregar el código modificado podemos hacer el merge.

 <p style="color:orange"> git merge nombre_de_la_branch </p>
 
Y si todo sale bien, nuestro merge habrá quedado pronto :)

<h2 align="center">🤔 ¿Qué hacer si hay un conflicto? 🤔</h2>
Primero que nada respirá hondo. No desesperes.

Muchas veces los conflictos son largos y complejos de resolver, por lo que es normal que te lleve un rato solucionarlos.

Seguí estos simples pasos para no entrar en pánico
1. Leé la lista de archivos que tuvieron conflicto (git le pondrá un CONFLICT al lado)
2. Dentro de cada archivo puede haber uno o varios conflictos, identificalos y empezá a resolverlos de a uno
3. Si sos el único programador que modificó el código hace memoria y pensá por qué hicisite el cambio en cuestión
4. Si no sos el único programador que trabajó en el conflicto, comunicate con él para resolverlo juntos, a menos que tengas muy muy claro lo que quiso hacer
5. Decidí cuales lineas de código deberían quedarse y cuales irse para que tu programa siga funcionando
6. Repetí para todos los conflictos que hayan
7. Testeá todo. Con énfasis particular en el las funcionalidades afectadas
8. Tomáte un café como recompensa por el buen trabajo