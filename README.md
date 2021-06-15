# INSTALACIÓN TENSORFLOW CON GPU FÁCIL Y RÁPIDO

## 1. Identificar tarjeta gráfica e instalar drivers
  https://la.nvidia.com/Download/index.aspx?lang=la
  
## 2. Instalar anaconda o miniconda
  https://www.anaconda.com/products/individual
  
## 3. Preparación del entorno
    $ conda create -n entornoGPU anaconda python=3.7.7
    $ conda activate entornoGPU
    $ conda install ipykernel
    $ python -m ipykernel install --user --name entornoGPU --display-name "entornoGPU"
    $ conda install tensorflow-gpu==2.1.0 cudatoolkit=10.1
    $ pip install tensorflow==2.1.0
    $ pip install jupyter
    $ pip install keras==2.3.1
    $ pip install numpy scipy Pillow cython matplotlib scikit-image opencv-python h5py imgaug IPython[all]
  

## 4. Probar versión y gpu
    $python
    $import tensorflow as tf
    $tf.__version__
    $tf.test.gpu_device_name()

## 5. Probar entrenamieneto 
   Ejecutar archivo MNISTEjmGPU.ipyng

# **Canal de Youtube**
[Click aquì pare ver mi canal de YOUTUBE](https://www.youtube.com/channel/UCr_dJOULDvSXMHA1PSHy2rg)
