# Trabajo Práctico Final Especialización en Ciencia de Datos ITBA

Versión de python: `Python 3.7.6`

## Dataset

El dataset ubicado en el directorio `data/raw/test` y `data/raw/train` fue obtenido de diversos links mencionados en https://github.com/lindawangg/COVID-Net. La unificación de dicho dataset se realizó con la notebook encontrada en `notebooks/create_dataset.ipynb` obtenida del proyecto COVIDx y modificada.


## Estructura del repositorio

- `data`: Directorio que contiene las imágenes en su estado `raw`, procesado intermedio y resultante
- `notebooks`: dentro se encuentra los scripts y código en python base del trabajo práctico final
- `results`: contiene imágenes y reportes a utilizar en la versión escrita del trabajo práctico.

### Notebooks

- `create_dataset.ipynb`
    - Script utilizado para unificar múltiples datasets de radiografías frontales y laterales de tórax con su correspondiente diagnóstico. Obtiene como resultado 2 carpetas (test y train) con las imágenes y 2 archivos csv (test y train) con su metadata.
- `preprocessing.ipynb`
    - Script utilizado para el preprocesamiento de imágenes para la utilización de HOG y NMF
- `models.ipynb`
    - Script utilizado para entrenamiento y prueba del modelo de HOG y el modelo de HOG con NMF previo.


## Correr los scripts

Se debe instalar jupyter notebook y correrlo desde la raíz del repositorio. Desde la interfaz de jupyter se pueden correr cada uno de los scripts



