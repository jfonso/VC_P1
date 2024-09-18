# Visión por Computador - Práctica 1

Esta práctica ha consistido en realizar una serie de tareas con el objetivo de adquirir la capacidad de utilizar OpenCV para crear una imagen de un determinado tamaño, acceder a los valores asociados a un determinado píxel, modificar dichos valores, dibujar primitivas gráficas básicas sobre una imagen, abrir una imagen de disco, así como acceder a los fotogramas de un vídeo o captura de cámara.

## TAREA 1: Crea una imagen, p.e. de 800x800 píxeles, con la textura del tablero de ajedrez
Para realizar esta tarea se ha inicializado la imagen en negro y dividiéndola en 8x8 segmentos, se rellenó en blanco los segmentos impares de las filas impares y los segmentos pares de las filas pares.

## TAREA 2: Crear una imagen estilo Mondrian (un ejemplo https://www3.gobiernodecanarias.org/medusa/ecoescuela/sa/2017/04/17/descubriendo-a-mondrian/ )
Para realizar esta tarea se ha inicializado la imagen en negro y se rellenó con varios rectángulos de diferentes colores en distintas posiciones, de manera que los huecos negros hacen de líneas.

## TAREA 3: Resuelve una de las tareas previas (a elegir) con las funciones de dibujo de OpenCV  :)
Para realizar esta tarea se repitió el proceso de la TAREA 1 utilizando las funciones de dibujo de OpenCV.

## TAREA 4: Modifica de forma libre los valores de un plano de la imagen
Pare realizar esta tarea se dibujó en la esquina inferior izquierda de uno de los planos tres círculos que forman la silueta de Mickey Mouse.

## TAREA 5: Pintar círculos en las posiciones del píxel más claro y oscuro de la imagen ¿Si quisieras hacerlo sobre la zona 8x8 más clara/oscura?
Para realizar esta tarea se ha determinado el brillo de los píxeles siguiendo el procedimiento de la fuente[^1]. El círculo de color rojo corresponde al más claro y el azul al más oscuro. En la segunda versión se ha dividido la imagen en segmentos de 8x8 y utilizado el P50 del brillo de los píxeles del segmento como valor representativo del brillo del segmento.

## TAREA 6: Llevar a cabo una propuesta propia de pop art
Para realizar esta tarea se ha dividido la imagen en cuatro segmentos. En el segmento superior derecho se ha aumentado la intensidad del plano verde, en el inferior izquierdo el azul y en el inferior derecho el rojo. En el superior izquierdo se ha insertado una versión reescalada de la imagen original y se ha repetido este proceso en ese segmento varias veces, creando algo similar al efecto espejo. 

## Autor
Javier A. Alfonso Quintana


## Fuentes
[^1]: https://stackoverflow.com/questions/596216/formula-to-determine-perceived-brightness-of-rgb-color
