# Eliminación

En Anytype, todo existe como objeto independiente: una misma imagen puede aparecer muchas veces en distintos documentos. Por esta razón, todo debe eliminarse por separado y de forma expresa. No existen carpetas que puedas borrar junto con todo su contenido.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Deletion System.jpg" alt=""/><figcaption></figcaption></figure></div>

## Cómo funciona

En Anytype, debes elegir expresamente lo que quieres eliminar en cada momento. Aquí tienes una descripción general del funcionamiento de la eliminación en Anytype.

<table><thead><tr><th width="190.3125">Acción</th><th>Tradicional</th><th>Anytype</th></tr></thead><tbody><tr><td><strong>Eliminar un bloque</strong></td><td>Las páginas tienen una ubicación; si eliminas el bloque en el que se ubica la página, se elimina toda la página.</td><td>Los bloques representan un enlace a un objeto; si eliminas un bloque, el objeto al que enlaza sigue existiendo.</td></tr><tr><td><strong>Eliminar una carpeta</strong></td><td>Todo el contenido de la carpeta se elimina junto con ella. Es posible eliminar sin querer elementos importantes difíciles de ver en una gran carpeta.</td><td>En Anytype no hay carpetas. Si eliminas un <a href="types.md">tipo</a>, se te preguntará si también quieres eliminar todos los objetos de ese tipo.</td></tr><tr><td><strong>Eliminar una base de datos</strong></td><td>Las bases de datos contienen todas sus entradas; si eliminas una base de datos, las entradas desaparecen con ella.</td><td>Las «bases de datos» de Anytype (tipos, consultas y colecciones) no contienen los objetos. Puedes eliminarlas y conservar todos los objetos.</td></tr></tbody></table>

Esta existencia independiente de los objetos de Anytype puede complicar un poco su eliminación. La función [Limpieza](deletion.md#limpieza) te ayuda a evitar la acumulación de objetos superfluos con el tiempo.

## Papelera

Los objetos eliminados se trasladan a la papelera, lo que también se puede llamar «archivarlos». De esta forma, tienes la oportunidad de restaurar el objeto en tu espacio si cambias de idea. Los objetos de la papelera se quedan allí para siempre hasta que los elimines de forma definitiva. Puedes abrir la papelera des de dos lugares:

* **Ajustes del canal** > Preferencias > Papelera
* **Barra lateral** > Gestionar secciones > Papelera

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Bin Intro.jpg" alt=""/><figcaption></figcaption></figure></div>

#### Selección

* **Seleccionar**: haz clic en la casilla a la izquierda del nombre del objeto.
* **Seleccionar todo**: haz clic en la casilla situada a la izquierda de la cabecera, junto a «Nombre».

Con uno o varios objetos seleccionados, puedes elegir entre eliminarlos definitivamente o restaurarlos.

#### Eliminar definitivamente

Al eliminar un objeto de la papelera, este desaparece para siempre y no se puede recuperar. Cada vez que lo hagas, se te pedirá confirmación.

#### Restaurar

Al restaurar un objeto desde la papelera, el objeto vuelve a tu espacio. Conservará todos los enlaces y ajustes que tuviera, incluidos los tipos, propiedades y plantillas.

#### Buscar y ordenar

Puedes buscar objetos por su nombre en la papelera y ordenarlos por fecha de eliminación. Por si algún objeto carece de fecha de eliminación, procura desplazarte hasta el principio o final de la lista para encontrar lo que buscas.

## Limpieza

La sección «Limpieza» te sugiere objetos que podrías eliminar para despejar tu espacio. Los objetos de esta lista **no están en la papelera**: siguen presentes en tu espacio como cualquier otro objeto que no hayas eliminado. Se trata solo de sugerencias. Encontrarás la sección «Limpieza» junto con la papelera en dos lugares:

* **Ajustes del canal** > Preferencias > Papelera > Limpieza
* **Barra lateral** > Gestionar secciones > Papelera > Limpieza

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Bin Cleanup.jpg" alt=""/><figcaption></figcaption></figure></div>

### Qué significa esto

Por la forma en que funcionan muchas aplicaciones, los usuarios suelen esperar que todo lo que se elimine se traslade a la papelera. Esto no ocurre siempre en Anytype, que es un sistema basado en objetos. Por eso, tu espacio puede acabar cargado de archivos sin eliminar que ya no sirven para nada. Esta sección te ayuda a mantener limpio tu espacio.

### Cómo funciona

Imagina que estás escribiendo un informe. Le añades tres imágenes, pero luego quitas una porque no encaja en el borrador final. Las tres imágenes siguen existiendo en tu espacio, ya que cada una es un objeto independiente, pero la imagen que quitaste del informe ya no es necesaria; solo es un residuo de tu proceso de edición que se ha quedado en tu espacio. Con el tiempo, estos residuos se acumulan y tu espacio acaba lleno de archivos que ya no tienen utilidad alguna.

Anytype lleva la cuenta de estas «eliminaciones sugeridas» y las muestra en la sección «Limpieza» para que las revises. Desde ahí, puedes descartar la sugerencia o eliminar el objeto de forma definitiva. Aparecen dos clases de objetos:

#### Creado en

Los objetos que se crean dentro de otro «objeto contenedor» y no tienen enlaces con ningún otro elemento aparecen aquí cuando se elimina el objeto contenedor. Por ejemplo:

1. Creas un «Proyecto A».
2. Mientras estás en la página del proyecto A, usas el comando `/página` para crear un objeto llamado «Tarea X».
3. Eliminas el proyecto A, por lo que la tarea X se queda huérfana: ya no está vinculada a nada.
4. Ahora, la tarea X aparecerá como sugerencia en la sección «Limpieza».

_Nota: Si la tarea X está vinculada a otro objeto, como un proyecto B, no aparecerá en Limpieza._

#### Enlace eliminado de

Los objetos que se crean dentro de otro «objeto contenedor» y no tienen enlaces con ningún otro elemento aparecen aquí cuando se elimina el bloque de enlace del objeto contenedor. Por ejemplo:

1. Creas un «Plan de vacaciones».
2. Mientras estás en la página del plan de vacaciones, arrastras y sueltas el PDF de tu tarjeta de embarque para el día 30 de agosto.
3. Te retrasan el vuelo, así que eliminas ese PDF y añades otro con la tarjeta de embarque del 1 de septiembre.
4. Ahora, el PDF del billete antiguo está huérfano (no tiene más vínculos).
5. El PDF del vuelo del 30 de agosto aparecerá como sugerencia en la sección «Limpieza».

_Nota: Esto se aplica a todo tipo de objetos, como documentos, tareas, imágenes y vídeos._

## Notas

{% hint style="info" %}
**Usa «eliminar definitivamente» con precaución**. Es imposible recuperar los objetos que hayas eliminado también de la papelera. Hazlo solo cuando tengas claro que no volverás a necesitarlos.
{% endhint %}

{% hint style="info" %}
**La papelera puede contener también tipos, propiedades, plantillas, etc.**, no solo documentos y archivos.
{% endhint %}
