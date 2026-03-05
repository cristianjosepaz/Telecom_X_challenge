# TelecomX LATAM - Análisis de Fidelización y Abandono de Clientes

## 🧠 Objetivo del Proyecto
El objetivo de este proyecto es analizar el comportamiento de los clientes de una empresa de telecomunicaciones para entender qué factores influyen en la fidelización o cancelación del servicio.
A través del análisis de datos se busca identificar patrones relacionados con variables como: 
- Tipo de contrato
- Método de pago
- Tipo de servicio de internet
- Soporte técnico
- Situación familiar del cliente
- Antigüedad en la empresa
- Nivel de gasto mensual y total
El propósito final es detectar perfiles de clientes con mayor riesgo de cancelación y proponer estrategias que ayuden a mejorar la retención.

## 📊 Metodología
Se emplea un **Análisis Exploratorio de Datos (EDA)** para comprender la distribución y relación entre las variables categóricas y numéricas con la variable objetivo Evasion (`Churn`).  
Se utilizan técnicas de visualización, incluyendo:  
- **Gráficos de barras y pastel** para distribución de categorías.  
- **Boxplots** y **violin plots** para comparar variables numéricas según fidelización.  
- **Heatmaps** para identificar combinaciones de factores de riesgo.
Este enfoque permite identificar patrones relevantes antes de aplicar modelos predictivos.

## 🔧 Herramientas y Tecnologías
- **Python**: Lenguaje de programación principal.  
- **Pandas**: Manipulación y análisis de datos.  
- **Matplotlib y Seaborn**: Visualización de datos.  
- **Jupyter Notebook / Google Colab**: Entorno interactivo para ejecutar el análisis.  

## 📁 Estructura del Proyecto
- **Notebook principal (`TelecomX_LATAM.ipynb`)**: Contiene el análisis completo, gráficos y conclusiones.  

## 🔍 Principales Hallazgos
El análisis permitió identificar varios factores asociados al abandono del servicio:
- Los **contratos mensuales** y el **pago por cheque electrónico** presentan mayor tasa de Cancelacion.  
- La **Fibra Óptica** es el servicio de internet con mayor riesgo de abandono, especialmente sin soporte técnico.  
- Los clientes **sin pareja ni dependientes** presentan mayor probabilidad de abandonar el servicio.
- Los clientes con cargos **mensuales altos y baja antigüedad** tienen mayor riesgo de cancelación.
- La suscripción a **soporte técnico** se relaciona con mayor fidelización.

## 💡 Recomendaciones
A partir de los resultados del análisis se proponen algunas acciones para mejorar la retención de clientes:
1. Incentivar contratos de mayor duración mediante beneficios o descuentos.
2. Promover métodos de pago automáticos para reducir la cancelación asociada al cheque electrónico.
3. Ofrecer soporte técnico como beneficio estratégico para clientes con mayor riesgo.
4. Mejorar la experiencia de clientes con fibra óptica, especialmente en etapas tempranas del servicio.
5. Implementar estrategias de retención durante los primeros años de relación con el cliente.
6. Diseñar ofertas específicas para perfiles con mayor riesgo de abandono.
