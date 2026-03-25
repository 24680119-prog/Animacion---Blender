##Amimacion en blender






## PASO 1:Configuracion inicial del entorno de trabajo
Se inició el proceso eliminando el stroke predeterminado presente en la escena inicial, con el objetivo de trabajar desde un entorno limpio, Posteriormente, se creó una nueva escena utilizando la herramienta Grease Pencil, seleccionando la opción de lienzo en blanco. Esto permitió generar un nuevo stroke junto con un material base para comenzar el dibujo del personaje.

Todo el desarrollo de la animación se realizó utilizando el software Blender en su versión 5.0.1, aprovechando las herramientas de animación 2D disponibles dentro de este entorno.

<img width="589" height="259" alt="image" src="https://github.com/user-attachments/assets/8353bbef-d9ed-4f89-ac28-a03d72c6595f" />

## Paso 2: Asignacion de materiales y color 
Una vez preparado el entorno de trabajo, se procedió a la creación del material para el dibujo. Para ello, se accedió a la sección de trazo (Stroke) dentro de las propiedades de Grease Pencil.

Posteriormente, se activó la opción de relleno (Fill) y se asignó un color, permitiendo así definir tanto el contorno como el interior del personaje. Finalmente, se creó y configuró el material que será utilizado en la animación.

<img width="278" height="740" alt="image" src="https://github.com/user-attachments/assets/e249ca11-241d-48e7-83e4-598867c786f8" />

## Paso 3: Inserción y ajuste de imagen de referencia
Como siguiente paso, se agregó una imagen de referencia con el fin de guiar el proceso de dibujo y mantener proporciones adecuadas del personaje. Para ello, se accedió al menú Agregar (Add) y se seleccionó la opción Imagen → Referencia (Image Reference). Una vez insertada en la escena, la imagen fue ajustada en tamaño utilizando la tecla S (Scale), permitiendo adaptarla correctamente al área de trabajo.


<img width="589" height="296" alt="image" src="https://github.com/user-attachments/assets/5562cc7b-9cb1-445c-bcf0-55c93e19df86" />

## Paso 4: Configuración de la línea de tiempo
En este paso, se organizó la duración de la animación dentro de la línea de tiempo. Para ello, se estableció el inicio en el fotograma 1 y el final en el fotograma 21. Esta configuración se realizó considerando un total de 7 imágenes (frames), asignando aproximadamente 3 fotogramas por cada una, lo que da como resultado una animación con una duración total de 3 segundos.
De esta manera, cada imagen tiene el tiempo suficiente en pantalla para percibir correctamente el movimiento del personaje.

<img width="589" height="63" alt="image" src="https://github.com/user-attachments/assets/db04dfbc-946d-4465-bc2b-0d5a95b6e96c" />

## Paso 5: Organización de capas en Grease Pencil
En este paso, se configuraron las capas dentro de Grease Pencil para organizar correctamente los elementos del dibujo. Se crearon y utilizaron diferentes capas, como “trazos” para las líneas del personaje y “relleno” para los colores. Esto permite trabajar de manera más ordenada, separando el contorno del relleno y facilitando futuras modificaciones. Además, se ajustaron las propiedades de visibilidad y bloqueo de cada capa, con el fin de evitar cambios accidentales durante el proceso de animación. Este proceso se realizó en el apartado de propiedades de Grease Pencil, específicamente en la sección de capas (Layers), donde se gestionan los elementos del dibujo.

<img width="264" height="381" alt="image" src="https://github.com/user-attachments/assets/151c34ca-b7be-46a4-a812-64a1a61ccd3f" />

## Paso 6: Inicio del trazado y animación en modo dibujo

En este punto se comienza el desarrollo de la animación mediante el uso de Grease Pencil. Para ello, se cambió del modo objeto (Object Mode) al modo dibujo (Draw Mode), lo que permite habilitar la herramienta Pencil para realizar los trazos. A continuación, se ajustó la intensidad del trazo para mejorar la visibilidad de las líneas y se utilizó el color previamente definido en el material. Con estas configuraciones, se inició el proceso de dibujo frame por frame, siguiendo la referencia establecida para construir cada una de las poses del personaje.


## Paso 7: Inicio del trazado en modo dibujo
En este punto, se comenzó el proceso de dibujo del personaje utilizando Grease Pencil. Para ello, se cambió del modo objeto (Object Mode) al modo dibujo (Draw Mode), lo que permite habilitar la herramienta Pencil para realizar los trazos. Se ajustaron parámetros como la intensidad del trazo, con el fin de mejorar la visibilidad y calidad de las líneas. Posteriormente, se utilizó el color previamente asignado en el material para comenzar a dibujar el personaje, tomando como base la imagen de referencia.

Durante el trazado, se emplearon herramientas como la selección de arco y curvas, lo que permitió crear líneas más suaves y precisas en las formas del dibujo. Una vez realizadas las curvas, se confirmaban los cambios presionando la tecla Enter, este procedimiento se repitió hasta completar todo el dibujo del personaje.

<img width="589" height="477" alt="image" src="https://github.com/user-attachments/assets/cf74f096-2b8a-444c-b24d-3a211bd71876" />

## Paso 8: Aplicación de relleno al dibujo

Una vez finalizado el trazado del personaje, se procedió a aplicar color en las áreas internas del dibujo mediante la herramienta de relleno (Fill) de Grease Pencil. Para ello, se accedió al apartado de materiales, donde se seleccionaron los materiales previamente creados con color. Posteriormente, se utilizó la herramienta de relleno para aplicar dichos materiales en las zonas delimitadas por los trazos.

Este proceso permitió mejorar la apariencia visual del personaje, haciéndolo más claro y definido. El relleno se aplicó cuidadosamente en cada parte del dibujo para mantener uniformidad y evitar errores en las áreas cerradas.

<img width="589" height="242" alt="image" src="https://github.com/user-attachments/assets/fc24821b-1f36-42c0-9340-517c5fc5eabb" />

## Paso 9: Desarrollo de la animación frame by frame
En este paso, se inició la creación de la animación mediante la técnica frame by frame. Para ello, se avanzaron 3 fotogramas en la línea de tiempo y se realizó nuevamente el trazado del personaje, tomando como referencia el dibujo anterior. Este proceso consistió en dibujar cada nueva pose del conejo ligeramente modificada respecto a la anterior, con el objetivo de generar la sensación de movimiento. Se utilizó la visualización de los dibujos previos (onion skin) como guía para mantener la coherencia en las proporciones y lograr una transición fluida entre cada fotograma. Este procedimiento se repitió a lo largo de toda la línea de tiempo hasta completar la secuencia de animación.

<img width="589" height="283" alt="image" src="https://github.com/user-attachments/assets/a177a61d-4a19-42bd-a5ce-dc626eb176a2" />

## Paso 10: Ajuste de posición de los fotogramas

En este paso, se realizó el ajuste de posición de los dibujos en cada fotograma para mantener la coherencia del movimiento. Primero, se ubicó el cursor en el fotograma 1 y se cambió al modo edición (Edit Mode). Posteriormente, se seleccionó todo el dibujo utilizando la tecla A, y se procedió a moverlo con la tecla G (Grab), colocándolo en una posición centrada dentro de la escena.
Este mismo procedimiento se aplicó en los demás fotogramas, ajustando cada dibujo de manera consistente. Esto permitió alinear correctamente las poses del personaje y lograr una animación más fluida y uniforme.

<img width="488" height="656" alt="image" src="https://github.com/user-attachments/assets/07ef858c-a55b-4d65-bbbe-f2b2b43f1528" />

## Paso 11 : 
