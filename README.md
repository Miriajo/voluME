# voluME

Práctica del módulo de Diseño para Devs del Bootcamp Mobile VIII de Keepcoding.

## Concepto

Este proyecto consiste en diseñar una interface para una App Mobile de Eventos a los que puedes invitar amigos y que todo el mundo colabore para generar una playlist musical para cada evento.

## Diseño Elegido

### Colores

El diseño tiene como color princial el propuesto por el profesor. Es el rosa estándar de iOS.

He optado por hacer una aplicación con fondo oscuro para centrar la vista en los elementos y que el blanco no canse al ojo, ya que se muestra mucho contenido de imagen.

Hay toques de color para resaltar elementos importantes.


### Diseño de pantallas

#### Eventos

La pantalla principal se divide en dos partes: Próximos Eventos y Eventos Disfrutados.

De esta manera no tenemos toda la información a la vista, ya que los eventos pasados ya están cerrados y se verán sólo para recordar o escuchar de nuevo la playlist elegida.

- **Próximos Eventos:** Está divida en secciones por ESTACIÓN (Primavera, Verano, Otoño, Invierno) siempre y cuando halla eventos para esas estaciones. Consta de una imagen grande con el evento más próximo y debajo habrá más eventos con un scroll horizontal.
- **Eventos Disfrutados:** Está divida en secciones por AÑO. Aparecerán sólo los eventos ya pasados. Se compone de elementos del mismo tamaño y hay una botón para ir mostrando más mediante scroll horizontal.

#### Invitados

Contiene una cuadrícula compuesta por 3 columnas y N filas (scroll vertical) con la foto, nombre y número de canciones propuestas de cada uno de los usuarios (invitados) de la App.

Si pinchamos en el menú de abajo en Eventos volveremos a la pantalla principal donde la hayamos dejado (Próximos o Disfrutados).


#### Detalle Evento Próximo

Se compone de:
- Un elemento con la fotografía del Evento y su información.
- Un botón para valorar la playlist
- Los invitados al evento (scroll vertical)

Al pinchar en "Valorar Música" nos llevará a la pantalla detalle del playlist donde podremos votar si nos quedamos o no con la canción que en eses momento está sonando. 

Disponemos de un reproductor para pausar o continuar la reproducción de la canción.

#### Detalle Evento Pasado

Esta pantalla es muy parecida a la de Evento Próximo, con la diferencia de que ya no podemos votar las canciones, sólo escuchar la playlist que se quedó como definitiva.

Podemos movernos de canción atrás o adelante y las miniaturas de las carátulas de los discos se recolocarán. Funcionamiento como el de la previsualización del Finder en forma de galería.