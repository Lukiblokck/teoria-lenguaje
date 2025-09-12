# Introducción a HTML, CSS y JavaScript

Este repositorio explica la **estructura, estilo y comportamiento** de las páginas web usando HTML, CSS y JavaScript, con ejemplos prácticos.

---

## 1. HTML: La estructura de la web

HTML (HyperText Markup Language) define **qué elementos hay** en la página y **cómo se organizan**. Es como el esqueleto de un edificio.

### Ejemplo básico:

<!DOCTYPE html>
<html>
  <head>
    <title>Mi página web</title>
  </head>
  <body>
    <h1>Hola, soy un título</h1>
    <p>Esto es un párrafo de texto.</p>
    <button>Haz clic aquí</button>
  </body>
</html>

**Explicación:**
- `<h1>`: Título principal.  
- `<p>`: Párrafo de texto.  
- `<button>`: Botón que luego puede interactuar con JavaScript.  

> HTML **solo define la estructura**, no cómo se ve ni cómo se comporta.

---

## 2. CSS: El estilo de la web

CSS (Cascading Style Sheets) define **cómo se ve** la página: colores, tamaños, fuentes, posiciones, etc.

### Ejemplo de CSS:

<style>
  body {
    background-color: black;
    color: white;
    font-family: Arial, sans-serif;
    text-align: center;
    padding: 50px;
  }

  button {
    background-color: green;
    color: white;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    font-size: 16px;
  }

  button:hover {
    background-color: limegreen;
  }
</style>

**Explicación:**
- `body`: cambia el fondo, color de texto y fuente de toda la página.  
- `button`: define colores, tamaño, borde y cursor del botón.  
- `button:hover`: efecto cuando el usuario pasa el mouse sobre el botón.  

---

## 3. JavaScript: El comportamiento de la web

JavaScript añade **interactividad y dinamismo** a la página. Puede responder a clics, cambiar contenido, hacer animaciones, etc.

### Ejemplo de JavaScript:

<script>
  const boton = document.querySelector("button");

  boton.addEventListener("click", () => {
    alert("¡Has hecho clic en el botón!");
  });
</script>

**Explicación:**
- `document.querySelector("button")`: selecciona el botón del HTML.  
- `addEventListener("click", ...)`: detecta cuando el usuario hace clic en el botón.  
- `alert(...)`: muestra una ventana emergente con un mensaje.  

> Con esto, el botón ahora **tiene un comportamiento** que antes no tenía solo con HTML y CSS.

---

## 4. Ejemplo completo

<!DOCTYPE html>
<html>
<head>
  <title>Mi primera web interactiva</title>
  <style>
    body {
      background-color: black;
      color: white;
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 50px;
    }

    button {
      background-color: green;
      color: white;
      border: none;
      padding: 10px 20px;
      cursor: pointer;
      font-size: 16px;
    }

    button:hover {
      background-color: limegreen;
    }
  </style>
</head>
<body>
  <h1>Hola, soy un título</h1>
  <p>Esto es un párrafo de texto.</p>
  <button>Haz clic aquí</button>

  <script>
    const boton = document.querySelector("button");

    boton.addEventListener("click", () => {
      alert("¡Has hecho clic en el botón!");
    });
  </script>
</body>
</html>

✅ Resultado:
- HTML: estructura de la página.  
- CSS: colores, fuentes y estilos.  
- JavaScript: hace que el botón sea interactivo.  

---

Este ejemplo demuestra cómo **HTML, CSS y JavaScript trabajan juntos** para crear páginas web modernas e interactivas.
