# Servidor Coach DB

Se explicara el paso a paso para conectarte de manera remota.

## Conexion SSH

Para iniciar la conexión, abre una terminal e ingresar tu nombre de usuario y la IP del servidor.

```bash
ssh usuario@ip_servidor
```
Despues te pedira la contraseña y deberas ingresar la contraseña de pila proporcionada.

Al lograr ingresar deberas cambiar la contraseña.
 ```bash
passwd
```
Te pedira tu contraseña actual primero, despues ingresaras tu contraseña nueva.

## Configuración del servidoe Lighttpd
Light es como su nombre lo dice, rapido y serguro.
Para configurarlo lo puedes hacer desde la ruta /var/www/html

Para subir archivos es el siguiente comando.

 ```bash
scp index.html usuario@ip_del servidor:/var/www/html/
```

Podras acceder a tu aplicacion web:

> "Recuerda cambiar la IP", [LINK](http://IP_DEL_SERVIDOR)。


## Usage

Para subir archivos al servidor usando SSH, te pedira la tura local, el nombre del archivo, la ip del servidor y la ruta remota, por ejemplo:

```bash
ejemplo.json usuario@ip_servidor:/ruta/remota/destino
```
Si se utiliza un software con interfaz grafica es importante colocar, tu nombre de usuario, IP del servidor y contraseña en la configuración de conexión.

## Acceder y subir datos en CouchDB

nota: CoachDB solo admite datos tipo JSON.

Couch te permite gestionar documentos desde su interfaz WEB. Primero Accede a la interfaz desde el siguiente enlace.

> "Recuerda cambiar la IP", [LINK](http://IP_DEL_SERVIDOR:5984/_utils)。
Ingresas tus credenciales, en caso de que no puedas ingresar con tus mismas credenciales de Ligthhpd, solicita al administrador tu usuario y constraseña asignados.


## End