# Regresión Lineal - Dataset Forest Fires (Portugal)

## Descripción
Análisis de correlación y modelo de regresión lineal múltiple sobre 
el dataset Forest Fires para predecir área quemada en hectáreas.

## Stack
Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn | SciPy

## Hallazgos
- Ninguna variable meteorológica muestra correlación fuerte con el área quemada (max 0.11)
- El modelo logra precisión limitada (R²≈0.027)
- Mejor desempeño en incendios pequeños (rango logarítmico 0.5–1.5)
- Pruebas de Shapiro-Wilk y KS confirman no-normalidad en residuos

## Conclusión
La regresión lineal no es el modelo adecuado para este problema.
Modelos no lineales (Random Forest, XGBoost) quedan como trabajo futuro.
