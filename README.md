En este repo estarán los códigos/ppts o informes respectivos asociados a los proyectos que he realizado durante este tiempo, donde presento un mini resumen con la pregunta que se realiza y los resultados obtenidos ;)
# Proyectos

🔭 Clasificación de líneas espectrales estelares mediante ML para el curso de deep learning

📁 /proyecto-espectros

¿Cómo saber, a partir del espectro de una estrella, si corresponde a una absorción o a una emisión?

Ese fue el problema a resolver: clasificar automáticamente líneas de espectros estelares en absorción o emisión. La base de datos original no traía esta clasificación etiquetada, por lo que primero se construyó el etiquetado usando los algoritmos Find Peaks y Derivate, validando que ambos detectaran correctamente los picos antes de modelar.

Luego se generaron ventanas sobre la longitud de onda y el flux para alimentar distintos modelos. El mejor resultado lo obtuvo una CNN 1D + GRU, con una precisión cercana al 94%, destacando por su estabilidad y rapidez frente a las demás arquitecturas probadas.
#### Herramientas: Python, TensorFlow/Keras, Polars/Pandas

📁 /proyecto-readmisiones hospitalarias

¿Qué variables nos pueden ayudar a predecir la readmisión de las personas con insuficiencia cardíaca?

En una primera instancia vemos la base de datos, cabe recalcar que esta es simulada. Revisamos si hay nulos o valores extraños y realizamos un análisis de correlación en base a nuestra variable objetivo (readmisión en 30 días). En base a tests estadísticos vimos que tanto el puntaje de adherencia al tratamiento como el BNP resultaban variables que tenían diferencias significativas entre los readmitidos y no readmitidos.
