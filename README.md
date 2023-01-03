# Proyectos-Robotica
Serie de proyectos para el ramo de "Robotica"

Ejercicios a realizar:

1.- Implemente el algoritmo de Value Iteration y simule el movimiento del robot siguiendo la política
óptima obtenida. El modelo supone un 90% de éxito en la ejecución de la acción y un 10% de
permanecer en la misma posición. Grafique con matplotlib los valores de V(s). Factor de descuento
del 98%. Utilice python + pygame.

2.- Implemente el algoritmo de QValue Iteration y simule el movimiento del robot siguiendo la
política óptima obtenida. El modelo supone un 85% de éxito en la ejecución de la acción y un 15% de
permanecer en la misma posición. Grafique con matplotlib los valores de Q(s,a). Factor de descuento
del 95%. Utilice python + pygame.

3.- Aplique el algoritmo de Relative Value Iteration Modificado (pseudo código en BlackBoard)
utilizando modelo de la pregunta 2. Grafique con matplotlib los valores de V(s).

4.- Utilizando la teoría de Cadenas de Markov de primer órden responda las siguientes preguntas de
manera clara y ordenada. Una maquinaria de un taller mecánico puede estar en tres estados diferentes:
P → Producción o M → Mantención o R → Reparación
Su distribución de probabilidades históricas (prior) y su matriz de transición es la siguiente:
![prior](https://user-images.githubusercontent.com/43975051/210423195-a0b91756-608b-47e0-b5e5-603cfe1a5c5a.PNG)

Calcule:
• ¿La probabilidad que la máquina funcione correctamente durante 7 días?
• ¿La probabilidad que la máquina entre a mantencion en 3 días?
• ¿La probabilidad que la máquina entre a reparación en 5 días?

Se deben instalar las librerias: 
•matplotlib
•math
•pygame
•numpy
•random

Además para los ejercicios 1,2 y 3 se debe tener una carpeta con los recursos a utilizar. En este caso, la carpeta es llamada "img" la cual contiene las imagenes a trabajar.

