# Sails_Project
Evaluación final Sails JS

## Consideraciones:
    Se utilizó npm sobre, yarn ya que este daba error y se actualizaron algunos modulos desactualizados.
    En el archivo fotosparatiDump_FacundoErbin.sql se encuentra un dump de la base de datos realizado una vez finalizado y comprobado el funcionamiento correcto, en este volcado las tablas ADMIN y CLIENTE cuenta con la columna alta. Esta propiedad es la que define si se algún usuario sea cliente o administrador puede iniciar sesión.

## Para arrancar el proyecto:

    Desde la carpeta del proyecto, en el mismo directorio donde se encuentra package.json, ejecutar el comando "npm install".
    Luego de la instalación proceder a levantar el servidor con "npm run dev" o "node app.js"
    Finalmente, abrir el navegador en http://localhost:1337/
    Para el correcto funcionamiento del sitio, debe estar corriendo de manera virtual una instancia de Postgresql con la base de datos del sistema en el puerto 5432.
