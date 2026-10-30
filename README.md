##  Tutorial de Instalación y Ejecución

Para desplegar y ejecutar el proyecto localmente utilizando XAMPP (con PHP 7.4 o superior y MySQL/MariaDB) y cualquier navegador web. Como primer paso, descarga el proyecto clonando este repositorio mediante el comando `git clone https://github.com/TU_USUARIO/TU_REPOSITORIO.git` o descargando el archivo ZIP comprimido, y nombra la carpeta principal como `ferreteria`.

A continuación, mueve la carpeta `ferreteria` al directorio `htdocs` de tu instalación de XAMPP (por ejemplo, en Windows dentro de `C:\xampp\htdocs\ferreteria`). Luego, abre el **XAMPP Control Panel** e inicia los servicios de **Apache** y **MySQL** haciendo clic en sus respectivos botones **Start**, verificando que ambos queden resaltados en verde.

Para configurar la persistencia, ingresa desde tu navegador a phpMyAdmin en `http://localhost/phpmyadmin` y crea una base de datos llamada `ferreteria`. Selecciona la base de datos en el panel izquierdo, dirígete a la pestaña **Importar**, selecciona el archivo de la estructura SQL (como `base_datos.sql`) y haz clic en **Importar** al final de la página. Si las credenciales predeterminadas de MySQL cambian en tu entorno, puedes ajustarlas en `conexion.php`. Finalmente, abre una pestaña en tu navegador e ingresa a `http://localhost/ferreteria/` para comenzar a interactuar con la aplicación.
