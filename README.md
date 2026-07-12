## House Prices: Advanced Regression Techniques
Proyecto de ciencia de datos desarrollado para la competencia de Kaggle, enfocado en la predicción de precios de viviendas en Ames, Iowa, mediante técnicas de regresión avanzada.

## Roadmap del Proyecto
![Roadmap](https://raw.githubusercontent.com/TuUsuario/house-prices-ames-regression/main/house_prices_roadmap.jpg)

## Metodología
**Fase 1 (Exploración):** Diagnóstico de skewness en la variable objetivo (aplicando log1p) y auditoría de datos nulos para definir estrategias de imputación.
**Fase 2 (Preprocesamiento):** Creación de un Diccionario de Encoding centralizado para garantizar consistencia entre las variables ordinales y nominales, asegurando la alineación exacta entre train y test.
**Fase 3 (Baseline):** Establecimiento de un floor de rendimiento mediante Ridge Regression validado con K-Fold Cross-Validation.
**Fase 4 (Ingeniería de Características):** Creación de variables de dominio (Total_SF, YearsSinceBuilt, YearsSinceRemod).
  - Análisis crítico de **multicolinealidad** sobre el set final de features.
**Fase 5 (Modelado Avanzado):** Implementación de un Stacking Regressor (Ensemble) que combina Ridge, XGBoost y LightGBM para maximizar la capacidad predictiva.

## Resultados
**RMSE Local (K-Fold): 0.1113**
**Public Leaderboard Score: 0.12519**

## Licencia
Este proyecto está bajo la licencia MIT.
