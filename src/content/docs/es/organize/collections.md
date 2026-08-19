---
title: "Colecciones"
description: Conjunto de objetos agrupados a mano
---


Una colección es un contenedor de objetos seleccionados por ti: lo más parecido a una carpeta en Anytype. Tú decides lo que incluyes y esos objetos se quedan en la colección hasta que los quites. Ten en cuenta que los objetos existen aparte de las colecciones: el mismo objeto puede aparecer en varias colecciones a la vez y no desaparece al eliminarlo de una colección; solo deja de formar parte de ella.

![docs collections intro](/assets/docs-collections-intro.jpg)

## Qué significa esto

Cuando los objetos tienen una relación clara, es fácil reunirlos con una [consulta](/es/organize/queries/), como «todo lo etiquetado como inspiración». Pero si no tienen en común una [propiedad](/es/organize/properties/) o un [tipo](/es/organize/types/) que los una, es mejor usar una colección, un contenedor para objetos en los que ves una relación que el sistema no podría distinguir.

## Cuándo usar colecciones

Para entender las colecciones, lo más fácil es compararlas con las [consultas](/es/organize/queries/). En una colección mantienes un conjunto de objetos que no van a cambiar demasiado con el tiempo. En una consulta estás filtrando objetos que probablemente cambien con el tiempo.

Considera las colecciones como algo que mantienes personalmente; por ejemplo, «Favoritos de la abuela». Considera las consultas como algo que defines con reglas y filtros; por ejemplo, todo lo que etiquetes como «importante».

|Consulta                                               |Colección                                                                                         |
|-------------------------------------------------------|--------------------------------------------------------------------------------------------------|
|Todos tus archivos de medios con valoración mínima de 4|Todo lo que quieres hacer en vacaciones: libros que leer, tareas que realizar, lugares que visitar|
|Todo lo marcado con prioridad alta                     |Materiales de incorporación para nuevos compañeros: tableros, personas, documentos                |
|Todo lo etiquetado como «familia»                      |Recursos que pueden servir en un proyecto: vídeos de YouTube, PDF y notas                         |

**Las colecciones son ideales para objetos que originalmente no están conectados.** Por ejemplo, una colección llamada «Publicidad 1T» podría contener tareas, archivos de diseño, noticias, empresas y notas de reunión. La colección agrupa todos esos objetos sin necesidad de imponerles un mismo tipo o propiedades comunes para que las encuentre una consulta.

**Las consultas son ideales cuando quieres que un conjunto de objetos se actualice automáticamente.** Por ejemplo, una consulta de «todo lo que tenga fecha final de hoy» mostrará automáticamente las tareas, proyectos y eventos de la fecha en la que estés. No tendrás que seleccionar nada a mano.

## Cómo crear una colección

Encontrarás las colecciones en los mismos lugares que los [tipos](/es/organize/types/): la barra lateral, el menú Crear y los ajustes del canal. Y al igual que los tipos, las colecciones cuentan con vistas, que funcionan de la misma manera.

Para crear una colección, puedes seguir estos pasos:

1. Haz clic en el [botón desplegable Crear](/es/create/objects/#menú-crear) de la barra lateral y selecciona **Colección** (Collection).
2. Añade objetos existentes de tu espacio o crea alguno nuevo.
3. Configura **filtros** y criterios de **orden**.
4. Elige un **diseño**.

![docs collections create](/assets/docs-collections-create.jpg)

![docs collections create add](/assets/docs-collections-create-add.gif)

## Cómo usar las colecciones

Puedes ver con detalle cómo gestionar las colecciones y sus ajustes en la sección [Vistas](/es/organize/views/#cómo-funciona).

### Cómo añadir y eliminar objetos

Puedes añadir un objeto a todas las colecciones que quieras; al hacerlo, se creará un vínculo entre ellos. Los objetos permanecen en las colecciones hasta que los eliminas de ellas.

#### **Para añadir un objeto**

* Haz clic derecho en el objeto en una [vista](/es/organize/views/) o, si lo tienes abierto, haz clic en el menú de tres puntos de la esquina superior derecha.
* En el menú, selecciona **Añadir a colección** y elige entre las opciones disponibles.

![docs collections add](/assets/docs-collections-add.jpg)

#### **Para eliminar un objeto**

1. Abre la colección desde la barra lateral.
2. Haz clic derecho en el objeto y selecciona una de estas opciones:
   1. **Desvincular de la colección** lo elimina de la colección, pero el objeto sigue existiendo en tu espacio.
   2. **Mover a la papelera** elimina el objeto de todas las colecciones y del espacio, aunque lo puedes restaurar desde la papelera.

![docs collections unlink](/assets/docs-collections-unlink.jpg)

#### **Para editarlos en lote**

Usa la [función de edición en lote de las vistas](/es/organize/views/#edición-de-objetos-en-lote) para organizar a la vez muchos objetos de una colección. Puedes crear una consulta para buscar los objetos y luego añadirlos todos a una colección.

#### Para establecer el tipo por defecto

Puedes elegir el [tipo](/es/organize/types/) y la [plantilla](/es/organize/templates/) que se usarán por defecto al crear un objeto nuevo en una colección. Con la colección abierta, haz clic en el botón desplegable que hay junto a «Nuevo» y selecciona los que quieras.

### Colecciones insertadas

Puedes insertar colecciones directamente en las páginas con el bloque **Colección insertada**. Así podrás ver los objetos junto con tu contenido.

1. Mientras editas una página, abre el menú de comandos con el botón `+` o escribe `/colección`:
2. Selecciona **Colección insertada**.
3. Crea una colección o inserta una existente.

![docs collections inline](/assets/docs-collections-inline.jpg)

#### Modificación de las colecciones insertadas

Las modificaciones que hagas en las vistas de una colección insertada solo se aplican a ese bloque y no afectan a la vista principal, que se mantiene sin cambios en el [tipo](/es/organize/types/), la [consulta](/es/organize/queries/) o la [colección](/es/organize/collections/) original. Esto significa que cada objeto puede tener su propia versión de la vista insertada sin modificar nunca la original.

Por el contrario, si modificas los objetos y sus propiedades en la vista insertada, esos cambios **sí** se aplicarán al objeto y se reflejarán allá donde aparezca en todo ese espacio.

### Widget con aspecto de carpeta

Las colecciones se pueden [añadir a la barra lateral](/es/organize/views/#vistas-en-la-barra-lateral) en forma de widgets, igual que cualquier vista. Sin embargo, en lugar de usar colecciones para simular la [estructura jerárquica de carpetas en la barra lateral](/es/basics/sidebar/widgets/#opciones-de-diseño), puedes crear una página con bloques de enlace:

1. Crea un objeto con formato de página.
2. En el editor, añade bloques de enlace a los objetos que quieras con `/enlace` o `@`. Puedes enlazar objetos, tipos, consultas y colecciones.
3. Organiza los bloques en la página de forma que representen tu jerarquía.
4. Ancla el objeto en la barra lateral.
5. Haz clic derecho en el widget y selecciona «Estructura jerárquica» en la configuración de la vista.
6. Para expandir cada nivel, haz clic en la flecha desplegable que aparece junto al icono.

![docs collections widget folder like](/assets/docs-collections-widget-folder-like.jpg)

### Cargar archivos desde el ordenador

Puedes arrastrar una carpeta de tu ordenador y soltarla en una colección de Anytype. Al hacerlo, se cargarán todos los archivos de la carpeta y formarán parte de esa colección. Es una buena forma de llevar a tu espacio un conjunto de archivos de tu disco, como una colección de fotos, la carpeta de un proyecto o tu biblioteca de música.

1. Selecciona y arrastra una carpeta de tu ordenador.
2. Suéltala en una colección abierta.

![docs collections drag folder](/assets/docs-collections-drag-folder.gif)

## Cómo eliminar colecciones

Al igual que las vistas, las colecciones son independientes de los objetos que organizan. Eliminar una colección no afecta a los objetos subyacentes: puedes eliminar cualquier colección de tu espacio sin perder ningún dato. Para eliminar una colección, ve a la sección «Colecciones» de la barra lateral. Desde ahí puedes eliminarla como cualquier objeto:

* Haz clic derecho en la colección para abrir el menú y selecciona «Mover a la papelera».
* Abre la colección, haz clic en el menú de tres puntos de la esquina superior derecha y selecciona «Mover a la papelera».

## Notas

:::note
**Las colecciones son una forma rápida y sencilla de organizar los objetos.** Aunque las consultas son mejores para mantener la organización a largo plazo, las colecciones requieren menos reflexión y planificación. Crea tantas cuantas quieras, ya que eliminarlas no afecta a los objetos que contienen.
:::

:::note
**Ancla colecciones de proyectos a tu barra lateral.** Una colección anclada sirve como panel del proyecto: con un solo clic, ves todo lo relacionado.
:::