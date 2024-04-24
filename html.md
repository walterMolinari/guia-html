# 1. Introducción a HTML:

## `¿Qué es HTML?`

HTML, o HyperText Markup Language, es el lenguaje estándar utilizado para crear y diseñar páginas web. Consiste en una serie de etiquetas que definen la estructura y el contenido de una página web. Las etiquetas HTML se utilizan para marcar diferentes partes de una página, como encabezados, párrafos, imágenes, enlaces, formularios, etc.

HTML surgió en la década de 1980 como parte del proyecto World Wide Web (WWW) liderado por Tim Berners-Lee en el CERN (Organización Europea para la Investigación Nuclear). En 1989, Berners-Lee propuso un sistema de gestión de información basado en hipertexto para compartir y distribuir documentos científicos entre investigadores. Este sistema se convirtió en la base de lo que eventualmente se conocería como la World Wide Web.

Para implementar este sistema, Berners-Lee creó el lenguaje HTML como un medio para estructurar y formatear documentos para la web. HTML permitía a los usuarios crear documentos con enlaces (hipervínculos) que conectaban diferentes partes del documento y con otros documentos, lo que facilitaba la navegación entre ellos.

La primera especificación formal de HTML, llamada "HTML 2.0", fue publicada en 1995 por el World Wide Web Consortium (W3C), una organización fundada por Berners-Lee para estandarizar y promover tecnologías web. Desde entonces, HTML ha experimentado varias revisiones y actualizaciones, con HTML5 siendo la versión más reciente y ampliamente utilizada en la actualidad.

A lo largo de los años, HTML ha evolucionado para incluir nuevas características y capacidades, lo que lo convierte en un lenguaje versátil y poderoso para la creación de contenido web. Su evolución ha sido fundamental para el desarrollo y la expansión de la World Wide Web tal como la conocemos hoy en día.

## `Estructura básica de un documento HTML`

1. **Etiquetas**: Son elementos básicos de HTML y se utilizan para estructurar el contenido de la página. Por ejemplo, `<p>` se utiliza para párrafos, `<h1>` a `<h6>` para encabezados de diferentes niveles, `<img>` para imágenes, `<a>` para enlaces, etc.

2. **Atributos**: Las etiquetas pueden tener atributos que proporcionan información adicional sobre el elemento. Por ejemplo, el atributo `src` se utiliza en la etiqueta `<img>` para especificar la ruta de la imagen que se debe mostrar.

3. **Anidamiento**: Las etiquetas HTML pueden anidarse dentro de otras etiquetas. Esto permite crear una estructura jerárquica para el contenido de la página.

4. **Modelo de caja**: Es un concepto importante en HTML y CSS que define cómo se representan visualmente los elementos en una página web. Cada elemento HTML se considera una caja rectangular con propiedades como ancho, alto, margen, borde y relleno.

5. **Versiones**: HTML ha evolucionado con el tiempo. Las versiones más recientes incluyen HTML5, que proporciona nuevas características y mejoras, como soporte integrado para audio y video, elementos semánticos adicionales y capacidades de almacenamiento local.

# 2. Estructura de una página HTML:

## `Encabezados (headings)`

Los encabezados en HTML son etiquetas que se utilizan para definir los títulos y subtítulos dentro de una página web. Estas etiquetas van desde `<h1>` hasta `<h6>`, donde `<h1>` representa el título más importante y `<h6>` el menos importante. Aquí tienes un ejemplo de cómo se utilizan:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejemplo de Encabezados HTML</title>
  </head>
  <body>
    <h1>Este es un título de nivel 1</h1>
    <h2>Este es un título de nivel 2</h2>
    <h3>Este es un título de nivel 3</h3>
    <h4>Este es un título de nivel 4</h4>
    <h5>Este es un título de nivel 5</h5>
    <h6>Este es un título de nivel 6</h6>
  </body>
</html>
```

Cada nivel de encabezado tiene su propio estilo predeterminado, que suele estar relacionado con su importancia semántica y visual. Los motores de búsqueda también consideran los encabezados para entender la estructura de la página y su contenido. Es importante usarlos correctamente para mejorar la accesibilidad y el SEO de tu sitio web.

## `Párrafos (paragraphs)`

Los párrafos en HTML se definen mediante la etiqueta `<p>`. Esta etiqueta se utiliza para estructurar y separar el contenido textual en bloques de texto coherentes.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejemplo de Párrafos HTML</title>
  </head>
  <body>
    <p>
      Este es un párrafo de ejemplo. Los párrafos son útiles para organizar y
      presentar el contenido de manera clara y legible.
    </p>

    <p>
      Este es otro párrafo. Puedes escribir varios párrafos en una página para
      dividir el contenido en secciones más pequeñas y fáciles de entender.
    </p>
  </body>
</html>
```

Los navegadores web automáticamente añaden un espacio en blanco antes y después de los párrafos para mejorar la legibilidad visual. Los párrafos son elementos fundamentales para estructurar el contenido textual en HTML y se utilizan comúnmente en la mayoría de las páginas web para presentar información de manera organizada.

## `Listas (lists)`

Hay dos tipos principales de listas: listas ordenadas y listas no ordenadas.

### Listas no ordenadas (`<ul>`)

Las listas no ordenadas se crean con la etiqueta `<ul>`, y cada elemento de la lista se define con la etiqueta `<li>`. Los elementos de una lista no ordenada se muestran con viñetas por defecto.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejemplo de Lista No Ordenada HTML</title>
  </head>
  <body>
    <h2>Lista de Compras</h2>
    <ul>
      <li>Manzanas</li>
      <li>Plátanos</li>
      <li>Naranjas</li>
    </ul>
  </body>
</html>
```

### Listas ordenadas (`<ol>`)

Las listas ordenadas se crean con la etiqueta `<ol>`, y cada elemento de la lista se define también con la etiqueta `<li>`. Los elementos de una lista ordenada se numeran automáticamente.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejemplo de Lista Ordenada HTML</title>
  </head>
  <body>
    <h2>Top 3 del Podio</h2>
    <ol>
      <li>Medalla de Oro</li>
      <li>Medalla de Plata</li>
      <li>Medalla de Bronce</li>
    </ol>
  </body>
</html>
```

Tanto las listas ordenadas como las no ordenadas son muy útiles para organizar y presentar información de forma estructurada en una página web.

## `Enlaces (links)`

Los enlaces en HTML se crean mediante la etiqueta `<a>`, que representa un hiperenlace a otra página web, un archivo, una ubicación en la misma página o cualquier otro recurso en línea.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejemplo de Enlace HTML</title>
  </head>
  <body>
    <h2>Enlaces</h2>
    <p>
      Visita la página de <a href="https://www.ejemplo.com">Ejemplo</a> para
      obtener más información.
    </p>
  </body>
</html>
```

En este ejemplo, el texto "Ejemplo" es el texto visible del enlace, y el atributo `href` especifica la URL a la que se enlaza el texto.

También es posible crear enlaces internos en una página web, lo que se conoce como anclajes. Esto permite a los usuarios navegar rápidamente a diferentes secciones de la misma página. Por ejemplo:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejemplo de Enlace Interno HTML</title>
  </head>
  <body>
    <h2>Tabla de Contenido</h2>
    <ul>
      <li><a href="#seccion1">Sección 1</a></li>
      <li><a href="#seccion2">Sección 2</a></li>
      <li><a href="#seccion3">Sección 3</a></li>
    </ul>

    <h2 id="seccion1">Sección 1</h2>
    <p>Contenido de la sección 1.</p>

    <h2 id="seccion2">Sección 2</h2>
    <p>Contenido de la sección 2.</p>

    <h2 id="seccion3">Sección 3</h2>
    <p>Contenido de la sección 3.</p>
  </body>
</html>
```

En este ejemplo, los enlaces en la lista de contenido apuntan a las secciones de la misma página utilizando el atributo `href` con el ID de cada sección como destino. Las secciones se identifican mediante el atributo `id`.

# 3. Formateo de texto:

## `Negrita, cursiva y subrayado`

En HTML, puedes aplicar formato de texto como negrita, cursiva y subrayado utilizando etiquetas específicas. Aquí tienes ejemplos de cómo hacerlo:

### Negrita (`<strong>` o `<b>`)

Puedes usar las etiquetas `<strong>` o `<b>` para hacer que el texto aparezca en negrita:

```html
<p>Este es un texto <strong>en negrita</strong>.</p>
<p>Este es otro texto <b>en negrita</b>.</p>
```

Ambas etiquetas (`<strong>` y `<b>`) tienen el mismo efecto visual. Sin embargo, semánticamente, `<strong>` se considera más apropiado para indicar énfasis fuerte o importancia, mientras que `<b>` es simplemente para hacer que el texto aparezca en negrita.

### Cursiva (`<em>` o `<i>`)

Puedes usar las etiquetas `<em>` o `<i>` para hacer que el texto aparezca en cursiva:

```html
<p>Este es un texto <em>en cursiva</em>.</p>
<p>Este es otro texto <i>en cursiva</i>.</p>
```

De manera similar a las etiquetas de negrita, `<em>` y `<i>` tienen el mismo efecto visual, pero `<em>` se considera más semánticamente correcto para indicar énfasis o importancia.

### Subrayado (`<u>`)

Para aplicar subrayado a un texto, puedes usar la etiqueta `<u>`:

```html
<p>Este es un texto <u>subrayado</u>.</p>
```

Sin embargo, es importante tener en cuenta que el subrayado a menudo se asocia con enlaces en la web, por lo que es una buena práctica evitar usar subrayado para evitar confusiones con los enlaces. En su lugar, es preferible utilizar otros métodos para resaltar texto, como negrita o cursiva.

## `Cambios de tamaño de texto`

Para cambiar el tamaño del texto en HTML, puedes utilizar la propiedad CSS `font-size` o las etiquetas `<span>` y `<font>` con el atributo `style`. Aquí tienes ejemplos de cómo hacerlo:

### Utilizando la propiedad CSS `font-size`:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejemplo de Cambio de Tamaño de Texto HTML (CSS)</title>
    <style>
      .grande {
        font-size: 24px;
      }
      .pequeño {
        font-size: 14px;
      }
    </style>
  </head>
  <body>
    <p>Este es un texto con tamaño normal.</p>
    <p class="grande">Este es un texto más grande.</p>
    <p class="pequeño">Este es un texto más pequeño.</p>
  </body>
</html>
```

En este ejemplo, se define una clase `.grande` con un tamaño de fuente de 24px y una clase `.pequeño` con un tamaño de fuente de 14px. Luego, estas clases se aplican a los elementos de párrafo correspondientes.

### Utilizando las etiquetas `<span>` y `<font>` con el atributo `style`:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejemplo de Cambio de Tamaño de Texto HTML (Etiquetas)</title>
  </head>
  <body>
    <p>Este es un texto con tamaño normal.</p>
    <p><span style="font-size: 24px;">Este es un texto más grande.</span></p>
    <p><font size="2">Este es un texto más pequeño.</font></p>
  </body>
</html>
```

En este ejemplo, se utiliza una etiqueta `<span>` con el atributo `style` para aplicar un tamaño de fuente específico, y también se usa la etiqueta `<font>` con el atributo `size` para especificar un tamaño de fuente relativo. Sin embargo, ten en cuenta que la etiqueta `<font>` está obsoleta en HTML5 y su uso se desaconseja en favor de CSS.

## `Uso de etiquetas de cita y código`

Para representar citas y código en HTML, puedes usar las etiquetas `<blockquote>` y `<code>`, respectivamente.

### Etiqueta de cita `<blockquote>`:

La etiqueta `<blockquote>` se utiliza para representar bloques de texto citados de otra fuente. El navegador web generalmente los mostrará con un margen izquierdo adicional.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejemplo de Etiqueta de Cita HTML</title>
  </head>
  <body>
    <p>El poeta Robert Frost dijo una vez:</p>
    <blockquote>
      <p>
        Dos caminos divergieron en un bosque, y yo—<br />
        yo tomé el menos transitado,<br />
        y eso hizo toda la diferencia.
      </p>
    </blockquote>
  </body>
</html>
```

### Etiqueta de código `<code>`:

La etiqueta `<code>` se utiliza para representar fragmentos de código dentro de un párrafo u otro bloque de texto. Los navegadores generalmente muestran el texto dentro de `<code>` con una fuente de monoespaciado, y algunos pueden aplicar otros estilos como resaltar la sintaxis.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejemplo de Etiqueta de Código HTML</title>
  </head>
  <body>
    <p>
      El siguiente fragmento de código en Python muestra cómo imprimir "Hola,
      mundo!":
    </p>
    <code>print("Hola, mundo!")</code>
  </body>
</html>
```

Estas etiquetas son útiles para proporcionar estructura semántica al contenido y mejorar la legibilidad de las citas y fragmentos de código dentro de una página web.

# 4. Imágenes:

## `Insertar imágenes en una página HTML`

Para insertar imágenes en una página HTML, utilizas la etiqueta `<img>` y especificas la ruta de la imagen en el atributo `src`.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejemplo de Inserción de Imagen HTML</title>
  </head>
  <body>
    <h2>Una Imagen</h2>
    <img src="imagen.jpg" alt="Descripción de la imagen" />
  </body>
</html>
```

En este ejemplo, "imagen.jpg" es la ruta de la imagen que quieres mostrar. El atributo `alt` proporciona un texto alternativo que se mostrará si la imagen no se puede cargar, y también es útil para la accesibilidad, ya que las herramientas de lectura de pantalla pueden leer este texto a los usuarios que dependen de ellas.

Aquí tienes algunos detalles adicionales a considerar:

- **Ruta de la imagen:** La ruta puede ser una URL si la imagen está alojada en la web, o una ruta relativa o absoluta si la imagen está en el mismo servidor o en el sistema de archivos local.
- **Dimensiones de la imagen:** Puedes especificar las dimensiones de la imagen usando los atributos `width` y `height`. Esto es útil para mejorar el rendimiento de la carga de la página al reservar espacio para la imagen antes de que se cargue.
- **Formatos de imagen compatibles:** Los formatos de imagen comunes que se pueden usar en la web son JPG, PNG y GIF, aunque otros formatos como SVG también son posibles dependiendo de la necesidad y compatibilidad del navegador.

Asegúrate de tener los derechos adecuados para usar la imagen en tu página web si no la has creado tú mismo, y también optimiza el tamaño y la calidad de la imagen para mejorar la carga de la página.

## `Atributos de las etiquetas de imagen.`

Los atributos más comunes que se utilizan con la etiqueta `<img>` en HTML son los siguientes:

1. **src:** Este atributo especifica la ruta de la imagen que se va a mostrar. Puede ser una URL si la imagen está en línea, o una ruta relativa o absoluta si la imagen está en el mismo servidor o en el sistema de archivos local.

2. **alt:** Proporciona un texto alternativo que se muestra cuando la imagen no se puede cargar. También es útil para la accesibilidad, ya que las herramientas de lectura de pantalla pueden leer este texto a los usuarios que dependen de ellas.

3. **width:** Este atributo especifica el ancho de la imagen en píxeles. Puedes establecer el valor en un número entero para definir el ancho de la imagen.

4. **height:** Este atributo especifica la altura de la imagen en píxeles. Puedes establecer el valor en un número entero para definir la altura de la imagen.

5. **title:** Proporciona un texto de título que se muestra cuando el usuario pasa el cursor sobre la imagen. Este texto aparecerá como una sugerencia emergente.

6. **loading:** Este atributo HTML5 especifica cómo se debe cargar la imagen. Los posibles valores son "auto", "eager" y "lazy". "Auto" es el valor predeterminado, que indica que el navegador debe decidir cuándo cargar la imagen. "Eager" indica que la imagen debe cargarse tan pronto como sea posible. "Lazy" indica que la imagen debe cargarse solo cuando esté cerca del área visible del navegador.

7. **decoding:** Este atributo HTML5 especifica cómo debe decodificarse la imagen antes de que se muestre. Los posibles valores son "async", "sync" y "auto". "Async" indica que el navegador debe decodificar la imagen de manera asíncrona. "Sync" indica que la imagen debe decodificarse de manera síncrona. "Auto" es el valor predeterminado y deja que el navegador decida.

Estos son algunos de los atributos más comunes que se utilizan con la etiqueta de imagen en HTML. Dependiendo de la situación y de los requisitos específicos, también pueden utilizarse otros atributos.

# 5. Tablas:

## `Crear tablas básicas.`

Para crear tablas básicas en HTML, puedes utilizar las etiquetas `<table>`, `<tr>` (fila), `<th>` (encabezado de tabla) y `<td>` (celda de datos). Aquí tienes un ejemplo de cómo crear una tabla simple con tres filas y tres columnas:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejemplo de Tabla HTML</title>
  </head>
  <body>
    <h2>Tabla Básica</h2>
    <table border="1">
      <tr>
        <th>Encabezado 1</th>
        <th>Encabezado 2</th>
        <th>Encabezado 3</th>
      </tr>
      <tr>
        <td>Dato 1</td>
        <td>Dato 2</td>
        <td>Dato 3</td>
      </tr>
      <tr>
        <td>Dato 4</td>
        <td>Dato 5</td>
        <td>Dato 6</td>
      </tr>
    </table>
  </body>
</html>
```

En este ejemplo, la etiqueta `<table>` define la tabla. Cada fila de la tabla se define con la etiqueta `<tr>`. Dentro de cada fila, las celdas de encabezado se definen con la etiqueta `<th>`, mientras que las celdas de datos se definen con la etiqueta `<td>`. El atributo `border="1"` se utiliza para agregar bordes a la tabla.

Este es un ejemplo básico de una tabla HTML. Puedes personalizarla aún más utilizando CSS para aplicar estilos, colores y otros elementos de diseño según tus necesidades.

## `Estilizar tablas con CSS.`

Para estilizar tablas con CSS, puedes utilizar selectores específicos para dirigirte a elementos de la tabla, como `<table>`, `<tr>`, `<th>`, y `<td>`.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejemplo de Estilizado de Tabla con CSS</title>
    <style>
      /* Estilos para la tabla */
      table {
        width: 100%;
        border-collapse: collapse;
      }

      /* Estilos para las celdas de encabezado */
      th {
        background-color: #f2f2f2;
        border: 1px solid #ddd;
        padding: 8px;
        text-align: left;
      }

      /* Estilos para las celdas de datos */
      td {
        border: 1px solid #ddd;
        padding: 8px;
        text-align: left;
      }

      /* Estilos para filas impares */
      tr:nth-child(odd) {
        background-color: #f9f9f9;
      }

      /* Estilos para filas al pasar el cursor */
      tr:hover {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
    <h2>Tabla Estilizada con CSS</h2>
    <table>
      <tr>
        <th>Encabezado 1</th>
        <th>Encabezado 2</th>
        <th>Encabezado 3</th>
      </tr>
      <tr>
        <td>Dato 1</td>
        <td>Dato 2</td>
        <td>Dato 3</td>
      </tr>
      <tr>
        <td>Dato 4</td>
        <td>Dato 5</td>
        <td>Dato 6</td>
      </tr>
      <tr>
        <td>Dato 7</td>
        <td>Dato 8</td>
        <td>Dato 9</td>
      </tr>
    </table>
  </body>
</html>
```

En este ejemplo:

- `table`: Se establece un ancho del 100% para que la tabla se ajuste al ancho del contenedor.
- `border-collapse: collapse;`: Esto hace que los bordes de las celdas se fusionen en una sola línea.
- `th`: Se aplican estilos de fondo, bordes, relleno y alineación de texto a las celdas de encabezado.
- `td`: Se aplican estilos de bordes, relleno y alineación de texto a las celdas de datos.
- `tr:nth-child(odd)`: Aplica estilos de fondo a las filas impares.
- `tr:hover`: Aplica estilos de fondo a las filas cuando pasas el cursor sobre ellas.

Estos son solo algunos ejemplos básicos de cómo puedes estilizar una tabla con CSS. Puedes experimentar y agregar más estilos según tus necesidades y preferencias de diseño.

# 6. Formularios:

## `Crear formularios simples.`

Aquí tienes un ejemplo básico de cómo crear un formulario simple en HTML:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Formulario Simple</title>
  </head>
  <body>
    <h2>Formulario de Contacto</h2>
    <form action="/submit-form" method="post">
      <label for="nombre">Nombre:</label>
      <input type="text" id="nombre" name="nombre" required /><br /><br />

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required /><br /><br />

      <label for="mensaje">Mensaje:</label><br />
      <textarea
        id="mensaje"
        name="mensaje"
        rows="4"
        cols="50"
        required
      ></textarea
      ><br /><br />

      <input type="submit" value="Enviar" />
    </form>
  </body>
</html>
```

En este formulario:

- La etiqueta `<form>` define el formulario. El atributo `action` especifica la URL a la que se enviarán los datos del formulario cuando se envíe, y el atributo `method` especifica el método HTTP que se utilizará para enviar los datos (en este caso, "post").
- `<label>` se utiliza para etiquetar los campos de entrada. El atributo `for` de `<label>` debe coincidir con el valor del atributo `id` del campo de entrada asociado. Esto mejora la accesibilidad del formulario.

- `<input>` se utiliza para campos de entrada como texto (`type="text"`) y correo electrónico (`type="email"`). El atributo `required` indica que el campo es obligatorio.

- `<textarea>` se utiliza para campos de texto más grandes. Los atributos `rows` y `cols` especifican el número de filas y columnas del área de texto, respectivamente.

- `<input type="submit">` crea un botón de envío que permite al usuario enviar el formulario.

## `Campos de texto, botones y menús desplegables.`

Aquí tienes un ejemplo de un formulario simple que incluye campos de texto, botones y menús desplegables en HTML:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Formulario con Campos de Texto, Botones y Menús Desplegables</title>
  </head>
  <body>
    <h2>Formulario de Registro</h2>
    <form action="/submit-form" method="post">
      <label for="nombre">Nombre:</label>
      <input type="text" id="nombre" name="nombre" required /><br /><br />

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required /><br /><br />

      <label for="edad">Edad:</label>
      <input
        type="number"
        id="edad"
        name="edad"
        min="18"
        max="100"
        required
      /><br /><br />

      <label for="genero">Género:</label>
      <select id="genero" name="genero">
        <option value="masculino">Masculino</option>
        <option value="femenino">Femenino</option>
        <option value="otro">Otro</option></select
      ><br /><br />

      <label for="intereses">Intereses:</label><br />
      <input type="checkbox" id="interes1" name="interes1" value="deportes" />
      <label for="interes1">Deportes</label><br />
      <input type="checkbox" id="interes2" name="interes2" value="musica" />
      <label for="interes2">Música</label><br />
      <input type="checkbox" id="interes3" name="interes3" value="lectura" />
      <label for="interes3">Lectura</label><br /><br />

      <input type="submit" value="Enviar" />
      <input type="reset" value="Limpiar" />
    </form>
  </body>
</html>
```

Este formulario incluye:

- Campos de texto para nombre (`<input type="text">`), email (`<input type="email">`) y edad (`<input type="number">`). Todos los campos son obligatorios (`required`), y la edad tiene un rango mínimo y máximo (`min="18"` y `max="100"`).
- Un menú desplegable para el género (`<select>`) con opciones de "Masculino", "Femenino" y "Otro".
- Campos de checkbox (`<input type="checkbox">`) para los intereses, con opciones de "Deportes", "Música" y "Lectura".
- Botones de envío (`<input type="submit">`) y limpieza (`<input type="reset">`).

Puedes adaptar este formulario según tus necesidades, agregando más campos, validaciones y estilos CSS según sea necesario.

## `Métodos de envío de formularios.`

En HTML, los formularios pueden enviarse utilizando dos métodos principales: `GET` y `POST`.

1. **GET:**
   - El método `GET` envía los datos del formulario como parte de la URL.
   - Los datos del formulario son visibles en la URL, lo que significa que pueden ser guardados en el historial del navegador y en los registros del servidor web.
   - Se recomienda usar el método `GET` para enviar datos que no son sensibles, como consultas de búsqueda.
   - Los datos tienen una limitación en cuanto a la longitud de la URL que pueden contener.

```html
<form action="/submit-form" method="get">
  <!-- Campos de formulario -->
  <input type="submit" value="Enviar" />
</form>
```

2. **POST:**
   - El método `POST` envía los datos del formulario en el cuerpo de la solicitud HTTP.
   - Los datos del formulario no son visibles en la URL.
   - Se recomienda usar el método `POST` para enviar datos sensibles, como contraseñas o información de tarjetas de crédito.
   - No hay limitaciones en cuanto a la longitud de los datos que se pueden enviar con el método `POST`.

```html
<form action="/submit-form" method="post">
  <!-- Campos de formulario -->
  <input type="submit" value="Enviar" />
</form>
```

Ambos métodos son comunes y tienen sus casos de uso específicos. La elección entre `GET` y `POST` depende de la naturaleza de los datos que se están enviando y de los requisitos de seguridad y usabilidad de tu aplicación.
