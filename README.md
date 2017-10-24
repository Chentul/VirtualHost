VirtualHost
=========================
Ejemplo de un archivo básico para la configuración de un VirtualHost en apache.

Ubicación de los archivos.
=========================
/etc/apache2/sites-available

Algunos comandos
=========================
- sudo a2ensite miarchivodeconfiguracion.conf (Comando para habilitar la configuración)
- sudo a2dissite miarchivodeconfiguracion.conf (Comando para deshabilitar la configuración)

Cabe mencionar que una vez ejecutado alguno de estos comandos habrá que reiniciar el servidor apache para que se vean 
reflejados los cambios.

Agregar dirección para que se vea afectada de manera local
=========================
Para que estos cambios se vean reflejados de manera local hay que agregar una configuración en el archivo /etc/hosts
- 127.0.1.1     www.midominio.com
