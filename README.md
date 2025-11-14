# Docker con Flask - Motos 
paso a paso de la creacion del docker

1. empezamos creando la parte del codigo en este caso fue en Visual Studio Code
   * se crea una carpeta que tendra: 3 archivos (app.py - dockerfile y requirements.txt) y una carpeta llamada templates, dentro de esta esta un archivo index.html, que como dice estara el codigo de la pagina web que en este caso sera con html
   * afuera de la carpeta se crea un archivo llamado docker-compose.yml

2. se crea el reposirotio en github que sea publico
3. en la termial entramos a la carpeta donde tenemos el archivo con todo el codigo, ya estando ahi, iniamos la compatibilidad con el repositorio, para asi poder subir los archivos a la nube
4. creamos en aws la maquina para descargar el docker.
5. accedemos a la maquina, se instala el docker y se copia lo que tenemos en el repositorio de la nube para tenerlo en la maquina y luego se pone a correr la pagina
