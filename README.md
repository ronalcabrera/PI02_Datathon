<p align="center">
<img src="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png"   
>
</p>

​
# <h1 align="center">**`Proyecto Individual 2`**

<p align="center">
<img src="https://www.larazon.es/resizer/CWZHT-xIdxYwHldVMEPv4sDO2dE=/600x400/smart/filters:format(webp):quality(65)/cloudfront-eu-central-1.images.arcpublishing.com/larazon/XK32YUBCTRDZHCTPY7KTJTZJ2Q.jpg"   
>
</p>

​
Bienvenidos a mi segundo proyecto individual, durante el mismo estaré poniendo en práctica mis habilidades adquiridas en el campo de la predicción.
​
## **Presentación del proyecto**
​
Un importante Centro de Salud necesita poder predecir si un paciente tendrá una estancia hospitalaria prolongada (9 días o mas), para poder administrar la demanda de camas en el hospital. Utilizando la información contenida en el dataset asociado, la cual recaba una muestra histórica de sus pacientes, elaborar un modelo de machine learning que prediga si los pacientes que ingresan lo estarán una estancia prolongada o no. 

## **Descripción, paso a paso**

• Análisis exploratorio de los datos (EDA), normalización de los datos y borrado datos inútiles. <br>

• Selección de features adecuados, entrenamiento y predicción utilizando el Modelo de clasificación: árbol de decisiones.<br>

• División de dataset en train y test utilizando train_test_split, para entrenar al modelo y probar funcionamiento.<br>

• Como método de evaluación del desempeño del modelo, se utilizaró la métrica de Exhaustividad (Recall) para las estadías hospitalarias largas, a partir de la matriz de confusión (Confusion Matrix). <br>

$$ Recall=\frac{TP}{TP+FN}$$
​

## **Métrica utilizada**
​
Como método de evaluación del desempeño del modelo, se utilizará la métrica de Exhaustividad (Recall) para las estadías hospitalarias largas, a partir de la matriz de confusión (Confusion Matrix). 

<br>
<br>

## **Descripción de las dimensiones**
- Available Extra Rooms in Hospital: Habitaciones adicionales disponibles en el hospital. Una habitación no es igual a un paciente, pueden ser individuales o compartidas.
- Department: Área de atención a la que ingresa el paciente. 
- Ward_Facility_Code: Código de la habitación del paciente.
- doctor_name: Nombre de el/la doctor/a a cargo del paciente.
- staff_available: Cantidad de personal disponible al momento del ingreso del paciente.
- patientid: Identificador del paciente.
- Age: Edad del paciente.
- gender: Género del paciente.
- Type of Admission: Tipo de ingreso registrado según la situación de ingreso del paciente.
- Severity of Illness: Gravedad de la enfermedad/condición/estado del paciente al momento del ingreso.
- health_conditions: Condiciones de salud del paciente. 
- Visitors with Patient: Cantidad de visitantes registrados para el paciente.
- Insurance: Indica si la persona posee o no seguro de salud. 
- Admission_Deposit: Pago realizado a nombre del paciente, con el fin de cubrir los costos iniciales de internación. 
- Stay (in days): Días registrados de estancia hospitalaria.
