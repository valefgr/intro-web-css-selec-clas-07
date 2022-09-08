# Lab: Selectores de clase

## Objetivos
- Agregar estilo al sitio web mediante el uso de selectores de clase
- Insertar diferentes propiedades en cada selector de clase


## Introducción 
Hemos aprendido que el selector universal `*` selecciona todos los elementos de cualquier tipo.Dirigirse a todos los elementos de la página se utiliza en algunos casos específicos, como por ejemplo para restablecer el estilo predeterminado del navegador o seleccionar todos los elementos secundarios de un elemento principal.


## Funcionalidad del Código
En este lab utilizaremos los selectores de clase para agregar diferentes estilos al sitio web

## Instrucciones
Bifurca (fork) y clona (clone) este lab en tu entorno local. Navega a su directorio en la terminal, luego ejecuta el comando `code .` para abrir sus archivos en Visual Studio Code. 

1. Agrega los siguientes estilos a las clases `.banner`, `.html-exp`, `.css-exp`, `.js-exp`, `.flappy-js` y `.html-img`.

```
.banner {

   background-image: url("bg.jpg");
   color: white;
   padding: 100px;
   text-align: center;

}

.html-exp, .css-exp, .js-exp {

   padding: 60px;

}
 
.flappy-js {

   background-image: url("fb-game-background.png");
   padding: 60px;
   height: 450px;
   display: flex;
   justify-content: center;
   align-items: center;

}

.html-img {

   text-align: center;

}

```

2. Guarda tus cambios (Archivo > Guardar)

3. Abre tu archivo html en el navegador y verifica que puedas ver los estilos que agregaste.

4. Sube tus cambios a Github y envía por Canvas el enlace a tu repositorio.