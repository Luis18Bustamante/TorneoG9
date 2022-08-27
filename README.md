# TorneoG9
Reto Ciclo 3 v2

# Descripción del Reto

La secretaría del deporte del departamento va a realizar un torneo de futbol departamental el cual se realizará en los estadios de los diferentes municipios, para este torneo se han invitado varios equipos para que se inscriban, la condición es que deben pertenecer a uno de los municipios del departamento. La secretaría ha asignado unos recursos para el desarrollo de un sistema de información que permita la gestión del torneo.

El torneo se desarrolla de la siguiente forma:

Cada equipo se sebe registrar, incluyendo el municipio al cual pertenece, sus jugadores y su director técnico.

Luego de tener todos los equipos registrados, se empieza la programación de los partidos, en los cuales se debe registrar el equipo local, el equipo visitante, la fecha y hora del partido, el estadio en el cual se realizará el juego y el árbitro que lo va a dirigir. Al finalizar el partido se debe registrar el marcador, y además se deben registrar las novedades del partido, como son las tarjetas amarillas, las tarjetas rojas y los goles, de las novedades se debe indicar la novedad, el minuto en que se registró y el jugador involucrado.

Luego de registrar el marcador del partido, se debe actualizar automáticamente la información del desempeño de cada uno de los equipos, la cual incluye la cantidad de partidos jugados, la cantidad de partidos ganados, la cantidad de partidos empatados, los goles a favor, los goles en contra y los puntos que tiene.

# Requerimientos

El sistema debe permitir realizar el CRUD de municipios. Se desea almacenar su id auto incrementable y su nombre. Se debe tener en cuenta que a los municipios pertenecen los equipos y pertenecen los estadios.

El sistema debe permitir realizar el CRUD de directores técnicos. Se desea almacenar su id auto incrementable, su nombre, su documento, y su teléfono. Se debe tener en cuenta que los directores técnicos pertenecen a los equipos.

El sistema debe permitir realizar el CRUD de equipos. Se desea almacenar su id auto incrementable, su nombre, además se debe tener en cuenta que un equipo pertenece a un municipio, y tiene un director técnico. También se debe tener en cuenta que un equipo tiene muchos jugadores.

El sistema debe permitir realizar el CRUD de jugadores. Se desea almacenar su id auto incrementable, su nombre, su número y su posición, pero se debe tener en cuenta que un jugador pertenece a un equipo.

El sistema debe permitir realizar el CRUD de árbitros. Se desea almacenar su id auto incrementable, su nombre, su documento, su teléfono y el colegio al que pertenece. Se debe tener en cuenta que a los árbitros dirigen partidos.

El sistema debe permitir realizar el CRUD de estadios. Se desea almacenar su id auto incrementable, su nombre, su dirección. Se debe tener en cuenta que cada estadio está en una ciudad, y en los estadios se realizan los partidos.

El sistema debe permitir crear partidos, los cuales tiene un id auto incrementable, la fecha y hora del partido, el equipo local y su marcador inicial que debe ser cero, el equipo visitante y su marcador inicial que debe ser cero, se debe también registrar el estadio en el cual se realizará el juego y el árbitro que lo va a dirigir.

El sistema debe permitir registrar el marcador al finalizar el partido.
El sistema debe permitir registrar las novedades del partido, como son las tarjetas amarillas, las tarjetas rojas y los goles, indicando la novedad, el minuto en que se registró y el jugador involucrado.

El sistema debe actualizar automáticamente la información del desempeño de cada uno de los equipos, la cual incluye la cantidad de partidos jugados, la cantidad de partidos ganados, la cantidad de partidos empatados, los goles a favor, los goles en contra y los puntos que tiene.

El sistema debe permitir mostrar la información de desempeño de los equipos.
