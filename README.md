# Proyecto-EDA-con-Python
 📊 Marketing Bank Campaign Analysis

🎯 **Objetivo del proyecto**
Realizar un **Análisis Exploratorio de Datos (EDA)** sobre campañas de marketing directo de una institución bancaria portuguesa, para comprender las características de los clientes y su relación con la suscripción de depósitos a plazo.
## 🗂 **Estructura del repositorio**
marketing-bank-analysis/
│
├── data/
│ ├── Crudo/
│ │ ├── bank-additional.csv
│ │ └── customer-details.xlsx
│ └── Limpio/
│ ├── bank_clean.csv
│ └── customers_clean.csv
│
├── notebooks/
│ └── eda_analysis.ipynb
│
├── README.md
└── requirements.txt

💻 **Herramientas utilizadas**
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Visual Studio Code
 

🔧 **Pasos seguidos en el proyecto**

1. **Carga de datos**
   - Lectura de `bank-additional.csv` y `customer-details.xlsx` (3 sheets) usando pandas.
   - Unificación de los datasets mediante `merge` por identificador (`id_` / `ID`).

2. **Transformación y limpieza**
   - Conversión de tipos de datos (fechas, numéricos).
   - Eliminación de duplicados.
   - Revisión y tratamiento de valores nulos.
   - Normalización de nombres de columnas y categorías si es necesario.

3. **Análisis descriptivo**
   - Estadísticas generales de variables numéricas: media, mediana, desviación estándar.
   - Distribuciones de variables categóricas: ocupación, estado civil, educación, etc.

4. **Visualización de datos**
   - Histogramas (edad).  
   - Boxplots (ingresos vs. suscripción).  
   - Countplots (ocupación, suscripción).  
   - Heatmap de correlaciones.

5. **Generación de insights**
   - Identificación de patrones en ingresos, edad, ocupación y suscripción.
 

## 📝 **Principales hallazgos**

✅ La mayoría de clientes tienen entre **30 y 40 años**.  
✅ Las profesiones más comunes son **blue-collar y management**.  
✅ Los ingresos más altos no garantizan suscripción al producto.  
✅ Existe correlación positiva entre **euribor3m** y suscripción.  
✅ El contacto anterior (poutcome) es un predictor relevante en la decisión.

Autor
Aida Herrero de Diego
