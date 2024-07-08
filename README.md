# Encriptador de Texto

¡Bienvenidas y bienvenidos a nuestro primer desafío!

Durante estas cuatro semanas, vamos a trabajar en una aplicación que encripta textos, permitiéndote intercambiar mensajes secretos con otras personas que conozcan el secreto de la encriptación utilizada.

## Descripción del Proyecto

La aplicación encripta y desencripta textos utilizando un conjunto específico de reglas. Estas reglas de encriptación son:

- La letra "e" se convierte en "enter"
- La letra "i" se convierte en "imes"
- La letra "a" se convierte en "ai"
- La letra "o" se convierte en "ober"
- La letra "u" se convierte en "ufat"

Por ejemplo:

- "gato" se convierte en "gaitober"
- "gaitober" se convierte de nuevo en "gato"

## Requisitos

- El programa debe funcionar solo con letras minúsculas.
- No deben ser utilizadas letras con acentos ni caracteres especiales.
- Debe ser posible convertir una palabra a su versión encriptada y también devolver una palabra encriptada a su versión original.
- La página debe tener campos para la inserción del texto que será encriptado o desencriptado.
- El usuario debe poder escoger entre las dos opciones.
- El resultado debe ser mostrado en la pantalla.

## Funcionalidades Extras

- Un botón que copie el texto encriptado/desencriptado al portapapeles, teniendo la misma funcionalidad de `Ctrl+C` o de la opción "copiar" del menú de las aplicaciones.

## Estructura del Proyecto

### Archivos Principales

- `index.html`: Contiene la estructura HTML de la aplicación.
- `styles.css`: Contiene los estilos CSS para la aplicación.
- `script.js`: Contiene la lógica de encriptación y desencriptación en JavaScript.

### Funcionalidades

1. **Encriptar**: Convierte el texto ingresado según las reglas especificadas.
2. **Desencriptar**: Devuelve el texto encriptado a su versión original.
3. **Copiar al Portapapeles**: Copia el texto resultante al portapapeles.

### Ejemplo de Uso

1. Ingresa el texto que deseas encriptar en el campo de texto.
2. Selecciona la opción "Encriptar" y presiona el botón correspondiente.
3. El texto encriptado aparecerá en el área de resultados.
4. Para desencriptar, ingresa el texto encriptado, selecciona la opción "Desencriptar" y presiona el botón correspondiente.
5. El texto desencriptado aparecerá en el área de resultados.
6. Utiliza el botón "Copiar" para copiar el texto encriptado/desencriptado al portapapeles
