## Proyectos en Streamlit

### Proyecto 1: Comparativa de Modelos de Clasificación

Este proyecto tiene como objetivo comparar la efectividad de distintos modelos de clasificación aplicados a diversos datasets. Los modelos evaluados son:

- K-Nearest Neighbors (KNN)
- Vector de Clasificación (VC)
- Random Forest

Los datasets utilizados para la evaluación son:

- Iris
- Breast Cancer
- Wine

Para cada modelo y dataset, se calcula el `accuracy_score` para medir el rendimiento. Además, se presenta una visualización gráfica de la proyección de los datos en los dos componentes principales utilizando Análisis de Componentes Principales (PCA).

#### Características del Proyecto:
- **Comparación de modelos:** Se comparan los `accuracy_scores` de los modelos KNN, VC y Random Forest.
- **Visualización de PCA:** Se proyectan los datos en los dos componentes principales para visualizar cómo se distribuyen las clases en un espacio bidimensional.

https://youtu.be/Klqn--Mu2pE

### Proyecto 2: Análisis de Encuesta sobre EPS en Colombia

Este proyecto se centra en el análisis de una encuesta realizada en Colombia sobre las Entidades Promotoras de Salud (EPS). Se proporciona una interfaz interactiva para aplicar distintos filtros a los datos utilizando sliders y multiselectores. Los resultados se presentan a través de gráficos de barras y gráficos de pastel.

#### Características del Proyecto:
- **Interfaz interactiva:** Los usuarios pueden filtrar los datos de la encuesta a través de sliders y multiselectores, lo que permite un análisis más detallado.
- **Visualización de datos:** Los resultados filtrados se presentan en gráficos de barras y gráficos de pastel para facilitar la interpretación de los datos.

https://youtu.be/FKfXtKAJxdk

---


### Instalación
Se necesitan estas dependencias:
```console
pip install streamlit
pip install scikit-learn
pip install matplotlib
```

### Ejecución

```console
streamlit run main.py
```
