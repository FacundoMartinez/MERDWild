# MERDWild: Multimodal Emotion Recognition Database in the Wild

MERDWild es una base de datos creada para el reconocimiento multimodal de emociones en entornos no controlados. Esta base de datos integra tres conjuntos de datos previos: AFEW, AffWild2 y MELD, y abarca las modalidades de imágenes faciales, audio y texto. Cada muestra en MERDWild está etiquetada con una de las siguientes siete emociones: "Angry" (Enojo), "Disgust" (Disgusto), "Happy" (Feliz), "Sad" (Triste), "Neutral" (Neutral), "Surprise" (Sorpresa) y "Fear" (Miedo). La base de datos se encuentra en inglés.

## Estructura de MERDWild
MERDWild está organizada en ficheros que separan los conjuntos de entrenamiento y validación, siguiendo las estructuras de las bases de datos originales.

![Estructura de MERDWild](https://github.com/FacundoMartinez/MERDWild/blob/main/Tesis-organizacion%20merdwild.drawio.png)

## Archivos CSV
Dentro de los archivos CSV, se encuentran datos relacionados con las emociones y las técnicas utilizadas para evaluar la calidad de los datos. Las columnas "Audio_KEY", "Image KEY" y "Images_KEY" se utilizan como identificador para acceder fácilmente a los archivos, ésta se debe concatenar con la ruta en la que se guarda la base de datos. 

## Modalidad de Audio y Texto
Dentro del archivo CSV de audio, también encontrarás información sobre las etapas de preprocesamiento de texto disponibles, las transcripciones, nombre del dataset original correspondiente a los archivos, técnicas aplicadas al preprocesamiento, entre otros.

![Ejemplo del archivo CSV de audio y texto](https://github.com/FacundoMartinez/MERDWild/blob/main/audio%20y%20texto%20csv.jpg?raw=true)

## Frecuencia de Emociones por Modalidad y Filtro
Las siguientes gráficas muestran la distribución de archivos en el conjunto de datos por modalidad y filtro:

![Frecuencia de archivos en el dataset por modalidad y filtro](https://github.com/FacundoMartinez/MERDWild/blob/main/frecuencia%20de%20archivos%20en%20dataset%20por%20modalidad%20y%20filtro.png?raw=true)
![Frecuencia de emociones por modalidad y filtro](https://github.com/FacundoMartinez/MERDWild/blob/main/frecuencia%20de%20emociones%20por%20modalidad%20y%20filtro.png?raw=true)

## Acceso a la Base de Datos
Para acceder a la base de datos MERDWild, es necesario enviar un correo a ana.aguilera@uv.cl solicitando el acceso.

¡Gracias por tu interés en MERDWild! Si tienes alguna pregunta o necesitas más información, no dudes en ponerte en contacto con nosotros.
