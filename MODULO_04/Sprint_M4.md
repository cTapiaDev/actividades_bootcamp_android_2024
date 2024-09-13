# Control de vistas

El enfoque de este Sprint es evaluar los conceptos más básicos para la creación de una aplicación representativa.

1. Debes crear una __actividad principal__ que se utilizará para presentar un producto (Puede ser un juego, una película, un nuevo reloj, etc.)
- En la vista debes distribuir __mínimo tres imágenes__ y agregar un texto relacionado al producto elegido.
- Utiliza __FontFamily__ para cambiar el tipo de fuente que Android trae por defecto.
- Además, no olvides agregar un botón que al darle clic llevará a la siguiente __actividad__.

2. La __segunda actividad__ debe mostrar el producto como tal.
- Agregar un botón que lleve directamente al _sitio web_ del producto. Es importante que la web se ejecute dentro de nuestra aplicación, __jamás debe sacarnos de ella__.
- La segunda actividad no es necesario que tenga una toolbar, _pero en la web del producto si debe existir un botón que permita volver a la actividad anterior_.
- Aprovecha el espacio en pantalla para crear un __Fragmento__ en el que vas a alojar un video del producto.

3. El video de la segunda actividad __no puede__ ocupar todo el espacio disponible en la vista _Portrait_, es por eso, que debes __crear un diseño diferente__ para la vista _Landscape_ de tal forma que el video se pueda visualizar mucho mejor.

4. Se evaluará el uso correcto de estilos para los textos ingresados en la primera actividad, también es importante implementar correctamente el uso de __viewBinding__ tanto en las actividades como en el fragmento.

5. No olvides utilizar un __webViewClient__ para que los enlaces se puedan visualizar dentro de la aplicación sin problema.

6. La aplicación debe ser mínimamente presentable, es decir, tanto los colores como la distribución de las imágenes debe seguir un _estándar de calidad_.

7. Una vez tengas listo tu proyecto crea un nuevo repositorio en tu __GitHub__ y aloja los cambios en el. Copia el enlace del repositorio y ponlo dentro de un archivo __.txt__ que subirás al nodo.

----------
__Se adjuntan imágenes de referencia del diseño__

![](https://i.imgur.com/9hLBoc7.png)
![](https://i.imgur.com/whtc409.png)
![](https://i.imgur.com/7iqLuGg.png)