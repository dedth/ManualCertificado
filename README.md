# Manual Para Generar Un Certificado Auto Firmado Para Windows

![apache-openssl](https://i0.wp.com/guidocutipa.blog.bo/wp-content/uploads/2019/01/apache-openssl.jpg?fit=640%2C204&ssl=1)

>>Manual para generar un certificado auto firmado

>>Existes varias formas de generar un certificado auto firmado para windows
como los siguentes.

* Utilizando las  Herramientas de windows

* Descargar openSSl

#### CERTIFICADO CON OPENSSL

>> Lo primero que hacemos es ingresar al siguiente link y descargamos openSSL

openSSL Link: [Win32OpenSSL](https://slproweb.com/products/Win32OpenSSL.html)

Despues de descargar en nuestra pc abrimos una terminal de cmd y entramos ala carpeta de OpenSSL-Win64 con el comando cd para ingresar despues ingresamos el siguiente comando:

* openssl req -x509 -newkey rsa:4096 -keyout key.pem -out cert.pem -sha256 -days 365 -nodes

### COMANDOS ADICIONALES DE CMD

| comandos | Accion|
|---------|---------|
| cd   | entrar a una carpeta    |
| cls   | 	Limpia la pantalla    |
| date   | 	Muestra o establece la fecha del sistema.    |
| del  | 	Permite eliminar archivos.   |
| replace  | 	Reemplaza archivos.   |
| set  | 	Muestra, establece o elimina variables de entorno de Windows.   |
| exit  | 	Termina la sesión actual del CMD.EXE.  |

Una vez generado el comando mencionado damos enter y acontunucion nos dara unas preguntas para generar el certificado:

1. Pais

2. Provincia

3. Correo electronico

4. Se guardara el certificado con su respectiva clave
