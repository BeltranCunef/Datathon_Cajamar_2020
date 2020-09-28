# Minsait Land Classification

Con este proyecto se obtuvo la 3ª plaza a nivel nacional.

Sobre el dataset facilitado se ha llevado a cabo un análisis exploratorio, un proceso de data engineering y feature creation y la elaboración de un modelo de clasificación XGBoost habiendo tuneado los hiperparámetros de este mediante método bayesianos.
En un primer momento enfocamos el proyecto en maximizar el “accuracy” sobre el conjunto de datos aportado, sin embargo, tras la entrega intermedia nos dimos cuenta de que la distribución de los datos de test era diferente a los del training. Este hecho nos hizo replantear el proyecto y enfocar el modelo a la optimización del recall de las clases minoritarias.
El proyecto se centró más en la ingeniería de variables que en la elección de modelos más complejos. Si bien se probaron múltiples ensembles o clasificaciones jerárquicas, concluimos que la mayor mejora era a través de la creación de nuevas variables relevantes.
