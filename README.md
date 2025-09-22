![Portada](portada2.png)

## Introducción al análisis
El bienestar mental de los estudiantes universitarios es un área de creciente preocupación. La presión académica, la transición a la vida adulta y los factores sociales pueden converger, creando un entorno de alto riesgo para el desarrollo de problemas de salud mental como la depresión.

Este estudio se basa en un conjunto de datos de estudiantes para explorar estas dinámicas. Utilizando técnicas de análisis de datos, se examinaron variables como edad, género, carrera, promedio académico (GPA) y métricas de estilo de vida (ansiedad, calidad del sueño, nivel de estrés) para construir un perfil de los factores asociados a la depresión.

---

## Prevalencia de la depresión
El primer paso fue cuantificar la magnitud del problema dentro de la muestra de estudio. Se encontró que una proporción considerable de los estudiantes reportaron experimentar depresión.

---

## Resumen 
Este informe presenta los hallazgos clave de un análisis exploratorio exhaustivo sobre los factores que influyen en la depresión de la población estudiantil. El objetivo principal fue identificar patrones demográficos, académicos y de estilo de vida que se correlacionan con mayor riesgo de depresión para informar el diseño de políticas de bienestar y sistemas de apoyo proactivos.

El análisis revela que, si bien factores como la carrera universitaria y el rendimiento académico tienen cierta influencia, las variables más determinantes son los altos niveles de ansiedad y estrés y una baja calidad del sueño, las cuales muestran una fuerte correlación positiva con los síntomas depresivos.

Se recomienda a las instituciones educativas centrar sus esfuerzos en programas de gestión del estrés, promoción de la salud mental y concienciación sobre la higiene del sueño.

---

## Distribución del sueño 

El gráfico de distribución del sueño muestra cómo varían las horas de sueño entre los estudiantes. La mayoría duerme entre 5 y 8 horas, con una concentración alrededor de la mediana. Tras la imputación de valores faltantes, la forma general de la distribución se mantiene, indicando que la imputación no distorsionó significativamente los datos originales. Esta información es clave para comprender el papel del sueño en el bienestar mental y su relación con la depresión estudiantil.

---

## Duración del sueño antes y después 
El objetivo de comparar las distribuciones de la duración del sueño antes y después de la imputación es evidenciar el impacto del proceso de imputación sobre la variable. Permite verificar que rellenar los valores faltantes con la mediana no altera significativamente la forma original de la distribución, asegurando que la variable sigue siendo representativa y válida para el análisis estadístico y la construcción de modelos predictivos.

---

## Relación entre la depresión y factores clave 
En esta fase, se cruzó la variable de depresión con otros factores para identificar posibles relaciones y grupos de riesgo.

---

## Presión académica entre estudiantes con y sin depresión 

El gráfico de distribución de presión académica por estatus de depresión muestra que los estudiantes con depresión tienden a reportar niveles más altos de presión académica en comparación con quienes no presentan depresión. Esto sugiere una posible asociación entre presión académica elevada y el riesgo de depresión en la población estudiantil.

---

## Análisis multivariado de correlaciones
Se calculó una matriz de correlación para identificar las relaciones más fuertes entre variables como el estrés, la ansiedad y el sueño en relación a la depresión.

**Interpretación de correlaciones clave:**
- **Correlación Positiva Fuerte:** Depresión, Ansiedad y Estrés suelen coexistir y reforzarse mutuamente.
- **Correlación Negativa Moderada:** La calidad del sueño y la depresión se relacionan negativamente: a menor calidad del sueño, mayor probabilidad de depresión.
- **Correlación Débil:** La relación entre depresión y GPA es relativamente débil, sugiriendo que el rendimiento académico no es, por sí solo, un predictor fiable de la salud mental.

---

## Relación entre el rendimiento académico y la satisfacción 

El gráfico muestra que los estudiantes sin depresión tienden a tener mayor satisfacción y, en muchos casos, mejores CGPA. Por el contrario, quienes presentan depresión suelen reportar menor satisfacción con el estudio, independientemente de su CGPA. Esto sugiere que la satisfacción académica está más asociada al bienestar mental que al rendimiento académico puro.

---

## Depresión y género
El análisis muestra cómo varía la prevalencia de depresión entre hombres y mujeres en la muestra estudiada. Se observa que el porcentaje de estudiantes con depresión es mayor en un género respecto al otro, lo que sugiere posibles diferencias de riesgo asociadas al género. Este hallazgo puede orientar intervenciones y análisis más específicos sobre factores de vulnerabilidad en cada grupo.

---

## Conclusiones y recomendaciones finales 
El análisis integral de los datos proporciona una visión clara de los factores de riesgo asociados a la depresión estudiantil.

---

## Recomendaciones estratégicas 
- **Priorizar la Salud Mental Integral:** Las universidades deben desarrollar un ecosistema de bienestar que integre servicios de salud mental, incluyendo talleres proactivos sobre manejo de estrés y ansiedad.
- **Enfocar Intervenciones en el Estilo de Vida:** Campañas de concienciación sobre la importancia de la higiene del sueño y recursos para mejorar hábitos de descanso.
- **Utilizar Datos para la Detección Temprana:** Encuestas periódicas para monitorizar niveles de estrés y ansiedad, identificando grupos de riesgo antes de que los problemas se agraven.

---

## Conclusiones 
- La depresión es un problema prevalente en la comunidad estudiantil analizada.
- Los indicadores de salud mental como la ansiedad y el estrés son los predictores más potentes de la depresión, mucho más que los factores demográficos o académicos.
- El estilo de vida, concretamente la calidad del sueño, juega un papel fundamental en el bienestar mental del estudiante.

---

## Tecnologías utilizadas

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
---

## Autor

Proyecto realizado por Johi Ortiz para el Bootcamp de IA P5 de Factoria-F5-Madrid.
