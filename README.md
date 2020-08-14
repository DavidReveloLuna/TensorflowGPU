# INSTALACIÓN TENSORFLOW CON GPU FÁCIL Y RÁPIDO

## 1. Identificar tarjeta gráfica e instalar drivers
  https://la.nvidia.com/Download/index.aspx?lang=la
  
## 2. Instalar anaconda o miniconda
  https://www.anaconda.com/products/individual
  
## 3. Crear entorno con python 3.7.7
    $conda create -n entornoGPU anaconda python=3.7.7
    
    $conda activate enetornoGPU
    
    $conda install ipykernel
    
    $python -m ipykernel install --user --name entornoGPU --display-name "entornoGPU"
  
## 4.Instalar tensorflow 2.1
    $conda install tensorflow-gpu
    $conda install tensorflow==2.1

## 5. Instalar jupyter
    $conda install jupyter

## 6. Instalar keras
    $conda install keras

## 7. Probar versión y gpu
    $python
    $import tensorflow as tf
    $tf.__version__
    $tf.test.gpu_device_name()

## 8. Probar entrenamieneto 
   Ejecutar archivo MNISTEjmGPU.ipyng
