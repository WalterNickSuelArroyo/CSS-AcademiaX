# 1. Presentacion

# 2. Prerequisitos

# 3. Sacarle mayor provecho al curso

# 4. Fuentes externas que pueden ayudar (google, stackoverfolw, chatgpt)

# 5. ¿Que es CSS?

**¿Qué es CSS y porqué debes aprenderlo?**

- CSS (Cascading Style Sheets) es un lenguaje de estilo utilizado para describir la apariencia y el formato de un documento escrito en HTML. Al utilizar CSS, puedes controlar la apariencia de varios elementos de HTML en un solo archivo de estilo, en lugar de tener que escribir el estilo para cada elemento individualmente. Esto hace que sea más fácil y rápido modificar la apariencia de un sitio web, y también hace que sea más fácil mantener y actualizar el sitio a lo largo del tiempo.

- Es importante aprender CSS porque es uno de los pilares de la creación de sitios web. Aunque puedes crear un sitio web básico usando solo HTML, CSS te permite darle estilo y diseño a tu sitio, lo que lo hace más atractivo y fácil de usar para los visitantes. Además, muchos trabajos relacionados con la creación de sitios web requieren conocimientos de CSS, por lo que aprender CSS puede ser beneficioso para tu carrera profesional.

 

**¿En dónde se utiliza CSS?**

CSS es utilizado en una amplia variedad de tecnologías y plataformas, incluyendo:

- Sitios web: La mayoría de los sitios web modernos utilizan CSS para dar estilo y diseño a sus páginas.

- Aplicaciones móviles: Muchas aplicaciones móviles utilizan CSS para controlar la apariencia de sus interfaces de usuario.

- Aplicaciones de escritorio: Algunas aplicaciones de escritorio también pueden utilizar CSS para dar estilo a sus interfaces de usuario.

- Presentaciones: Algunas herramientas de presentación, como Microsoft PowerPoint, permiten utilizar CSS para dar estilo a las diapositivas.

- Correo electrónico: Algunos programas de correo electrónico, como Microsoft Outlook, permiten utilizar CSS para dar estilo a los mensajes de correo electrónico.

- Aplicaciones de publicación digital: Las aplicaciones de publicación digital, como Adobe InDesign, pueden utilizar CSS para dar estilo a los documentos que se crean con ellas.

 

**¿Qué trabajos puedes conseguir al aprender CSS?**

Al aprender CSS, podrías considerar trabajar como:

- Diseñador/a web: Un diseñador/a web utiliza herramientas como HTML y CSS para crear y dar formato a sitios web.

- Desarrollador/a front-end: Un desarrollador/a front-end se encarga de la parte de un sitio web que los visitantes ven y interactúan, y utiliza tecnologías como HTML, CSS y JavaScript para crear la interfaz de usuario.

- Diseñador/a gráfico: Un diseñador/a gráfico puede utilizar CSS, junto con otras herramientas de diseño, para crear elementos visuales para sitios web y otras plataformas.

- Diseñador/a de correo electrónico: Un diseñador/a de correo electrónico se encarga de crear y diseñar mensajes de correo electrónico atractivos y bien diseñados que sean fáciles de leer y navegar. Pueden utilizar CSS para dar estilo a estos mensajes.

- Diseñador/a de aplicaciones móviles: Un diseñador/a de aplicaciones móviles utiliza herramientas como CSS para crear y dar formato a las interfaces de usuario de las aplicaciones móviles.

Estos son solo algunos ejemplos de trabajos que puedes conseguir al aprender CSS. Hay muchas otras opciones disponibles en el campo de la creación de sitios web y el diseño de aplicaciones.

 

**¿Cuánto puedes ganar usando CSS en tu trabajo?**

El salario que puedes ganar al utilizar CSS en tu trabajo dependerá de varios factores, como tu nivel de experiencia, tu ubicación geográfica y el tipo de trabajo que realices. En general, el salario de las personas que utilizan CSS en su trabajo puede variar ampliamente, desde unos pocos miles de dólares al año hasta varios cientos de miles de dólares al año.

A continuación se presentan algunos ejemplos de salarios promedio para algunos trabajos que involucran el uso de CSS:

Diseñador/a web: El salario promedio para un diseñador/a web en Estados Unidos es de alrededor de $50,000 al año.

Desarrollador/a front-end: El salario promedio para un desarrollador/a front-end en Estados Unidos es de alrededor de $75,000 al año.

Diseñador/a gráfico: El salario promedio para un diseñador/a gráfico en Estados Unidos es de alrededor de $50,000 al año.

Diseñador/a de correo electrónico: El salario promedio para un diseñador/a de correo electrónico en Estados Unidos es de alrededor de $50,000 al año.

Diseñador/a de aplicaciones móviles: El salario promedio para un diseñador/a de aplicaciones móviles en Estados Unidos es de alrededor de $80,000 al año.

Estos salarios son solo una guía y pueden variar ampliamente dependiendo de la ubicación y otras circunstancias. Además, es importante tener en cuenta que el salario no es el único factor a considerar al elegir un trabajo. Otros factores, como el ambiente de trabajo y las oportunidades de crecimiento profesional, también son importantes.

 

**¿Cuales son las preguntas más comunes sobre CSS?**

Aquí hay algunas preguntas comunes sobre CSS:

¿Qué es CSS y para qué se utiliza?
¿Cuál es la diferencia entre CSS y HTML?
¿Cuáles son algunas de las principales propiedades de CSS?
¿Cómo puedo utilizar CSS para dar estilo a los elementos de un sitio web?
¿Cómo puedo hacer que mi sitio web sea responsive con CSS?
¿Cómo puedo utilizar la hoja de estilo en cascada (CSS) para crear animaciones?
¿Cómo puedo utilizar media queries en CSS para crear diseños móviles?
¿Cómo puedo utilizar CSS para crear efectos de hover en los enlaces?
¿Cómo puedo utilizar CSS para crear diseños de grillas y maquetas?
¿Cómo puedo utilizar CSS para crear diseños adaptativos y cambiar la apariencia de un sitio web según el tamaño de la pantalla?
Después de finalizar este curso podrás responder a estas preguntas sin problemas. 🙂

# 6. Setup

Setup
Este curso no necesita ninguna configuración especial ya que utilizaremos un editor en línea que se llama CodeSandbox en https://codesandbox.io/dashboard/home

# 7. Editor en Linea: codesandbox y Hola Mundo

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      p {
        color: red;
      }
    </style>
  </head>
  <body>
    <p>Hola Mundo</p>
  </body>
</html>
```

# 8. Usos de CSS

Se puede utilizar:

- Un archivo externo
- Utilizando el tag style
- Ponerlo en linea

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="style.css" />
    <style>
      p {
        font-weight: 900;
      }
    </style>
  </head>
  <body>
    <p style="font-size: 25px;">Hola Mundo</p>
  </body>
</html>
```

```css
p {
  color: blue;
}
```

# 9. Herramientas para resetear estilos y pueda tener la misma configuracion en los diferentes navegadores.

- https://meyerweb.com/eric/tools/css/reset/
- https://necolas.github.io/normalize.css/
- https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css


```html
<!DOCTYPE html>
<html>
  <head>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css"
    />
  </head>
  <body>
    <fieldset>
      <legend>Radio Buttons</legend>
      <input type="radio" value="Uno" />
      <label for="uno">Uno</label>
      <input type="radio" value="Dos" />
      <label for="dos">Dos</label>
      <input type="radio" value="Tres" />
      <label for="tres">Tres</label>
    </fieldset>
  </body>
</html>
```

# 10. Comentarios e intro a selectores

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <style>
      /*Comentario*/
      p.primero,
      h1 {
        color: red;
        font-size: 25px;
      }
    </style>
  </head>
  <body>
    <h1>Titulo</h1>
    <p class="primero">Parrafo</p>
    <p>Parrafo</p>
  </body>
</html>
```