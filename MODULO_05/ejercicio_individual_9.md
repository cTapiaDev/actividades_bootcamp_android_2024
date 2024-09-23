# Calculadora de IMC

Vamos a comenzar a crear una pequeña aplicación, _pero no te asustes_, no será todo de una vez, si no que la fragmentaremos en diferentes partes para evaluar los contenidos aprendidos durante las clases.

1. Lo primero que evaluaremos será la capacidad de fragmentar el código en diferentes componentes y carpetas, es decir, utilizar la primera parte de una arquitectura más compleja __(MVVM)__.

2. El __MainActivity__ solo debe llamar a la vista principal o __HomeView__.

3. Los componentes utilizados dentro de la vista, como botones e inputs, debes crearlos de manera independiente, de tal forma que se pueda _reutilizar el código_.

4. Se evaluará la creación de __un Text__, __tres OutlinedTextView__, __un Button__ y __un MultiButton Segmentado__.

5. Al final de la explicación se adjunta la __documentación__ para implementar correctamente la estructura del __MultiButton Segmentado__.
    - __Importante:__ Debes modificar el funcionamiento de este Button para que solamente se pueda dar clic en una de las opciones, es decir, si se selecciona _"Hombre"_, se debe desmarcar _"Mujer"_ y viceversa.

6. Una vez completes las funcionalidades, crea un nuevo repositorio en __GitHub__ y sube el enlace al nodo dentro un archivo __.txt__
----------
[Documentación de MultiChoiceSegmentedButtonRow( )](https://developer.android.com/reference/kotlin/androidx/compose/material3/MultiChoiceSegmentedButtonRowScope)

----------
__Se adjuntan imágenes de referencia del diseño__

![](https://i.imgur.com/Nq7DrSx.png)

![](https://i.imgur.com/CD8DnzU.png)

![](https://i.imgur.com/IzpD2Am.png)
