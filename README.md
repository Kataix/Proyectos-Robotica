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

Además para los ejercicios 1,2 y 3 se debe tener una carpeta con los recursos a utilizar. En este caso, la carpeta es llamada "img" la cual contiene las siguientes imagenes:
![Fondo](https://user-images.githubusercontent.com/43975051/210423550-0f1b081f-b4d3-4e7b-99f7-2c1b019870f2.png)

![Lose](https://user-images.githubusercontent.com/43975051/210423552-7f03819e-f76c-4e25-8a06-bc05f97beb97.png)

![Normal](https://user-images.githubusercontent.com/43975051/210423553-1e965cf0-e734-407f-9c6d-82b339331f90.png)

![Robot](https://user-images.githubusercontent.com/43975051/210423555-e81f36fe-5e3e-4b85-b22f-be9d005b9eec.png)

![Win](https://user-images.githubusercontent.com/43975051/210423557-b62a4271-be7e-46c7-b80b-a73d97566ed2.png)

