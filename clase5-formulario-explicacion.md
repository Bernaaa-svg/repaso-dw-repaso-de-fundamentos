# Explicación de formulario HTML avanzado (index-4.html)

## Estructura básica
- `<form>`: Define el formulario. Atributos comunes: `action` (destino de los datos), `method` (GET o POST).
- `<label>`: Etiqueta descriptiva para cada campo, mejora la accesibilidad.
- `<input>`: Campo de entrada. Tipos comunes:
    - `text`: texto simple.
    - `email`: correo electrónico.
    - `radio`: opción única entre varias.
    - `checkbox`: selección múltiple.
    - `submit`: botón para enviar el formulario.
- `name`: Atributo que identifica el campo en el envío de datos.

## Ejemplo de casos comunes
- **Nombre y Email**: Campos obligatorios con `required`.
- **Radio**: Selección de género, solo se puede elegir uno.
- **Checkbox**: Selección de intereses, se pueden elegir varios.
- **Submit**: Botón para enviar el formulario.

## Accesibilidad
- El uso de `label` con el atributo `for` vincula la etiqueta al campo correspondiente.

## Bibliografía y recursos
- [MDN Web Docs: HTML forms](https://developer.mozilla.org/es/docs/Learn/Forms)
- [W3Schools: HTML Forms](https://www.w3schools.com/html/html_forms.asp)
- [HTML Living Standard](https://html.spec.whatwg.org/multipage/forms.html)

Este archivo te ayuda a comprender la estructura y los elementos más usados en formularios HTML modernos.
