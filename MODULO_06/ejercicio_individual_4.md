# Conexión con la API News

Ya tienes la __API News__ con su respectiva llave funcionando sin ningún problema _(En caso de que API News sufriera una caída, contactarse con el relator para gestionar un cambio de API)_, así que es hora de realizar las configuraciones pertinentes para crear una aplicación de noticias.

1. Gestiona correctamente la configuración de las constantes para tener una __construcción ordenada__ de la API.

2. Utiliza __Retrofit__ para manejar las conexiones de datos que se vayan a generar. No olvides seguir el _"flujo de navegación"_ para construir correctamente el backend.

3. Debes utilizar __Gson__ para transformar los datos a objetos y poder interactuar con ellos a la hora de realizar el apartado visual y/o interactivo de la aplicación.

4. __Analiza la API__ y crea las __data class__ necesarias para obtener los siguientes datos:
    - id
    - name
    - author
    - title
    - description
    - url
    - urlToImage

5. Avanza con la Configuración hasta crear el __ViewModel__ y dos funciones: La primera debe permitir capturar la totalidad de noticias en una lista y la segunda, capturar una noticia por su id o name (Analiza cual te conviene más según la respuesta de datos que proporcione la API).

6. Una vez tengas lista la parte del Backend de tu proyecto, súbelo a tu __GitHub__ y copia el enlace dentro de un archivo __.txt__ que subirás a la plataforma del nodo.