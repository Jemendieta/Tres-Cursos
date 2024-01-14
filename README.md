# Desarrolo web inicial basado en los tres cursos base | HTML - CSS - JS

---

![Curso FrontEnd Base - HTML CSS JS](assets/img/portada.jpg)

---

1. [HTML](#html)
2. [CSS](#css)
3. [JavaScript](#js)

---

<div id="html"/>

### Iniciaciamos con el curso de HTML - Sergie Code.

    - Analizamos los elementos meta en html.
    - Estructura base de una web con html.
      - header - nav
      - section - article
      - aside
      - footer
    - Etiquetas de texto.
    - Etiquetas de line y de bloque
    - Listas
    - Tablas
      - Estructura para formularios y contenido
    - Agrupadores
      - div
    - Iframe
    - Formularios
      - Estructura de etiqueta select
    - SVG
    - Realizamos el proyecto final con la estructura bas de html para 4 secciones nav y hacemos uso de algunos estilos en css para cada una de ellas.

    <div id="css"/>

2.  ## Curso de CSS - Sergie Code.

    ### Sintaxsis básica, selector (etiqueta, clase, id), atributo y valor:

    ```CSS
       h1{
         color:red;
       }

    ```

    ### Selectores

    - Etiqueta (p, h1, h2, body)
    - Id (#)
    - Clase (.)
    - !Important

    ### Los comentarios son importantes para indicar secciones de nuestro código, pueden ser de una o varias líneas.

    ### Colores:

    - red, pink
    - #ffffff - Hexadecimal
    - rgb (red, green, blue)
    - rgba (red, green, blue, alpha = transparencia)
    - hsl (hue - ángulo, saturation - saturación , lightness - iluminación).

    ### Background - Fondo

    - image, repeat, position, attachment
    - Revisar formas abreviadas de algunos atributos css.

    ### Bordes

    - Existen diversos atributos para hacer uso de los bordes:
      - dotted
      - dashed
      - solid
      - double
      - groove
      - inset
      - outset
      - none
      - hidden
      - mix
    - El atributo border también cuenta con su versión abreviada
    - También tenemos el atributo borber-radius

    ### Unidades de Medida

    - Tenemnos distintas unidades de medida:
      - % - relativo al elemento padre
      - em - relativo al font-zise del elemento
      - rem - relativo al font-zise del elemento
      - vh - relativo al 1% del alto del vieport
      - vw - relativo al 1% del ancho del vieport
      - px - medida absoluta en píxeles
      - vmax - relativo al 1% del lado más grande del vieport
      - vmin - relativo al 1% del lado más pequeño del vieport
      - ex - medida de altura de tamaño de fuente de letra

    ### Márgenes

    - es la distancia que se aplcia de un elemento con respecto a los que tiene al lado.
    - top, right, bottom, left - son los márgenes que podemos asignarle al elemento seleccionado.

    ### Padding

    - Es la distancia que tiene el contenido del elemento con respecto al borde.

    ### Texto

    - Podemos asignarle varios atributos que van desde el color, el tamaño, el tipo de fuente, transformación, el alineamiento, entre otros.
    - forma abreviada del atributo text-decoration.
    - Sombras en los textos con el atributo text-shadow

    ### Fuentes

    - Sans Serif - planas
    - Serif - Tienen un diseño más estilizado
    - Dentro de CSS hacemos uso de las tipografías haciendo uso del atributo font-family

    ### Iconos

    - Existen muchos sitios web desde los cuales tomar iconos para nuestros proyectos, uno de los más recomendados es el repositorio de google. [Iconos de google](https://fonts.google.com/icons "Iconos de Google").
    - Existen otras alternativas para iconos como los de bootsrap o font awesome.

    ### Listas

    - En css podemos personalizar nuestras listas ordenadas o desordenadas con iconos e imágenes.
    - podemos hacer uso del atributo list-style para personalizar los items de nuestras listas
    - como por ejemplo el atributo list-style-image : url(ruta de la imagen para nuestras listas);

    ### Tablas

    - con los diferentes atributos de borde podeos personalizar el diseño de nuestras tablas.

    ### Display & Visibility

    - Se usa para mostrar nuestros elementos de formas diversas ya sea en bloque o en línea o no mostrarlos si es lo que necesitamos.
    - Podemos hacer uso del atributo display el cual contiene muchos valores que podemos usar.
      - block
      - inline
      - grid
      - flex
        entre otros.
    - el atributo visivility nos permite ocultar un elemento de nuestra web.
      - Visibility: hidden;
      - algo a considerar es que el elemento puede conservar su espacio ocupado a pesar de que ya no se muestre en la web.

    ### Position

    - Dos conceptos claves en position, el flujo y el espacio en el flujo de los elementos HTML.

      - Flujo: Es el orden en el que aparecen los elementos en nuestra web o en nuestro html.
      - Espacio en el flujo: ese espacio se puede reservar en algunas ocasiones.
      - Es el lugar en el que podemos ubicar a nuestros elementos y desde donde se mueve.
      - Tiene distintos valores:

        - <b>Static</b> = basicamente es que el elemento mantiene su posició según el flujo. Por defecto, es la posición de todos los elementos dentro del HTML.

        - <b>Relative</b> = Las coordenadas (top, right, bottom, left) de relative están en relación a su posición inicial, si se mueve, su espacio se conserva.

        - <b>Ansolute</b> = rompe la maquetación y se sale del flujo, su espacio no se reserva, se reduce a cero, sus coordenadas se calculan respecto al ancestro más cercano que esté posicionado y si no se calcula respecto al vieeport.

        - <b>Fixed</b> = Pierde su espacio en el flujo, sus dimensiones se ajustan al contenido, sus coordenadas siempre son relativas al viewport, nunca hace scroll, se queda en el lugar indicado y se sobrepone a otros elementos.

        - <b>Sticky</b> = fija un elemento según el scroll, elemento pegajoso.

      - Un elemento se considera posicionado siempre y cuando tenga alguna de las propiedades anteriores menos static.
      - Algo que debemos considerar es que para posicionar nuestros elementos haremos uso de las propiedades top, right, bottom y left.
      - Algo a considerar es que top y bottom fincionan siempre y cuando el elemento contenedor tiene altura definida.
      - El ancho de un elemento posicionado está definido por su contenido.

    ### Z-index

    - El elemento que tenga mayor valor aparece primero, define la posición de un elemento en el eje z, sobre todo se usa cuando hay elementos super puestos.
    - Si tenemos varios elementos a los cuales aplicaremos z-index, se recomienda colocar valores grandes para poder manipularlos más facilmente.
    - Cuando trabajamos con pseudo-elementos, el z-index solo tiene dos valores posibles, 1 y -1 y que además el elemento padre no tenga un z-index declarado.

    ### Overflow

    - permite ocultar o asignar un scroll al contenido que no sabe en su contenedor padre.

    ### Float

    - es una característica que le podemos asignar a un elemento para que ocupe una posición flotante alrededor de otro elemento.
    - ubica un elemento al lado izquierdo o derecho de su contenedor, permitiendo a los elementos de texto y en línea aparecer a su costado.

    ### Selectores Combinados.

    - Cuando usamos mas de un selector para tener mayor especificidad. Esto sucede cuando por ejemplo usamos selectores descendientes.
      - por ejemplo <b>p img{}</b>
      - <b> > </b> Los elementos hijos se seleccionan con el símbolo >
      - <b>+</b> Los elementos adyacentes con el símbolo +, por ejemplo los elementos en linea.
      - <b>~</b> Los hermanos generales, incluso si no son directamente adyacentes, estos se seleccionan con el símbolo ~
      - <b> \* </b> Para seleccionar todos los elementos hacemos uso del \* , conocido también como selector universal.

    ### PseudoClases

    - Actuan sobre los elementos html asignándoles propiedades especiales como lo hace Hover, la cual actúa al pasar el puntero del mouse sobre el elemento.

    ```CSS
     p:hover{
      background-color:red;
      <!-- Cuando se pase el puntero por encima del elemento este se pondrá de color rojo -->
     }
     a:visited{
      color:cyan;
      <!-- luego de que el enlace sea visitado se colocará de color cyan -->
     }
     p:first-child{
      color:blue;
      <!-- El primer hijo tendrá color azul -->
     }
     p:nth-child(2){
      color:red;
      <!-- El segundo hijo tendrá color rojo -->
     }
     p:nth-child(odd){
      color:yellow;
      <!-- Todos los elementos impares tendrán color amarillo -->
     }

    ```

    - Existen muchas PseudoClases de las cuales podemos hacer uso [Click Aquí](https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-classes "PseudoClases CSS")

    ### PseudoElementos

    -
