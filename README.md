# challenge2-data-science-LATAM

# 📊 Análisis de Evasión de Clientes (Churn Analysis)
Este repositorio contiene un análisis detallado sobre la evasión de clientes en el sector de telecomunicaciones. Se han explorado diversos factores que influyen en la cancelación de servicios, utilizando técnicas de limpieza de datos, visualización y análisis exploratorio.
---
## 📌 Introducción
El objetivo de este análisis es identificar patrones y factores clave en la cancelación de clientes, con el fin de proporcionar estrategias para mejorar la retención y reducir la evasión.
---
## 🔍 Limpieza y Tratamiento de Datos
- Separación de valores anidados en la columna `Charges` (`Charges.Monthly` y `Charges.Total`).
- Conversión de variables categóricas (`Churn`, `Contract`, `PaymentMethod`) y tratamiento de datos faltantes.
- Normalización de valores numéricos (`Total`, `tenure`) para mejorar la visualización.
## 📊 Análisis Exploratorio de Datos
Se realizaron diversas visualizaciones para identificar tendencias en la cancelación de clientes:
- 📉 **Distribución de meses de contrato (`tenure`) según evasión**.
- 💰 **Impacto del costo mensual (`Charges.Monthly`) en la cancelación**.
- 📜 **Relación entre el tipo de contrato (`Contract`) y la retención de clientes**.
- 💳 **Métodos de pago y su influencia en la cancelación**.
Se utilizó panda, matplotlib, seaborn
