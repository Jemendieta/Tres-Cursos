# Desarrolo web inicial basado en los tres cursos base | HTML - CSS - JS

---

![Curso FrontEnd Base - HTML CSS JS](assets/img/portada.jpg)

---

1. [HTML](#html)
2. [CSS](#css)
3. [JavaScript](#js)

---

<div id="html"/>

1. ## Iniciaciamos con el curso de HTML - Sergie Code.

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

2. ## Curso de CSS - Sergie Code.

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

   - Son elementos que se añaden a elementos ya existentes y que además permiten añadir estilos a una parte en concreto, son varios los que podemos utilizar como por ejemplo los siguientes:
     - ::firts-line : actúa sobre la primera letra de una palabra.
     - ::before: crea un elemento antes.
     - ::after: crea un elemento despues.
     - ::marker: para los marcadores o viñetas.
     - ::selection

   ### Opacidad

   - Nos permite definir un nivel de transparencia de un elemento, en que grado se superpone el fondo de nuestro sitio.
   - su valor está entre 0 y 1

     ```CSS
     p{
       opacity:0.7;
     }
     ```

   ### Selectores de Atributos

   - Seleciona los elementos cuyos atributos coinciden con un atributo determinado. En los siguientes ejemplos, seleccionamos a los elementos que contengan el atributo title y href conteniendo a .org

   ```CSS
     a[title] {
       color: purple;
     }

     a[href$=".org"] {
       font-style: italic;
     }

   ```

   ### !important

   - Permite superponer estilos a un elemento por encima de que los que ya tenía pre definidos.
   - Se recomienda solo en casos muy particulares, pues su uso reiterado no es una buena práctica.

   ```CSS
   p {
      color: red !important;
     }
   ```

   ### Animaciones

   - Nos permiten dar mayor dinamisno a nuestros sitios web.
   - Haremos uso de la propiedad animation Y de las keyframes como en el siguiente ejemplo:

   ```CSS
      p {
       animation-duration: 3s;
       animation-name: slidein;
     }

     @keyframes slidein {
       from {
         margin-left: 100%;
         width: 300%;
       }

       to {
         margin-left: 0%;
         width: 100%;
       }
     }
   ```

   - Las posibilidades para hacer uso de este recurso son infinitas y dependerán de nuestra creatividad y necesidades del sitio.
   - Animation tiene una forma abreviada en donde podemos agrupar varios valores.

   ### Transiciones

   - Nos ofrecen otra forma de crear animaciones en css.

   ```CSS
     div {
         transition-property: opacity, left, top, height;
         transition-duration: 3s, 5s, 3s, 5s;
       }
   ```

   ### Media Queries

   - Los media queries son un conjunto de estilos con los cuales podemos hacer que nuestro sitio se adapte a la pantalla de diversos dispositivos como laptps, celulares y tablets.
   - La estructura de la declaración css, dependerá de la pantalla a la queramos adaptar ek sitio.

   ```CSS
      @media (max-width: 1250px) {
         /* … */
       }

   ```

   ### FlexBox

   - Es un modelo de layout que nos permite definir la forma en la que los elementos se muestran en la pantalla o en el flujo de nuestro sitio.
   - Estudiando cada una de sus propiedades y valores podremos sacarle su máximo provecho. [Click Aquí](https://developer.mozilla.org/es/docs/Learn/CSS/CSS_layout/Flexbox "FlexBox")

   ### Grid

   - Es un modelo de Layout que nos permite hacer que nuestros sitios sean mas adaptables a las necesidades del usuario dividiendo la página en una cuadrilla en la cual podremos distribuir nuestros elementos.
   - En compañía de FlexBox, nos resulta en un herramienta sumamente potente. [Click Aquí](https://developer.mozilla.org/es/docs/Web/CSS/CSS_grid_layout "CSS Grid")

<div id="js"/>

3. ## Curso de JavaScript

   ### Comenzamos

   - Fundamentos de Js - Declaraciones.

     - **Las variables** son contenedores que almacenan valores.
     - Tenemos tres formas de declarar variables:

       - **var**: nombreDeLaVariable = valor
       - En JS existe algo que se conoce como camel case, es decir, el uso de minúsculas y mayúsculas con en nombreDeVariable.
       - No se recomienda el uso de var debido al scope.
       - **let** nombreVariable = valor
       - let es la forma recomendada de declarar variables.
       - **const** nombreVariable = "valor"
       - En el caso de const, es obligatorio declarar un valor a nuestras variables.
       - const no permite reasignar la declaración de una variebla a diferencia de var y let que si lo hacen, const es un valor constante.

       ```JS
          var = "miVariable1";
          let = "miVariable2";
          const = "miVariable3";

          // Declaración de varias variables a la vez
          let x,y,z;
          // Luego le asignamos los valores
          x = 1;
          y = 2;
          z = x + y;
       ```

       - EL punto y coma permite separar ejecuciones de líneas de cógigo, no es obligatorio pero es recomendable.

   - Tipos de Datos number y string:

     - Números:

     ```JS
      let variableNumero = 37;
      let decimal = 1.2;
     ```

     - Texto, cadena o string:

     ```JS
      let variableTexto = "Jorge";

     ```

   ### Operadores

   - Tenemos el operador de aisgnación que es el signo igual **=**.
   - También tenemos los operadores aritméticos representados por los símbolos de las cuatro operacioens básicas **(+, -, \*, /)**
   - Tenemos el símbolo de **%** que nos dá el resto de una división.
   - Si queremos colocar un exponente, podemos hacerlo con el operador **\*\***.

   ```JS
    const suma = 1 + 3; // suma o concatenación
    const resta = 3 - 1; // resta
    const multiplicacion = 4 * 3; // multiplicación
    const division = 2 * 2; // división
    const resto = 5 % 2; // resto
    const exponente = 3 ** 3; // exponente
   ```

   - Si quisieramos ver el resultado de alguna de las operaciones que se muestran arriba usaríamos la consola.

   ```JS
    console.log(suma);
    console.log(resta);
    console.log(multiplicacion);
    console.log(division);
   ```

   ### Sintaxis de las variables

   - La manera de declarar variables tiene ciertas reglas, una de ellas es el uso de camelcase, es decir el uso de minúsculas y mayúsculas.
   - se puede iniciar el signo de dolar o guion bajo.

   ```JS
    const $variable = 1;
    const Variable2 = 2;
    const miVariable = 3;
    const _varaible4 = 4;
    const varaible_cinco = 6;
   ```

   - algo a considerar es que JS es case sensitive, es decir que una una dos variables pueden llamarse igual pero se diferencian por como han sido declaradas, por ejemplo:

   ```JS
    const nombre = "Jorge";
    const Nombre = "Jorge";
    <!-- ambas varaibles parecen iguales, pero la letra minúscula o mayúscula las hace distintas -->
   ```

   ### Scope (alcance de una variable)

   - Es el contexto de ejecución de una varaible dependiendo de donde ha sido declarada.

   ```js
   // Variable con scope externo
   let x = 2;
   {
     // variable con scope interno
     let x = 3;
     concole.log(x);
     //mostrará 3
   }
   console.log(x);
   //mostrará 2
   ```

   - En el ejemplo anterior hemos declarado dos variables las cuales tienen un scope(ambito o alcance) distinto, una existe de forma global, y otro existe dentro de las llaves.
   - el scope va desde afuera hacia adentro.

   ```JS
    let x = 2,
    {
      let y = 3;
      x += y;
      console.log(x)
      // mostrará 5, pues la variable x tiene scope externo
    }
   ```

   ### Tipos de Datos

   - Números, floats, strings, boolean.
   - Antes ya vimos números y strings, ahora veremos que es un **booleano**.
   - solo nos pueden devolver valores verdaderos (true) o falsos (false).
   - Tenemos también los **undefined** (indfinidos), los cuales se presentan cuando aún no se ha asignado un valor aunque ya se ha declarado una variable.
   - **Null** el cual es la ausencia de valor.
   - **Objeto** son pares de clave valor, usado para guardar una colección de datos definidos y entidades más complejas.
   - **Array** el cual es un arreglo, un conjunto o lista de valores.
   - **date** para el manejo de fechas.

   ```JS
    //Booleanos
    let de = true;
    let b = false;
    //Indefinidos
    let variable;
    //Nulos
    let variable = null;
    // Objeto
    let objeto {
      clave: valor
    }
    // Arrays
    lst frutas = ["manzana", "pera", "fresa"];
    console.log(frutas);
    // Fechas
    let fecha = new Date("01-31-2024");
    console.log(fecha);
   ```

   ### Operadores Lógicos

   - Nos permiten lleavr a cabo ciertas acciones como comparación de valores o tipos de datos.
   - doble(==) y triple (===) igual.
   - Negación !, nos permite negar o comprbar si un valor es distinto a otro.
   - comparación con < > <= >=
   - Operador && (y) el cual nos permite comparar mas de un valor.
   - Operador || (ó)
   - **Ejemplos**...👇👇👇

   ```JS
    // Doble y triple igual
    let x = 2;
    let y = 4;
    // doble igual compara si el valor absoluto es igual
    let z = x == y;
    // triple igual compara si el valor y tipo de dato son iguales
    let z = x === y;

    // Negación
    let num1 = 2;
    let num2 = 2;
    let result = num1 != num2;
    console.log(result);

    // Mayor o Menor
    let a = 2;
    let b = 2;
    let resul = a > b;
    console.log(resul);
    // operador &&
    let a = 2;
    let b = 1;
    let c = 3
    let resul = a > b && c < a;
    console.log(resul);
   // operador ||
    let a = 2;
    let b = 2;
    let resul = a > b || a > c;
    console.log(resul);
   ```

   ### Consola

   - Nos permite contar con una herramienta medinte la cual podemos llevar a cabo muchas operaciones como la ejecución de JS haciendo uso de Node Js entre muchas otras cosas.

   ### Funciones

   - Son un conjunto de instrucciones de calculan y devuelven un valor o que llevan a cabo un tarea específica.
   - Se declaran de la siguiente manera...👇

   ```JS
    function nombreFuncion(parametro1, parametro2, ...){
      //instrucciones
    }
    //ejemplo práctico con función clásica o declarada
    function suma(a,b){
      return a + b;
    }
    suma(2,4);
    let respuesta = suma(2,4);
    console.log(respuesta);
    //con lo anterior devolvemos mediante una función la suma de dos números.
   ```

   - Existen otras formas de declarar una función.

   ```JS
      //Funciones tipo flecha
      let sumaDos = numero => numero + 1;
      console.log(sumaDos(3));
     // esto nos devolvería 4

      //Funciones por expresión, consiste en guardar un función en una variable
      const square = function (number) {
       return number * number;
      };
      let x = square(4); // x obtiene el valor 16
      console.log(x);
   ```

### Objetos

- Son estructuras de datos, formados por pares de clave valor, que pueden tener propiedades y métodos.
- son representaciones de algo real en código.👇👇

```JS
  let auto = {
    marca: "Fiat",
    modelo: "uno",
    peso: 1000,
    color: "rojo"
  }
  console.log(auto);
  // para mostrar un valor específico haríamos lo siguiente
  console.log('El color del auto es: ', auto.color);
  console.log(auto["peso"]);

  // ejemplo de objeto con un array
  let vendedor = {
    nombre:"Jorge",
    empresa:"Hola",
    habilidades:['carisma','puntualidad'],
  }
  console.log(vendedor.habilidades);
```

### Eventos

- acciones que suceden denro de la página web, los cules se desencadenan por acción del usuario o por las características de la propia web.

```HTML
<!-- EJemplo del uso de eventosen el que mostramos la fecha abtul haciendo click en el boton -->
  <h1>Eventos</h1>
  <p id="seleccionable"></p>
  <button onclick="mostrar()">Click Here</button>
  <script>
    function mostrar(){
      document.getElementById('seleccionable').innerHTML = Date()
    }
  </script>
  <!-- mismo ejemplo pero que se ejecuta al pasar el mouse por encima del boton, esto por el evento onmouseover -->
  <h1>Eventos</h1>
  <p id="seleccionable"></p>
  <button onmouseover="mostrar()">Click Here</button>
  <script>
    function mostrar(){
      document.getElementById('seleccionable').innerHTML = Date()
    }
  </script>
```

- Existen muchos tipos de eventos que desencadenan distintas acciones en JS. [Lista de Eventos](https://fonts.google.com/icons "Eventos JS").

### Strings

- Existen ciertas situaciones en la que el uso de las comillas puede resultar algo complejo, es por eso que tenemos la siguiente solución.

```JS
// colocamos una barra invertida para agregar un apóstrofe que en situaciones normales sería tomada como comilla.
  let texto1 = 'Let\'s Do it';
  //en este segundo ejemplo usamos dos barras para usar las comillas como cita
  let text2 = 'Alber Einstein dijo que\'La relatividad es cool\''
  console.log(texto1);
  console.log(texto2);

  //Salto de línea
  let texto3 = 'esto está arriba \n y esto está abajo'
  console.log(texto3)

  // existen muchas otras características que pueden ser usadas en distintos contextos.
  // Con el siguiente ejemplo obtenemos la cantidad de caracteres de valor que contiene la variable text4
  let texto4 = "murciélago";
  console.log(texto4.lenght);
```

- Tenemos también métodos con el uso de strings

```JS
  let texto = "Educación";
  // Haciendo uso de slice obtenemos los caracteres despues del cuarto hasta el séptimo
  let corte = texto.slice(4,7)
  console.log(corte)

  let textoMas = "La educación es importante en Perú";
  // con replace, reemplazamos un texto por otro
  let result = textoMas.replace('Perú', 'En el mundo');
  console.log(result);

  // cambiar a mayúsculas
  let minusculas = "hola soy jorge";
  let mayusculas = minusculas.toUpperCase();
  console.log(mayusculas);

  // quitar espacios en blanco y concatenar otra variable
  //trimp() quita los espacios en blanco
  let espacios = "      texto con espacios";
  let pais = "  Perú";
  let textoSinEspacios = espacios.trimp().concat(pais);
  console.log(textoSinEspacios)

  // Método split. El cual divide un objeto en un array
  //
  let text = "hola. como estas. espero que bien"
  // con el uso del punto le indicamos donde tiene que separar
  let rel = text.split('.')
  console.log(rel)
```

###
