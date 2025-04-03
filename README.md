# ML_Students_Performance

Spanish version:

## Predicción del Rendimiento Académico de Estudiantes
### Descripción del Proyecto
Este proyecto busca predecir el rendimiento académico de estudiantes de secundaria mediante técnicas de clasificación. A partir de diversas características sociodemográficas y académicas, el modelo desarrollado puede identificar patrones que influyen en el desempeño estudiantil, lo que puede ser útil para diseñar estrategias de mejora educativa.

### Dataset
El conjunto de datos utilizado pertenece a Rabie El Kharoua y está disponible públicamente en Kaggle. Se puede acceder en el siguiente enlace:
[Students Performance Dataset](https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset)

El dataset contiene información sobre estudiantes, incluyendo variables como género, nivel educativo de los padres, tiempo de estudio, entre otros factores, y su impacto en el rendimiento académico.

### Solución Adoptada
Para abordar el problema, se han desarrollado y probado varios modelos de clasificación utilizando diferentes enfoques. Se han evaluado métricas como la precisión, recall y F1-score para seleccionar el mejor modelo. Finalmente, se han guardado los modelos más eficientes en formato .pkl para su reutilización.

### Estructura del Repositorio
La organización del proyecto es la siguiente:
```
src/
│── data/                     # Contiene los datos utilizados en el proyecto  
│   ├── Student_performance_data_.csv  
│── img/                      # Imágenes utilizadas en los notebooks o reportes  
│   ├── cabecera.jpg  
│── models/                   # Modelos entrenados almacenados en formato .pkl  
│   ├── best_model_bin.pkl  
│   ├── best_model_multi.pkl  
│── notebooks/                # Distintas versiones de los notebooks exploratorios y de modelado  
│   ├── notebook_v1.ipynb  
│   ├── notebook_v2.ipynb  
│   ├── ...  
│── results_notebooks/        # Notebooks con resultados finales  
│   ├── result_notebook.ipynb  
│── utils/                    # Scripts con funciones auxiliares  
│   ├── __init__.py  
│   ├── bootcampviztools.py  
│   ├── data_sample.xlsx  
```

### Autora
Este proyecto ha sido desarrollado íntegramente por Mar Pérez.



Engilsh version:

## Predicting Academic Performance of Students
### Project Description
This project aims to predict the academic performance of high school students using classification techniques. By analyzing various socio-demographic and academic factors, the developed model can identify patterns that influence student performance, which can be useful for designing educational improvement strategies.

### Dataset
The dataset used belongs to Rabie El Kharoua and is publicly available on Kaggle. You can access it through the following link:
[Students Performance Dataset](https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset)

The dataset contains information about students, including variables such as gender, parental education level, study time, and other factors that impact academic performance.

### Adopted Solution
To address the problem, multiple classification models were developed and tested using different approaches. Metrics such as accuracy, recall, and F1-score were evaluated to select the best-performing model. The most efficient models were then saved in .pkl format for future use.

### Repository Structure
The project is organized as follows:

```
src/
│── data/                     # Contains the data used in the project  
│   ├── Student_performance_data_.csv  
│── img/                      # Images used in notebooks or reports  
│   ├── cabecera.jpg  
│── models/                   # Trained models stored in .pkl format  
│   ├── best_model_bin.pkl  
│   ├── best_model_multi.pkl  
│── notebooks/                # Different versions of exploratory and modeling notebooks  
│   ├── notebook_v1.ipynb  
│   ├── notebook_v2.ipynb  
│   ├── ...  
│── results_notebooks/        # Notebooks with final results  
│   ├── result_notebook.ipynb  
│── utils/                    # Scripts with utility functions  
│   ├── __init__.py  
│   ├── bootcampviztools.py  
│   ├── data_sample.xlsx  
```

### Author
This project was entirely developed by Mar Pérez.