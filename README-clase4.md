# Explicación de index-3.html

## Imágenes
La etiqueta `<img>` se usa para mostrar imágenes. Ejemplo:
```html
<img src="https://via.placeholder.com/150" alt="Imagen de ejemplo" width="150" height="100">
```
- `src`: ruta de la imagen.
- `alt`: texto alternativo.
- `width` y `height`: tamaño.

## Tablas
Permiten organizar datos en filas y columnas:
```html
<table border="1">
  <tr>
    <th>Nombre</th>
    <th>Edad</th>
  </tr>
  <tr>
    <td>Ana</td>
    <td>23</td>
  </tr>
</table>
```
- `<table>`: tabla.
- `<tr>`: fila.
- `<td>`: celda de datos.
- `<th>`: celda de encabezado.

## Listas
- `<ol>`: lista ordenada.
- `<ul>`: lista desordenada.
- `<li>`: elemento de lista.

## Div y Span
- `<div>`: bloque (block), ocupa todo el ancho.
- `<span>`: en línea (inline), solo el espacio necesario.

## Block vs Inline
- **Block**: inicia nueva línea y ocupa todo el ancho (`<div>`, `<p>`, `<table>`).
- **Inline**: no inicia nueva línea, solo el espacio de su contenido (`<span>`, `<a>`, `<img>`).

## id y class
- `id`: identificador único.
- `class`: agrupa elementos para estilos.

## Ejemplo de diferencias
```html
<div style="border:1px solid #000;">Div es block</div>
<span style="border:1px solid #000;">Span es inline</span>
```

Este archivo resume los conceptos y ejemplos del código de la clase 4 para tu estudio.
