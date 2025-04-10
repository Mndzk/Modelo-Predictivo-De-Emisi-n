📊 Predicción de Pólizas Emitidas con CatBoost
-Este proyecto tiene como objetivo predecir si una cotización de seguro se convertirá en una póliza emitida, utilizando datos reales extraídos desde una base de datos SQL corporativa. 
La solución implementada se apoya principalmente en el modelo CatBoostClassifier, el cual demostró un rendimiento excepcional frente a otros algoritmos tradicionales como Random Forest, XGBoost o LightGBM.

🧠 ¿Por qué CatBoost?
-CatBoost fue elegido como modelo final por su capacidad para manejar automáticamente variables categóricas, su eficiencia computacional y su robustez frente a overfitting. 
En pruebas comparativas internas, superó de manera consistente a otros modelos tanto en AUC como en precisión.

📐 Sobre el enfoque de este notebook
Este notebook se centra principalmente en el pipeline de modelado y no en la exploración visual de datos. Esto se debe a que:

-El análisis exploratorio y visual se realizó previamente utilizando Power BI, lo cual permitió comprender a fondo la estructura y patrones del dataset.

-La selección de características también fue resultado de una etapa previa de análisis en Power BI y consultas específicas en SQL.

-Este notebook es una continuación lógica de ese trabajo, enfocándose en el entrenamiento, validación y evaluación del modelo final.

✅ ¿Qué incluye este notebook?
-Limpieza y transformación de datos desde SQL

-Preprocesamiento puntual (e.g. imputación de edad)

-Entrenamiento de CatBoost con ajuste de hiperparámetros

-Evaluación con métricas como Accuracy, AUC, matriz de confusión y curvas ROC/PR

-Validación cruzada estratificada para validar estabilidad del modelo

-Análisis de importancia de variables

