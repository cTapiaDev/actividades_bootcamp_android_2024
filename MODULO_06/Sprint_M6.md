# Caso "MobiStore"

La empresa distribuidora de equipos móviles __MovilCL__ busca iniciar su transformación digital con el desarrollo de una aplicación móvil Android. En esta primera fase, el objetivo principal es crear un _mínimo producto viable (MVP)_ que permita a los posibles clientes visualizar un catálogo de teléfonos móviles disponibles y seleccionar aquellos que les interesen.

## Alcance del Proyecto.

- Los usuarios podrán navegar por un listado de teléfonos móviles que se encuentran en venta.
- Los usuarios podrán seleccionar un teléfono especifico para obtener más detalles.

## Detalles Técnicos.

- El equipo de desarrollo BackEnd ha implementado una __API REST__ que provee la información necesaria sobre los teléfonos y sus características.
- Se solicita desarrollar una aplicación Android que consuma la __API REST__ proporcionada.
- El servicio __REST__ cuenta con __dos endpoints__; El primero proporciona la totalidad de equipos móviles disponibles, y el segundo entrega los detalles de cada equipo a través de su identificador. 
- El proyecto debe ser lo suficientemente flexible para ser escalado y mejorado con funcionalidades adicionales en fases futuras.
- Bajo los paradigmas de flexibilidad y escalabilidad, además de costos de mantención bajos, La API mínima para realizar el proyecto es 27 y su target 34.

1. __APIs:__
    - https://my-json-server.typicode.com/Himuravidal/FakeAPIdata/products/
    - https://my-json-server.typicode.com/Himuravidal/FakeAPIdata/details/1

2. No olvides utilizar el estilo de Arquitectura __MVVM-StateFlow-ROOM__.
    - Esto quiere decir que debes utilizar un código limpio, respetar estilos de codificación y evitar a toda costa el código espagueti.
    - Antes de mostrar los elementos en la primera lista, captura la respuesta de la API en ROOM para generar una persistencia de datos.

3. El proyecto consta de dos vistas:
    - La primera es aquella que muestra la _totalidad de equipos_.
    - La segunda muestra _al detalle_ la información del equipo seleccionado.
    - __Importante:__ La segunda pantalla debe poseer un botón flotante que permita enviar un correo.

4. Dentro de la primera vista los elementos se deben mostrar por medio de una __Columna__ o una __Grilla__, el diseño queda a tu elección.
    - Demás está decir que tanto la columna como la grilla deben ser de la familia __Lazy__ _(LazyColumn o LazyVerticalGrid)_.

5. La navegación dentro de la aplicación debe ser controlada por un __navManager__ y a nivel de diseño por una __TopBar__.

6. La paleta de colores de la aplicación consta de cuatro colores que debes utilizar con mucha sabiduría:
    - 0xFF252243
    - 0xFF5161F1
    - 0xFF63E9F8
    - 0xFFFFFFFF
    - _(Pueden agregar colores extras sin problema, siempre y cuando exista una armonía en el diseño)_

7. Ningún color dentro de la aplicación debe establecerse a la fuerza, es decir, debes crear sus respectivas variables y modificar el __Theme__ según corresponda.

8. Todo texto dentro de la aplicación debe estar dentro de su _respectiva variable_. A excepción de aquellos que provienen directamente de la API.

9. La API de detalle retorna una valor booleano de "credit", es importante que al momento de crear la vista de detalle, este dato __no se muestre__ tal cual y se cambie por:
    - __true:__ Acepta Crédito.
    - __false:__ Sólo Efectivo.

10. La segunda vista además de mostrar el detalle al que se accedió a través del id del móvil, debe tener un __botón flotante__:
    - Al darle clic se debe abrir la aplicación que permite enviar correos.
    - La siguiente información debe aparecer por defecto:
        - __Destinatario:__ info@novaera.cl
        - __Asunto:__ Consulta {name} - Id: {id}
        - __Mensaje predefinido (Pueden modificarlo a su gusto, lo importante es que muestre el nombre y el id):

        "Hola
        Me gustaría obtener más información del móvil {name} de código {id}.
        Quedo atento."

11. Realiza __dos Test__ dentro de la aplicación:
    - 1 Test Unitario
    - 1 Test Instrumental

12. Una vez completo tu proyecto, crea un repositorio en tu __GitHub__ y alojalo allí. Copia el enlace dentro de un archivo __.txt__ y súbelo al nodo.
