# python-kids-tutorial
Tutorial para aprender Python para niños.

Autor: Claudio Alarcón.

El objetivo principal es que mi hija de 7 años pueda programar cosas sencillas en Python, usando Python 3.x y la plataforma Jupyter.

La idea es que cada documento indique algún tópico de programación.

Es muy posible que el desarrollo de este proyecto sea muy lento, pues lo iré ajustando al nivel de interés de ella. 

Dentro de tutorial/ estará el contenido del tutorial.

Para iniciar el tutorial se requiere una instalación de Python 3 que incluya venv:

    python3 -m venv env
    source env/bin/activate  # En Windows env/Scripts/activate.bat
    python3 -m pip install jupyter
    python3 -m jupyter notebook --notebook-dir=tutorial/
