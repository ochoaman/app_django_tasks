"# django-crud-auth" 
…or create a new repository on the command line

echo "# django-crud-auth" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ochoaman/django-crud-auth.git
git remote add origin https://github.com/ochoaman/app_django_crud.git

git push -u origin main


…or push an existing repository from the command line


git remote add origin https://github.com/ochoaman/django-crud-auth.git
git branch -M main
git push -u origin main


*************
.gitignore
__pycahe__
venv


En windows cancelar la operación de GIT
del .git

En Linux o Mac cancelar la operación de GIT

rm -rf .git

PROYECTO app GAMES.
APP web de python con endesive

En el Explorador de Windows ir a:
C:\BIZANCIO\appBizancio\GAMES pla barra de path de EXPLORADOR DE WINDOWS, digitar:
CMD
crear virtual environment

python -m venv myvenv

luego activarlo
 c:\BIZANCIO\appBizancio\GAMES\myvenv\Scripts\activate.bat

segunda forma
.\myvenv\Scripts\activate.bat

pip freeze > requirements.txt
Actualizar python, hay comando sugerido en pantalla: ... CONSULTAR

Previamente instalar bibliotecas como: se puede poner todas las libraries seguidas de: pip install endesive Flask mysql-connector-python pymysql 
pip install flask_mysqldb flask_wtf flask_login
python.exe -m pip install --upgrade pip

pip install endesive

pip install Flask

pip install mysql-connector-python

pip install pymysql

COMPROBAMOS LO QUE SE HA INSTALADO:

pip list

Package      Version
------------ -------
blinker      1.9.0
click        8.1.7
colorama     0.4.6
Flask        3.1.0
itsdangerous 2.2.0
Jinja2       3.1.4
MarkupSafe   3.0.2
pip          24.3.1
Werkzeug     3.1.3

-- AYUDA MEMORIA PARA AUTHENTIFY LOGIN, CREAR TASK CRUD AND DEPLOY EN render.com
py -m virtualenv env
para activar
.\env\Scripts\activate

pip install Django
django-admin --version
5.1.4

django-admin startproject django-crud .

crea carpeta django-crud y manage.py

correr con: 
python manage.py runserver
ya se puede ir a localhost:8000

crear las tasks
python manage.py startupp tasks

... crea la carpeta task 

-- pip install gunicorn
pip freeze requirements.txt


APP web de python endesive
OJO. instalar endesive
pip install endesive
también
pip install Flask

pip install mysql-connector-python

pip install pymysql

-- para login
pip install virtualenv
python -m virtualenv env
para activar
.\env\Scripts\activate
pip install -r requirements.txt

Carpeta GAMES: C:\LRM\TECNICO\GAMES

Abrir y levantar Apache, Mysql

Base de datos: crudmysql, tabla: juegos

correr: python main.py

Previamente crear la tabla:

CREATE TABLE `juegos` (
  `id` bigint(20) unsigned NOT NULL AUTO_INCREMENT,
  `nombre` varchar(255) NOT NULL,
  `descripcion` varchar(255) NOT NULL,
  `precio` decimal(9,2) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=5 DEFAULT CHARSET=utf8mb4;



En cualquier navegador.

http://127.0.0.1:8000/

(aparece el CRUD con los botones Agregar, Editar, Eliminar)
