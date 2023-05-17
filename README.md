# patito
Proyecto de apiRestful, se integro en el archivo properties las propiedades de hibernate para que solo al agregar el usuario y password junto a ip y puerto de la base de datos a la que se quiere conectar, se genere de manera automatica las tablas sql con las relaciones pertinentes entre tablas.

El proyecto fue compilado con la version de Java 11 y fue construido con intellij, por lo que se recomienda utilizar este mismo, para poder compilar y descargar las dependencias necesarias para su ejecucion.

El script de sql no es necesario porque agregue la configuracion de hibernate para que utilizando el mapeo de las entidades, genere a travez de la persistencia de datos, las tablas en la base de datos a lacual generen su conexion.
