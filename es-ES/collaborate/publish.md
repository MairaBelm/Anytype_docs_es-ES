---
description: Publica objetos como páginas estáticas en un subdominio personal.
---

# Publicar

La **publicación en la web** te permite convertir cualquier objeto en una página web con una URL que cualquiera puede visitar. Elige un objeto, haz clic en «Publicar» y Anytype generará una página HTML estática en un subdominio de tu uso exclusivo en `<tu-id-any>.any.org/<titulo>`.

Esta función está pensada para contenido que quieras **hacer público**, como entradas de blog, perfiles públicos, documentación, programas de encuentros o cualquier otra cosa que publicarías en un sitio web personal.

Con la publicación web, el objeto que has creado se convierte en la página publicada. Modifica el objeto, vuelve a publicarlo y la página pública se actualizará. No tienes que mantener una segunda plataforma.

## Cómo publicar un objeto

1. Abre el objeto que quieres publicar.
2. Haz clic en el botón **Compartir** de la esquina superior derecha.
3. Revisa el **título** que completará la URL.
4. Haz clic en **Publicar**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Publish.jpg" alt=""><figcaption></figcaption></figure></div>

En cuestión de segundos, tu objeto aparecerá en `<tu-id-any>.any.org/<titulo>`. Copia la URL o compártela directamente desde el diálogo.

## Cómo actualizar una página publicada

Modifica el objeto como de costumbre. Los cambios no se publicarán automáticamente; para aplicarlos a la página, tienes que actualizar la publicación:

1. Abre el objeto.
2. Haz clic en **Compartir**.
3. Elige **Cancelar publicación** o **Actualizar**.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Publish Update.jpg" alt=""><figcaption></figcaption></figure></div>

## Cómo gestionar las páginas publicadas

Puedes encontrar y gestionar lo que has publicado desde los **ajustes del arca > Mis sitios**:

* Verás una lista de todos los objetos publicados con su título, URL y fecha de la última actualización.
* Haz clic en la URL para abrir esa página en un navegador.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Publish My Sites.jpg" alt=""><figcaption></figcaption></figure></div>

## Qué se publica y qué no

La publicación web todavía está en desarrollo.

#### Compatibles con la publicación de páginas

* **Todo el formato de texto**: párrafos, títulos, listas, avisos, citas.
* **Imágenes y bloques de imágenes** como parte de la página publicada.
* **Bloques de código** con resaltado de sintaxis.
* **Fórmulas de LaTeX** como MathML estático.
* **Incrustados** que funcionen en contextos estáticos: YouTube, Vimeo, diagramas de Mermaid (se trazan en el servidor), imágenes.
* **Icono y portada del objeto** en la parte superior de la página.
* **Propiedades visibles**: las propiedades seleccionadas aparecen en los metadatos o la cabecera de la página.
* **Bloques des plegables**: contraídos por defecto en la vista publicada, expandibles al hacer clic.

#### Incompatibles por ahora

* **Objetos enlazados**: los enlaces a otros objetos de tu canal apuntan a una «página no publicada» a menos que esos objetos estén publicados también.
* **Consultas y colecciones insertadas**: no se muestran en las páginas publicadas.
* **Chats y debates**: no se exponen al público.
* **Sitios con varias páginas**: puedes publicar varios objetos, pero serán páginas independientes y no un sitio con conexiones (esto está en nuestra hoja de ruta).
* **Temas o estilos personalizados**: las páginas publicadas usan un estilo predeterminado de Anytype.
* **Dominios personalizados**: las páginas se publican en `<tu-id-any>.any.org`; los dominios personalizados están en la hoja de ruta

Presta atención al registro de cambios de las actualizaciones de Anytype.

## Notas

{% hint style="warning" %}
**No publiques objetos con propiedades confidenciales.** Si no las excluyes antes de publicar, en la página aparecerán propiedades como el estado, notas privadas y datos personales. Revisa las que están visibles antes de hacer clic en «Publicar».
{% endhint %}

{% hint style="warning" %}
**Cualquiera que tenga la URL puede ver la página publicada**: esto incluye archivadores de webs, motores de búsqueda y herramientas de captura de pantalla. Trata la URL como algo público, aunque no la compartas con muchas personas.
{% endhint %}
