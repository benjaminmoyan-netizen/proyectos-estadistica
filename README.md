# Benjamín Andrés Moya Naranjo

Estudiante de Ingeniería Estadística con formación en análisis de datos y modelamiento estadístico, con experiencia en riesgo de crédito bajo normativa IFRS 9.
Interesado en soluciones basadas en datos, especialmente en riesgo de crédito, data science, analítica y astronomia. Destaco por mi capacidad analítica y pensamiento crítico.


# Proyectos

🔭 Clasificación de líneas espectrales estelares mediante ML para el curso de deep learning

📁 /proyecto-espectros

¿Cómo saber, a partir del espectro de una estrella, si corresponde a una absorción o a una emisión?

Ese fue el problema a resolver: clasificar automáticamente líneas de espectros estelares en absorción o emisión. La base de datos original no traía esta clasificación etiquetada, por lo que primero se construyó el etiquetado usando los algoritmos Find Peaks y Derivate, validando que ambos detectaran correctamente los picos antes de modelar.

Luego se generaron ventanas sobre la longitud de onda y el flux para alimentar distintos modelos. El mejor resultado lo obtuvo una CNN 1D + GRU, con una precisión cercana al 94%, destacando por su estabilidad y rapidez frente a las demás arquitecturas probadas.
#### Herramientas: Python, TensorFlow/Keras, Polars/Pandas

📁 /proyecto-readmisiones hospitalarias


