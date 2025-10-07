# Regresion-lineal
Regresión lineal sobre ventas en la empresa Nissan utilizando informes financieros de 2010 a 2020 en sus estados de resultados
# Regresión Lineal: Publicidad y Ventas

Este proyecto muestra la aplicación de un **modelo de regresión lineal simple** para analizar la relación entre la inversión en publicidad y las ventas de una empresa.

El objetivo es comprender cómo varían las ventas al modificar el gasto en publicidad y validar los supuestos básicos de la regresión.

---

## Descripción del proyecto

Se utilizan datos de ejemplo para construir y evaluar un modelo predictivo.
El análisis incluye:

* Entrenamiento del modelo con **scikit-learn**.
* Evaluación de supuestos con **Statsmodels**:

  * Normalidad de residuos (Shapiro-Wilk).
  * Heterocedasticidad (Breusch-Pagan).
  * Autocorrelación (Durbin-Watson).
  * Multicolinealidad (VIF).
* Visualización de la relación entre publicidad y ventas.

---

## 🧠 Herramientas utilizadas

* **Python**
* **Google Colab**
* **Librerías:**

  * pandas
  * numpy
  * matplotlib
  * scikit-learn
  * statsmodels
  * scipy

---

## 📈 Resultados principales

* Se encontró una relación **positiva y significativa** entre la inversión en publicidad y las ventas.
* El modelo obtuvo un **R² aceptable**, indicando una buena capacidad explicativa.
* Los residuos cumplen los supuestos de normalidad y homocedasticidad.
* No se detectaron problemas severos de multicolinealidad ni autocorrelación.

---

## 📂 Cómo usar este notebook

1. Abre el archivo `.ipynb` en **Google Colab** o **Jupyter Notebook**.
2. Ejecuta las celdas en orden para reproducir el análisis.
3. Reemplaza los valores de ejemplo por tus propios datos si deseas probar el modelo en otro contexto.

---

## 👤 Autores

* Ángel Iván Izquierdo Oviedo
* Carlos Eduardo Martínez Chavarría

---

*Este proyecto forma parte del portafolio de análisis de datos y modelado estadístico, enfocado en aplicar herramientas de Python al estudio de relaciones económicas y empresariales.*
