# Ingreso de datos al paciente

En el ejercicio anterior integramos una nueva vista que permite ingresar múltiples pacientes a la aplicación. Siempre que se ingresa uno de los pacientes se genera un botón de _"Calcular IMC"_ que lleva a la calculadora que previamente habíamos creado, ahora es momento de ponerla a trabajar y tomar los resultados para llevarlos de vuelta a la vista principal en donde están todos los pacientes con sus datos.

1. Preocúpate que __la navegación__ del botón esté funcionando correctamente.

2. Esta vez agregaras un par de cosas a la calculadora:
    - Bajo la vista del resultado debes integrar un espacio para mostrar el __estado de salud__ del paciente _(Bajo peso, Peso Normal, Sobrepeso, Obesidad I, II o III - Se adjuntará al final una imagen con la tabla de la OMS para poder realizar el cálculo)_.
    - Además de eso se debe generar un botón que nos __permite guardar__ todos los datos para llevarlos de vuelta a la vista principal.
    - __Ojo:__ El botón de guardar _únicamente se debe visualizar_ cuando la calculadora __fue usada__, si se ingresa __por primera vez__ solo se debe ver el botón de calcular.

3. Al momento de dar clic sobre el botón de __"Guardar"__ es importante que la __edad__, el __sexo__, el resultado del __IMC__ y el __estado de salud__, _retornen a la vista principal_.

4. En la vista principal la Card del cliente va a sufrir __modificaciones__:
    - Ya __no debe mostrar__ el botón para _"Calcular IMC"_.
    - Pero __si debe mostrar__ todos los datos capturados desde la calculadora, es decir, debe aparecer en la Card el _nombre_, la _edad_, el _sexo_, el _IMC_ y el _estado de salud_ del paciente.

5. __Importante:__ Las imágenes del final son solo una referencia en cuanto al diseño, lo primordial es que se visualicen correctamente los datos pedidos, luego la orientación dentro de la Card es a libre elección.

6. Una vez implementes el nuevo ejercicio, actualiza tu repositorio de __GitHub__ y sube el enlace a la plataforma por medio de un archivo __.txt__

----------
__Se adjuntan imágenes de referencia del diseño__

![](https://i.imgur.com/ivGfsqS.png)
![](https://i.imgur.com/xM4WqR9.png)
![](https://i.imgur.com/lN35ZMY.png)