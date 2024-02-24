# ProyectoModelosAprendizajes

Este proyecto esta centrado aprovechar las características extraídas por médicos sobre casos de cáncer de mama, entregando como resultado 1 modelo de aprendizaje automático que sean capaz de identificar si un paciente que tiene o no cáncer. Bienvenidos.

•	Carga y exploración datos: El conjunto de datos utilizado, posee información sobre el cáncer de mama, se lo obtuvo desde el Repositorio de Aprendizaje Automático de la UCI mantenido por la Universidad de California, Irvine. 

El conjunto de datos contiene 569 muestras de células tumorales malignas y benignas. Las dos primeras columnas del conjunto de datos almacenan los números de identificación únicos de las muestras y el diagnóstico correspondiente (M = maligno, b = benigno), respectivamente. Las columnas 3 a 32 contienen 30 entidades de valor real que se calcularon a partir de imágenes de valor real.

•	Preprocesamiento datos: Una vez cargado el archivo de datos, se lo unificó con sus cabeceras. Posterior se aplicó técnicas para duplicados o nulos, se eliminó columnas innecesarias y finalizamente se reemplazó por valores numéricos las banderas M y B de la columna diagnósticos.

•	Técnicas Aprendizaje Automático : Repartidos los datos en conjuntos de entrenamiento y test, se aplicó una estandarización, es decir centrar las características alrededor de cero y escalarlas para que tengan una desviación estándar de 1. Esto puede ser beneficioso para muchos algoritmos de aprendizaje automático, especialmente aquellos que son sensibles a las diferencias en la escala de las características.

Posterior, se creo una función para el procesamiento de los 3 modelos a probar, la cual proporciona un enfoque genérico para entrenar un modelo, hacer predicciones, evaluar el rendimiento y visualizar la matriz de confusión normalizada y el informe de clasificación.

•	Evaluación: Obtenido el rendimiento de cada uno de los modelos con la matriz de confusión y su puntaje de precisión. Podemos obtener como conclusión que para el caso presentado un Modelo de Regresión Logística es el mas adecuado, ya que su predicción de pertenencia a una categoría o clase arrojó buenos resultados en su evaluación.

El informe de clasificación nos resumen que, el modelo parece tener un rendimiento sólido con altas precisiones, recalls y F1-scores para ambas clases. La alta exactitud general respalda la calidad del modelo en la clasificación de las instancias.



