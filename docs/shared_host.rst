Pasos para utilizar cacao-accounting en un shared hots:

Compilar Python 3.8
===================

Hay que acceder vía ssh a la terminal del shared hosy:

Descargar la última versión de Python desde https://www.python.org/downloads/


wget https://www.python.org/ftp/python/3.8.5/Python-3.8.5.tgz
tar xvzf Python-3.8.5.tgz
rm Python-3.8.5.tgz
cd Python-3.8.5/
./configure --prefix=$HOME
make
make install



