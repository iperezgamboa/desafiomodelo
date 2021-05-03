# desafiomodelo

Descripción

En el siguiente desafío utilizaremos todas las funcionalidades que nos provee la ex gema
"rails-ujs", hay que recordar que fue incorporada a Rails en la versión 5.1.
Los últimos dos requerimientos son los que muestran casos de uso más prácticos para el
uso de "rails-ujs".

La idea de este desafío es crear un modelo a elección y estructurar su código de la misma
forma, cumpliendo con los requerimientos solicitados más adelante.

En caso de necesitar un punto de partida, pueden generar un scaffold para un modelo Post
y crear un controlador ujs para agregar todos los requerimientos solicitados.

Requerimientos
1. Link o formulario que tenga el atributo data-confirm.
2. Formulario que ocupe el atributo data-disable_with.
3. Crear hipervínculos que ocupen los métodos HTTP POST y DELETE, se pueden guiar
con los links que genera un scaffold.
4. Crear un formulario para poder realizar el create de algún modelo pero que funcione
por AJAX (usando remote, se puede usar jquery).
5. En la vista index del controlador ujs o donde crean los post con AJAX, que al crearse
un post se agregue al div con id my_posts, recordar crear un partial para los posts.
