# Carrito
Pagina Web levantada mediante el framework de Django, conectada a una base de datos MySQL, la pagina web esta adecuada para un simular un carrito de comprar


Pasos para ejecutar
Clonar el repositorio con - git clone (url del repositorio)
Ejecutar scripts para descargar todas las dependencias y librerias utilizadas.
Orden de ejecucion
- ./install_docker.sh (una vez ejecutado salir y entrar de la intancia)
- ./docker_re-build.sh (con esto ya estara levantado el servidor)
en caso de querer vizualizar bases de datos
- ./MySQL_installer.sh
- SHOW DATABASES;

Para agregar un producto al carrito
- Primero ejecutar ./setup_env.sh para intalar dependencias (esto abrira el shell de python, cerrar con ctrl+D)
-  python agregar_producto.py (esto generara varios imputs con los parametros de los productos)
