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
