# Fuente Roboto en formato web (woff y woff2)
## ¿Cómo añadir la fuente a mi tema en Wordpress?
Incluir en el archivo CSS de tu tema o del tema hijo:
```
@font-face {
	font-family: 'Roboto-Bold';
	src: url('/RUTA/AL/DIRECTORIO/roboto/Roboto-Bold.woff') format('woff'),
		url('/RUTA/AL/DIRECTORIO/roboto/Roboto-Bold.woff2') format('woff2');
		  font-display: auto;
		  font-weight: normal;
		  font-style: normal;
}
@font-face {
	font-family: 'Roboto-Medium';
	src: url('/RUTA/AL/DIRECTORIO/roboto/Roboto-Medium.woff') format('woff'),
		url('/RUTA/AL/DIRECTORIO/roboto/Roboto-Medium.woff2') format('woff2');
		  font-display: auto;
		  font-weight: normal;
		  font-style: normal;
}
@font-face {
	font-family: 'Roboto-Regular';
	src: url('/RUTA/AL/DIRECTORIO/roboto/Roboto-Regular.woff') format('woff'),
		url('/RUTA/AL/DIRECTORIO/roboto/Roboto-Regular.woff2') format('woff2');
		  font-display: auto;
		  font-weight: normal;
		  font-style: normal;
}
```
Luego se debe indicar en qué partes quieres usar la fuente, por ejemplo:
```
h1, h2 {
    font-family: 'Roboto-Bold', sans-serif;
    font-weight: normal;
}
```
O
```
body {
    font-family: 'Roboto-Regular', sans-serif;
    font-weight: normal;
}
```
# Roboto Font in Web Format (woff and woff2)
## How to Add the Font to My WordPress Theme?
Include the following in the CSS file of your theme or child theme:
```
@font-face {
	font-family: 'Roboto-Bold';
	src: url('/PATH/TO/DIRECTORY/roboto/Roboto-Bold.woff') format('woff'),
		url('/PATH/TO/DIRECTORY/roboto/Roboto-Bold.woff2') format('woff2');
		  font-display: auto;
		  font-weight: normal;
		  font-style: normal;
}
@font-face {
	font-family: 'Roboto-Medium';
	src: url('/PATH/TO/DIRECTORY/roboto/Roboto-Medium.woff') format('woff'),
		url('/PATH/TO/DIRECTORY/roboto/Roboto-Medium.woff2') format('woff2');
		  font-display: auto;
		  font-weight: normal;
		  font-style: normal;
}
@font-face {
	font-family: 'Roboto-Regular';
	src: url('/PATH/TO/DIRECTORY/roboto/Roboto-Regular.woff') format('woff'),
		url('/PATH/TO/DIRECTORY/roboto/Roboto-Regular.woff2') format('woff2');
		  font-display: auto;
		  font-weight: normal;
		  font-style: normal;
}
```
Then, specify where you want to use the font, for example:
```
h1, h2 {
    font-family: 'Roboto-Bold', sans-serif;
    font-weight: normal;
}
```
Or
```
body {
    font-family: 'Roboto-Regular', sans-serif;
    font-weight: normal;
}
```
