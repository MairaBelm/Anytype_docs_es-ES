# CSS personalizado

Publicado inicialmente por [LavaC](https://community.anytype.io/u/LavaC) en el foro de la comunidad:

{% embed url="https://community.anytype.io/t/tutorial-of-custom-css/14234" %}

Si necesitas ayuda con esta guía de CSS o con CSS en general, envía un comentario al tema original, en el enlace anterior.

## Dónde encontrar la opción<a href="#where-1" id="where-1"></a>

Para habilitar la hoja de estilos CSS personalizada, ve a `Menú > Archivo > Aplicar CSS personalizado`.

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/custom-css.png" alt=""><figcaption></figcaption></figure></div>

Para editar el archivo CSS personalizado, ve a `Menú > Archivo > Abrir > CSS personalizado`.

## Cómo funciona<a href="#how-2" id="how-2"></a>

Muchos de los métodos de este artículo están orientados a principiantes y no emplean las prácticas más recomendables. Si ya sabes de CSS, podrás saltarte la mayor parte del contenido.

#### Color del tema <a href="#theme-color-3" id="theme-color-3"></a>

En desarrollo de software, se suele empezar por establecer primero una base de variables de estilo. Es igual en Anytype. Si quieres aplicar tu propio estilo, normalmente empezarás por aquí.

Estas variables suelen estar bajo el selector `:root` y podemos verlas con las herramientas de desarrollo.

<div data-with-frame="true"><figure><img src="https://community-static.anytype.io/optimized/2X/8/8c798a22e6bddd7bd190043a2ec7c226fcf5cf24_2_690x408.png" alt=""><figcaption></figcaption></figure></div>

Por ejemplo, `--color-text-primary` parece ser la variable de color para el texto negro más oscuro, así que podemos escribir esto en el archivo custom.css:

<div data-with-frame="true"><figure><img src="https://community-static.anytype.io/original/2X/b/bbefbe5a417032384cde12b1e80e4b2f480ded68.png" alt=""><figcaption></figcaption></figure></div>

Después de guardar, puedes actualizar Anytype pulsando `(Cmd/Ctrl) + R`.

> También puedes modificarlo con las herramientas de desarrollo y ver los efectos al instante.

Aquí podemos ver que el valor `red` (rojo) ha sustituido el valor predefinido y mi texto se ha vuelto rojo.

<div data-with-frame="true"><figure><img src="https://community-static.anytype.io/optimized/2X/0/0e16feda708cfeee241bc7128caa3f802a09c66d_2_690x384.png" alt=""><figcaption></figcaption></figure></div>

Lo que viene a continuación es una parte del archivo custom.css que modifiqué basándome en [Solarized 18](https://en.wikipedia.org/wiki/Solarized). Es como un juego de rellenar palabras: cambia alguna de las variables para ver el efecto que tiene y así sabrás lo que tienes que modificar.

<div data-with-frame="true"><figure><img src="https://community-static.anytype.io/optimized/2X/0/0a67ca485d41ba2d1e72dd5b30b5cae7f489f82e_2_690x394.jpeg" alt=""><figcaption></figcaption></figure></div>

```css
:root {
    --color-text-primary: #002b36;
    --color-text-secondary:	#586e75;
    --color-text-tertiary: 	#839496;
    --color-text-inversion: #eee8d5;
    --color-shape-primary: 	#586e75;
    --color-shape-secondary: 	#eee8d5;
    --color-shape-tertiary: 	#eee8d5;
    --color-shape-highlight-medium: rgba(79, 79, 79, 0.08);
    --color-shape-highlight-light: rgba(79, 79, 79, 0.04);
    --color-control-accent: #252525;
    --color-control-active: #b6b6b6;
    --color-control-inactive: #dcdcdc;
    --color-control-bg: #fff;
    --color-bg-primary: #fdf6e3;
    --color-bg-loader: rgba(255,255,255,0.7);
    --color-system-accent-100: #ffb522;
    --color-system-accent-50: #ffd15b;
    --color-system-accent-25: #ffee94;
    --color-system-selection: rgba(24, 163, 241, 0.15);
    --color-system-drop-zone: rgba(255, 187, 44, 0.25);
    --color-yellow: #ecd91b;
    --color-orange: #ffb522;
    --color-red: #f55522;
    --color-pink: #e51ca0;
    --color-purple: #ab50cc;
    --color-blue: #3e58eb;
    --color-ice: #2aa7ee;
    --color-teal: #0fc8ba;
    --color-lime: #5dd400;
    --color-green: #66B395;
}
```

#### Tipografía<a href="#fonts-4" id="fonts-4"></a>

En CSS, el atributo relacionado con los tipos de letra (también llamados «fuentes») es [font-family](https://developer.mozilla.org/en-US/docs/Web/CSS/font-family). Para asegurarnos de que todo el texto usa el mismo tipo de letra, ponemos el estilo en el elemento `body`.

```css
body {
    font-family: "霞鹜文楷", "jetBrainsMono";
}
```

Por supuesto, el requisito previo para que funcione es que tengas ese tipo de letra en tu ordenador; si no es así, puedes instalarla o importarla de Internet.

<details>

<summary>Importar tipo de letra de Internet</summary>

[<img src="https://community-static.anytype.io/optimized/2X/d/d1348ecf28fafeb4c079d5cd9ba343b30ee6f9d2_2_690x494.png" alt="image" data-size="original">](https://community-static.anytype.io/original/2X/d/d1348ecf28fafeb4c079d5cd9ba343b30ee6f9d2.png)\
[![image](https://community-static.anytype.io/optimized/2X/a/aaf23f71f95b30839021c2489a9153cc46f2b8be_2_690x271.png)](https://community-static.anytype.io/original/2X/a/aaf23f71f95b30839021c2489a9153cc46f2b8be.png)\
[![image](https://community-static.anytype.io/optimized/2X/d/d29da78fce6ac4d052c0b030fd322fab4fef2a1a_2_690x458.png)](https://community-static.anytype.io/original/2X/d/d29da78fce6ac4d052c0b030fd322fab4fef2a1a.png)\
[![image](https://community-static.anytype.io/optimized/2X/8/87c8c15932c29ee8bd91d58928d2958209db39e3_2_690x107.png)](https://community-static.anytype.io/original/2X/8/87c8c15932c29ee8bd91d58928d2958209db39e3.png)\
[![image](https://community-static.anytype.io/optimized/2X/6/690391b23293397bb0844789dee9d500300a3028_2_690x435.png)](https://community-static.anytype.io/original/2X/6/690391b23293397bb0844789dee9d500300a3028.png)

</details>

#### Modo oscuro<a href="#dark-mode-5" id="dark-mode-5"></a>

Los estilos del modo oscuro se deben especificar dentro de `html.themeDark`.

```css
/* El valor por defecto se aplica al modo claro */
.blocks {
    .block.blockText.textCallout>.wrapContent{
        border-radius: 30px;
    }
}

html.themeDark {
    /* Se aplica al modo oscuro */
    --color-text-primary: red;
    .blocks {
        .block.blockText.textCallout>.wrapContent{
            border-radius: 2px;
        }
    }
}

```

#### Otros elementos <a href="#other-elements-6" id="other-elements-6"></a>

Si quieres modificar un elemento concreto, puedes abrir las herramientas de desarrollo, en la esquina superior izquierda, y seleccionar el elemento que quieres modificar; al hacerlo, verás los estilos que le afectan en la columna **Estilos**.

<figure><img src="https://community-static.anytype.io/optimized/2X/3/3d111c1232f10345c8584f5a2cf15ec36cba8864_2_690x460.png" alt=""><figcaption></figcaption></figure>

Puedes probar a modificar directamente los valores para ver su efecto.

<figure><img src="https://community-static.anytype.io/optimized/2X/6/6ec5d48153fd5abfd34274a2c9cfb736de865a14_2_690x283.png" alt=""><figcaption></figcaption></figure>

Si crees que los efectos no están mal, puedes copiar todo este contenido en tu hoja de estilos custom.css para guardarlo.

<figure><img src="https://community-static.anytype.io/original/2X/8/8c83f1c7406a1a651cac26da10c6429bd59f2dcb.png" alt=""><figcaption></figcaption></figure>

#### Cambiar iconos <a href="#change-icons-7" id="change-icons-7"></a>

Los iconos de Anytype usan el formato SVG.

<details>

<summary>Por ejemplo, los iconos de relación</summary>

[<img src="https://community-static.anytype.io/optimized/2X/6/6d596177b0b332db51cd793630c415891538f8f7_2_672x500.png" alt="image" data-size="original">](https://community-static.anytype.io/original/2X/6/6d596177b0b332db51cd793630c415891538f8f7.png)

El texto que comienza con `data:image/svg...` son los datos de SVG convertidos a Base64.\
Puedes descifrar estos datos en este [sitio web](https://base64.guru/converter/decode/image/svg), por ejemplo, para obtener la imagen SVG.

</details>

Si quieres usar un icono propio, puedes convertir tu SVG a formato Base64 empleando, por ejemplo, un [sitio web](https://base64.guru/converter/encode/image/svg).

Como fuente para los iconos SVG, recomiendo este [sitio web](https://pictogrammers.com/libraries/).

> Procura que tu icono SVG no sea muy complicado para que el texto en Base64 no se alargue demasiado.

Cuando obtengamos el texto en Base64, sustituimos el original y habremos cambiado el icono.

```css
.header .icon.relation {
  background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvb......);
}
```

![image](https://community-static.anytype.io/original/2X/3/30b788e54c7daa2db54352ca4ff721ecc6d2e027.png)

**Si crees que el icono original está muy bien y solo quieres cambiar el color, también hay una forma de conseguirlo, aunque un poco complicada.**

```css
.header .icon.relation {
  // El contenido de `url` en la siguiente línea es el contenido del atributo `background-image` de este icono. 
  mask-image: url(data:image/svg+xml;base64,.......);
  mask-repeat: no-repeat;
  background: red; // el color que quieras
}
```

Si has usado PS, deberías ser capaz de adivinar que se trata de una función de máscara similar, pero el resultado final no es muy fino.\\

<figure><img src="https://community-static.anytype.io/original/2X/7/72dbdcf71ef643f5873aa7ea1ea814bf282dfec5.png" alt=""><figcaption></figcaption></figure>

## Ejemplos

{% embed url="https://community.anytype.io/t/anytype-mist-light-dark-a-brand-new-anytype-theme/16329" %}
