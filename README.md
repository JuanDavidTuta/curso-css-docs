#  CURSO CSS

## Seccion 1: Introducción a CSS

### - Que es HTML?

Es un lenguaje de marcado de hipertexto, define como se organiza o se dispone la información en una página o documento

### - Que es CSS?

Es un lenguaje de estilos (Hojas de estilo de casdada), el cual nos permite darle estilos al documento

Para definir un estilo de CSS hay que tener en cuenta este se compone de 3 partes:

```css
/* Selector */
h1 {
  /* color: Propiedad */
  color: blue;
  /* blue: Es el valor de la propiedad */
}
```

### - Como usar CSS

Para usar CSS seguir los siguentes pasos

1. Se crea una carpeta `curso-css`
2. Dentro de la carpeta de crea un archivo `index.html`
3. Para usar css desde un archivo externo, creamos el arhivo `style.css`
4. Invocamos el archivo css desde le header del documento HTML

```html
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Aqui se invoca el archivo style.css -->
    <link rel="stylesheet" href="css/style.css">
    <title>Curso CSS</title>
</head>
<body>
    <h1>Hola Mundo</h1>
</body>
</html>
```

```css
/* css/style.css */
h1 {
  color: blue;
}
```