## Análisis Exploratorio de Datos

**Base de datos para el modelo supervisado:**

* **Fuente:** Sitio web de noticias "El Tiempo"
* **Período:** 2020 - 2023
* **Categorías:**
    * Deportes
    * Política
    * Cultura
    * Vida
    * Economía
    * Tecnosfera

**Resultados:**

* **Mayor cantidad de noticias:** Deportes (47.99%)
* **Menor cantidad de noticias:** Tecnosfera (1.07%)

**Análisis de frecuencia de palabras:**

* Se identificaron palabras clave relevantes para cada categoría.
* Se observó una intersección de temas entre "deportes" y "cultura" en junio de 2022, coincidiendo con las elecciones presidenciales.

## Experimentación de Modelos para la Detección de Temas

**Modelos:**

* Naive Bayes
* Regresión logística
* XGBoost
* Modelo Transformers Bert

**Métricas:**

* Precisión
* Recall
* F1 Score

**Resultados:**

* **Mejor modelo:** Bert
    * Precisión: 0.81%
    * Recall: 0.851%
    * F1 Score: 0.872%
    * Sin sesgo entre las diferentes clases

## Aplicación del Modelo Supervisado

**Base de datos:** 1,801,635 tuits de usuarios colombianos (junio de 2022)

**Resultados:**

* **Mayor frecuencia de temas:**
    * Cultura (704,947 tuits)
    * Política (361,315 tuits)
    * Deportes (243,031 tuits)

## Experimentación para la Generación de Tópicos

**Modelo:** Bertopic

**Objetivo:** Generar automáticamente tópicos relacionados con la clase política

**Parámetros:**

* Agrupación de documentos
* Reducción de dimensionalidad
* Agrupación
* Bolsa de palabras
* Número de temas
* N-gramas

**Métricas:**

* CV (coherencia del vocabulario)
* UMASS (coherencia de los tópicos)

**Resultados:**

* **Mejor combinación de parámetros:**
    * Número de vecinos: 20
    * Número de componentes: 8
    * Tamaño mínimo de clúster: 20
    * CV: 0.45
    * UMASS: -0.44

## Aplicación del Modelo Bertopic Sintonizado

**Base de datos:** Tuits relacionados con la clase política (junio de 2022)

**Resultados:**

* **Total de tópicos:** 752
* **Temas más populares:**
    * Tópico 1 (8000 tuits)
    * Tópico 0 (7886 tuits)
    * Tópico 2 (6663 tuits)
* **Temas menos frecuentes:**
    * Tópico 699 (27 tuits)
    * Tópico 717 (28 tuits)
    * Tópico 611 (34 tuits)

**Análisis temporal:**

* Se observa una evolución de los temas a lo largo del tiempo.
* Se identifican picos de actividad en ciertos temas en fechas específicas.

## Conclusiones

* El estudio demuestra la eficacia de Bertopic para la detección de temas en Twitter.
* Los resultados muestran la capacidad del modelo para comprender y segmentar las discusiones en línea.
* Se identifican temas relevantes en las diferentes categorías analizadas.
* La información obtenida puede ser utilizada para análisis político, estrategias de publicidad dirigida y otros campos.

## Recomendaciones

* Continuar explorando y refinando modelos de procesamiento de lenguaje natural.
* Ampliar el alcance del análisis a otros eventos políticos y sociales.
* Implementar técnicas de visualización para facilitar la comprensión de los resultados.

## Limitaciones

* La cantidad de datos disponibles para el entrenamiento del modelo puede afectar su rendimiento.
* La selección de los parámetros de los modelos puede influir en los resultados obtenidos.
* La interpretación de los temas generados por el modelo puede ser compleja.

## Aplicaciones

* Análisis de opinión pública
* Monitoreo de redes sociales
* Marketing político
* Investigación social
* Detección de noticias falsas
