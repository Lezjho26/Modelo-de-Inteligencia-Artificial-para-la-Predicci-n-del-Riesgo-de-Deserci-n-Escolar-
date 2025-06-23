# Modelo de Inteligencia Artificial para la Predicción del Riesgo de Deserción Escolar

Este repositorio contiene el desarrollo completo del modelo predictivo propuesto en el Trabajo de Fin de Máster titulado **“Modelo de Inteligencia Artificial para la Predicción del Riesgo de Deserción Escolar”**. Su objetivo es anticipar posibles casos de abandono escolar en educación secundaria mediante el análisis de variables sociodemográficas, académicas y emocionales.

## Objetivos del proyecto

- Identificar estudiantes con mayor riesgo de abandonar el sistema educativo.
- Implementar modelos de machine learning que permitan una toma de decisiones informada por parte de instituciones educativas.
- Promover el uso ético y responsable de la inteligencia artificial en contextos educativos.

## Modelos implementados

- **Random Forest Classifier** (`scikit-learn`)
- **Multi-Layer Perceptron (MLPClassifier)** - Red Neuronal
  
modelo-desercion-escolar/

─ Notebook principal
─ Scripts de preprocesamiento, entrenamiento y evaluación
─ Dependencias del proyecto
─ README.md  Este archivo



## Preprocesamiento

- Limpieza y eliminación de valores nulos
- Codificación ordinal y One-Hot Encoding para variables categóricas
- Escalado de datos para redes neuronales
- División en conjunto de entrenamiento (80%) y prueba (20%)

## Evaluación de los modelos

| Modelo               | Accuracy | Precision | Recall | F1 Score |
|----------------------|----------|-----------|--------|----------|
| Random Forest        | 0.97     | 0.98      | 0.98   | 0.98     |
| Red Neuronal (MLP)   | 0.94     | 0.96      | 0.95   | 0.96     |

- También se incluyó el análisis de importancia de variables y visualización de curvas ROC.

##  Entornos de desarrollo

- **Jupyter Lab** (entorno local)
- **Amazon SageMaker** (entorno en la nube)

## Requisitos

Instala las dependencias necesarias con:

```bash
pip install -r requirements.txt
```

## Licencia

Este proyecto se distribuye bajo la Licencia MIT. Eres libre de usar, modificar y distribuir el código con fines académicos y no comerciales.

## Contacto

Lezly Jhovanna Carmona Saavedra  
lezjho01@gmail.com
https://github.com/lezjho26/Modelo-de-Inteligencia-Artificial-para-la-Predicci-n-del-Riesgo-de-Deserci-n-Escolar-

