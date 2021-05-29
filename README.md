# Introducción a la práctica

Este repositorio es parte de la Práctica 2 de la asignatura Tipología y Ciclo de Vida de los Datos del master de Ciencia de Datos.

En esta práctica, haremos uso del Dataset *[Heart Attack Analysis & Prediction Dataset](https://www.kaggle.com/rashikrahmanpritom/heart-attack-analysis-prediction-dataset)* de [Kaggle](Kaggle.com) con el fin de analizar los casos en los que es más probable que una persona sufra un ataque al corazón, así como los factores más influyentes a la hora de que estos casos se den.

# Contenido del dataset a analizar

Este dataset, cuenta con 14 variables:

age : Edad del paciente.

sex : Género del paciente.

cp : Tipo de dolor en el pecho 

 1. Angina típica.
 2. Angina atípica
 3. Dolor no-anginal.
 4. Asintomático.

trtbps : Presión arterial en reposo (en mm Hg)

chol : Colesterol (en mg/dl) 

fbs : (Glucemia > 120 mg/dl) (1 = True; 0 = False)

restecg : Resultados de electrocardiograma en reposo.

  0. Normal
  1. Anomalías de onda ST-T (Inversiones de onda T y/o una elevación de la onda en el segmento ST > 0.05 mV)
  2. Muestra una probable hipertrófia del ventrículo izquierdo por el criterio Estes.

thalachh : Ritmo cardiaco máximo.

exng: Si el paciente ha sufrido una angina provocada por el ejercicio (1 = Si, 0 = No)

oldpeak: Depresión en el segmento ST al hacer ejercicio en relación con el reposo.

slp: Pendiente del segmento ST en la electrocardiograma.

1. Pendiente ascendente.
2. Plano.
3. Pendiente descendente.

caa: Número de vasos principales del corazón (De 0 a 3).

thall: Prueba de esfuerzo cardiaco (Thallium stress test).

1. El test muestra un defecto irreversible.
2. El flujo sanguineo se encuentra dentro de los valores normales.
3. El test muestra un defecto reversible.

target : Variable de clase. 0 equivale a un menor riesgo de ataque cardiaco mientras que 1 equivale un mayor riesgo.

# Miembros del grupo

El grupo está formado por:

 1. Óscar López Montero
 2. José Manuel Jara

# Ficheros

En este repositorio, tenemos los siguientes ficheros:

Dentro de la carpeta Code, tenemos los ficheros referentes al código, en R. El fichero PRA2.Rmd contiene la resolución a los apartados planteados en la práctica, junto al fichero resultante en html para su mejor visualización.

Dentro la carpeta Data, tenemos los ficheros .csv que han sido utilizados para la realización de la práctica.

Para finalizar, se tendrá un fichero .pdf en el que se dará respuesta a las preguntas planteadas y con una tabla de contribuciones de los diferentes miembros del grupo.
