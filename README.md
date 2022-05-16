# Predicción de fallos cardiacos en pacientes
## Proyecto final del curso de Estadística de la Maestría en Ciencia de Datos

Las enfermedades cardiovasculares (ECV) son la principal causa de muerte a nivel mundial cobrando un estimado de 17,9 millones de vidas cada año, lo que representa el 31% de todas las muertes en todo el mundo. Cuatro de cada 5 muertes por ECV se deben a ataques cardiacos y accidentes cerebrovasculares, y un tercio de estas muertes ocurren prematuramente en personas menores de 70 años. La insuficiencia cardiaca es un evento común causado por las ECV y este conjunto de datos contiene 11 características que pueden usarse para predecir una posible enfermedad cardiaca.

Las personas con enfermedad cardiovascular o que se encuentran en alto riesgo cardiovascular (debido a la presencia de uno o más factores de riesgo como hipertensión, diabetes, hiperlipidemia o enfermedad ya establecida) necesitan una detección y manejo precoces donde un modelo de aprendizaje automático puede ser de gran ayuda.

Los datos se obtuvieron a partir de la plataforma de Kaggle: [Heart Failure Prediction](https://www.kaggle.com/fedesoriano/heart-failure-prediction). El dataset fue creado a partir de otros conjuntos de datos que se encontraban disponibles de forma independiente pero que no se habían combinado anteriormente. En este conjunto de datos, se combinan 5 conjuntos de datos cardiacos sobre 11 características comunes, lo que lo convierte en el conjunto de datos de enfermedades cardiacas más grande disponible hasta ahora para fines de investigación. Los cinco conjuntos de datos utilizados son:

* Cleveland: 303 observaciones
* Hungarian: 294 observaciones
* Switzerland: 123 observaciones
* Long Beach VA: 200 observaciones
* Stalog (Heart) Data Set: 270 observaciones

Se eliminaron las observaciones duplicadas para así obtener un total de 918 observaciones.

### Descripción de los datos

1. Age: age of the patient [years]
2. Sex: sex of the patient [M: Male, F: Female]
3. ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
4. RestingBP: resting blood pressure [mm Hg]
5. Cholesterol: serum cholesterol [mm/dl]
6. FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
7. RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
8. MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
9. ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
10. Oldpeak: oldpeak = ST [Numeric value measured in depression]
11. ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
12. HeartDisease: output class [1: heart disease, 0: Normal]
