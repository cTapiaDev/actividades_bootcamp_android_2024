# Backend MovieDB App

Vamos a poner en práctica conocimientos claves aprendidos hasta ahora. Es por eso por lo que lo principal será conseguir la llave de la __API__ que usaremos en el proyecto.

Crea una cuenta en https://www.themoviedb.org. Accede a la __sección API__ del menú superior y completa los pasos que la web te pedirá.

Una vez aceptes la licencia y llenes los campos, te darán acceso a la __Clave de la API__. 

Con la llave en tu poder ya puedes acceder a la __Documentación de la API__ y utilizar sus datos: https://developer.themoviedb.org/docs/getting-started

1. Dentro de la documentación, accede a __"API Reference"__ y selecciona la ruta que más te acomode de __"Movie lists"__, entre ellas: _Now Playing_ - _Popular_ - _Top Rated_ - _Upcoming_.

2. Es importante que el __Endpoint__ que selecciones te permita realizar un model con los siguientes datos:
    - original_title
    - poster_path
    - release_date
    - vote_average
    
3. Ten en cuenta que la respuesta del __"poster_path"__ no es la url completa de la imagen, revisa la sección __"Images"__ de la documentación para descubrir como completar la ruta.

4. Realiza las configuraciones necesarias para recibir los datos de la __API__, y también tener una base de datos __SQLite__ que permita almacenarlos de manera local.

5. Una vez tengas lista las configuraciones, sube tu proyecto a __GitHub__ y copia el enlace dentro de un archivo __.txt__ para subirlo al nodo.