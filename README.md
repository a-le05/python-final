# Clase 11 Actividad en Python
```sh
1. # Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window
2. # Creamos una carpeta o directorio: 
mkdir python-final
3. # Entramos en ella: 
cd python-final
4. # Iniciamos el repositorio:
git init
5. # Creamos un archivo:
touch finales.py
6. # Abrimos VSC:
code .
7. # En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
python -V
python3 -V
8. # Creamos el entorno virtual en Python:
python3 -m venv venv #Creamos el entorno virtual
9. # Activamos el entorno virtual:
source venv/bin/activate #Activamos el entorno virtual en Linux
venv/scripts/activate #En windows
10. # Hacemos actualización del pip de Python
python3 -m pip install --upgrade pip #Actualizamos el pip
```
11. ## Investigar ¿Qué es el pip y porque lo actualizamos?
<sub> ¿Qué es pip? </sub>
<sub>
pip es el sistema de gestión de paquetes estándar para Python. Permite instalar y gestionar bibliotecas y dependencias que no están incluidas en la biblioteca estándar de Python. Con pip, los usuarios pueden buscar, descargar e instalar paquetes desde el Python Package Index (PyPI) y otros índices.</sub>
<sub> ¿Por qué actualizamos pip? </sub>
<sub>
Actualizar pip es importante por varias razones:</sub>
<sub>
Nuevas Funcionalidades: Las actualizaciones suelen incluir nuevas características que pueden mejorar la funcionalidad y la usabilidad de pip.
Corrección de Errores: Las versiones más recientes de pip incluyen correcciones de errores detectados en versiones anteriores. Esto puede mejorar la estabilidad y el rendimiento.
Mejoras de Seguridad: Las actualizaciones pueden incluir parches de seguridad importantes que protegen contra vulnerabilidades descubiertas en versiones anteriores.
Compatibilidad: Mantener pip actualizado asegura que sea compatible con la versión más reciente de Python y con otros paquetes.
Rendimiento: Las mejoras en el rendimiento son comunes en las actualizaciones, lo que puede hacer que las operaciones de instalación y gestión de paquetes sean más rápidas y eficientes. </sub>

12. ## Hacer al primer commit de este trabajo y unirlo al repositorio remoto.
```sh
git commit -m "clase 11 python agregue finales.py y readme.md" #commit mas comentario
```
13. ## Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba. 