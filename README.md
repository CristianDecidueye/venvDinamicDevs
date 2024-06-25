# ¿QUE ES EL PIP?

<p>pip es el gestor de paquetes oficial para Python. Se utiliza para instalar, actualizar y desinstalar paquetes de software escritos en Python. Aquí están las funciones básicas:

1. Instalación de paquetes: Puedes usar pip para instalar paquetes disponibles en el Python Package Index (PyPI). Por ejemplo, para instalar el paquete requests, usarías el siguiente comando en tu terminal:
<strong>pip install requests</strong>

2. Actualización de paquetes: pip también permite actualizar paquetes a sus versiones más recientes. Para actualizar el paquete requests, usarías:
<strong>pip install --upgrade requests</strong>

3. Desinstalación de paquetes: Si necesitas desinstalar un paquete, pip puede hacerlo fácilmente. Para desinstalar requests, usarías:
<strong>pip uninstall requests</strong>

4. Listado de paquetes instalados: Puedes listar todos los paquetes instalados en tu entorno de Python con el siguiente comando: 
<strong>pip list</strong>

5. Generación de archivos de requisitos: Es común que los proyectos de Python incluyan un archivo requirements.txt que enumere las dependencias del proyecto. Para generar este archivo, puedes usar:
<strong>pip freeze > requirements.txt</strong>

6. Instalación desde un archivo de requisitos: Para instalar todas las dependencias listadas en un archivo requirements.txt, usarías:
<strong>pip install -r requirements.txt</strong>

</p>
<h2>¿Por qué se debe actualizar el pip?</h2>
<p>
Actualizar pip es importante por varias razones:

1. Nuevas características: Las versiones más recientes de pip suelen incluir nuevas funcionalidades que pueden mejorar tu flujo de trabajo.

2. Corrección de errores: Las actualizaciones corrigen errores y problemas que pueden haber estado presentes en versiones anteriores.

3. Seguridad: Las nuevas versiones incluyen parches de seguridad que protegen tu entorno de desarrollo contra vulnerabilidades conocidas.

4. Compatibilidad: Mantener pip actualizado asegura que sea compatible con las últimas versiones de Python y otros paquetes que podrías necesitar.

Para actualizar pip, puedes usar el siguiente comando:
<strong>pip install --upgrade pip</strong>
</p>

<h2>Pasos para crear un entorno virtual</h2>
<p>
1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 

mkdir python-final

3. Entramos en ella: 

cd python-final

4. Iniciamos el repositorio:

git init

5. Creamos un archivo:

touch finales.py

6. Abrimos VSC:

code .

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

python -V

python3 -V

8. Creamos el entorno virtual en Python:

python3 -m venv venv #Creamos el entorno virtual

9. Activamos el entorno virtual:

source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows

10. Hacemos actualización del pip de Python

python3 -m pip install --upgrade pip #Actualizamos el pip
</p>