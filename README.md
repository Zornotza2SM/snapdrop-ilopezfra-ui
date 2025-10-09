# Despliega tu segunda aplicación con Docker (Snapdrop)

### 1. Ejercicio: Despliega el proyecto de docker compose y responde a las siguientes preguntas.


1. Snapdrop se trata de una aplicación para transferir archivos entre equipos a través de la red, averigua tu ip y trata de transferir archivos con algún compañero de clase, ambos teneis que conectaros al mismo servidor. Muestra una captura de la aplicación Snapdrop en el momento de recibir un archivo.



Por ejemplo, la dirección de este equipo es:
`INF200615-8GELA.zornotzalh.eus`
![alt text](image-14.png)
2. ¿Que puertos expone esta aplicacion? ¿Sabrías decirme para que protocolos e usan estos puertos?
![alt text](image-13.png)
3. ¿Cuantos contenedores incluye este proyecto?
![alt text](image-15.png)
4. ¿Has notado cambios en la carpeta de tu proyecto al desplegar la aplicación? Indica cuales.

5. Cuando termines de responde a todas las preguntas. Haz commit de los cambios realizados con el mensaje.


1. Contenedores
¿Dónde podemos ver los contenedores en ejecución en la aplicación Docker Desktop? (Captura de pantalla)
![alt text](image-2.png)
Para ver los contenedores en ejecución desde la terminal se utiliza el comando docker ps. Ejecútalo. (Captura de pantalla)
![alt text](image-3.png)
¿Qué muestra el comando docker container?
![alt text](image-4.png)
¿Qué muestra el comando docker container ls?
 ![alt text](image-5.png)
2. Imágenes
¿Dónde podemos ver las imágenes descargadas en la aplicación Docker Desktop? (Captura de pantalla)
¿Qué muestra el comando docker images?
![alt text](image-6.png)
¿Qué muestra el comando docker image ls?
![alt text](image-7.png)
3. Volúmenes
¿Dónde podemos ver los volúmenes que tenemos en la aplicación Docker Desktop? (Captura de pantalla)
![alt text](image-8.png)
¿Qué podemos ver si accedemos a uno de los volúmenes en Docker Desktop? (Captura de pantalla)
![alt text](image-9.png)
¿Qué muestra el comando docker volume?
![alt text](image-10.png)
¿Qué muestra el comando docker volume ls?
![alt text](image-11.png)
4. Gestión de contenedores
Si accedemos a un contenedor, veremos las siguientes pestañas. Las más importantes son Logs, Exec y Files. Explica para qué crees que sirve cada una.
Pestañas de un contenedor en Docker Desktop

Si queremos ejecutar comandos dentro de un contenedor, podemos usar Docker Desktop o el comando docker exec.
Para abrir un terminal podemos ejecutar el programa bash con el parámetro -it (t para terminal e i para Standard Input):
docker exec -it <NOMBRE_DEL_CONTENEDOR> bash
Ejecuta el comando y muestra una captura de pantalla del terminal dentro del contenedor.
![alt text](image-12.png)
Apaga todos los contenedores de este proyecto con el comando docker compose down. (Captura de pantalla)
📤 Finalmente, entrega la tarea con los siguientes comandos (ejecutar en la raíz del proyecto):
git add --all

git commit -m "readme modificado"

git push