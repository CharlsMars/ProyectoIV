# StudyBook

## Problema
Cuando es época de exámenes, las salas de estudio completan su aforo y encontrar sitio donde estudiar se convierte una tarea difícil. 

## Solución
Por esto, propongo una herramienta que ayudándose de la base de datos de la UGR, el usuario pueda saber cuántos puestos hay libres en las distintas aulas de estudio/bibliotecas, pudiendo así saber de antemano dónde poder ir. La aplicación permitiría la reserva de puestos, procesando las peticiones de los usuarios.

## Lógica de negocio
La herramienta requerirá la localización de usuario, ya que ésta calculará la distancia a las bibliotecas/salas de estudio más cercanas y que tengan puestos libres. También otra idea que tendría que investigar más adelante es la posibilidad de que la aplicación sepa qué carrera estamos estudiando y filtre por libros disponibles en la biblioteca compatibles con la carrera del usuario.

## Lista de comprobación
* [ ] ¿Se trata de un problema real del que se tenga conocimiento personal?

Sí, en ocasiones he acudido a salas de estudio y no he podido acceder porque estaba el aforo completo.
* [ ] ¿Se trata de un problema que para solucionar requiera el despliegue
   de una aplicación en la nube?

Sí, ya que cada estudiante se encuentra en un lugar diferente y todos tienen que acceder a los datos del servidor.
* [ ] ¿La solución requiere una cierta cantidad de lógica de negocio, en vez
    solucionarse sólo almacenando y buscando?

Sí, porque dependiendo de la distancia y la especialidad del usuario, mostrará unos resultados u otros.
* [ ] ¿Se ha incluido la configuración del repositorio y se ha enlazado desde el
`README`?

Sí, he configurado y usado las claves SSH y he seleccionado el tipo de licencia.
* [ ] ¿Tienes todos los datos necesarios para poder resolver el problema, o vas
a requerir que el usuario los introduzca?

Del usuario requerimos poca información.
