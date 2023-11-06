# MERDWild
Multimodal Emotion Recognition Database in the Wild es una base de datos para orientada en el reconocimiento multimodal de emociones. Contiene las modalidades de imágenes faciales, audio y texto, se encuentra etiquetada con siete emociones. Este conjunto de datos fue creado a partir de la unificación, limpieza y transformación de tres conjuntos de datos recogidos en entornos no controlados, llamados AFEW. AffWild2 y MELD.
Esta base de datos se encuentra organizada mediante ficheros, separando el conjunto de entrenamiento y validación correspondientes a las bases de datos originales, con leves variaciones en el caso de AFEW.
![Estructura de MERDWild](https://github.com/FacundoMartinez/MERDWild/blob/main/Estructura%20(1).png?raw=true))

Dentro de las emociones se encuentra "Angry" (Enojo), "Disgust" (Disgusto), "Happy" (Feliz), "Sad" (Triste), "Neutral" (Neutral), "Surprise" (Sorpresa) y "Fear" (Miedo).
El idioma en el que se encuentra la base de datos es inglés.


Dentro de los archivos CSV se encuentran las emociones y las técnicas utilizadas para la detección de la calidad de los datos. La columna "KEY" es la conexión entre los datos, se debe concatenar con la ruta donde se está guardando la base de datos para lograr acceder facilmente a los archivos.  

En el CSV de audio se encuentran también las etapas del proprocesamiento de texto disponible y las transcripciones. 

Algunos datos relevantes se encuentran en las siguientes dos imágenes:
![Frecuencias de emociones por modalidad y filtro]())

![Frecuencia de archivos en dataset por modalidad y filtro]()

