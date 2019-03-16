# UT08 Almacenamiento

## Introduccion

Ejercicio con Almacenamiento

## Autor

Guillermo Rodríguez Moraga

## Versiones

Version 0.3.2
- Al eliminar producciones se hacen de todas las tablas de la base de datos

Version 0.3.1
- Las modificaciones, eliminado y añadido de directores, actores y categorias se hacen sobre la base de datos

Version 0.3
- Se han creado las bases de datos con la relacion entre los objetos del sistema
- Se ha creado una funcion para mostrar el modal y la pagina de inicio
- Cambios menores en los comentarios del codigo
- Las producciones de las categorias se muestran en funcion de la relacion de las bases de datos
- Las producciones del actor se muestran en funcion de la relacion de las bases de datos
- Las producciones del director se muestran en funcion de la relacion de las bases de datos

Version 0.2.5
- Cambios en la funcion getObject de los objetos Movie y Serie
- Los formularios de moficiacion validan mejor los campos
- Se han corregido fallos en los objetos del sistema

Version 0.2.4
- Ahora puedes pinchar sobre las tarjetas y no solo sobre los botones de las tarjetas
- Cambios en la interfaz
- Solucionado el error que hacia que desapareciese el titulo al volver al inicio desde una produccion

Version 0.2.3
- Cambios en el cronometro 
- Mejoras a la hora de gestionar los duplicados en la base de datos

Version 0.2.2
- Se ha añadido un cronometro a la interfaz junto con su funcionalidad

Version 0.2.1
- Se ha corregido un error al intentar eliminar categorias, actores y directores creados si se ha recargado la pagina
- Ahora al realizar operaciones si son un exito muestra un modal para informar al usuario
- Se ha corregido un fallo con las bases de datos y las tablas

Version 0.2
- Cambios en el objeto Person
- Se ha corregido un error al pinchar sobre el logo
- Se han cambiado todos los iteradores de actores y directores por llamadas a la base de datos mediante cursores
- Ahora al añadir, borrar o modificar un actor o director se hace sobre la base de datos

Version 0.1.1
- Se han separado las funciones de validaciones de campo en un fichero JS aparte yse ha enganchado al HTML
- Se ha cambiado el nombre del fichero video.html a index.html

Version 0.1
- Se ha creado una funcion para crear la base de datos y se han añadido los objetos iniciales
- Se han cambiado todos los iteradores de categorias por llamadas a la base de datos mediante cursores
- Ahora al añadir, borrar o modificar categoria se hace sobre la base de datos

Version 0.0.1
- Se ha creado el repositorio y copia el sistema de ficheros de la practica anterior
- Se ha añadido la funcion getObject() a cada objeto del archivo ObjetosVideo.js que devuelve un objeto literal