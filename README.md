# Diagnóstico de enfermedad cardiaca a partir de variables fisiológicas utilizando redes neuronales

Este proyecto forma parte del módulo de *Machine Learning* del curso Data Science, Programa de Becas Santander Tecnología | Talento Digital para el Futuro | Bedu 2023. El objetivo principal elaborar un modelo de Machine Learning de redes neuronales para diagnóstico temprano de enfermedades cardiovasculares (ECVs).

## Integrantes del equipo
* José Carlos Barreras Maldonado
* Cristina Basulto Ávila
* Ricardo Iván Carpio Fragoso
* Gamaliel Osvaldo Naranjo Bernal
* Víctor Hugo Pérez Núñez

## Descripción del proyecto 

Este proyecto tiene como objetivo fundamental desarrollar un modelo de Machine Learning basado en redes neuronales tipo perceptrón multicapa para la detección temprana de enfermedades cardiovasculares (ECVs). Dado que las ECVs representan una de las principales causas de mortalidad en todo el mundo, contar con una herramienta precisa y eficaz es esencial para favorecer un diagnóstico temprano. La aplicación exitosa de este modelo tiene el potencial de mejorar las tasas de supervivencia y la calidad de vida de los pacientes, al permitir intervenciones médicas oportunas. 

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

## 1. Base de datos

La base de datos proviende del sitio de Kaggle (https://www.kaggle.com). Este proyecto se enfoca en el uso de un conjunto de datos que combina información de 918 pacientes con y sin ECVs. Los datos contienen la variable dependiente Enfermedad cardiaca (HeartDisease) y 11 variables explicativas relacionadas con la salud de los pacientes: Edad del paciente (Age), Género del paciente (Sex), Tipo de dolor en el pecho (ChestPainType), Presión arterial en reposo (RestingBP), Colesterol sérico (Cholesterol), Nivel de azúcar en la sangre en ayunas (FastingBS), Actividad eléctrica del corazón (ECG o electrocardiograma) en reposo (RestingECG), Frecuencia cardiaca máxima (MaxHR), Dolor en el pecho al ejercitarse (ExerciseAngina), Valor numérico de depresión (ST) inducido por el ejercicio relacionado al reposo (Oldpeak) y Pendiente del segmento ST en ejercicio máximo (ST_Slope).













