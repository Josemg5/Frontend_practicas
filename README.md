# Frontend_practicas
// Proyecto 2 Desarrollo del Frontend
/*
En nuestro nuevo proyecto debemos tener claro que tenemos que tener instalado todo lo del proyecto anterior.

Lo primero que tenemos que hacer es en la carpeta con la ultima version de nuestro servidor usar el comando "create vue@latest" para tener nuestra pagina web. Para crear esta pagina web tenemos que tener claro que debemos poner las opciones de:

  -Router(SPA development)
  Nos agrega Vue Router, que permite crear rutas y navegación entre vistas/páginas sin recargar la página completa (SPA - Single Page Application).
  
  -Pinia(state management)
  Permite manejar datos globales (como el carrito de compras, usuario autenticado, etc.) de forma centralizada y reactiva.

  -ESLint(error prevention)
  Analiza tu código para encontrar errores comunes y asegurarse de que sigas buenas prácticas.
  
  -Prettier (code formatting)
  Formatea automáticamente tu código (espacios, sangrías, comillas, etc.) para mantener un estilo coherente.

El programa de veu nos indicara en verde lo que debemos de hacer, los comandos que nos marca que hacer es movernos al directorio creado con "cd Nombre_Directorio".

A continuacion usaremos el comando "npm install" se usa para instalar todas las dependencias que tu proyecto necesita, el siguiente que usaremos es "npm run format" se usa para formatear el código fuente del proyecto, y por ultimo usaremos el comando "npm run dev"  se usa para iniciar el servidor de desarrollo.

Una vez iniciado lo que debemos hacer es con la direccion que nos da de localhost ponerlo en el navegador y veremos que nos saldra dos un aviso de que nos hemos conectado.

Para poder editarlo y añadir nuevas categorias, lo que haremos sera iniciar la base de datos, instalaremos el CORS con el comando "npm install cors" y el axios con el comando "npm install axios". 

  -CORS es un mecanismo de seguridad del navegador que restringe las solicitudes HTTP entre diferentes orígenes 

  -Axios es una herramienta para conectarte con APIs (backends, servicios externos, etc.).
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Lo siguiente parte de nuestro proyecto es diseñar la pagina web con las siguientes especificaciones:

  -La rama principal debe ser un archivo vue y los demas archivos html e imagenes se enlazan desde la carpeta Public. 
  
  -Un menu principal en el que se elija los componentes y categorias con dos botones que nos lleve a la pagina de compra de componentes y categorias.
  
  -Dos paginas una de categoria y componentes en el cual tenga varios articulos que despues nos dirija al stock de los articulos en los cuales se pueda editar, eliminar y añadir.
  
  -Tener un sistema de volver a las paginas anteriores.

  -Tener botones con la imagenes de los articulos.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  A continuacion lo quen haremos sera conectar nuestra pagina web con nuestra base de datos. Para poder conectarlo en cada archivo que tenemos necesitamos meter un script en cada archivo   html, que va enlazado con los metodos utilizados en postman.

  Cada metodo tendra su propio boton, exepto el metodo get que es el resultado que se muestra en las tablas.

  Para la correcta conexion de la pagina web necesitaremos conectar con el localhost del node server.js que seria el localhost:3000. 
  Para acceder a la pagina web necesitaremos el enlace que sera: "http://localhost:5173/".

  Y necesitaremos tener el server.js y Vue abierto(entraremos con el enlace de Vue).
*/ 
