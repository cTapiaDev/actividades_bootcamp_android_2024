# App Noticias

Si estás leyendo esto es porque la conexión con tu ViewModel __está recibiendo datos correctamente...__ _o eso espero_. 

1. Crea una primera vista que muestre la __lista de noticias disponibles__.
    - Es importante que en un comienzo __solo carguen 5 noticias__, las demás comenzarán a cargar a medida que se requiera visualizarlas, es decir, _cuando se haga scroll hasta ellas_.

2. Crea una __Card__ que contenga la información de cada noticia. El diseño es de libre elección, pero si se deben distribuir en ella los __siguientes elementos:__
    - name,
    - author,
    - title,
    - urlToImage: _Se debe visualizar como imagen, no como la url que está llegando desde la API_.

3. __Configura las rutas de navegación__, marcando la lista de noticias como la vista principal de la aplicación.

4. Genera una __segunda vista__ que se abrirá al momento de dar clic sobre una de las noticias.
    - La forma en que se ejecute este proceso es de tu elección: por ejemplo, puede ser un botón de _"Ver más"_, un _icono_ o que la _Card por completo sea un elemento clickable_.

5. La segunda vista debe tener un diseño en el que se visualice la totalidad de datos del model _(Excepto id)_.

6. No olvides tener una __TopBar__ que permita navegar de vuelta a la vista principal.

7. Una vez los cambios estén listos, actualiza tu repositorio de __GitHub__ y sube el enlace a la plataforma por medio de un archivo __.txt__