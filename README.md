# APP Restaurante

Restaurante | ConfiguroWeb es una aplicación web que gestiona el orden del menú del restaurante entre el perfil mesero y el chef

## Comenzando 🚀

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu maquina local para propositos de desarrollo y pruebas._

Mira **Deployment** para conocer como desplegar el proyecto.


## Pre-requisitos 📋
Con estos requisitos son necesarios para ejecutar el proyecto en un servidor local:

* PHP 7.1 o superior
* MySQL DataBase
* Apache Tmomcat 8.5.64 o superio
* o instalar
* XAMPP contiene todo lo que es necesario para compilar el proyecto PHP

1. Se descarga el ejecutable PHP 7.3.27 o superior de las version windows:
   [Enlace de Descarga PHP](https://www.php.net/downloads.php) mas informacion: https://www.php.net/download-docs.php
2. Se descarga el ejecutable MySQL 8.0.23 en windows:
   [Enlace de Descarga MySQL](https://dev.mysql.com/downloads/installer/) mas informacion: https://dev.mysql.com/doc/
3. Se descarga el ejecutable Tomcat 8.5.64 Released o superior:
   [Enlace de Descarga Tomcat](https://tomcat.apache.org/download-10.cgi)
   O solo se instala XAMPP:
    [Enlace de Descarga XAMPP](https://www.apachefriends.org/es/download.html)


### Instalación 🔧
Nota: Recuerde Descargar el proyecto del repositorio
![image](https://user-images.githubusercontent.com/28444922/113646567-ada7c180-964e-11eb-9742-35b4060b9625.png)

**1. Instalamos XAMPP**

 1.1 Iniciar el asistente de instalación.
   * Aparecera la pantalla de inicio del asistente para instalar XAMPP. Para ajustar las   configuraciones de la instalación se hace clic en “Next”.
 	
 1.2 Selección de los componentes del software
   * Se recomienda la configuración estándar para un servidor de prueba local, con la cual se instalan todos los componentes disponibles. Confirma la selección     haciendo clic en “Next”.
   
 1.3 Selección del directorio para la instalación
   * Se escoge el directorio donde se instalará el paquete. Si se ha escogido la configuración estándar se creará una carpeta con el nombre XAMPP en C:\.
   
 1.4 Iniciar el proceso de instalación
   * El asistente extrae los componentes seleccionados y los guarda en el directorio escogido en un proceso que puede durar algunos minutos.
	
 1.5 Configurar Firewall
   * Durante el proceso de instalación es frecuente que el asistente avise del bloqueo de Firewall. En la ventana de diálogo puedes marcar las casillas correspondientes para permitir la comunicación del servidor Apache en una red privada o en una red de trabajo. Recuerda que no se recomienda usarlo en una red pública.
   
 1.6 Cerrar la instalación
   * Una vez extraídos e instalados todos los componentes puedes cerrar el asistente con la tecla “Finish”.
   
 1.7 Panel de control de XAMPP
   * En la interfaz de usuario del panel de control se protocolan todas las acciones y es posible activar o desactivar los módulos por separado con un simple clic.
 
 1.8 Iniciar módulos
   * En la parte superior se pueden iniciar o interrumpir los módulos de XAMPP por separado mediante los comandos “Start” y “Stop” bajo “Actions”.
 
 1.9 phpMyAdmin
   * Haciendo clic en la tecla “Admin” de la base de datos se abre phpMyAdmin, donde se pueden administrar las bases de datos del proyecto web que se quiere probar con XAMPP.  

## Despliegue ðŸ“¦
Para el despliegue en el servidor local:
1. Se descarga el proyecto del repositorio
2. Se descomprime y se mueve el proyecto a la carpeta C:\xampp\htdocs 
3. Ejecutamos el XAMPP para desplegar el Apache y MySQL donde se crea e importa la DB
4. Por ultimo http://localhost/Arquitectura_Restaurante-main/index.php
> Para el despliegue en el servidor

## Construido con ðŸ› ï¸?

_Menciona las herramientas que utilizaste para crear tu proyecto_

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - El framework web usado
* [Maven](https://maven.apache.org/) - Manejador de dependencias
* [ROME](https://rometools.github.io/rome/) - Usado para generar RSS

## Contribuyendo ðŸ–‡ï¸?

Por favor lee el [CONTRIBUTING.md](https://gist.github.com/villanuevand/xxxxxx) para detalles de nuestro cÃ³digo de conducta, y el proceso para enviarnos pull requests.

## Wiki ðŸ“–

Puedes encontrar mucho mÃ¡s de cÃ³mo utilizar este proyecto en nuestra [Wiki](https://github.com/tu/proyecto/wiki)

## Versionado ðŸ“Œ

Usamos [SemVer](http://semver.org/) para el versionado. Para todas las versiones disponibles, mira los [tags en este repositorio](https://github.com/tu/proyecto/tags).

## Autores âœ’ï¸

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_

* **Mauricio Sevilla Britto** - *Creador* - [Mauricio Sevilla Britto](https://github.com/configuroweb)
* **Leabiv Leonardo Rivera Cardenas** - *Colaborador de DocumentaciÃ³n e InstalaciÃ³n* - [Leabiv](https://github.com/leabiv)
* **Diana Lucia LeÃ³n Figueroa** - * Colaborador de Frontend* - [Kotoko04](https://github.com/kotoko04)
* **Jarbir Stewart Mejia** - *Colaborador de DocumentaciÃ³n* - [jarbirS](https://github.com/jarbirS)
