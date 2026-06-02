# Gestión de Notas - Configuración del Entorno

Este proyecto consiste en un script de automatización en Python diseñado para leer variables de entorno y validar la configuración local del sistema de gestión de notas.

## Requisitos Previos
* Python 3.10 o superior
* Entorno virtual configurado (`.venv`)

## Configuración del Archivo .env
Para que el proyecto funcione correctamente, debes crear un archivo `.env` en la raíz del proyecto basándote en la siguiente plantilla:

```env
PORT=tu_puerto_local
DB_URI=tu_cadena_conexion_base_datos
SECRET_KEY=tu_clave_secreta_segura
DEBUG=True_o_False
good