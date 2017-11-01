# **Nuestras coders**
En este proyecto se pide colocar la imagen de seis personas, para ello debemos ubicarlas en columnas de tres.    
Para poder realizar este reto es importante conocer la propiedad [position](http://es.learnlayout.com/position.html)  y [float](http://es.learnlayout.com/float.html).
***
## Estructura del proyecto

+ Cuenta con un carpeta `assets` en donde encontraremos las imagenes para realizar el proyecto.
+ Una carpeta `css` que continen un archivo de `main.css` para desarrollar tus estilos.
+ Un archivo de `index` para realizar la estructura de la página.

## Recordatorio
+ Siempre debemos comenzar con una estructura y a la vez enlazarlo con  el `main.css`.
+ Realizar las buenas práticas al momento de estructurar y trabajar el estilo.
+ Trabajar de manera ordenada el `main.css`.

### Estructura de un index
***
```` html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Nuestras Coders</title>
    <link rel="stylesheet" href="css/main.css">
  </head>
  <body>
      <section>
      </section>
  </body>
</html>
````
### Estructura de un css
***
```` css

/*Damos un estilo de fuente al título*/
body {
  font-family: fantasy;
}
 /*Aplicamos un display-bloque*/
section {
  /*outline: 1px solid blue;*/
  margin-left: 40px;
  overflow: auto;
  display: inline-block;

}
/* Realizaremos un div para contener a la imagen*/
/*utilizamos la propiedad position*/
div {
 /* outline: 1px solid red;*/
  box-sizing: border-box;
  float: left;
  margin: 1rem 1rem; /*Damos espacio entre imagen*/
  /**/
  position: relative;
 }

````
## Producto final
En este proyecto trabajado debemos tener la siguiente estructura terminada:
[**Nuestras coders**](https://lauraisa.github.io/Nuestras-coders/)