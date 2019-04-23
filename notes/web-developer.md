## Desarrollo Web
### Frontend:
Es la experiencia del usuario. Pasar el diseño a código, formas, colores. Cualquier evento que haga el usuario.
Un Frontend debe manejar mínimo 3 tecnologías:

**HTML**: Hypertext languaje, lenguaje de marcado para hacer websites. Determina el contenido, texto, imágenes, video, enlaces.
**CSS**: Cascade style sheet, lenguaje para definir la presentación de documentos HTML
**JS**: lenguaje de programación del navegador
**Backend**: resguardan los datos y la seguuridad de las aplicaciones.

### Estas son algunas de las especializaciones:

#### Arquitecto Frontend
- Desarrollador JavaScript
- Devops (Servidores)

### Introducción al Desarrollo Web
- Git y github (manejo y gestión de desarrollo(código programación) profesional)
- Responsive Design (adaptar a cualquier plataforma)
- CSS Grid Layout (organización y presentación)
- Animaciones (para web)
- PostCSS(syntaxis especializada en CSS - más sostenible)
- jQuery a JavaScript (JavaScript sin librerías)
- Fundamentos JS(básico de JavaScript técnico)
- Webpack(JS como base aplicación - encapsulación)
- React.js - Redux(manejo de datos) - ReactRouter - React Native

### BOM
El **BOM** (Browser Object Model) consiste en el navegador de objetos, el historial, la pantalla, la ubicación y el documento que son elementos secundarios de la ventana. En el nodo del documento está el **DOM** (Document Object Model),
es la forma en la que internamente el navegador (Chrome, Firefox, Microsoft Edge, etc) organiza todo nuestro html dentro de una estructura especial, además crea internamente el árbol de como los datos están estructurados.
El Document Object Model ( DOM ) es un multi-plataforma y lenguaje -independiente interfaz de programación de aplicaciones que se trata a un HTML , XHTML o XML documento como una estructura de árbol en la que cada nodo es un objetorepresentando una parte del documento. El modelo DOM representa un documento con un árbol lógico. Cada rama del árbol termina en un nodo, y cada nodo contiene objetos. Los métodos DOM permiten el acceso programático al árbol; Con ellos se puede cambiar la estructura, el estilo o el contenido de un documento. Los nodos pueden tener controladores de eventos adjuntos a ellos. Una vez que se activa un evento, los controladores de eventos se ejecutan.

### Cómo resolver la compatibilidad con HTML5

Seguramente esta es una de las grandes cuestiones. La clave está en detectar características soportadas por el navegador. ¿Cómo es esto? Bueno, primero y principal es probable que no necesitemos utilizar todas las características de HTML5 en todos nuestros proyectos. Lo que debemos hacer, mediante JavaScript, es detectar si la característica que estamos incluyendo es soportada por el navegador.

Una librería Open Source que nos simplifica mucho este camino es Modernizr. De una forma sencilla, nos permite incluirla en nuestras páginas y comprobar la compatibilidad con el navegador.

### Etiquetas HTML
Cada etiqueta es usada para crear contenido.
Las etiquetas HTML representan la informacion que vamos a tener dentro de nuestro web site.

- title: sirve para colocar el titulo que dentro del tag de donde este corriendo el web site, como lo puede ser el navegador
- Meta: sirve para colocar metadatos, agregar información acerca de que codificado se esta empleando, por ejemplo, si se están utilizando ñ o tildes se debe emplear el charset utf-8
- doctype: nos sirve para asignar que tipo de documento es el que se esta escribiendo
- link: nos sirve para enlazar hojas de estilo
- style: para poner estilos dentro de etiquetas html
- script: para poner JS dentro de una etiqueta
- noscript: para poner cualquier mensaje por si no hay JS disponible dentro del navegador que cargo el web site
- body: es la seccion principal, donde se va a englobar todo el contenido visible para el website
- article: nos sirve para diferenciar alguna parte de nuestro contenido que pueda vivir por si misma, por ejemplo:
Un proyecto dentro del portafolio podría ser un article.
Se podría decir que es una sección del contenido de la página, como un blog o publicación en un foro, que se puede reutilizar de forma aislada.
- nav: especializada para menus de navegación
- aside: para contenido que no sea muy relevante, como la publicidad del website
- section: nos permite diferenciar las secciones grandes del contenido
- header: especializada en la parte de las cabeceras
- footer: especializada para los pie de pagina
- headings 'h1, h2, ..., h6': títulos principales, va de mayor a menor.
- main: para colocar partes principales.
- address: para colocar direcciones
- p: para agrupar contenido en parrafos
- hr: para colocar una linea horizontal
- ol: listas, para colocar listas ordenadas
- ul: listas, para colocar listas desordenadas
- li: list items
- figure: contenedor de los elementos img
- div: división, cualquier división necesaria para generar una variante del contenido
- span: es un div a nivel de textos

Mas especificadas
<title> . . . <title>
La etiqueta title especifica el título del documento, el cual generalmente se muestra en la barra superior del navegador (pestaña), fuera de la ventana de contenido normal, así como también en los marcadores de un usuario o en la lista de favoritos.

<header> . . . </header>
La etiqueta header representa la información que va al comienzo de una sección, con más frecuencia en el encabezado, también puede incluir enlaces de navegación, publicidad, presentaciones, etc.

<section> . . . </section>
La etiqueta section representa una sección (una agrupación temática de contenido) de un documento o aplicación con su propio esquema interno, cabe mencionar que no es un contenedor genérico.

<footer> . . . </footer>
La etiqueta footer representa información asociada con y generalmente se encuentran en la parte inferior de un documento, como derechos de autor, fecha de publicación, información del autor o una lista de enlaces relacionados.

<nav> . . . </nav>
La etiqueta nav representa una sección del documento destinado para la navegación, los enlaces dentro de un elemento de navegación pueden ser para otros documentos o para otras áreas dentro del documento actual.

<ul> . . . </ul>
La etiqueta ul define una lista desordenada, en la que el orden de los elementos de la lista (li) no es importante.

<ol> . . . </ol>
La etiqueta ol define una lista ordenada (numerada) que consta de uno o más elementos de lista (li).
Por defecto siempre va a querer numerar los items que la componen

<li> . . . </li>
La etiqueta li define un elemento en una lista, se usa dentro de las etiquetas ol y ul.

<a> . . . </a>
La etiqueta a define un anclaje que se puede usar como un enlace de hipertexto o un fragmento con nombre dentro del documento.

<html> . . . </html>
La etiqueta html es el elemento raíz de los documentos HTML, lo que significa que todos, absolutamente todos los demás elementos están contenidos en él.

<head> . . . </head>
La etiqueta head contiene información sobre el documento, una colección de metadatos, debe incluir una etiqueta title que proporcione una descripción del documento, también puede incluir: base, link, meta, noscript, script y style.

<body> . . . </body>
La etiqueta body, valga la redundancia, contiene el contenido del documento.
<hn> . . . </hn> (h1, h2, h3, h4, h5, h6)
Las etiquetas hn especifica un encabezado que describe brevemente la sección que presenta, hay seis niveles de encabezados, desde h1 (más importante) hasta h6 (menos importante). La sintaxis HTML requiere que los encabezados aparezcan en orden (por ejemplo, un h2 no debe preceder a h1) para una estructura de documento adecuada.

<figure> . . . </figure>
La etiqueta figure nos indica algún conjunto de contenido independiente que se hace referencia desde el contenido principal, como ilustraciones, ejemplos de códigos, diagramas y poemas.

<img/>
La etiqueta img representa una imagen en el contenido.

<article> . . . </article>
La etiqueta article representa una pieza de contenido independiente, ya sea un artículo de revista, una publicación de blog, un comentario de un lector.

<p> . . . </p>
La etiqueta p denota un párrafo, pueden contener texto y elementos en línea, pero no pueden contener otros elementos de bloque, incluidos otros párrafos.

<small> . . . </small>
La etiqueta small nos indica un apéndice o una nota al margen al texto principal, como por ejemplo la “letra pequeña” legal en la parte inferior del documento.

<strong> . . . </strong>
La etiqueta strong indica que una palabra o frase es importante o que requiere atención adicional (generalmente se muestra en negrita).


Etiquetas y definiciones

<!doctype html> Define que el documento esta bajo el estandar de HTML 5

<head> Representa una colección de metadatos acerca del documento, incluyendo enlaces a, o definiciones de, scripts y hojas de estilo.

<title> Define el título del documento, el cual se muestra en la barra de título del navegador o en las pestañas de página. Solamente puede contener texto y cualquier otra etiqueta contenida no será interpretada.

<base> Define la URL base para las URLs relativas en la página.

<link> Usada para enlazar JavaScript y CSS externos con el documento HTML actual.

<meta> Define los metadatos que no pueden ser definidos usando otro elemento HTML.

<style> Etiqueta de estilo usada para escribir CSS en línea.

<body> Representa el contenido principal de un documento HTML. Solo hay un elemento <body> en un documento.

<section> Define una sección en un documento

<nav> Define una sección que solamente contiene enlaces de navegación

<article> Define contenido autónomo que podría existir independientemente del resto del contenido.

<aside> Define algunos contenidos vagamente relacionados con el resto del contenido de la página. Si es removido, el contenido restante seguirá teniendo sentido

<h1>,<h2>,<h3>,<h4>,<h5>,<h6>	Los elemento de cabecera implementan seis niveles de cabeceras de documentos; <h1> es la de mayor y <h6> es la de menor impotancia. Un elemento de cabecera describe brevemente el tema de la sección que introduce.

<header> Define la cabecera de una página o sección. Usualmente contiene un logotipo, el título del sitio Web y una tabla de navegación de contenidos.

<footer> Define el pie de una página o sección. Usualmente contiene un mensaje de derechos de autoría, algunos enlaces a información legal o direcciones para dar información de retroalimentación.

<address> Define una sección que contiene información de contacto.

<main> Define el contenido principal o importante en el documento. Solamente existe un elemento <main> en el documento.

<p>	Define una parte que debe mostrarse como un párrafo.

<ol>	Define una lista ordenada de artículos.

<ul>	Define una lista de artículos sin orden.

<li>	Define un artículo de una lista ennumerada.

<div> Representa un contenedor genérico sin ningún significado especial.
### Enlaces
Son un ancla, que puede ser una pagina interna o una pagina externa al website

### Favicons
Favicon Generator ayuda a que tu icono favicon tenga máxima compatibilidad en todos los navegadores posibles de manera casi automatica.

Si lo haces manual tendrás que exportar tu icono favicon a cada resolucion aceptada para cada tipo de display y cada navegador. Todo uno por uno. Incluso puede que se te olvide colocar alguno.

#### UTF-8
UTF-8 es la forma más utilizada para representar texto Unicode en páginas web, y siempre debemos usarla al crear nuestras páginas web.
Pero, ¿Qué es Unicode?
Unicode es un estándar universal de codificación de caracteres que se utiliza para admitir caracteres no compatibles con ASCII.

#### Compresor de imagenes
En el caso de las imágenes, les recomiendo comprimirlas para que la página web cargue más rápido. El compresor que más utilizo y me ha dado grandes resultados ha sido: https://compressor.io

## figure
La etiqueta <figure> se utiliza para «vincular» la imagen a un pequeño texto descriptivo de la misma (conocido como caption).
El beneficio es semántico. El navegador sabrá de la relación entre esa imagen y ese texto.
No es necesario utilizar <figure> si tu imagen no necesita de ese refuerzo de texto.


### form
Es posible agregar reglas a los formularios como, por ejemplo, que un campo sea requerido para enviar el formulario.
El primer input al recibir el atributo “required” condicionara al segundo input a que no se podrá enviar el formulario hasta que se rellene el campo del primer input.

También existen los inputs de tipo email que mostraran al usuario un mensaje si no coloco un texto con formato de email, por ejemplo:

Un tip que me ha servido mucho, si por algún motivo no quieres que tu formulario se complete automáticamente, dentro de la etiqueta <form> puedes agregar el atributo autocomplete=“off”.

Apunte interesante, pero necesario a mi manera de ver:
Existen dos maneras de enviar los datos mediante un formulario, mediante el metodo post y el metodo get.

<form action="index.html"method="post">
<form action="index.html"method=""get>
La diferencia entre los métodos get y post radica en la forma de enviar los datos a la página cuando se pulsa el botón “Enviar”. Mientras que el método GET envía los datos usando la URL, el método POST los envía de forma que no podemos verlos (en un segundo plano u “ocultos” al usuario).



En esta clase se mostró como hacer una navegacion interna sin js, solo con html. Pero existe la posibilidad de animar la navegación al hacer scroll con ANIMATE SCROLL.



target
Especifica en donde desplegar la URL enlazada:

**self**: Carga la URL en el mismo contexto de navegación que el actual. Este es el comportamiento por defecto.
**blank**: Carga la URL en un nuevo contexto de navegación. Usualmente es una pestaña, sin embargo, los usuarios pueden configurar los navegadores para utilizar una ventana nueva en lugar de la pestaña.
**parent**: Carga la URL en el contexto de navegación padre (parent) del actual. Si no existe el padre, este se comporta del mismo modo que **self**.
**top**: Carga la URL en el contexto más alto de navegación (el cual es un ancestro del actual, y no tiene padre (parent)). Si no hay padre (parent), este se comporta del mismo modo que **self**.



Existen 3 formas de agregar estilos a nuestro sitio:

Estilo en línea (Inline):
Utiliza el atributo style.
No es para nada recomendado ya que Html sirve para definir la estructura y semántica del código y no el aspecto visual, aquí estaríamos mezclando todo.
Esta tiene mas peso que al usar la etiqueta style o utilizando un archivo externo

Estilo interno (Internal):
Utiliza una etiqueta style.
Separa en cierto modo, de una forma menos sucia (por decirlo así). Esta forma sigue sin ser la más recomendada porque seguimos mezclando lo que es el aspecto visual con la estructura y semántica del código.

Estilo externo (External):
Utilizando un archivo CSS externo al documento HTML.
Esta es la forma más recomendada porque estamos separando totalmente la estructura y semántica con el aspecto visual.

Orden de los estilos en cascada por prioridad:

Estilo Inline.
Estilo externo o interno (dependen de la posición en la que se declaren en el html, recordar que van en “cascada”).
Estilo por defecto del navegador.
Se puede utilizar !important para romper cascadas y priorizar (aunque no es recomendable).

### Estructura CSS
También recordar que existen varios tipos de selectores:
1. Selector de etiqueta: refiere a etiquetas HTML, como el ejemplo de la imagen.
2. Selector descendiente: refiere a etiquetas HTML de forma hereditaria.
3. Selector de id: refiere a atributos id de etiquetas HTML.
4. Selector de class (clase): refiere a atributos class de etiquetas HTML.

Selector de etiqueta: selecciona únicamente la etiqueta que escribimos.
Ej:

/*si ponemos el siguiente código*/
a {
color: blue;
}
/*Nos aplicará un color azul a todas las etiquetas de ancla en el documento HTML*/
Selector descendente: Ej:

bodyheaderdivnavolli a{
	color: green;
}
/*nos aplicará el estilo únicamente a las etiquetas de ancla (<a>) que estén dentro de <li>*/
Selector de Id: selecciona únicamente el elemento con ese id
Ej:

/*supongamos que tenemos una etiqueta de párrafo con la id "parrafo1"...*/

#parrafo1{
	color: blue;
}

/*Nos aplicará el estilo únicamente a ese párrafo con id "parrafo1", PD las id son únicas no puedes poner una misma id en dos etiquetas distintas*/
Selector de clase: Este selector aplicará los estilos a todas las etiquetas con la misma clase independientemente de su Id o tipo de etiqueta.

Ej:
supongamos que tenemos una etiqueta de ancla (<a>), una de párrafo (<p>) y una de titulo 2 (<h2>) con la clase “importante”…

.importante {
	color: pink;
}
Este código pondrá de color rosado el texto de las etiquetas con esta clase, en este ejemplo estas son: (<a>), (<p>) y (<h2>).




Recordar:

Los id deben son únicos, es decir, no se pueden repetir.
Las clases si se pueden repetir.



Cuando desarrollamos una página web, notamos que ésta se ve diferente según el navegador que utilicemos, una alternativa es Normalize.css.
Pero ¿Qué es Normalize.css?
Normalize.css es un pequeño archivo CSS que proporciona una mejor coherencia entre navegadores en el diseño predeterminado de los elementos HTML.



### Unidades de medida y colores
Podemos representar un color de 3 formas dentro de CSS:

Palabra clave: red, blue, pink, etc.
Hexadecimales: 0123456789ABCDEF
hls() hlsa()
#000000 = Negro
#FFFFFF = Blanco
- Se representan por grupos de 2 -> Primeros dos representan Red, siguientes dos representan Green, siguientes dos representan Blue
- El '0' representa ausencia de color
- La 'F' representa que se posee toda la luminosidad que refleja color blanco


#FF0000 = Rojo
#00FF00 = Verde
#0000FF = Azul
Para obtener un color más exacto se utiliza rgb o rgba:

rgb(0, 200, 145)
rgba(0, 50, 70, 0.5) para obtener transparencia

La unidad de medida por excelencia dentro del mundo digital es el pixel
¿Qué es un pixel?
La menor unidad homogenea en color que forma parte de una imagen digital.


En realidad si tiene impacto usar HEX o RGB dentro de los navegadores…
La mejor compatibilidad la tiene RGB, pues todos los navegadores soportan el rango 0-255
Por otro lado con RGB se pueden obtener una pequeña gama más amplia a diferencia de HEX.
Sí, es cierto que es más común HEX, pero por mejor compatibilidad se recomienda RGB.

>Los tags html tambien tienen estado: hover, active, focus, focus-within, visited


los colores HLS = equivalen a (tono, saturación, luminosidad), que le permite declarar los colores con el uso de estos tres parámetros:

Hue = tom, Saturation = saturacion and Lightness = luminosidade

se usan asi
selector { color: hsl(120, 75%, 50%); }

el primer valor del ángulo sigue las reglas de la trigonometría para medir los ángulos, tiene limites de 0 grados a 360 grados, y no se admiten numeros negativos.
Ej: 120 grados, 45 grados, 0 grados, 360grados

El segundo valor es para la saturación (saturación) del color. Su valor se expresa en porcentaje. Un valor igual al 100% representa saturación total del color y 0 es un ligero sombreado gris de saturación

**El tercer valor** es para el brillo (ligereza). Su valor se expresa en porcentaje. Un valor igual al 100% resulta en color blanco y 0 en color negro, siendo el 50% el valor normal.

Los colores de HSLA = equivalen a (tonalidad, saturación, ligereza, alfa-opacity) es una manera extendida de la declaración HSL en la que un cuarto argumento define la opacidad del color. Este cuarto argumento es un número decimal entre 0 y 1.

se rige a las mismas reglas que el HLS, pero incluyendo la opacidad que, este **campo A (opacidad alfa)** admite decimales de 0 a 1 siendo 0 transparentes y 1 opaco. Los valores decimales se escriben con un punto de punto. Ejemplo: 0.5

### Fonts
line-height para modificar el alto de linea
font-size para modificar el tamaño de la fuente
font-weight para modificar el tipo de fuente
font-style para modificar el estilo de la fuente
letter-spacing para modificar el espacio entre letras
text-transform para transformar la fuente (mayúsculas, minúsculas, etc)
text-decoration para modificar la decoración de la fuente

### Background
background-color para agregar unn color de fondo
color para agregar un color al texto
text-decoration para modificar la decoración del texto
background-image para agregar una imagen de fondo
background-size para modificar el tamaño del background asignado
background-repeat para modificar la repetición del backgound asignado
background-position para modificar la posición del bakground asignado

### Bordes
Para asignar un borde:

border: tamaño tipo estilo
Para asignar el borde solo en una parte podemos usar:
border-top
border-right
border-bottom
border-left

Para redondear el borde:

border-radius: tamaño

### Margenes
La propiedad CSS margin establece el margen para los cuatro lados. Es una abreviación para evitar tener que establecer cada lado por separado con las otras propiedades de margen: margin-top, margin-right, margin-bottom y margin-left.

Margin collapsing: Cuando dos elementos tienen un margen y están juntos, no se suman sino que se mantiene como dominante el de aquel elemento que tengan el mayor margen. Ejemplo div-A tiene un margen-bottom: 50px; y div-B tiene un margin-top: 20px; El margen total no es de 70px sino que se mantiene el mayor por lo tanto sería de 50px.

Nota: Un margen no empuja a otro. El margen es un espaciado fuera de los elementos.

### Padding
La propiedad CSS padding establece el espacio de relleno requerido por todos los lados de un elemento. El área de padding es el espacio entre el contenido del elemento y su borde (border) no se permiten valores negativos.

La propiedad padding es un atajo para evitar la asignación de cada lado por separado (padding-top, padding-right, padding-bottom, padding-left).

padding: arriba derecha abajo izquierda;
Diferencias de las propiedades padding y margin:

Margin es el margen que hay desde un elemento hasta los que tenga al lado.
Padding es el espacio que hay en un contenedor entre el contenido y los bordes del contenedor.

El padding es un espaciado dentro de los elementos.


### Modelo de caja
El modelo de caja esta compuesto por 3 elementos fundamentales: Tamaño del elemento, el padding y el margin, estos elementos pueden formar el espacio de ubicación del elemento

EL modelo de caja puede ser alterado mediante display especiales o propiedad especial que ayude a leer el modelo de caja

Una de esas propiedades es box-sizing : border-box lo que permite que siempre sin importar el borde o el paddin ocupe un mismo tamaño, siempre

El modelo de cajas o “box model” es seguramente la característica más importante del lenguaje de hojas de estilos CSS, ya que condiciona el diseño de todas las páginas web. El modelo de cajas es el comportamiento de CSS que hace que todos los elementos de las páginas se representen mediante cajas rectangulares.

Las cajas de una página se crean automáticamente. Cada vez que se inserta una etiqueta HTML, se crea una nueva caja rectangular que encierra los contenidos de ese elemento. La siguiente imagen muestra las tres cajas rectangulares que crean


### Display
Todos los elementos tienen algun elemento display, incluyendo elementos que no se ven

Display Block: Hace que un elemento quiera ocupar todo el ancho posible sin importar la cantidad de contenido

Display Inline : Permite apilar al lado los elementos que tenga el mismo display, esperando un poco mas de contenido hacia su lado, es decir va creciendo deacuerdo a la cantidad de contenido

Estos elementos son el comportamientop basico de las etiquetas

Para los elementos que queremos que no se vean podemos usar:
display: none;

La propiedad display es una de las propiedades CSS más infrautilizadas. Aunque todos los diseñadores conocen esta propiedad y utilizan sus valores inline, block y none, las posibilidades de display son mucho más avanzadas.

De hecho, la propiedad display es una de las más complejas de CSS 2.1, ya que establece el tipo de la caja que genera cada elemento. La propiedad display es tan compleja que casi ningún navegador es capaz de mostrar correctamente todos sus valores.

El valor más sencillo de display es none que hace que el elemento no genere ninguna caja. El resultado es que el elemento desaparece por completo de la página y no ocupa sitio, por lo que los elementos adyacentes ocupan su lugar. Si se utiliza la propiedad display: none sobre un elemento, todos sus descendientes también desaparecen por completo de la página.

Si se quiere hacer un elemento invisible, es decir, que no se vea pero que siga ocupando el mismo sitio, se debe utilizar la propiedad visibility. La propiedad display: none se utiliza habitualmente en aplicaciones web dinámicas creadas con JavaScript y que muestran/ocultan contenidos cuando el usuario realiza alguna acción como pulsar un botón o un enlace.

Los otros dos valores más utilizados son block e inline que hacen que la caja de un elemento sea de bloque o en línea respectivamente.
Display block : toma todo el ancho

Display inline: espera elementos a su costado en algunos casos sin respetar valores que se le asignen a la propiedad width

Display inline-block: espera elementos a su costado y toma como ancho los valores asignados en la propiedad width
Display Inline : Permite apilar al lado los elementos que tenga el mismo display, esperando un poco mas de contenido hacia su lado, es decir va creciendo de acuerdo a la cantidad de contenido

Display flex: Lo puedes ver como un conjunto de propiedades que van a hacer mas dinamica la forma en que quieras alinear los elementos en el DOM

block -> ocupa el 100% del su ancho disponible, lo cual lo hace perfecto para elementos que sean contenedores
inline -> ocupa el ancho respectivo al contenido que tenga su elemento, por lo tanto si un elemento tiene un texto lo suficientemento largo dentro de el va ocupar todo el ancho, sin excepcion, aunque le apliquemos un width
inline-block -> hace lo mismo que inline pero respeta el width que le dimos al elemento

### Flexbox
Tradicionalmente, en CSS se ha utilizado el posicionamiento (static, relative, absolute…), los elementos en línea o en bloque (y derivados) o los float, lo que a grandes rasgos no dejaba de ser un sistema de creación de diseños bastante tradicional que no encaja con los retos que tenemos hoy en día (sistemas de escritorio, dispositivos móviles, múltiples resoluciones, etc…).

Flexbox es un sistema de elementos flexibles que llega con la idea de olvidar estos mecanismos y acostumbrarnos a una mecánica más potente, limpia y personalizable, en la que los elementos HTML se adaptan y colocan automáticamente y es más fácil personalizar los diseños.

La propiedad display cuando toma el valor flex, se debe recordar que esta propiedad sólo afecta a los componentes html hijos directamente. En tal sentido sí dentro de lo componentes html hijo hay otros componentes html ésta misma propiedad no afectará

Al aplicar la propiedad display: flex los elementos del contenedor se ubicarán en filas, esto se debe a que el valor predeterminado de su distribución es flex-direction: row
La propiedad de flex-direction especifica la dirección de los elementos flexibles. Nota: si el elemento no es un elemento flexible, la propiedad de flex-direction no tiene efecto.

Propiedad Shrink para evitar que los elementos hijo ajuste automáticamente el ancho de dicho elemento, para mantener las propiedades de ancho de cada elemento hijo (cuyo padre sea FLEX y dicho hijo también sea FLEX), es con: flex-shrink: 0; => esto es el factor de encogimiento.

flex-shrink: 0 - 1;

Esta propiedad se aplica a los hijos, y determina que tan flexibles pueden ser estos, siendo 0 nada flexibles, es decir no se va a modificar para nada el ancho o el alto, o 1 que indica que si pueden ser flexibles

La propiedad flex-wrap de CSS especifica si los elementos "hijos" son obligados a permanecer en una misma línea o pueden fluir en varias líneas. tiene dos valores. flex-wrap: wrap; pueden fluir en varias líneas y flex-wrap: nowrap; por defecto, no pueden fluir a otras lineas
