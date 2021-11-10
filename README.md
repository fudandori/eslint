# eslint

1 instalar extensión eslint en visual studio

2 instalar eslint de forma global:
    
    npm install -g eslint
    
3 inicializar el package.json:

    npm init
    
Dejar todos los valores por defecto (darle al enter hasta que deje de pedir cosas). 

4 inicializar eslint

    eslint --init
    
Preguntará tus preferencias. Para una web de JS pura las opciones generales son (por orden de las preguntas):

1 To check syntax, find problems, and enforce code style

2 JavaScript modules (import/export)

3 None of these

4 No

5 Browser

6 Use a popular style guide

7 Airbnb: https://github.com/airbnb/javascript (esto ya va según preferencias, airbnb es de las más populares)

8 JSON

9 Would you like to install them now with npm? ---> Yes

Ya deberías ver cómo ESlint funciona subrayando el código malo

# importante
Todas estas instalaciones/configuraciones generarán 3 ficheros y una carpeta

    package.json
    .eslintrc.js
    .eslintrc.json
    node_modules
    
Asegúrate que no suben al desplegar proyecto. Esto se configura en el firebase.json. No son necesarias para que corra el código, sólo sirven para que funcione el ESlint en local

# comillas simples en prettier

En visual studio abre la pestaña de extensiones, botón derecho sobre la extensión Prettier y seleccionar ajustes de extensión

En el panel que se abre, buscar la opción Prettier: Single Quote que queda a mitad de pantalla y marcar la casilla

### Happy coding!
