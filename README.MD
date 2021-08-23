# Chatbot Concejo Municipal de Copacabana, arquitectutra Seq2Seq 
Este repositorio contiene el codigo fuente para un chatbot implementado usando una arquitectura Seq2Seq.

## Como probar el chatbot por linea de comandos
Para ejecutar el chatbot como programa de linea de comandos es necesario ejecutar el comando `python cli.py`. Luego
de esto el programa tomara unos segundos en lanzarse. Cuando este listo, el programa imprimara en la salida estandar
un mensaje de bienvenida. Si se desea salir del programa basta con escribir la palabra `adios` o presionando `Ctrl-C`

## Posibles mejoras
Algunas posibles estrategias para mejorar el desempeño del chatbot son:
- Usar pesos precalculados para la capa de Embedding, por ejemplo Glove.
- Usar un corpus mas grande para entrenamiento.
- Añadir preguntas similares formuladas de manera diferente.
- Modificar la arquitectura del Encoder y/o Decoder, por ejemplo, añadiendo mas capas de LSTM.
