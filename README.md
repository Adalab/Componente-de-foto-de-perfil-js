# Componente de foto de perfil (Javascript)
Componente listo para usar con la subida de imagen de perfil

## Elementos
Para que funcione correctamente necesitaremos estos elementos:
- **Campo de tipo "file"**: no podemos darles estilos correctamente pero lo necesitamos para añadir un archivo; lo vamos a ocultar ;)
- **Botón**: Podemos darle los estilos que queramos y al hacer click en él generaremos un clic automático en el campo oculto
- **Contenedor principal de la imagen**: tiene una imagen por defecto a través del atributo style
- **Contenedor de la previsualización de la imagen**: por defecto aparece vacío

## Cómo usarlo
Tendremos que enlazar el archivo `get-avatar.js` a nuestro html y asegurarnos de que nuestros cuatro elementos tienen estas clases (además de las que usemos para dar estilos):

| Elemento | Clase |
|---|---|
| Campo de tipo "file" | `js__profile-upload-btn` |
| Botón | `js__profile-trigger`|
| Contenedor principal de la imagen | `js__profile-image` |
| Contenedor de la previsualización de la imagen | `js__profile-preview` |

>  Nota de estilos:  
La hoja de estilos del proyecto es para verlo funcionar. Lo único a tener en cuenta es que el campo de tipo "file" debe ocultarse.

***

**Al turrón!**
