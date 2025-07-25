# Explicaciones de HTML

## ¿Qué significa HTML?
HTML significa **HyperText Markup Language** (Lenguaje de Marcado de Hipertexto). Es el lenguaje principal para crear páginas web.

## Sintaxis
La sintaxis de HTML se basa en etiquetas que se escriben entre los signos < y >. Por ejemplo: `<p>Contenido</p>`.

## Elementos
Un elemento HTML está formado por una etiqueta de apertura, contenido y una etiqueta de cierre. Ejemplo:
```html
<p>Esto es un párrafo</p>
```
Algunos elementos pueden estar "anidados" dentro de otros.

## Atributos
Los atributos proporcionan información adicional sobre los elementos. Se escriben dentro de la etiqueta de apertura. Ejemplo:
```html
<a href="https://www.ejemplo.com" target="_blank">Enlace</a>
```
Aquí, `href` y `target` son atributos.

## Ejemplo de elementos y conceptos
- `<p>`: Define un párrafo.
- `<a>`: Define un enlace. Puede tener atributos como `href`, `target`, `title`, etc.
- `<strong>`: Da énfasis fuerte (negrita) al texto.
- `<em>`: Da énfasis (cursiva) al texto.
- **Anidar**: Colocar una etiqueta dentro de otra, por ejemplo: `<strong>Texto <em>enfatizado</em></strong>`.

## Diferencia entre etiquetas abiertas y cerradas
- **Etiqueta cerrada**: Tiene apertura y cierre, por ejemplo: `<p>Texto</p>`.
- **Etiqueta abierta (autocontenida)**: No necesita cierre, por ejemplo: `<br>`.

## Ejemplo de múltiples atributos
```html
<a href="https://www.otroejemplo.com" class="boton" id="enlace2">Otro enlace</a>
```
Aquí, el elemento `<a>` tiene tres atributos: `href`, `class` e `id`.
