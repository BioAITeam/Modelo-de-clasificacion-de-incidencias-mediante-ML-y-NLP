# Modelo de clasificación de incidencias utilizando aprendizaje de máquina para la línea de soporte técnico de la empresa SIGMA ingeniería S.A
La Inteligencia Artificial (IA) es uno de los componentes reconocidos por su potencial para transformar radicalmente el modo en el que vivimos actualmente. Hace posible que las máquinas aprendan de la experiencia, se ajusten a nuevas aportaciones y realicen tareas emulando a seres humanos. Esta investigación se centra en el ámbito empresarial y propone el desarrollo de un modelo computacional de clasificación de incidencias utilizando Aprendizaje Automático (ML por sus siglas en inglés) y Procesamiento de Lenguaje Natural (NLP por sus siglas en inglés) enfocado al área de soporte técnico en una empresa de desarrollo de software que actualmente resuelve los requerimientos de los clientes de forma manual. A través de técnicas de ML y NLP aplicadas a los datos de la empresa, es posible conocer la categoría de una solicitud dada por el cliente. Este proceso permite aumentar la satisfacción del cliente al revisar los registros históricos para analizar su comportamiento y proporcionar correctamente el protocolo de solución esperada a las incidencias presentadas. Además, reduce el coste y el tiempo dedicado a la gestión relacional con el consumidor potencial. Este modelo evalúa diferentes técnicas de ML como máquinas de vectores de soporte (SVM por sus siglas en inglés), Extra Trees, Regresión logística, árboles de decisión, análisis discriminante lineal, Naïve Bayes y K Vecinos más cercanos. El algoritmo SVM entrega el mayor desempeño, con un 90.47% de precisión, aplicando balanceo de clases, optimización de hiperparámetros y técnicas de preprocesamiento

## Citar

Si utiliza nuestro proyecto para su investigación o si encuentra este documento y el repositorio útiles, por favor considere citar el trabajo.

Cite el repositorio: [![DOI](https://zenodo.org/badge/500692485.svg)](https://zenodo.org/badge/latestdoi/500692485) 

## Carpetas

- **Data** carpeta que contiene las bases de datos entregadas por SIGMA Ingeniería S.A que pertenecen a los datos almacenados en Timework por el área de soporte y servicio al cliente de la empresa.
- **Notebook** carpeta que contiene el algoritmos de ocho técnicas de ML aplicados a las bases de datos de Timework mediante los cuatro experimentos propuestos en la tesis 


## Pre-requisitos
Este repositorio requiere las siguientes librerías:

- NumPy
- Pandas
- string
- Seaborn
- openpyxl
- scikit-learn
- TfidfVectorizer
- NLTK
- spaCy
- imbalanced-learn
- Matplotlib
- Yellowbrick
- Time

Este SW fue desarrollado en el lenguaje de programación Python 3 (3.8).

## Instalación

Si no usa Google Colab, le recomendamos que use e instale packages de Python dentro de un entorno de Anaconda. Para crear, ejecute el siguiente comando:
```
conda create --name TCC python=3.8
```
y actívelo con el siguiente comando:
```
conda activate TCC
```
Ahora, proceder a instalar los packages
```
pip install ipykernel
```
y visualice el entorno en jupyter
```
python -m ipykernel install --user --name TCC --display-name "TCC"
```
Finalmente, instale las librerías:
```
conda install -c conda-forge matplotlib
```
```
conda install -c anaconda seaborn
```
```
conda install -c anaconda scikit-learn
```
```
conda install -c districtdatalabs yellowbrick
```
```
conda install -c anaconda nltk
```
```
conda install -c conda-forge imbalanced-learn
```
```
conda install -c conda-forge spacy
```
```
python -m spacy download es_core_news_sm
```
```
python -m spacy download en_core_web_sm
```
```
conda install openpyxl
```
```
conda install xlrd
```

## Ejecución
Después de instalar todos los requisitos, debe clonar el repositorio usando:
```
git clone https://github.com/BioAITeam/Modelo-de-clasificacion-de-incidencias-mediante-ML-y-NLP.git
```
Si se va a usar colab, cargue la carpeta clonada en la unidad, luego abra la carpeta y ejecute el notebook.

Si se va a usar la computadora, instale:
```
conda install jupyter 
```
Ingrese a la carpeta clonada, luego ingrese a la carpeta y ejecute el notebook.
