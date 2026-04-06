EVALUACIÓN MÓDULO 3

Alumna Serra Lorena


Este repositorio contiene el desarrollo técnico y analítico de la base de datos de una aerolínea. El objetivo del proyecto es transformar datos brutos de actividad y perfiles de clientes en información estratégica que permita optimizar el programa de fidelización y entender los hábitos de consumo según variables demográficas y económicas.

Estructura de Datos:
El análisis se basa en la integración de dos fuentes principales:

Customer Flight Activity: Registro detallado de las reservaciones, meses de actividad y distancia recorrida por los pasajeros.

Customer Loyalty History: Base de datos con el perfil sociodemográfico (Educación, Salario, Estado Civil) y nivel de fidelidad (Tipo de Tarjeta).

Fase 1: Preprocesamiento y Limpieza
Para asegurar la calidad de las conclusiones, se ejecutaron las siguientes tareas de ingeniería de datos:

Unificación de Fuentes: Ejecución de un left join para consolidar la actividad de vuelo con el perfil de lealtad de cada cliente.

Tratamiento de Nulos: Análisis e imputación de valores faltantes en la columna Salary, asegurando que el sesgo estadístico fuera mínimo.

Normalización: Ajuste de tipos de datos y eliminación de registros inconsistentes para preparar el dataset para el análisis exploratorio (EDA).

Fase 2: Visualización de Variables Categóricas
Distribución de la Fidelidad
Se analizó la composición del programa de lealtad mediante la proporción de tarjetas. El hallazgo principal muestra que el nivel Star es el más voluminoso, mientras que el nivel Aurora mantiene una exclusividad ligada a perfiles de mayor poder adquisitivo.

Perfil Demográfico: Educación y Salario
El análisis confirma una jerarquía salarial clara basada en la formación académica. Existe una brecha significativa de ingresos entre los clientes con estudios de postgrado (Doctorado/Master) frente al nivel de entrada universitario, lo que define el potencial de gasto de cada segmento.

Fase 3: Evaluación Estadística (Hallazgos Críticos)
Impacto del Estado Civil en la Frecuencia de Vuelo
Mediante la comparación de medias, se determinó que los clientes solteros presentan una frecuencia de reserva ligeramente superior a los casados y divorciados. No obstante, la varianza es reducida, indicando que la necesidad de viaje es una variable transversal al estatus civil.

Correlación Distancia vs. Recompensa
Se identificó una correlación lineal positiva perfecta. El sistema de acumulación de puntos es estrictamente proporcional a la distancia del vuelo, lo que garantiza un modelo de recompensas transparente y predecible para el usuario.



