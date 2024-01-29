<h1>Analisis de datos de Youtube</h1>

<h2>Resumen del proyecto</h2>
Tenemos un cliente que quiere lanzar una campaña online y han seleccionado youtube como su principal canal publicitario, quieren responder algunas de las preguntas iniciales que se plantean, como por ejemplo:


- cómo clasificar los vídeos en función de sus comentarios y estadísticas 

- cuáles son los factores que influyen en la popularidad de un vídeo de YouTube 

estas son las cosas que quieren entender antes de invertir dinero en la campaña de youtube, eligieron YouTube ya que es el segundo sitio web mas visitado del mundo.  

<h2> Objetivos del proyecto</h2>

1. Ingesta de datos: Crearemos una mecanismo para la ingesta de data de diferentes fuentes.
2. ETL: Estamos recibiendo los datos en formato raw, transformaremos esta data en un formato apropiado.
3. Data Lake:  Vamos a obtener datos de múltiples fuentes por lo que necesitamos un repositorio centralizado para almacenarlos.
4. Escalabilidad: A medida que el tamaño de nuestros datos aumenta, tenemos que asegurarnos de que nuestro sistema escala con él.
5. Cloud: No podemos procesar grandes cantidades de datos en nuestro ordenador local, por lo que necesitamos utilizar la nube, en este caso, utilizaremos AWS.
6. Reporte: Creamos un dashboard para obtener respuestas a las preguntas que formulamos anteriormente.

<h2>Servicios que utilizaremos</h2>

1. Amazon S3: servicio de almacenamiento de objetos que proporciona escalabilidad, disponibilidad de datos, seguridad y rendimiento.
2. AWS IAM: Servicio que le permite administrar el acceso a los servicios y recursos de AWS de forma segura.
3. Amazon QuickSight: servicio de Business Intelligence (BI) escalable, sin servidor que facilita el análisis de datos y la obtención de información.
4. AWS Glue: Servicio de integración de datos sin servidor que facilita el descubrimiento, preparar, mover e integrar datos de múltiples fuentes.
5. AWS Lambda: Lambda es un servicio informático que permite a los programadores ejecutar código sin crear ni gestionar servidores.
6. AWS Athena: Athena es un servicio de consulta interactivo para S3 en el que no es necesario cargar datos, sino que estos permanecen en S3.

<h2>Conjunto de datos usados</h2>
Este dataset de Kaggle contiene estadísticas (archivos CSV) sobre vídeos populares diarios de YouTube a lo largo de varios meses. Hay hasta 200 vídeos de tendencias publicados cada día para muchas ubicaciones. Los datos de cada región están en su propio archivo. El título del vídeo, el título del canal, la hora de publicación, las etiquetas, las visualizaciones, los "me gusta" y "no me gusta", la descripción y el recuento de comentarios son algunos de los elementos incluidos en los datos. También se incluye un campo category_id, que difiere según la zona, en el archivo JSON vinculado a la región.


[https://www.kaggle.com/datasets/datasnaek/youtube-new](https://www.kaggle.com/datasets/datasnaek/youtube-new)
