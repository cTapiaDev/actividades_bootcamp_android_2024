# Diseño MovieDB App

Para este punto ya deben estar lista las configuraciones del Backend, es decir, la __API__ debe responder los datos que le estamos pidiendo y nuestra base datos __SQLite__ debe estar correctamente configurada para poder interactuar con ella.

1. Crea una vista que contenga una __TopBar__ con su respectivo título y un botón que permita agregar una nueva película.
    - Al momento dar clic al botón se deben pedir los datos a la __API__ y en el mismo proceso almacenarse en la base de datos.

2. Es importante que cada nueva película se pueda visualizar en el __LazyColum__ que va a mostrar la totalidad que agreguemos. 
    - __Importante:__ Algunas API's suelen agrupar los datos en pages de 10 o más elementos, _de ser ese el caso_ __debes generar una paginación interna__ que permita acceder a las películas de las paginas siguientes.

3. Crea una __Card__ para el diseño de las películas que componen la vista.
    - Incluye __todos__ los datos del model.
    - Incluye un __botón de eliminar__ dentro de la Card.
    - El tamaño de la Card debe ser tal, que al momento de iniciar nuestra aplicación deben verse __máximo dos películas__ en la columna.

4. En caso de que quieras realizar un diseño más novedoso, puedes modificar el __Model__ para obtener más datos de la __API__, especialmente la ruta del _"backdrop_path"_ que puede servir para generar una Card más llamativa.
    - Este punto __es opcional__, pero le podría dar un plus extra al diseño de tu aplicación.

5. Una vez los cambios solicitados estén listos, actualiza el repositorio de __GitHub__ y comparte nuevamente el enlace en el nodo.