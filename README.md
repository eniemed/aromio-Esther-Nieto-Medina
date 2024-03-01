## Esther Nieto Medina 

*Nota: Una documentación mucho más detallada se puede encontrar en este repositorio en esta misma ruta del proyecto, llamado Documentación-EstherNietoMedina.md*

<img src="/src/assets/Portada.png" />

### Índice

<li> Introducción.
<li> Descripción del resultado.
<li> Instalación y preparación necesaria.
<li> Diseño.
<li> Secuencia de desarrollo.
<li> Despliegue.
<li> Manual de la aplicación.
<li> Conclusiones

# 1. INTRODUCCIÓN

Empecé este proyecto con la idea de hacer una web para vender café artesano, llamada Aromio. Quería que tuviera varias páginas y funcionalidades para que fuera atractiva para los compradores. Implementé distintos elementos características como un carrito de compra, un modo oscuro, y una página para cada producto con detalles entre otras. Para montar todo esto, usé Vue.js y CSS para el front, y creé el back con Laravel, creando mi propia base de datos y API.

# 2. DESCRIPCIÓN DEL RESULTADO

Quedé bastante contenta con cómo quedó todo. Logré hacer la mayoría de las cosas que me propuse, las cuales enumero en la documentación detallada.

La aplicación cuenta con:

<li> Una página de inicio con un botón que redirija a la tienda.
<li> Icono de carrito en esquina superior derecha que guardará los productos incluso tras el cierre de sesión.
<li> Icono de modo oscuro.
<li> Página de tienda con un buscador y filtrado que muestre todos los productos disponibles.
<li> Botón de añadir al carrito.
<li> Botón de añadir a wishlist.
<li> Producto con fondo personalizado para darle un toque personal a cada uno de ellos.
<li> Página de producto individual accesible desde la card clicable de cada producto en la tienda, la cual tendrá más información del producto.
<li> Página de wishlist donde se almacenarán los productos que el usuario haya preferido desde la página de la tienda. Desde la misma podrá retirarlos de la wishlist o añadirlos al carrito.
<li> Página de perfil de usuario que muestre sus datos y permita el cierre de sesión.
<li> Formularios de contacto, inicio de sesión y registro del usuario, teniendo un impacto en la base de datos para que la web sea funcional.

# 3. INSTALACIÓN Y PREPARACIÓN NECESARIA

Para realizar el proyecto, hice un "npm install" desde Visual Studio Code, intalé pinia con el sencillo comando "npm install pinia" y "npm instal pinia-persist-plugin" para instalar el conveniente plugin de pinia que se ocupa de la persistencia en el localStorage.

Luego instalé laravel por separado y desde phpmyadmin introduje un script para la creación de la base de datos, las tablas y los inserts. Más tarde explicaré los pasos a realizar para conseguir desplegar el proyecto en local usando docker.


# 4. DISEÑO

Para la realización del diseño me dejé llevar por mis preferencias personales, dándole a la web una estética que he considerado agradable. Procedo a numerar el diseño de cada página y una captura del mismo desde la aplicación de Figma. Adjunto enlace también:

<a href="https://www.figma.com/file/iGHjwl7uJfKTRgcvnKxMAT/Proyecto-CLIENTE-%2B-DISE%C3%91O---Esther-Nieto-Medina-2%C2%BA-DAW?type=design&node-id=0%3A1&mode=design&t=dY9kLuaJ5kVRsmgD-1">Proyecto de Figma de Esther Nieto Medina</a>

En la documentación añado captura de cada una de las páginas con el nombre de la misma sobre ella para ahorrar entrar en figma durante la corrección.

# 5. SECUENCIA DE DESARROLLO

Los pasos que tomé fueron:

1. Decidir la temática.
2. Diseñar la web en Figma siguiendo mis preferencias.
3. Documentarme sobre las tecnologías que iba a usar (laravel, vue, docker, etc.)
4. Implementar todo el código de la aplicación a la vez de sus estilos.
5. Despliegue en docker.

El desarrollo en vue se me ha hecho cómodo, por lo que no sabría destacar ninguna dificultad por encima de otras. Creo que en general he aprendido mucho con este proyecto y me ha ayudado a mejorar la organización de mis proyectos y con mi fluidez de programación. Donde realmente he encontrado grandes problemas ha sido en el despliegue y en el desarrollo del back-end, sin embargo, con mucho trabajo y muchas horas todo ha salido hacia delante.

# 6. DESPLIEGUE

Pasos para desplegar la aplicación:

1. "npm install" en el proyecto de Vue
2. Levantar el docker manualmente o con el comando "docker-compose up -d --build" desde el proyecto de laravel
3. "npm run dev" en el proyecto de Vue

# 7. MANUAL DE LA APLICACIÓN

En la app, arrancas en la página de inicio y de ahí puedes ir a todas las páginas de la web en cualquier momento con el navbar, como la tienda, donde ves todos los productos y puedes añadirlos al carrito o a la wishlist. Cada producto tiene su página con más información. También puedes registrarte, iniciar sesión, y ver tu perfil, donde puedes cerrar sesión. Todo está pensado para ser intuitivo y fácil de usar.

# 8. CONCLUSIONES

Como conclusión, creo que mi proyecto ha resultado bastante parecido al que tenía en mente en un principio y me parece que he avanzado bastante desde el principio de este año. 

Hay muchas cosas que se le pueden añadir a una aplicación así como la posibilidad del usuario de editar sus datos personales, página de carrito más allá de un desplegable, etc. y espero poder implementárselas en un futuro.
