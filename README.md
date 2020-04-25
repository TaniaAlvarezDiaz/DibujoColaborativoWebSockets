# DibujoColaborativoWebSockets
Aplicación de dibujo colaborativo que permite al usuario dibujar figuras en la pantalla. Esta aplicación tiene:
 - [Servidor](https://github.com/TaniaAlvarezDiaz/DibujoColaborativoWebSocketsServidor): se encarga de gestionar las conexiones de los
distintos usuarios y los dibujos que estos van añadiendo al canvas.
 - [Cliente](https://github.com/TaniaAlvarezDiaz/DibujoColaborativoWebSocketsCliente): permite a los usuarios conectarse al servidor, recibir loscontenidos que hay dibujados hasta ese momento y colaborar en el dibujo.
 
Adicionalmente, en este repositorio se hace referencia a la documentación de la aplicación.

# Ejecución

Para ejecutar el proyecto seguir los siguientes pasos:
1. Descargar [Node.js](https://nodejs.org/es/)

2. Descargar el proyecto:
   * git clone https://github.com/TaniaAlvarezDiaz/DibujoColaborativoWebSockets.git
   * Acceder a la carpeta y ejecutar:
      * git submodule update --init

3. Ejecutar la consola de Node.js.
   * Ir a la ruta donde se encuentra el servidor (**DibujoColaborativoWebSocketsServidor**).
   * Ejecutar "node server.js".
   
4. Ir a la ruta donde se encuentra el cliente (**DibujoColaborativoWebSocketsCliente**).
   * Abrir el fichero "index.html" en el navegador Chrome.
      * Abrir tantas pestañas como clientes se deseen.
   
