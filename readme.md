# Uso de Redes Neuronales Convolucionales para Clasficación de imagenes médicas

Este repositorio es un ejemplo para probar clasificadores basados en redes convolucionales para clasificar una base de datos de imagenes médicas.
Diseñado para la asignatura de _Ciencia de Datos en Salud_, Universidad de Valparaíso.

## Instalacion

### Clonar el repositorio
En la parte superior izquierda, aparece como clonar este repositorio, tambien pueden hacerlo desde una terminal (teniendo `git` instalado):
```bash
git clone https://github.com/dmelladoc/CNNMedicalTutorial.git
```
Otra opción es descargar el repositorio completo como ZIP.


### Crear un ambiente
Para evitar que las librerias a utilizar tengan conflictos con archivos de sistema, vamos a crear un ambiente de trabajo.
Si utilizan **Anaconda**:

```bash
conda create -n taller-cnn python
```

Posteriormente, terminando la creación de este ambiente, entramos en el utilizando el comando 
```bash
conda activate taller-cnn
```

### Instalar requisitos
El archivo `requeriments.txt` contiene el listado de las librerías que utilizaremos.
para instalar solo debe ejecutarse
```bash
pip install -r requirements.txt
```

O pueden instalarlos uno por uno (no recomendado), utilizaremos de forma general:

- NumPy
- [pytorch](https://www.pytorch.org)
- torchmetrics
- matplotlib
- [medMNIST](https://medmnist.com/)

## Notebooks
- [Evaluar Imagen](Notebooks/ClasificadorCNN.ipynb)
- [Entrenamiento con MedMNIST](Notebooks/Entrenamiento.ipynb)
- [Explicabilidad](Notebooks/Explicabilidad.ipynb)



