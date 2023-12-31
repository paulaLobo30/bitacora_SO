# Bitácora de Comandos SO
Bitácora de Comandos para SO
| Comando | Descripción | Ejemplo de uso |
|--|--|--|
| `ls`  | Da la información de los archivos | `ls -l` muestra los archivos en lista |
| `nano` | Creación de archivos | `nano archivo.txt` crea un archivo de texto con ese nombre |
| `cat` | Visualización de archivos | `cat archivo.txt` da la visualización del contenido de ese archivo |
| `mkdir`| Creación de carpetas |  `mkdir usuario` crea una carpeta con el nombre usuario |
| `rm` | Borrar algun archivo | `rmdir` borra un directorio vacío |
|`mv`| Mover archivo |`mv` más el directorio inicial y al que se desea mover hace el traspaso exitoso |
|`ip`| Te va a dar la dirección ip en la que estás | `ip addr` Enumera y muestra todas direcciones ip |
|`man`| Muestra el manual de lo que necesites | `man ls` muestra el manual de la información de archivos |
|`cd`| Elegir carpeta | `cd paula`  elige la carpeta con ese nombre |
| `sudo apt install` | Comando para instalar | `sudo apt install pyton` da los permisos e intalará la aplicación elegida|
|`cp`| Copiar un archivo | `cp` junto el nombre del archivo y a la carpeta que desea copiarse hacen exitosa la copia |
|`whoami`| Saber usuario | `whoami` en el terminal muestra en el usuario que está |
| `pwd` | Ubicacón carpeta | `pwd` con el nombre de la carpeta muestra donde está ubicado |
| `su root` | Iniciar sesión en root | `su root`  inicia la sesión para tener todos los permisos |
|`sudo passwd` | Cambio de contraseña | `sudo passwd` permite el cambio de contraseña al usuario de ser necesario |
|`exit` | Salir del root | `exit` si ya no se necesita el root |
|`clear`| Borrar | `clear` cuando se quiere borrar todo de la terminal |
|`more` | Mostrar el resultado de la ejecución de un comando en la terminal de a una página a la vez | `ps -ef more` La pantalla se llenará con una lista de datos, pero se detendrá al final de la página con el mensaje "more" |
| `ps`| Ver lista de procesos corriendo| `ps-aux`  muestra información detallada sobre los procesos en ejecución en el sistema|
| `chmod` | Cambia los permisos | `chmod` al usuarlo con un archivo o carpeta permite cambiar los permisos |  
| `echo` | Va a mostrar un mensaje o variable en la salida | `echo Hola Mundo` Muestra el mensaje "Hola Mundo" |
| `chown` | Cambiar propietarios | `chown` permite cambiar el propietario |
| `useradd`| Agregar usuario | `useradd usuario` Agrega un nuevo usuario llamado "usuario"|
|`deluser` | Eliminar usuario | `deluser` elimia el usuario "usuario"|
|`top` | Mostrar lista de procesos | `top` monitorea en tiempo real la actividad del sistema, incluyendo la utilización de la CPU, la memoria y otros |
|`reboot`| Reiniciar | `sudo reboot`  reinicia el sistema |
| `date` | Fecha y hora | `date` muestra la fecha y hora actual del sistema |
|`history`| Historial | `history` muestra el historial de comandos usados |
| `apt`| Gestiona paquetes | `sudo apt update` actualiza los paquetes |
| `du` | Muestra el espacio utilizado por archivos y directorios | `du -h archivo.txt` muestra el espacio  utilizado en el archivo |
| `wget` | Descarga archivos desde la web | `wget https://paula.com/archivo.txt` descarga el archivo que se pidió |
| `zip` | Crea archivos ZIP | ` zip archivo.zip archivo.txt` el archivo seleccionado se convierte en ZIP |
| `unzip`| Descomprime archivos ZIP | `unzip archivo.zip`  descomprimr todo lo que haya en el archivo seleccionado |
| `ping` | Envía paquetes ICMP a una dirección para comprobar conectividad | `ping google.com` envia paquetes ICMP a "google.com" para verificar la conectividad |
| `df` | Muestra el espacio en disco utilizado y disponible| `df -h` muestra el espacio en disco utilizado y disponible |
|`curl` | Obtiene datos desde URLs | `curl https://ejemplo.com` Obtiene y muestra el contenido de la URL|
|`tar` | Comprime y descomprime archivos y directorios | `tar -cvzf archivo.tar.gz carpeta` Creará un archivo comprimido tar.gz de la carpeta |
| `killall` | Finaliza procesos por nombre | `killall nombre_proceso` finaliza todos los procesos con el nombre especificado |
|`at` | Ejecuta comandos en un momento específico en el futuro | `at now + 1 hour` programará un comando para ejecutarse en una hora|
| `watch`| Ejecuta un comando repetidamente y muestra la salida en tiempo real | `watch -n 1 df -h` Ejecuta repetidamente el comando df -h cada segundo y muestra la salida en tiempo real|
|`find` |Busca archivos y directorios en función de varios criterios | `find /ruta -name "patrón"` Busca archivos y directorios en la "ruta" especificada que coincidan con el "patrón" de nombre|
|`visudo` |Edita el archivo sudoers para configurar el acceso sudo | `sudo visudo` Abre el archivo sudoers para editar los permisos de sudo de manera segura|
|`shutdown` |Apaga o reinicia el sistema|`sudo shutdown -h now` apaga el sistema de inmediato|
|`sed` |Editor de flujo para transformar textos| `sed 's/antiguo/nuevo/g' archivo.txt` reemplaza "antiguo" con "nuevo" en "archivo.txt"|
|`iwconfig` |Muestra la configuración de redes inalámbricas | `iwconfig wlan0` muestra la configuración de la interfaz inalámbrica wlan0|
|`awk` | Procesa y transforma datos de texto|`awk {'print $1}' archivo.txt` imprime la primera columna del archivo|
| `sudo pacman -Sy` | Actualiza la lista de paquetes disponibles en los repositorios| `sudo pacman -Sy` se conectará a los repositorios y actualizará la lista de paquetes disponibles |
|`grep`| Busca patrones en archivos de texto| `grep "buscar_texto" archivo.txt` busca "buscar_texto" en "archivo.txt"|
|`rsync`| Sincroniza archivos y directorios localmente o entre servidores|`rsync -av carpeta/ servidor:/ruta/destino` sincroniza una carpeta con un servidor remoto|
| `scp` |Copia archivos de/a un servidor remoto| `scp archivo.txt usuario@servidor:/ruta/destino` copia "archivo.txt" al servidor remoto|
|`lsof` | Muestra los archivos abiertos por procesos|`lsof -i :80` muestra procesos que escuchan en el puerto 80|
