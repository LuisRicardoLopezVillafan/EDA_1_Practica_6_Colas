# Práctica 6. Colas
## Ejercicio 1. Definiciones incompletas
El primer ejercicio consiste de tres incisos:

a. Las primeras definiciones que hacen falta llenar se encuentran en el archivo "queue1.c". Para comprobar que el programa funciona correctamente, ingresa el siguiente input:

  `a 102`
  
  `b 203`
  
  `a 140`
  
  `b 111`
  
  `a 200`
  
  `b 333`
  
  `b 31`
  

Luego, presiona `Ctrl + D`.

**Pregunta**: De acuerdo con lo que imprime la consola, ¿qué está haciendo el bloque main?

b. Generar un nuevo archivo de encabezado "circular_queue.h" y, basados en el archivo "queue.h", definir las operaciones básicas de las colas circulares.

c. Generar un nuevo archivo de encabezado "double_linked_queue.h" y, basados en el archivo "queue.h", definir las operaciones básicas de las colas doblemente ligadas.


## EJercicio 2. Sistema de comandas
Basándose en el bloque `main` del archivo "queue.c", generar un sistema de _comandas_ en un restaurante. El sistema debe de preguntarle al usuario cuál es la siguiente orden (pueden ingresar las órdenes en forma de texto libre, o guardar los platillos posibes en el encabezado del programa, por ejemplo con la función "enum" quien toma la orden solamente tendría que ingresar un número para indicar el platillo, tal y como ocurre en las cadenas de comida rápida).
