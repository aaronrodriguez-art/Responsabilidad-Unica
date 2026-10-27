# Responsabilidad-Unica
Principio Responsabilidad Unica de SOLID


Este principio se aplica dividiendo las tareas en clases independientes para que cada una tenga una única razón de cambio:

- La clase `Libro` se encarga exclusivamente de manejar los datos del libro, como su título y su autor.
- La clase `Guardar` se encarga por separado de la lógica de almacenamiento o impresión de los datos del libro.

De esta forma evitamos mezclar responsabilidades en una sola clase, logrando que el código sea más ordenado y fácil de mantener.
