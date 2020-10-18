# musica_tfg
Este repositorio contiene varios ejemplos de música generada empleando _deep learning_

* En la carpeta `abc_char` se encuentran todos los ficheros de música generados empleando notación ABC. Se puede consultar tanto el código ABC generado como el archivo MIDI obtenido a partir de éste. No todos los ficheros ABC generados son válidos para ser convertidos a MIDI, por lo que algunos se han copiado y modificado manualmente para que esto sea posible (estos ficheros tienen `_mod` en el nombre)

* En la carpeta `abc_token` están los ficheros ABC y MIDI obtenidos mediante la generación token a token empleando notación ABC.

* En la carpeta `midi` están los archivos MIDI generados empleando una representación muy simplificada de las notas.

* En la carpeta `performance` están los archivos MIDI generados empleando la codificación que emplea Performance RNN. Los archivos que tienen el sufijo `_train` se han generado empleando como semilla el comienzo de alcuna pieza del conjunto de entrenamiento.

* En la carpeta `wavenet` se pueden encontrar archivos de 1 segunde duración generados en cada _epoch_ durante el entrenamiento además de un archivo de un minuto de duración generado al final.
