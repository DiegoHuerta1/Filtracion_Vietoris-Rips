# Filtracion_Vietoris-Rips
FIltracion de Vietoris-Rips en un conjunto de datos de palarbas

Se usa un conjunto de datos de palabras. Se consideran las siguientes 11 palabras:

["hola", "gato", "pato", "cola", "coma", "malo", "mano", "toga", "cosa", "casa", "pasa"]

Notar que todas estas palabras tienen 4 letras. Debido a esto, se usa la distancia de Hamming en estas
palabras. Esta distancia se usa para modelar diferencias de letras en las palabras. Es decir, dos palabras
son similares si tienen las mismas letras en las mismas posiciones.

La lista de palabras junto con la métrica considerada, conforman un espacio métrico finito, es decir un
conjunto de datos. Considerando estos datos, se hacen filtraciones de Vietoris-Rips para distintos valores
de épsilon

Se visualiza una realizacion geometricas del complejo simplicial generados. Para considerar las vectorizaciones de las palabras se usa la matriz de distancia. Es decir, los componentes de una palabra son sus ditancias a las otras palabras, se usa pca para reducir estos componentes a dos cooredenadas, que se usan en la visualizacion.
