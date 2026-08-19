---
description: Conjunto de objetos agrupados a mano
---

# Colecciones

Una colección es un contenedor de objetos seleccionados por ti: lo más parecido a una carpeta en Anytype. Tú decides lo que incluyes y esos objetos se quedan en la colección hasta que los quites. Ten en cuenta que los objetos existen aparte de las colecciones: el mismo objeto puede aparecer en varias colecciones a la vez y no desaparece al eliminarlo de una colección; solo deja de formar parte de ella.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Collections Intro.jpg" alt=""/><figcaption></figcaption></figure></div>

## Qué significa esto

Cuando los objetos tienen una relación clara, es fácil reunirlos con una [consulta](queries.md), como «todo lo etiquetado como inspiración». Pero si no tienen en común una [propiedad](properties.md) o un [tipo](types.md) que los una, es mejor usar una colección, un contenedor para objetos en los que ves una relación que el sistema no podría distinguir.

## Cuándo usar colecciones

Para entender las colecciones, lo más fácil es compararlas con las [consultas](queries.md). En una colección mantienes un conjunto de objetos que no van a cambiar demasiado con el tiempo. En una consulta estás filtrando objetos que probablemente cambien con el tiempo.
Para entender las colecciones, lo más fácil es compararlas con las [consultas](queries.md). En una colección mantienes un conjunto de objetos que no van a cambiar demasiado con el tiempo. En una consulta estás filtrando objetos que probablemente cambien con el tiempo.

Considera las colecciones como algo que mantienes personalmente; por ejemplo, «Favoritos de la abuela». Considera las consultas como algo que defines con reglas y filtros; por ejemplo, todo lo que etiquetes como «importante».

|Consulta                                               |Colección                                                                                         |
|-------------------------------------------------------|--------------------------------------------------------------------------------------------------|
|Todos tus archivos de medios con valoración mínima de 4|Todo lo que quieres hacer en vacaciones: libros que leer, tareas que realizar, lugares que visitar|
|Todo lo marcado con prioridad alta                     |Materiales de incorporación para nuevos compañeros: tableros, personas, documentos                |
|Todo lo etiquetado como «familia»                      |Recursos que pueden servir en un proyecto: vídeos de YouTube, PDF y notas                         |

**Las colecciones son ideales para objetos que originalmente no están conectados.** Por ejemplo, una colección llamada «Publicidad 1T» podría contener tareas, archivos de diseño, noticias, empresas y notas de reunión. La colección agrupa todos esos objetos sin necesidad de imponerles un mismo tipo o propiedades comunes para que las encuentre una consulta.

**Las consultas son ideales cuando quieres que un conjunto de objetos se actualice automáticamente.** Por ejemplo, una consulta de «todo lo que tenga fecha final de hoy» mostrará automáticamente las tareas, proyectos y eventos de la fecha en la que estés. No tendrás que seleccionar nada a mano.

## Cómo crear una colección

Encontrarás las colecciones en los mismos lugares que los [tipos](types.md): la barra lateral, el menú Crear y los ajustes del canal. Y al igual que los tipos, las colecciones cuentan con vistas, que funcionan de la misma manera.

Para crear una colección, puedes seguir estos pasos:

1. Haz clic en el [botón desplegable Crear](../create/objects/#menu-crear) de la barra lateral y selecciona **Colección** (Collection).
2. Añade objetos existentes de tu espacio o crea alguno nuevo.
3. Configura **filtros** y criterios de **orden**.
4. Elige un **diseño**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Collections Create.jpg" alt=""/><figcaption></figcaption></figure></div>

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Collections Create Add.gif" alt=""/><figcaption></figcaption></figure></div>

## Cómo usar las colecciones

Puedes ver con detalle cómo gestionar las colecciones y sus ajustes en la sección [Vistas](views.md#como-funciona).

### Cómo añadir y eliminar objetos

Puedes añadir un objeto a todas las colecciones que quieras; al hacerlo, se creará un vínculo entre ellos. Los objetos permanecen en las colecciones hasta que los eliminas de ellas.

#### **Para añadir un objeto**

* Haz clic derecho en el objeto en una [vista](views.md) o, si lo tienes abierto, haz clic en el menú de tres puntos de la esquina superior derecha.
* En el menú, selecciona **Añadir a colección** y elige entre las opciones disponibles.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Collections Add.jpg" alt=""/><figcaption></figcaption></figure></div>

#### **Para eliminar un objeto**

1. Abre la colección desde la barra lateral.
2. Haz clic derecho en el objeto y selecciona una de estas opciones:
   1. **Desvincular de la colección** lo elimina de la colección, pero el objeto sigue existiendo en tu espacio.
   2. **Mover a la papelera** elimina el objeto de todas las colecciones y del espacio, aunque lo puedes restaurar desde la papelera.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Collections Unlink.jpg" alt=""/><figcaption></figcaption></figure></div>

#### **Para editarlos en lote**

Usa la [función de edición en lote de las vistas](views.md#edicion-de-objetos-en-lote) para organizar a la vez muchos objetos de una colección. Puedes crear una consulta para buscar los objetos y luego añadirlos todos a una colección.

#### Para establecer el tipo por defecto

Puedes elegir el [tipo](types.md) y la [plantilla](templates.md) que se usarán por defecto al crear un objeto nuevo en una colección. Con la colección abierta, haz clic en el botón desplegable que hay junto a «Nuevo» y selecciona los que quieras.

### Colecciones insertadas

Puedes insertar colecciones directamente en las páginas con el bloque **Colección insertada**. Así podrás ver los objetos junto con tu contenido.

1. Mientras editas una página, abre el menú de comandos con el botón `+` o escribe `/colección`:
2. Selecciona **Colección insertada**.
3. Crea una colección o inserta una existente.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Collections Inline.jpg" alt=""/><figcaption></figcaption></figure></div>

#### Modificación de las colecciones insertadas

Las modificaciones que hagas en las vistas de una colección insertada solo se aplican a ese bloque y no afectan a la vista principal, que se mantiene sin cambios en el [tipo](types.md), la [consulta](queries.md) o la [colección](collections.md) original. Esto significa que cada objeto puede tener su propia versión de la vista insertada sin modificar nunca la original.

Por el contrario, si modificas los objetos y sus propiedades en la vista insertada, esos cambios **sí** se aplicarán al objeto y se reflejarán allá donde aparezca en todo ese espacio.

### Widget con aspecto de carpeta

Las colecciones se pueden [añadir a la barra lateral](views.md#vistas-en-la-barra-lateral) en forma de widgets, igual que cualquier vista. Sin embargo, en lugar de usar colecciones para simular la [estructura jerárquica de carpetas en la barra lateral](../basics/sidebar/widgets.md#opciones-de-diseno), puedes crear una página con bloques de enlace:

1. Crea un objeto con formato de página.
2. En el editor, añade bloques de enlace a los objetos que quieras con `/enlace` o `@`. Puedes enlazar objetos, tipos, consultas y colecciones.
3. Organiza los bloques en la página de forma que representen tu jerarquía.
4. Ancla el objeto en la barra lateral.
5. Haz clic derecho en el widget y selecciona «Estructura jerárquica» en la configuración de la vista.
6. Para expandir cada nivel, haz clic en la flecha desplegable que aparece junto al icono.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Collections Widget Folder-like.jpg" alt=""/><figcaption></figcaption></figure></div>

### Cargar archivos desde el ordenador

Puedes arrastrar una carpeta de tu ordenador y soltarla en una colección de Anytype. Al hacerlo, se cargarán todos los archivos de la carpeta y formarán parte de esa colección. Es una buena forma de llevar a tu espacio un conjunto de archivos de tu disco, como una colección de fotos, la carpeta de un proyecto o tu biblioteca de música.

1. Selecciona y arrastra una carpeta de tu ordenador.
2. Suéltala en una colección abierta.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Collections Drag Folder.gif" alt=""/><figcaption></figcaption></figure></div>

## Cómo eliminar colecciones

Al igual que las vistas, las colecciones son independientes de los objetos que organizan. Eliminar una colección no afecta a los objetos subyacentes: puedes eliminar cualquier colección de tu espacio sin perder ningún dato. Para eliminar una colección, ve a la sección «Colecciones» de la barra lateral. Desde ahí puedes eliminarla como cualquier objeto:

* Haz clic derecho en la colección para abrir el menú y selecciona «Mover a la papelera».
* Abre la colección, haz clic en el menú de tres puntos de la esquina superior derecha y selecciona «Mover a la papelera».

## Notas

**{% hint style="info" %}
Las colecciones son una forma rápida y sencilla de organizar los objetos.** Aunque las consultas son mejores para mantener la organización a largo plazo, las colecciones requieren menos reflexión y planificación. Crea tantas cuantas quieras, ya que eliminarlas no afecta a los objetos que contienen.
{% endhint %}

**{% hint style="info" %}
Ancla colecciones de proyectos a tu barra lateral.** Una colección anclada sirve como panel del proyecto: con un solo clic, ves todo lo relacionado.
{% endhint %}