
# studentOverFlow

Este es un proyecto Django que se puede ejecutar localmente usando el comando `python manage.py runserver`.

## Requisitos

Antes de comenzar, asegúrate de tener instalados los siguientes requisitos en tu sistema:

- Python 3.6 o superior
- pip (el gestor de paquetes de Python)
- Un entorno virtual de Python (opcional pero recomendado)

## Instalación

Sigue estos pasos para configurar y ejecutar la aplicación localmente:

1. **Clonar el repositorio**

   Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/AdrianSimei/studentOverFlow.git
   cd studentOverFlow
   ```

2. **Crear y activar un entorno virtual (opcional pero recomendado)**

   Crea un entorno virtual para el proyecto:

   ```bash
   python -m venv venv
   ```

   Activa el entorno virtual:

   En Windows:

   ```bash
   venv\Scripts\activate
   ```

   En macOS/Linux:

   ```bash
   source venv/bin/activate
   ```

3. **Instalar dependencias**

   Instala las dependencias del proyecto desde el archivo `requirements.txt`:

   ```bash
   pip install -r requirements.txt
   ```

4. **Configurar la base de datos**

   Aplica las migraciones para configurar la base de datos:

   ```bash
   python manage.py migrate
   ```

5. **Crear un superusuario (opcional)**

   Si deseas acceder al panel de administración de Django, puedes crear un superusuario:

   ```bash
   python manage.py createsuperuser
   ```

   Sigue las instrucciones en pantalla para configurar el superusuario.

6. **Ejecutar el servidor de desarrollo**

   Ejecuta el servidor de desarrollo:

   ```bash
   python manage.py runserver
   ```

   La aplicación estará disponible en [http://127.0.0.1:8000/](http://127.0.0.1:8000/) por defecto.

7. **Acceder al panel de administración (opcional)**

   Si has creado un superusuario, puedes acceder al panel de administración en:

   [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)
