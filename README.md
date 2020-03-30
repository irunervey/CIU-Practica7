# CIU-Practica7
Práctica 7 de creando interfaces de usuario

## Autoría.
El trabajo fue realizado por Iru Nervey Navarro Alejo.

## Descripción.
Para esta práctica he realizado un pequeño juego en el cual se trata de eliminar las pelotas utilizando la cara. Al eliminar estas pelotas se producira un sonido dependiendo de la posición de la pelota y el tamaño de esta. Ademas hay un ritmo de bateria sonando de fondo el cual puede ser silenciado.

## Controles.

- Pulsa espacio para salir del menú
- Para cambiar entre el modo de juego y de rebote pulsa la e.
- Para cambiar en el modo de juego si se creara una nueva pelota o no pulse la r.
- Para quitar o poner el rectángulo facial pulse la t.
- Para pausar la musica pulsar m.
- Con el click del raton apareceran más pelotas.

## Implementación.
He utilizado la libreria [open CV](http://www.magicandlove.com/blog/2018/11/22/opencv-4-0-0-java-built-and-cvimage-library/)  abajo para identificar las caras que aparezcan en la imagen para despues comprobar si colisionan con la cara. He implementado un modo rebote en el cual las pelotas rebotan en la cara o caras de los jugadores.
Para la reproduccion de sonido utilizo el metodo makeMusic() y el código que reproduce el sonido al eliminar las pelotas se encuentra en el metodo faceDetect(Mat grey).

## Herramientas utilizadas.

Debe estar instalada la libreria de [open CV](http://www.magicandlove.com/blog/2018/11/22/opencv-4-0-0-java-built-and-cvimage-library/).

Debe estar instalada la libreria de [soundcipher](http://explodingart.com/soundcipher/download.html).
