# Análisis Completo de Churn – TelecomX LATAM

Este proyecto consiste en un **análisis completo de evasión de clientes (Churn)** en TelecomX LATAM. Se investigan patrones de comportamiento, factores que influyen en la retención y se generan insights clave para la toma de decisiones estratégicas.

---

## 📂 Contenido del proyecto

- **Notebook principal:** [Analisis_Completo_Churn_TelecomX.ipynb](https://github.com/marcelazam/Alura-Store-/blob/main/Analisis_Completo_Churn_TelecomX.ipynb)  
  Contiene la carga de datos, limpieza, análisis exploratorio, visualizaciones y conclusiones.  

- **Extra – Análisis de correlación entre variables:**  
  Incluye la exploración adicional de relaciones entre variables clave (Tenure, Charges.Monthly, Charges.Total, SeniorCitizen) para identificar patrones más profundos de Churn.

---

## 🔹 Objetivos del análisis

1. Estudiar la distribución de Churn en la base de clientes de TelecomX LATAM.
2. Analizar cómo diferentes variables categóricas (género, tipo de contrato, método de pago, servicios contratados) se relacionan con la evasión.
3. Evaluar variables numéricas (tenure, cargos mensuales y totales) para identificar riesgos de abandono.
4. Generar insights estratégicos que permitan proponer acciones de fidelización y retención de clientes.

---

## 🔹 Proceso realizado

1. **Carga y limpieza de datos:**  
   - Datos en formato JSON transformados a DataFrame de pandas.  
   - Columnas con diccionarios separadas para análisis más claro.  
   - Corrección de tipos de datos y valores nulos.

2. **Análisis exploratorio de datos (EDA):**  
   - Distribución general de Churn.  
   - Análisis de variables categóricas y numéricas.  
   - Visualización con gráficos de barras, boxplots y countplots.

3. **Insights del análisis de correlación (Extra):**  
   - Tenure y Charges.Total muestran correlación positiva fuerte.  
   - Charges.Monthly correlaciona moderadamente con Charges.Total.  
   - SeniorCitizen no presenta correlación fuerte, aunque puede combinarse con otras variables categóricas para análisis adicional.

---

## 🔹 Conclusiones

- La duración del contrato y el método de pago son los factores más determinantes en la evasión de clientes.  
- Clientes nuevos o con bajo gasto total tienen mayor riesgo de Churn.  
- El género no es un factor determinante.  
- Los insights permiten priorizar estrategias de retención y fidelización para clientes en riesgo.

---

## 🔹 Recomendaciones

- **Fidelización de clientes nuevos:** ofrecer incentivos a clientes con menor tenure.  
- **Promoción de contratos largos:** incentivar contratos anuales o de dos años.  
- **Seguimiento de métodos de pago de riesgo:** clientes con cheques electrónicos podrían recibir alertas o beneficios.  
- **Monitoreo de cargos altos o inconsistentes:** garantizar que los clientes perciban valor en sus pagos mensuales.

---

## 📌 Resumen

Este análisis proporciona una visión clara de los patrones de evasión, identifica clientes de riesgo y propone estrategias para mejorar la retención. Incluye visualizaciones y análisis adicionales que fortalecen la comprensión del comportamiento de los clientes en TelecomX LATAM.
