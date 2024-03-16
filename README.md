# Reading_notes_class5

En esta sesión, exploramos la importancia de utilizar CSS para dar vida y color a las páginas web. El trabajo con CSS va más allá de simplemente aplicar colores y tipografías; también implica crear una armonía visual entre los elementos utilizados en el diseño. CSS nos permite mejorar la estética y la experiencia del usuario al momento de explorar una página web. 

## Preguntas:
### - ¿Cuál es el propósito de CSS?
El propósito de CSS (Cascading Style Sheets) es definir el aspecto y la presentación de los elementos de HTML en una página web, con CSS nos da la posibilidad de editar el color, la tipografía, el espaciado y el diseño de una pagina web.

### - ¿Cuáles son las tres formas de insertar CSS en tu proyecto?
  1. **Estilo en linea:** En esta forma se puede incluir estilos CSS directamente en las etiquetas HTML. Esta técnica es útil para estilos específicos que se aplican solo a un elemento individual.
```
<p> style="color: red; font-size: 16px;".</p>
```
  3. **Estilo Incrustado**: Se aplica CSS dentro de la sección <style> en la cabecera de un documento HTML. Esta técnica es útil para aplicar estilos a varios elementos en un documento HTML
  ```
<!DOCTYPE html>
<html>
<head>
    <style>
        p {
            color: blue;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <p>Este es un ejemplo de Estilo Incrustadox.</p>
</body>
```
  
  5. **Estilo Enlace externo:**  Aqui los archivos CSS van separado y se enlaza con un documento HTML  utilizando la etiqueta <link> en la sección <head> luego se crea otro archivo con el nombre estilos.css, pu
     
```
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="estilos.css">
</head>
<body>
    <p>Este es un ejemplo de Enlace Externo.</p>
</body>
</html>
```
Archivos estillos.css
```
p {
    color: green;
    font-size: 18px;
}
```

### - Escribe un ejemplo de una regla CSS que daría texto rojo a todos los elementos <p>
```
p {
    color: red;
}
```
