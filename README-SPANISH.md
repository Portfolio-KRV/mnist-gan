# Mnist-gan
Desarrollado en el curso de Redes Neuronales por: Diego Quezada y Kevin Reyes.
## Objetivos
- Implementar una Red Advesaria Generativa (GAN) para generar números escritos a mano en base a un ruido aleatorio inicial. 
- Comparar el resultado de la red del ruido aleatorio generador de dos números y el número generado por el promedio del ruido de ambos números.

## Descripción
Red Adversaria Generativa (GAN) para la predicción de números escritos a mano.

## Conclusiones
- El aprendizaje del discriminador es más rápido que la del generador, lo que puede provocar un estancamiento en el aprendizaje del generador, dado que podría llegar el punto donde el discriminador siempre detecte que la imagen es falsa y por tanto nunca de indicios del camino correcto al generador.
- Se debe buscar que el discriminador y generador mejoren su desempeño de forma similar en el entrenamiento.
- Las imágenes no son del todo convincentes, si bien se generan patrones similares a números reales, hay ciertos trazos de ruido que no se corresponden con la forma de los números.
- Al aplicar el generador sobre el promedio del ruido aleatorio generador de dos números obtenemos un número con características de ambos números generados.

## Stack de tecnologías
- Keras.
- Numpy.
- Matplotlib.