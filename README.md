### Proyecto: Clasificación de Imágenes con el Perceptrón

---

#### Descripción del Proyecto

Este proyecto se centra en la clasificación de imágenes utilizando un perceptrón, un tipo de red neuronal básica. La implementación abarca desde la carga y preprocesamiento de los datos hasta la evaluación del modelo de perceptrón entrenado.

---

#### Objetivos

1. **Cargar y preprocesar el conjunto de datos de imágenes**: Asegurar que las imágenes estén en un formato adecuado para ser utilizadas como entrada en el perceptrón.
2. **Entrenar un modelo de perceptrón**: Utilizar los datos preprocesados para entrenar un modelo simple de red neuronal.
3. **Evaluar el rendimiento del modelo**: Analizar la precisión y otras métricas relevantes para determinar la efectividad del modelo de perceptrón.

---

#### Estructura del Proyecto

1. **Carga de datos**:
   - Se cargan las imágenes desde un directorio especificado.
   - Se transforman las imágenes en arrays adecuados para el procesamiento por parte del modelo.

2. **Preprocesamiento de datos**:
   - Se normalizan los datos para mejorar el rendimiento del modelo.
   - Se dividen los datos en conjuntos de entrenamiento y prueba.

3. **Definición y entrenamiento del modelo**:
   - Se define un perceptrón utilizando librerías de aprendizaje automático.
   - Se entrena el modelo con los datos de entrenamiento.

4. **Evaluación del modelo**:
   - Se utilizan los datos de prueba para evaluar el rendimiento del modelo.
   - Se calculan métricas de evaluación como la precisión, la sensibilidad y la especificidad.

---

#### Librerías Utilizadas

- **NumPy**: Para el manejo de arrays y operaciones matemáticas.
- **Pandas**: Para la manipulación de datos tabulares.
- **Matplotlib**: Para la visualización de datos e imágenes.
- **Scikit-learn**: Para la implementación del modelo de perceptrón y métricas de evaluación.
- **Pillow**: Para la carga y manipulación de imágenes.

---

#### Resultados

- **Precisión del Modelo**: La precisión del modelo de perceptrón se evaluó en el conjunto de datos de prueba.
- **Métricas Adicionales**: Además de la precisión, se calcularon otras métricas como la matriz de confusión, sensibilidad y especificidad.
- **Visualización de Resultados**: Se generaron gráficos para visualizar el rendimiento del modelo y la distribución de las clases predichas.

---

#### Conclusiones

El uso del perceptrón para la clasificación de imágenes demuestra la capacidad de las redes neuronales simples para abordar problemas de clasificación. A pesar de su simplicidad, el perceptrón puede ofrecer resultados útiles, aunque su rendimiento puede no ser óptimo en comparación con modelos más complejos como las redes neuronales convolucionales (CNNs). El proyecto subraya la importancia del preprocesamiento de datos y la correcta evaluación del modelo para obtener resultados significativos.
