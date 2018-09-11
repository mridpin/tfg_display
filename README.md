# Material TFG
Material para la demostración del TFG de Manuel Ridao, Universidad Pablo de Olavide 2018. El manual de uso se encuentra en el Anexo 2 del documento.

## Versión local con permanencia
Será necesario instalar Java y XAMPP, y crear una base de datos con colación _utf8_spanish_ci_ llamada _tfg_rol_. Para ello, es necesario seguir los siguientes pasos:

1. Arrancar MySQL y Apache y acceder al panel de control de MySQL haciendo clic en
“Admin”.

![configuración xampp](https://i.imgur.com/dVkdD32.png "XAMPP")

2. En el panel lateral, hacer clic en “New”, introducir el nombre de la base de datos, y elegir
su colación. No es necesario crear ninguna tabla. Desde este panel de control se puede
comprobar el contenido de las tablas.

![configuración mysql](https://i.imgur.com/w6GRB4g.png "MySQL")

3. Descargar el comprimido desde
https://github.com/mridpin/tfg_display/tree/master/Local%20con%20permanencia y
descomprimirlo en una ubicación. Este comprimido contiene el fichero JAR con la
aplicación en sí y las carpetas necesarias para su funcionamiento y las pruebas.

![contenido zip](https://i.imgur.com/5k6XY59.png "Contenido zip")

4. Ejecutar la aplicación. Se puede ejecutar haciendo doble clic en el fichero JAR, o
lanzándolo desde la terminal con el comando java -jar app.jar. Esta segunda opción
permite visualizar los comandos que la aplicación está ejecutando.

![lanzamiento app](https://i.imgur.com/XVTsSkQ.png "Lanzamiento app")

5. Acceder a la aplicación mediante http://localhost:8080 desde el navegador.

## Versión local portátil

Repetir el procedimiento anterior desde el punto 3, pero descargando la versión desde https://github.com/mridpin/tfg_display/tree/master/Local%20port%C3%A1til. Se puede acceder al contenido de la base de datos mediante el enlace http://localhost:8080/h2 y las credenciales por defecto.

## Versión en el hosting

Para la versión alojada en el hosting, bastará con acceder a http://historol.upotfgrol.tk/ desde un navegador.
