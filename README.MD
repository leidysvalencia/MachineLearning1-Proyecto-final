# Machine Learning 1
## Proyecto 3 – Predicción de Obesidad a partir de Hábitos de Vida

## Integrantes
* **Leidys Valencia** - Interpretación de resultados y documentación
* **Marjoris Parejo** - Preprocesamiento de datos y modelado.
* **Adriana Maldonado** - Análisis de datos y visualización.
* **Julio Cesar Rodríguez** - Optimización de modelos y evaluación.

---

## Descripción del Proyecto

Este proyecto tiene como objetivo estimar los niveles de obesidad en poblaciones de México, Perú y Colombia mediante el análisis de hábitos alimenticios y condiciones físicas. Utilizando un conjunto de datos que contiene 2111 registros y 17 variables, se aplicaron técnicas de agrupamiento no supervisado (clustering) y modelos de clasificación supervisada para identificar patrones que permiten predecir los niveles de obesidad.

La metodología incluye la segmentación de datos, la reducción de dimensionalidad mediante PCA (Análisis de Componentes Principales) y el entrenamiento de modelos de clasificación como Random Forest, SVM y XGBoost. Los resultados obtenidos proporcionan insights valiosos para la personalización de estrategias de salud pública en función de factores como edad, género y hábitos alimentarios.

## Estructura del Proyecto

### Archivos y Carpetas

* **`Datos/`**: Contiene el archivo de datos original (`ObesityDataSet_raw_and_data_sinthetic.csv`) utilizado para el análisis.
* **`Código/`**: Carpeta donde se encuentran los cuadernos de Jupyter (`Proyecto 3 - Agrupación de datos sobre obesidad.ipynb`) que incluyen el preprocesamiento, el análisis y la interpretación de los datos.
* **`images/`**: Carpeta dentro de la carpeta código, donde se almacenan las visualizaciones generadas, como la matriz de correlación y gráficos de componentes principales.
* **`Documentación/`**: Contiene el documento detallado (informe final.pdf) que incluye el resumen ejecutivo, la metodología, los resultados y conclusiones del proyecto.

### Dependencias

Para ejecutar el proyecto, necesitas:

- **Python** 3.8 o superior
- **Poetry** para la gestión de dependencias y el entorno virtual. Puedes instalar Poetry siguiendo las instrucciones en su [documentación oficial](https://python-poetry.org/docs/).

### Instalación de Dependencias

Para instalar todas las dependencias necesarias, sigue los siguientes pasos:

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/leidysvalencia/MachineLearning1-Proyecto-final.git
   cd MachineLearning1-Proyecto-final

