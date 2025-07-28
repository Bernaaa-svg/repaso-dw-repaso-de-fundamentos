# Explicación de etiquetas de formato y enlaces en HTML

## Etiquetas de formato
- `<b>`: Muestra el texto en negrita, solo visual.
- `<strong>`: Negrita semántica, indica importancia.
- `<i>`: Muestra el texto en cursiva, solo visual.
- `<em>`: Cursiva semántica, indica énfasis.
- `<mark>`: Resalta el texto (fondo amarillo).
- `<small>`: Texto más pequeño.
- `<del>`: Texto tachado (eliminado).
- `<ins>`: Texto subrayado (insertado).
- `<sub>`: Subíndice (ejemplo: H<sub>2</sub>O).
- `<sup>`: Superíndice (ejemplo: x<sup>2</sup>).

## Enlaces y rutas
- `<a href="...">`: Crea un enlace.
    - **Ruta absoluta**: Incluye el dominio completo. Ejemplo: `https://www.ejemplo.com`
    - **Ruta relativa**: Solo el nombre del archivo o carpeta. Ejemplo: `pagina.html`

## Diferencias entre ruta relativa y absoluta
- **Ruta absoluta**: Apunta a una dirección web completa, funciona desde cualquier lugar.
- **Ruta relativa**: Apunta a archivos dentro del mismo proyecto o carpeta, depende de la ubicación del archivo actual.

## Ejemplo de código
```html
<p><b>Texto en negrita con &lt;b&gt;</b></p>
<p><strong>Texto en negrita semántica con &lt;strong&gt;</strong></p>
<p><i>Texto en cursiva con &lt;i&gt;</i></p>
<p><em>Texto enfatizado con &lt;em&gt;</em></p>
<p><mark>Texto resaltado con &lt;mark&gt;</mark></p>
<p><small>Texto pequeño con &lt;small&gt;</small></p>
<p><del>Texto tachado con &lt;del&gt;</del></p>
<p><ins>Texto insertado con &lt;ins&gt;</ins></p>
<p>Texto con subíndice: H<sub>2</sub>O</p>
<p>Texto con superíndice: x<sup>2</sup></p>
<p>Enlace absoluto: <a href="https://www.ejemplo.com">Ir a ejemplo.com</a></p>
<p>Enlace relativo: <a href="pagina.html">Ir a pagina.html</a></p>
```
