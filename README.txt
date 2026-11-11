INSTRUCCIONES PARA EJECUTAR LA APLICACIÓN EN DOCKER

1. Abrir una terminal dentro de esta carpeta descomprimida.
2. Construir la imagen de Docker con el comando:
   docker build -t mi-app-web .

3. Crear y ejecutar el contenedor con el comando:
   docker run -d -p 8080:80 --name contenedor-web mi-app-web

4. Abrir el navegador web e ingresar a:
   http://localhost:8080