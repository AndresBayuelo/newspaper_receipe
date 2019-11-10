----
## Qué versión de python?
Descargar [Python 3.8.0](https://www.python.org/ftp/python/3.8.0/python-3.8.0-amd64.exe)

> La versión de Python utilizada para la ejecución de este código es la anteriormente referenciada.

----
## Ejecución en Windows
1. Instalar Python.
2. Instalar virtualenv.
```
pip install virtualenv
```
3. Instalar virtualenvwrapper.
```
pip install virtualenvwrapper-win
```
4. Ubicado en el directorio del proyecto crear el entorno virtual especificando la versión de Python previamente instalada.
```
virtualenv -p C:\Python\Python38\python.exe venv
```
5. Instalar las dependencias.
```
venv\Scrips\pip install -r requirements.txt
```
6. Ejecutar.
```
venv\Scrips\python newspaper_receipe.py --help
```
```
venv\Scrips\python newspaper_receipe.py eluniversal_2019_11_08_articles.csv
```
