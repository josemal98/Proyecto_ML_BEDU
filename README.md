# Diagnóstico de enfermedad cardiaca a partir de variables fisiológicas utilizando redes neuronales

Este proyecto forma parte del módulo de *Machine Learning* del curso de *Data Scientist* de BEDU 2023. El objetivo principal es aplicar las distintas herramientas vistas hasta ahora en el curso para el entrenamiento y validación de un modelo de inteligencia artificial, empleando una base de datos de nuestra elección. 

## Integrantes del equipo
* Cristina Basulto Avila
* Gamaliel Osvaldo Naranjo Bernal
* Víctor Hugo Pérez Núñez
* José Carlos Barreras Maldonado
* Ricardo Iván Carpio Fragoso

## Descripción del proyecto 

Este proyecto tiene como objetivo fundamental desarrollar un modelo de inteligencia artificial basado en redes neuronales tipo perceptrón multicapa para la detección temprana de enfermedades cardiovasculares (ECVs). Dado que las ECVs representan una de las principales causas de mortalidad en todo el mundo, contar con una herramienta precisa y eficaz es esencial para favorecer un diagnóstico temprano. La aplicación exitosa de este modelo tiene el potencial de mejorar las tasas de supervivencia y la calidad de vida de los pacientes, al permitir intervenciones médicas oportunas. 

El proyecto se divide en 5 etapas fundamentales:

```mermaid
graph TB;

%% Subgrafos para los paneles
subgraph sg5[5. Evaluación del modelo]
  R[Predicciones de la red con conjunto de validación]
  L[Matriz de confusión]
  M[Métricas de desempeño de la red]
end

subgraph sg4[4. Selección y entrenamiento del modelo]
  N[Estructura de la red neuronal]
  Q[Conjuntos de entrenamiento y validación]
  O[Validación cruzada con k iteraciones]
end

subgraph sg3[3. Preparación de los datos]
  E[Estandarización de formatos]
  F[Manejo de valores faltantes]
  G[Manejo de valores atípicos]
end

subgraph sg2[2. Comprensión de los datos]
  I[Gráficos y visualizaciones]
  J[Estadísticos descriptivos]
  K[Correlación entre variables]
end

subgraph sg1[1. Obtención de los datos]
  A[Selección de base de datos de interés]
  B[Descarga programática de datos]
  C[Organización de los datos]
end
```

### Planteamiento del problema 

Las enfermedades cardiovasculares o ECVs constituyen un desafío de salud global, siendo la principal causa de muerte en todo el mundo. Estas enfermedades engloban una variedad de trastornos cardíacos y vasculares, incluyendo cardiopatías coronarias y accidentes cerebrovasculares. Las ECVs son responsables de un alto número de defunciones prematuras, afectando tanto a hombres como a mujeres.

El problema principal que este proyecto de aprendizaje automático aborda es la necesidad de contar con un método de diagnóstico temprano y preciso para las ECVs. Un diagnóstico oportuno puede marcar la diferencia en el tratamiento y la supervivencia de los pacientes. Sin embargo, en muchos casos, los síntomas pueden ser sutiles o incluso estar ausentes, lo que dificulta la detección temprana mediante métodos convencionales.

El proyecto busca aprovechar el potencial de las redes neuronales artificiales para analizar una amplia gama de datos de pacientes, incluyendo factores como edad, sexo, niveles de colesterol, presión arterial y más, con el objetivo de identificar patrones y relaciones que puedan utilizarse para predecir la presencia de ECVs de manera precisa.

### 

