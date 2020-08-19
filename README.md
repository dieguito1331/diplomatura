# Clases

## Overview

Este repositorio contendra las clases para la diplomatura en Ciencias de Datos Aplicadas, Para poder instalar las librerias se deberan realizar varios pasos:
1) Instalacion del ejecutable de python en la siguiente ruta: https://www.python.org/downloads/
Este codigo esta realizado con la version Python 3.7.6

2) Instalar la libreria virtualenv
```
pip install virtualenv
```

3) crear un entorno virtual. Para esto se debera elegir en donde se guardara fisicamente el entorno virtual. Recomiendo que el entorno no se encuentre fisicamente en la misma carpeta en donde se encuentra el codigo
```
virtualenv entornoVirtual
```
Tener en cuenta que si se posee mas de un interprete de python (por ejemplo una version Python 2.7 y otra version Python 3.7) se debera seleccionar con que interprete de python se elegira crear el entorno virtual
```
pip install virtualenv --python="rutaDondeSeEncuentraElInterprete"
```

4) Activar el entorno virtual
###Windows
```
cd entornoVirtual/Scripts
activate
```
###Mac/Linux
```
source entornoVirtual/bin/activate
```

5) Instalar las librerias necesarias
Para eso hay que posicionarse en la carpeta en donde se encuentra el archivo requirements.txt
```
pip install -r requirements.txt
```

6) Por ultimo ejecutar la siguiente sentencia
```
jupyter lab build --minimize=False
```

7) abrir jupyterlab
```
jupyter lab
```

## Bases para trabajar

Las bases de datos se deberán descargar del siguiente link: https://bit.ly/3iX8uF9
La carpeta completa se deberá dejar en la raíz de la carpeta del proyecto