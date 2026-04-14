# CAPO - Reto de clasificación de imágenes

## Descripción del Problema
El objetivo de este reto es desarrollar un pipeline robusto de clasificación de imágenes para 10 clases de objetos cotidianos. Se os proporcionará un conjunto de datos de entrenamiento para construir vuestro modelo. 

Deberéis analizar cuidadosamente los datos proporcionados, extraer vuestras propias conclusiones, diseñar la arquitectura adecuada y preparar vuestro sistema para la evaluación final. Durante los próximos días se irán revelando pistas cruciales sobre la naturaleza del conjunto de imágenes de test, que será el que defina la puntuación final.

---

### Datos
El dominio del problema abarca las siguientes 10 clases: `taza, silla, reloj, bicicleta, zapato, gafas, mochila, teclado, guitarra, paraguas`.

* **Volumen:** 1000 imágenes etiquetadas.

---

# Fases del Reto

### Día 1: Análisis y Construcción del Baseline
**Objetivo:** Desarrollar el modelo de clasificación y comprender los datos.

**Limitaciones:** No hay limitaciones de uso de herramientas o técnicas para obtener el modelo de clasificación.

---


### Día 2: Brecha de Seguridad en el Entorno de Test
Las imágenes de test que evaluaréis han recibido cambios. Daremos un tiempo para adaptaros

---


### DÍA 3: Contrarreloj de Inferencia
**Dinámica de la Prueba:**
* **9:00:** Liberación del conjunto de Test Adversario (imágenes sin etiquetar).
* **15:00:** Cierre estricto del buzón de recepción.

** Formato de Entrega:**
Antes del tiempo límite, enviad un único archivo `predicciones_nombre_de_equipo.csv` con la misma estructura que `etiquetas.csv`:

```csv
archivo, etiqueta_num, clase
sdf7a77fa6f8sf9.png, 0, taza
```

---

## 🏆 Criterios de Evaluación Final

La evaluación se realizará contra el *ground truth* oculto del test.

**Métrica Principal** 
- F1-Score Macro.
