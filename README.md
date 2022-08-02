# ComposeDjango-EmmanuelLópezGarcía

1. Abrir una terminal y ejecutar la aplicación de Django:

`docker-compose up`

2. Ir al navegador e ingresar en la url para verificar el funcionamiento

`http://localhost:8000`

3. Detener los servicios con comando:

`docker-compose down`

>NOTA: Algo que sucedió cuando se quería cargar el repositorio a GITHUB, la carpeta /data generaba problemas porque no se podía subir debido a los permisos que tenía (root), para ello solo se cambiaron los permisos, o bien, el propietario con el comando: sudo chown -R $USER:$USER data estando dentro del repositorio.
