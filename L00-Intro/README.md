# L0. Entorno de trabajo en Python

## Objetivo

En esta clase el alumno conocerá:

* La configuración e instalación de Python
* La implementación de ambientes virtuales
* La instalación de bibliotecas para el desarrollo del curso
* El uso de Notebooks de Python
* Manejo de Numpy y Pandas


## Ambientes virtuales

[`Uso de ambientes virtuales`](./L00-1-Ambiente/README.md)


__Reto 1. Creación de un ambiente virtual__

1. Crear un ambiente virtual desde Anaconda en la terminal o en la interfaz gráfica llamado `test`` con las siguientes características:

* Utilice la versión de Python 3.10
* Incluya la última versión de Numpy y de Pandas   

2. Crear un notebook de Jupyter que utilice el ambiente creado

3. Importar las librerías Numpy y Pandas 

```Python
import numpy as np
import pandas as pd
```

## Numpy

Es una librería enfocada al cálculo numérico y manejo de Arrays.

- Es muy veloz, hasta 50 veces más rápido que usar una lista de Python o C.
- Optimiza el almacenamiento en memoria.
- Maneja distintos tipos de datos.
- Es una librería muy poderosa, se pueden crear redes neuronales desde cero.

[`Jypiter Notebok Numpy`](./L00-2-Numpy/L00-2-numpy.ipynb)


## Pandas

Pandas está enfocada a la manipulación y análisis de datos.

- Al estar construido sobre NumPy es veloz.
- Requiere poco código para manipular los datos.
- Soporta múltiples formatos de archivos.
- Ordena los datos en una alienación inteligente.

Se pueden manejar ***grandes cantidades de datos***, hacer analítica y generar dashboards.

[`Jupyter Notebok Pandas`](./L00-3-Pandas/00_numpy_pandas.ipynb)
