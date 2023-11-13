

### Instalación de Git

Primero, se verifica e instala `git` utilizando el gestor de paquetes `apt`.

```bash
sudo apt install git
git --version
```
![git](/img_vmn1/01_install-git.png)


### Clonación del Repositorio

Se clona el repositorio de GitHub que contiene el código de la aplicación.

```bash
git clone https://github.com/KIRILL3POK/BlackJack
```
![git clone](/img_vmn1/02-clone.png)

El repositorio se clona en el directorio BlackJack.

### Verificación del Código de la Aplicación

Se navega al directorio del juego y se verifica el contenido.

```bash
cd BlackJack/CodigoJuego/
ls
```

![confirmacion descarga](/img_vmn1/03-codigo-juego.png)

Los archivos index.html y el directorio assets son confirmados.

### Instalación de Apache2

Se actualiza la lista de paquetes y se instala Apache2.

```bash
sudo apt-get update
sudo apt-get install apache2
```
![apache](/img_vmn1/04-apache.png)

Se verifica el funcionamiento de Apache accediendo a la IP pública de la VM, la cual muestra la página por defecto de Apache.

![resultado apache](/img_vmn1/04-resultado-Apache.png)

### Configuración de Apache y Permisos de Archivos

```bash
sudo cp -R * /var/www/html/
sudo chown -R www-data /var/www/html
sudo chmod -R 755 /var/www/html
```

Se copian los archivos de la aplicación al directorio raíz de Apache y se establecen los permisos necesarios.
***
*El directorio /var/www/html/ en sistemas Linux que utilizan el servidor web Apache es el lugar predeterminado para alojar los archivos de contenido web. Este es el directorio raíz del servidor web, también conocido como "document root".*

*Cuando se configura Apache y se pone en marcha, cualquier archivo que coloques en este directorio será servido por Apache y accesible a través del navegador web utilizando la dirección IP o el dominio asociado a tu servidor*
***




### Reinicio del Servidor Apache

Para aplicar los cambios, se reinicia el servicio de Apache.

```bash
sudo systemctl restart apache2
```
![renicio](/img_vmn1/06-apache-retart.png)


### Resultado final 

![resultado final](/img_vmn1/resultado-final.png)

Después de reiniciar Apache, la aplicación debería estar accesible desde el navegador utilizando la IP pública de la VM.


