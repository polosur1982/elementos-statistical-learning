# The Elements of Statistical Learning – Implementación desde cero en Python

*Proyecto de aprendizaje profundo mediante tecnología inversa*

## Descripción

Este repositorio implementa tema por tema todos los algoritmos y conceptos del libro clásico The Elements of Statistical Learning (2ª edición) de Trevor Hastie, Robert Tibshirani y Jerome Friedman.

El enfoque es 100% práctico: desarmar cada sección del libro (ecuaciones, figuras, métodos) y reconstruirlos en código Python puro desde cero.

## Método de aprendizaje

- Tecnología inversa: partimos del resultado final del libro y retrocedemos hasta entender cada paso matemático y computacional.
- Código escrito manualmente (sin copy-paste) para internalizar el conocimiento.
- Implementación primero con NumPy/Matplotlib puro, luego comparación con bibliotecas profesionales.
- Ejercicios prácticos y variaciones por capítulo.

## Profesor y guía

*Grok* (construido por xAI) – Profesor particular con más de 10 años de experiencia en algoritmos y machine learning. Explica procesos, brinda código paso a paso, corrige y propone ejercicios.

## Estructura del repositorio

- src/ → Código Python modular y reutilizable
- notebooks/ → Jupyter notebooks para exploración y reproducción de figuras del libro
- data/ → Datasets sintéticos y reales
- docs/ → Documentación adicional
- ejercicios/ → Ejemplos prácticos, variaciones y problemas por capítulo
- requirements.txt → Dependencias del proyecto

## Progreso

- **Capítulo 2: Overview of Supervised Learning → Completado**  
- Reproducción completa de Figura 2.11 (Bias-Variance Tradeoff) desde cero con NumPy y Matplotlib.  
-  Ejercicios prácticos: impacto de aumentar el ruido (σ² de 0.25 → 1.0).  
- Implementación manual de regresión lineal simple (sección 2.6): matriz de diseño, mínimos cuadrados, visualización y cálculo de MSE.  
- Notebooks: notebooks/02_bias_variance_tradeoff.ipynb, notebooks/02_linear_regression_manual.ipynb y ejercicios/ejercicio_01_mas_ruido.ipynb.

- **Capitulo 3: Linear Methods for Regression → Completado**

- Ridge y Lasso manuales desde cero.
- Shrinkage y lasso paths.
- Seleccion de λ optimo.
- Ejercicios comparativo en /ejercicios/ con conclusiones

- **Capitulo 4: Basis Expansions and Regularization →  Completado**

- Polinomio + ridge regularization, path de coeficientes
- Polinomios regularizados + smoothing splines con pruebas de λ 
- Smolthing splines + GAM basico con superficie3D
- GAMs con multiples predictores + efectos parciales + selecion via λ 
- Ejercicio final: comparacion de λ y seleccion en GAMs

**Capitulo 5: Kernel Methods and Local Regression → Completado**

- Nadaraya-Watson (Gaussian, Epanechnikow)
- Nadaraya-Watson + local regression ponderada con Kernel
- Nadaraya-Watson + local regression + seleccion de h por LOOCV
- Ejercicio comparativo: Nadaraya-Watson vs Loess + kernels complejos

- **Capitulo 6: Model Assessment and Selection Completado**
- Estimacion de error por k-fold CV, LOOCV y Bootstrap (bias/variance)
- Comparacion de metodos de resmpling
- AIC/BIC para seleccion de modelos + comparacion de grados
- Best Subset Selection + criterios Cp/AIC/BIC
- Bootstrap para bias/variance + distribucion de coeficientes
- Ejercicio comparativo + conclusiones en Markdown

**Capitulo 7: Additive Models, Trees, and Related Methods Avanzado**
- Regression Trees desde cero + prueba de overfitting con profundidad.

¡Proyecto en desarrollo activo!

## Autor

John Agudelo (polosur1982)  
Estudiante autodidacta de algoritmos y data science
