# Sistema de Clasificación de Imágenes
# Descripción del Proyecto
Este proyecto tiene como objetivo desarrollar un sistema de clasificación de imágenes para distinguir entre fotos de perros y gatos. El conjunto de datos utilizado consiste en fotos de perros y gatos proporcionadas como un subconjunto de un conjunto de datos más grande de 3 millones de fotos anotadas manualmente, obtenidas a través de una colaboración entre Petfinder.com y Microsoft.

# Instrucciones
# Paso 1: Carga del Conjunto de Datos
El conjunto de datos se encuentra en Kaggle y puedes acceder a él para descargarlo desde la siguiente competición: Dogs vs. Cats.
Descarga la carpeta dataset y descomprime los archivos. Obtendrás una carpeta llamada train que contiene 25.000 archivos de imagen (formato .jpg) de perros y gatos etiquetados por su nombre de archivo, con la palabra "dog" o "cat".

# Paso 2: Visualiza la Información de Entrada
Carga e imprime las primeras nueve fotos de perros en una sola figura y repite lo mismo para los gatos. Asegúrate de que todas las imágenes tengan un tamaño fijo de 200x200 píxeles.

# Paso 3: Construye una Red Neuronal Artificial (RNA)
Utiliza una arquitectura de Convolutional Neural Network (CNN) como VGG16 para construir un clasificador robusto capaz de manejar la variedad de tamaños y formatos de las imágenes.

# Paso 4: Optimiza el Modelo Anterior
Importa los métodos ModelCheckpoint y EarlyStopping de Keras. Crea objetos de ambos y pásalos como funciones callback a fit_generator. Carga el mejor modelo obtenido anteriormente y utiliza el conjunto de prueba para hacer predicciones.

# Paso 5: Guarda el Modelo
Almacena el modelo entrenado en la carpeta correspondiente para su uso posterior.

# Archivo del Proyecto
El archivo que contiene el proyecto se llama Proyecto.ipynb.
