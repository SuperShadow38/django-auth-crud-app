# Django CRUD APP

Django CRUD Auth is a Django-based web application that provides user authentication and CRUD (Create, Read, Update, Delete) functionality for managing user accounts.

## Características

- Registro de usuarios: Permite a los usuarios crear nuevas cuentas proporcionando información básica como nombre de usuario, dirección de correo electrónico y una contraseña segura.
- Autenticación de usuarios: Implemente la autenticación segura y la funcionalidad de inicio de sesión para garantizar que sólo los usuarios registrados puedan acceder a sus cuentas.
- Perfil de usuario: Permitir a los usuarios ver y actualizar la información de su perfil, incluyendo foto de perfil, biografía y otros detalles.
- Operaciones CRUD: Proporcione operaciones de creación, lectura, actualización y eliminación para gestionar las cuentas de usuario en el sistema.
- Restablecimiento de contraseña: Implemente una función de restablecimiento de contraseña para permitir a los usuarios restablecer su contraseña en caso de que la olviden.
- Control de acceso basado en roles: Asigne diferentes roles (por ejemplo, administrador, usuario normal) a los usuarios y aplique un control de acceso basado en roles para funcionalidades específicas.

## Requisitos

- Python 
- Django 

#Instalación

1. Asegúrate de que tienes Python y Django instalados en tu máquina.

2. Clona o descarga el repositorio "django-crud-auth".

3. Navega hasta el directorio del proyecto en tu terminal.

4. Crea y activa un entorno virtual (opcional, pero recomendado).

5. Instala las dependencias del proyecto ejecutando el siguiente comando:
   ```shell
   pip install -r requirements.txt
   
6. Aplique las migraciones:
   ```shell
   python manage.py migrate

7. Inicie el servidor de desarrollo:
   ```shell
   python manage.py runserver
   
8. Acceda a la aplicación en su navegador web en http://localhost:8000.

## Uso

- Visite la página de registro para crear una nueva cuenta.
- Utilice la página de inicio de sesión para autenticarse y acceder a su cuenta.
- Actualice la información de su perfil y gestione la configuración de su cuenta.
- Realice operaciones CRUD para gestionar cuentas de usuario.
- Si olvida su contraseña, utilice la función de restablecimiento de contraseña para restablecerla.
- Los usuarios administradores pueden acceder a funciones adicionales, como la gestión de funciones y permisos de usuario.

## Licencia

Este proyecto se publica bajo la licencia "Libre uso", lo que significa que es libre de usar, modificar y distribuir sin restricciones adicionales.

## Contacto

Si tiene alguna pregunta o sugerencia, no dude en ponerse en contacto con nosotros en fabioavila537@gmail.com.

Asegurate de personalizar el archivo README con detalles específicos sobre su proyecto, como instrucciones de instalación, directrices de uso e información de contacto.

¡Buena suerte con tu proyecto Django CRUD Auth! Si tienes más preguntas, no dudes en hacerlas.
