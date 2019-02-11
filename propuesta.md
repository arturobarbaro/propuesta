% MyFit
% Arturo Barba Rodríguez
% Curso 2018/19

# Descripción general del proyecto


MyFit será una "red social" para deportistas o usuarios que quieran iniciar un estilo de vida más saludable.
Cada usuario contará con un perfil personal, y una red de contactos (seguidores y seguidos) con los que podrá estar en comunicación.

MyFit calculará el gasto calórico de cada usuario en función de sus datos personales y sus actividades realizadas.


## Funcionalidad principal de la aplicación

Esta aplicación tendrá como objetivo registrar las actividades físicas de cada usuario, que pueden ser compartidas y visibles para otros usarios o no.
Cada usuario podrá así realizar un seguimiento de su propia actividad física y podrá tener la posibilidad de ver un seguimiento de otros usuarios. 

MyFit además podrá informar de actividades futuras de un usuario seguido, creando así un evento.
Cada usuario podrá anotar comentarios junto a la actividad física realizada, está almacenará así el tipo de actividad (como puede ser correr, nadar o un entrenamiento de fuerza), la fecha de inicio de la actividad junto a su fecha de fin o su duración, la distancia, el gasto calórico de cada usuario y anotaciones del propio usuario (observaciones, sensaciones, anécdotas, etc). 

De cara al exterior otros usarios podrán dar "like" y dejar comentarios asociados a esta actividad.

## Objetivos generales

* Objetivo: "gestionar las actividades físicas de cada usuario, así como interactuar con otros".
* Casos de uso: 
	- Invitados: "registrarse", "ver detalles de un entrenamiento", "buscar otros usuarios", "ver a otro usuario".
	- Usuarios: "iniciar sesión", "cerrar sesión", "registar un entrenamiento", "eliminar un entrenamiento propio", "comentar un entrenamiento", "descomentar un entrenamiento", "dar like a un entrenamiento", "quitar like a un entrenamiento", "ver detalles de un entrenamiento", "editar un perfil personal", "borrar una cuenta personal", "buscar otros usuarios", "ver a otro usuario", "seguir a otro usuario", "ser seguido por otro usuario", "modficar un entrenamiento personal antes de guardarlo".
	- Administrador: "iniciar sesión", "cerrar sesión", "registar un entrenamiento", "eliminar un entrenamiento", "borrar comentarios de un entrenamiento", "ver detalles de un entrenamiento", "editar un perfil", "borrar una cuenta", "buscar otros usuarios", "ver a otro usuario", "añadir un tipo de actividad", "borrar un tipo de actividad", "modificar un tipo de actividad".

# Elemento de innovación


Amazon S3 o Amazon Simple Storage Service, como servicio de almacenamiento y protección de datos.

Uso de la tecnología Google Maps para añadir una ruta a cada entrenamiento.

