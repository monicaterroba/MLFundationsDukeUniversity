# ⚡ Predicción de Energía en Planta de Ciclo Combinado

Este proyecto utiliza **Machine Learning** para predecir la **energía eléctrica generada** por una planta de ciclo combinado a partir de variables ambientales. Es parte del proyecto final de un curso de aprendizaje automático en Coursera.

---

## 📘 Descripción del problema

El objetivo es predecir la variable `PE` (Net hourly electrical energy output en MW) usando lecturas ambientales horarias:

- `AT` — Temperatura ambiente (°C)
- `V` — Vacío de escape (cm Hg)
- `AP` — Presión ambiente (mbar)
- `RH` — Humedad relativa (%)

---

## 📁 Archivos del repositorio

- `CCPP_data.csv`: dataset con 9,568 muestras de sensores.
- `ccpp_energy_prediction.ipynb`: notebook con el análisis, entrenamiento y evaluación del modelo.
- `README.md`: este archivo.

---

## 🧪 Flujo de trabajo del proyecto

1. **Exploración de datos**: análisis visual y estadístico.
2. **Preprocesamiento**: división train/test, validación cruzada.
3. **Modelado**: comparación entre Regresión Lineal y Random Forest.
4. **Evaluación**: RMSE, MAE, R² en conjunto de prueba.
5. **Interpretación y conclusiones**.

---

## 📊 Resultados

El mejor modelo fue **Random Forest**, con:

- **RMSE**: 3.25
- **MAE**: 2.33
- **R² Score**: 0.9637

Esto indica que el modelo es muy preciso prediciendo el output energético.



## 🚀 Herramientas utilizadas

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🧠 Autor

Proyecto realizado por Monica Flores Terroba, como parte del curso de Machine Learning.

