## Descripción del Problema

En el contexto de las elecciones presidenciales de Colombia en 2022, es crucial comprender las discusiones y temas predominantes en la plataforma de Twitter. La vasta cantidad de datos y la naturaleza dinámica de las conversaciones hacen que sea difícil para los analistas procesar y comprender la información de manera efectiva. Además, la identificación de temas relevantes puede proporcionar información valiosa para los actores políticos y los medios de comunicación.

## Descripción del Modelo

Se implementan dos enfoques principales para abordar el problema: un modelo supervisado basado en aprendizaje automático. El modelo supervisado utiliza Bert para clasificar noticias recopiladas de "El Tiempo"

## Evaluación del Modelo

Los modelos se evalúan utilizando métricas estándar de aprendizaje automático, como precisión, recall y F1 score. 

## Conclusiones

El estudio demuestra la eficacia de Bertopic en la detección de temas en Twitter durante las elecciones presidenciales de Colombia en 2022. Los resultados muestran la capacidad del modelo para comprender y segmentar las discusiones en línea de manera efectiva. Además, se destacan las aplicaciones potenciales del análisis de temas en áreas como el análisis político y las estrategias de publicidad dirigida.

## Recomendaciones

Se recomienda continuar explorando y refinando modelos de procesamiento de lenguaje natural para mejorar la detección de temas en Twitter. Además, se sugiere ampliar el alcance del análisis para incluir otros eventos políticos y sociales relevantes. Esto podría proporcionar una comprensión más completa de las opiniones expresadas en la plataforma y su impacto en la sociedad.

## Análisis Exploratorio de Datos

Para entrenar el modelo supervisado de detección de temas, se utilizó como fuente de datos el sitio web de noticias "El Tiempo", un periódico colombiano con una amplia circulación en el país. Se recopilaron noticias de los años 2020 a 2023, clasificadas en categorías como deportes, política, cultura, vida, economía y tecnosfera. Se observó que la categoría de deportes presentó la mayor cantidad


# Resumen 

En este estudio, se analiza y detecta los temas discutidos en Twitter durante las elecciones presidenciales de Colombia en junio de 2022. Se implementan dos estructuras secuenciales basadas en el procesamiento de lenguaje natural. La primera estructura se apoya en técnicas de aprendizaje automático y modelos Transformers para identificar temas globales, como política, economía y cultura. Por otro lado, la segunda estructura utiliza modelos no supervisados, específicamente la técnica Bertopic, ajustando los hiperparámetros mediante algoritmos como UMAP y HDBSCAN. Los resultados experimentales revelan el potencial de estas técnicas para analizar y comprender las opiniones expresadas en la sociedad digital, así como para identificar y segmentar los temas más relevantes. Las aplicaciones de esta investigación trascienden el ámbito electoral, abarcando desde modelos predictivos de noticias hasta estrategias de publicidad dirigida y análisis político en diversos contextos.

# Descripción del Problema

En el contexto de las elecciones presidenciales de Colombia en 2022, es crucial comprender las discusiones y temas predominantes en la plataforma de Twitter. La vasta cantidad de datos y la naturaleza dinámica de las conversaciones hacen que sea difícil para los analistas procesar y comprender la información de manera efectiva. Además, la identificación de temas relevantes puede proporcionar información valiosa para los actores políticos y los medios de comunicación.

# Descripción del Modelo

Se implementan dos enfoques principales para abordar el problema: un modelo supervisado basado en aprendizaje automático y Bertopic, un modelo no supervisado. El modelo supervisado utiliza Bert para clasificar noticias recopiladas de "El Tiempo", mientras que Bertopic se emplea para detectar automáticamente temas en los tuits de Twitter. Se selecciona Bertopic debido a su capacidad para generar temas coherentes y su desempeño equilibrado en métricas de evaluación.

# Evaluación del Modelo

Los modelos se evalúan utilizando métricas estándar de aprendizaje automático, como precisión, recall y F1 score. Se comparan varios modelos, y Bertopic muestra un rendimiento prometedor en la detección de temas en Twitter. Se observa una falta de sesgo entre las diferentes clases y una capacidad para identificar temas relevantes en las conversaciones en línea.

# Conclusiones

El estudio demuestra la eficacia de Bertopic en la detección de temas en Twitter durante las elecciones presidenciales de Colombia en 2022. Los resultados muestran la capacidad del modelo para comprender y segmentar las discusiones en línea de manera efectiva. Además, se destacan las aplicaciones potenciales del análisis de temas en áreas como el análisis político y las estrategias de publicidad dirigida.

# Recomendaciones

Se recomienda continuar explorando y refinando modelos de procesamiento de lenguaje natural para mejorar la detección de temas en Twitter. Además, se sugiere ampliar el alcance del análisis para incluir otros eventos políticos y sociales relevantes. Esto podría proporcionar una comprensión más completa de las opiniones expresadas en la plataforma y su impacto en la sociedad.

