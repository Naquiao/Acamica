# Amazon stars reviews prediction
Este trabajo tiene como objetivo crear un modelo que, dado un comentario de un producto en amazon, lo analice, y pueda predecir cuantas estrellas va a tener ese comentario 

Notebook con el desarrollo: https://github.com/Naquiao/NLP-Project/blob/main/Amazon_stars_prediction_NLP.ipynb

## Dataset :
The Multilingual Amazon Reviews corpus.( https://registry.opendata.aws/amazon-reviews-ml/)
 
 - Link para descarga https://drive.google.com/uc?export=download&id=11XnXB7Ubgf3t6gotXGlM4FCwPOMHhDLX

## Pipelines :
Trabajé bajo la misma metodología en los 4 deliverables, tienen en siguiente orden:

 **1. Pipeline 1 - Benchmark**: Es el benchmark del proyecto. Se ejecuta un pipeline con mínima transformación de los datos. Se obtienen métricas con las que voy a comparar el resto de los pipelines.
 
 **2. Pipeline 2 - Multiclase general**: Modelo utilizado para la clasificación de etiquetas multiclases (las 5 estrellas). Se evaluan diferentes modelos y vectorizadores para diferentes preprocesamientos de los datos de entrada. 
 
 **3. Pipeline 3 - Multiclase direccionada**: Modelo de clasificación multiclase donde reducimos el conjunto de los datos a un subconjunto específico de categoría de productos. En otras palabras, se creó un modelo para una categoría de producto en particular.
 
 **4. Pipeline 4 - Clasificación Binaria**: Se cambia el target de los modelos anteriores. Ahora, en vez de clasificar entre 1,2,3,4 o 5 estrelas, vamos a clasificar entre comentario positivo (target -  1) o comentario neagtivo ( target - 0 ).
 
 
