# Explicación de la estructura de una página web en HTML

## Etiquetas principales
- `<!DOCTYPE html>`: Indica que el documento es HTML5.
- `<html>`: Etiqueta raíz que envuelve todo el contenido.
- `<head>`: Contiene información para el navegador (no visible para el usuario).
- `<meta>`: Metatag, por ejemplo, para definir la codificación de caracteres (`charset`).
- `<title>`: Título de la página que aparece en la pestaña del navegador.
- `<!-- ... -->`: Comentarios, no se muestran en la página.

## Etiquetas de contenido
- `<body>`: Contiene el contenido visible de la página.
- `<h1>`, `<h2>`: Títulos y subtítulos. `<h1>` es el principal, `<h2>` es secundario.
- `<p>`: Define un párrafo.
- `<br>`: Salto de línea, no necesita etiqueta de cierre.

## Atributo style
Permite aplicar estilos CSS directamente en una etiqueta. Ejemplo:
```html
<h1 style="color:blue;">Título principal</h1>
<p style="font-size:18px;">Texto con tamaño personalizado</p>
```

## Ejemplo de estructura
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <!-- Comentario: Información para el navegador -->
    <meta charset="UTF-8">
    <title>Ejemplo de estructura web</title>
</head>
<body>
    <!-- Comentario: Contenido visible -->
    <h1 style="color:blue;">Título principal con estilo</h1>
    <h2>Título secundario</h2>
    <p style="font-size:18px;">Este es un párrafo con atributo style.</p>
    <p>Este es otro párrafo.<br>Este texto está en una nueva línea gracias a la etiqueta &lt;br&gt;.</p>
    <!-- Comentario: Fin del contenido -->
</body>
</html>
```

## Resumen
- Las etiquetas estructuran y organizan el contenido.
- Los comentarios ayudan a documentar el código.
- Los atributos permiten personalizar el comportamiento y estilo de los elementos.
- El atributo `style` aplica estilos directamente en la etiqueta.
