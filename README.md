# Taller de introducción a Deep Learning

En este taller daremos una introducción a Deep Learning y redes neuronales utilizando TFlearn y TensorFlow. En el proyecto vamos a desarrollar una red neuronal que puede distinguir dígitos escritos a mano. Antes de poder comenzar, es necesario hacer cierta configuración.

## La manera corta (sugerida)

[Colab](https://colab.research.google.com/notebook) es un proyecto gratuito de Google que fue anunciado públicamente hace unos meses. Esta herramienta permite utilizar cuadernos de Python (Jupyter) guardándolos en Google Drive y corriendo en máquinas virtuales de Google de manera gratuita. Estas máquinas virtuales ya vienen con todos los programas requeridos y, por lo tanto, no requiere instalación. Sin embargo, dado que recién se ha anunciado, está en una fase en la que se debe pedir acceso para poder utilizar (se tardan alrededor de un día en otorgarlo, pero este tiempo puede variar). Para pedir acceso, sólo debes abrir el [enlace y registrarte](https://research.google.com/colaboratory/unregistered.html). Para acceder al cuaderno de este taller, sólo hay que [abrirlo aquí](https://colab.research.google.com/notebook#fileId=1LM8-LIvp2ZS4Q_4EasayHYPijTKRbuKD) y hacer una copia. ¡Ahora tú podrás correr el código y hacer los cambios que quieras!

## La manera larga 

La instalación y configuración puede ser un poco tediosa, pero, si se hace bien, servirá para siempre. Anaconda es una herramienta que permite manejar ambientes de manera flexible y modular. Python tiene dos versiones diferentes del lenguaje y muchas libreras tienen diferencias. Esto puede hace difícil que tu código funcione en otras computadoras. Anaconda hace fácil esto creando un ambiente en tu computadora y usando versiones especficas de estos paquetes. Lo único que se necesita saber para lograr esto es utilizar la terminal de tu sistema operativo (sólo vamos a correr unos cuántos comandos, nada complicado).

En el siguiente [link](https://www.continuum.io/downloads) se explica como instalar Anaconda para cualquier sistema operativo. No es necesario tener nada más instalado. Elige Python 3.6 (desde Anaconda podrás instalar otras versiones más adelante).

Una vez que hayas instalado Anaconda, sólo es necesario crear el ambiente

```
conda create -n taller-dl python=3.5
``` 

Finalmente, activamos el ambiente e instalamos libreras necesarias.

Mac o Linux: 

```source activate taller-dl```

Windows: 

```activate taller-dl```

```
conda install numpy pandas jupyter notebook matplotlib
```

Instalación de librerías principales (scipy, TensorFlow, y TFlearn):

```
conda install scipy h5py
pip install tensorflow
pip install TFLearn
```

En este momento podemos correr el comando jupyter notebook, y este dará un enlace para abrir el cuaderno en cualquier navegador (se debe navegar a la carpeta donde está el cuaderno). Arriba a la derecha puedes descargar el cuaderno como zip.
