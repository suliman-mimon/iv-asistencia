# IV Asistencia

## Descripción del problema

Tengo actividades a lo largo del día para las que le quiero dedicar un tiempo específico, y tras ello quedarme el mínimo tiempo posible. Esas actividades conllevan desplazamientos en autobús: ya sea un desplazamiento de ida y uno de vuelta (ir al gym durante 1h, o ir a la biblioteca durante 2h) o dos desplazamientos que unen tres sitios (uni-comedor-biblioteca para comer durante 30min). No quiero perder tiempo esperando autobuses y no quiero dedicar a la actividad más tiempo del necesario. Podría intentar cuadrarlo yo mismo, pero además de que no me fío de Google Maps, eso me requeriría muchísimo esfuerzo mental cada vez que lo quiera hacer.

## Especifiación adicional del problema

Ya no pienso en los sitios a los que tengo que ir, sino en sus paradas más cercanas.
El tiempo a pie no importa, ya que las paradas están cerca y si tengo claro qué autobús coger, puedo salir con suficiente antelación, o correr (soy muy de correr). Aunque se puede introducir un pequeño margen adicional al tiempo necesario de la actividad.
Solo me interesan los trayectos directos, los transbordos casi nunca me funcionan bien.
Normalmente, suelo conocer de antemano la hora a la que salir hacia la actividad, ya que suele depender de actividades previas (como la hora que finaliza las clases que tenga ese dia). Pero, me gusta tener un margen de +- 15 min, ya que si me interesa más coger un autobús que sale antes de esa hora, podría salir un poco antes de clase, o si el autobús que me interesa sale un poco más tarde, me puedo quedar terminando alguna tarea en vez de estar esperando el autobus.

## Descripción del dataset

La fuente de datos es el [GTFS estático de los autobuses urbanos de Granada](http://movilidadgranada.org/gtfs/gtfs.zip). Es un archivo ZIP que contiene tablas en formato CSV con las paradas, líneas, viajes y horarios programados para el periodo en curso. 

Los archivos relevantes son:
- `stops.txt`: las paradas.
- `routes.txt`: las líneas
- `trips.txt`: cada viaje de una línea, su dirección y el servicio al que pertenece
- `stop_times.txt`: cuándo pasa cada viaje por cada parada
- `calendar.txt`: días de la semana en los que opera cada servicio.
- `calendar_dates.txt`: añade o elimina servicios en fechas concretas.

## Material de la actividad

![Fotografía de la tarjeta del cliente](imagenes/tarjeta-cliente.jpg)

![Fotografía de la tarjeta del desarrollador](imagenes/tarjeta-desarrollador.jpg)

## Documentación de configuración

[Configuración del repositorio](docs/configuracion.md)
