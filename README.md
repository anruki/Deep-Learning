# Deep-Learning
Practica 1 - Computer Vision
El objetivo de la práctica 1 es construir diferentes tipos de Redes Neuronales Profundas para vision por computador con el propósito de comprender el funcionamiento de las redes de neuronas convolucionales y las diferentes entre los procesos de Pre-Train y Fine-Tunning.

mundo-marino.jpg

Tecnologías
Servidor de notebooks Jupyter/Colab para Python.

Pandas.

Numpy.

Keras y TensorFlow.

Matplotlib y/o Seaborn.

Descripción del trabajo
Esta práctica consiste en desarrollador diferentes modelos capaces de reconocer una especio marina representada en una imagen. Para poder construir este tipo de modelos es necesarios utilizar redes convolucionales profundas, las cuales nos permiten extraer las características de las imágenes a través de la información recogida en los píxeles. 

Fase 1 - Preparación del entorno
Crea un notebook llamado PW1_red_1_n.ipynb (donde n se corresponde con el identificador del grupo) en el servidor de notebooks de tu elección (Colab, Jupyter, etc.).

Crea un notebook llamado PW1_red_2_n.ipynb (donde n se corresponde con el identificador del grupo) en el servidor de notebooks de tu elección (Colab, Jupyter, etc.).
Descargar el dataset Download datasetcon las imágenes referentes a los ejemplos. 

Examina el conjunto de datos para identificar las diferentes clases.

Prepara el conjunto de datos para el entrenamiento, transformando/escalando las características y los valores de las clases (si es necesario).

Construir un algoritmo que permita agrupar los diferentes ejemplos disponibles en los datasets de entrenamiento, test y validación en clases mediante carpetas. Para poder realizar esta operación se dispone de fichero annotations.csv donde se indica para cada imagen la clase que le corresponde. 

IMPORTANTE: El conjunto de datos de entrenamiento debe ser el mismo para ambos procesos de entrenamiento. 

Fase 2 - Implementación en modo Pre-Train
Desarrollar una Red Neuronal Convolucional profunda en el notebook denominado PW1_red_1_n.ipynb utilizando el framework Keras, cumpliendo con las siguientes especificaciones:

Debe incluir al menos 3 capas convolucionales.

Debe utilizar ReLU como función de activación.

Debe utilizar la función softmax para la salida de la última capa.

Debe utilizar la función categorical crossentropy como función de pérdida.

Debe utilizar el algoritmo RMSprop para minimizar la función de pérdida.

Una vez definida la red, se deberán implementar tres configuraciones diferentes para los tamaños de kernel, tamaños de pooling, número de capas y tasa de aprendizaje (learning rate) para ejecutar el proceso de entrenamiento.

Selecciona el mejor de los tres modelos justificando tu elección mediante la utilización de diferentes métricas de bondad. 

Dibuja la matriz de confusión del conjunto de entrenamiento. 

Dibuja un gráfico que muestra la variación de la pérdida (error) en función de las épocas para el conjunto de entrenamiento. 

Dibuja la arquitectura de la red correspondiente a la red seleccionada. 

Fase 3 - Implementación en modo Fine-Tunning
Desarrollar una Red Neuronal Convolucional profunda en el notebook denominado PW1_red_2_n.ipynb  utilizando el framework Keras, mediante la utilización de los pesos de una red de neuronas generada previamente. 

Una vez seleccionada la red, se deberán implementar tres configuraciones diferentes para la tasa de aprendizaje (learning rate) y el número de iteraciones para ejecutar el proceso de entrenamiento.

Selecciona el mejor de los tres modelos justificando tu elección mediante la utilización de diferentes métricas de bondad. 

Dibuja la matriz de confusión del conjunto de entrenamiento. 

Dibuja un gráfico que muestra la variación de la pérdida (error) en función de las épocas para el conjunto de entrenamiento. 

Fase 4 - Evaluación
Para los dos modelos seleccionados en las fases 2 y 3 analizar su capacidad de generalización mediante la utilización del conjunto de test y responder a las siguientes preguntas:

Dibuja las matrices de confusión de ambos modelos sobre el conjunto de test. ¿Qué diferencias observas entre ellas?
¿Cual de los modelos generados tiene mayor capacidad de generalización? Justifica tu respuesta utilizando datos empíricos. 

¿Existe alguna manera de mejorar los modelos? Razona tu respuesta. 
Documentación
Crea un documento llamado P1_informe_n.pdf (donde n es el número de grupo) que resuma el trabajo realizado siguiendo la siguiente estructura:

Portada.

Resumen (Abstract).

Tabla de contenidos.

Descripción de los experimentos realizados y las respuestas a las diferentes preguntas realizadas a lo largo de los diferentes pasos.

Conclusiones que resuman los principales resultados, aprendizajes e implicaciones de los experimentos.

Referencias.

Reglas
El trabajo práctico debe realizarse en grupos de 3 o 4 personas.

El código de los diferentes notebooks debe compilar correctamente; de lo contrario, el trabajo práctico no será evaluado.

La evaluación del trabajo práctico se basará en la información proporcionada en el informe. El notebook servirá como una herramienta para generar gráficos, tablas y datos, garantizando que esta información pueda utilizarse eficazmente en la elaboración del informe.

El uso de sistemas de generación de código, como GitHub Copilot, GEMINI o ChatGPT, está estrictamente prohibido.

Se deben entregar dos archivos separados:

Un documento de investigación en formato PDF.

Dos archivo de tipo notebook (.ipynb).

Estos archivos deben comprimirse en un único archivo llamado P1_n.zip (donde n se corresponde con el identificador del grupo).

El documento de investigación debe tener un máximo de 10 páginas, excluyendo la portada, el resumen, la tabla de contenido y la bibliografía.

Es obligatorio incorporar comentarios detallados sobre las diferentes operaciones ejecutadas para la preparación y visualización de los datos.
