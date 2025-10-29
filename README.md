# Spring.io, Websockets y ReactJs

Vamos ahora a realizar un tutorial para implementar una aplicación pequeña que implementa
un a aplicación Web que utiliza Web Sockets.

## Arquitectura

Queremos construir una aplicación web con comunicación bidirectional entre el cliente y el
servidor. El servidor hace un broadcast de un mensaje cada 5 segundos a todos los clientes
conectados. Para realizarlo utilizaremos:

- Spring como servidor web y de aplicaciones
- El browser con Js y ReactJs como cliente pesado
- WebSockets para establecer la conexión bidirectional

### Cree la estructura básica del proyecto:

**1. Crear una aplicación java básica usando maven**

**2. Actualizar el pom para utilizar la configuración web-MVC de spring boot. Incluya lo
siguiente en su pom**

**3. Cree la siguiente clase que iniciará el servidor de aplicaciones de Spring**}

Para los pasos 1,2 y 3 hacemos uso de ``spring initializr`` que nos genera de manera automatica todo lo anterior, importante añadir la dependencia de web para el punto 2.

