# Proyecto Django

## Creacion de un entorno virtual para el proyecto Django

Un entorno virtual es un espacio aislado donde se instalan paquetes de python y sus dependencias, sin afectar al sistema global. Esto permite tener diferentes versiones de paquetes y librerias para cada proyecto, evitando conflictos y problemas de compatibilidad.

python -m venv .venv

## Activacion del entorno virtual en Windows (PowerShell) y Linux (Bash)

### Windows (PowerShell)

.venv\Scripts\activate (con .venv/Scripts/activate tambien lo toma)

### Linux (Bash)

source .venv/bin/activate

## Instalacion de Django en el entorno virtual

pip install django

## Verificacion de la instalacion de Django

django-admin --version

## Crear .gitignore para el proyecto Django
