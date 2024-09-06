Coffe Shop - Proyecto Django
============================

Bienvenido a este proyecto de una tienda virtual de Cafeteria en el cual podras crear, pedir y agregar productos de cafeteria, en el cual con tu usuario podras disfrutar de todos los servicios disponibles.


Requerimientos
--------------

* **SQLite** (Puedes cambiar al motor de base de datos que mas te guste)
* **Python 3.12.4**


Guia para la Instalacion
------------------------

Sigue los siguientes pasos para que puedas utilizar el proyecto en tu maquina local
### 1\. Clona el Respositorio del Proyecto

Clona el proyecto desde Github en tu maquina local

```bash
git clone https://github.com/MiguelEspalda/coffee_shop.git coffe_shop
cd coffe_shop
```

### 2\. Crea y Activa el entorno virtual

Crea el entorno virtual y luego activalo para instalar las librerias y extensiones necesarias

```bash
python -m venv venv
source venv/bin/activate
```

### 3\. Instala las dependencias necesarias

Instala las dependencias y librerias necesarias con el Paquete de python llamado "pip"

```bash
pip install -r requirements.txt
```

### 4\. Crea un superusuario

Crea el superusuario que utilizaras para acceder a la interface de admin en Django

```bash
python manage.py createsuperuser
```

### 5\. Ejecuta el proyecto en un servidor de desarrollo

Inicia el proyecto de Django

```bash
./manage.py runserver
```
Accederas al proyecto de Django en el puerto ```http://127.0.0.1:8000``` en tu navegador.


Estructura del proyecto
-----------------------

*   **products**: Aplicacion encargada de la logica de los productos.
*   **users**: Aplicacion que controla y maneja los usuarios del proyecto.
*   **orders**: Aplicacion que se encarga de las ordenes de los productos que maneja el usuario.


Contribuyendo
------------

¡Agradecemos las contribuciones! Trabaje con el repositorio y envíe solicitudes de extracción para cualquier característica, mejora o corrección de errores.
