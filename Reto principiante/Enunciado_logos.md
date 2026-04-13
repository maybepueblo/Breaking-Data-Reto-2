# CAPO - Reto de conteo de logos

## Descripción
Determinar el número exacto de logos en un set de imágenes. Los logos sufren rotaciones ($0^{\circ}$ a $360^{\circ}$), escalas ($0.3x$ a $2x$) y solapes (máx. $20\%$).

---

### Datos disponibles
* **Input:** Set de imágenes `.png` y archivo `logo.png`.

### Predicciones generadas
* **Output:** Archivo CSV (`filename, label`) con el conteo por imagen, donde 'filename' es el nombre de la imagen dentro de la carpeta y 'label' es el número de logos presentes en la misma.

---

### Evaluación
La precisión se medirá mediante **MAE (Mean Absolute Error)**:

$$MAE = \frac{1}{n} \sum_{i=1}^{n} |y_i - \hat{y}_i|$$

*Donde $y_i$ es el valor real y $\hat{y}_i$ la predicción.*