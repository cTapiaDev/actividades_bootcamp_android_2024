# Control de errores

Cuando los datos son ingresados correctamente, el calculo va a salir bien y la aplicación funcionará exactamente como lo esperamos... __¿Qué ocurre si los datos no son entregados?__ o __¿Son erróneos?...__ Con eso ya cambian un poco las cosas y es probable que comiencen a aparecer los errores, convirtiéndose en un escenario fatal si es el usuario quién se ve enfrentado a ellos, por eso, es __tu turno__ de __buscar la forma de adelantarte a los hechos__.

1. Identifica el _nombre del error_ que se genera en caso de recibir un tipo de dato que no corresponde al esperado, o directamente no recibir el dato.

2. Busca una solución para __impedir__ que el usuario ingrese texto si solo se está esperando datos de tipo numérico.
    - _Quizás se podría hacer algo con el teclado que visualiza el usuario_.

3. En caso de existir un inconveniente con los datos o no contar con ellos, _genera una ayuda visual para el usuario_; puede ser por medio de una __notificación__ o algo más consistente como __un modal__ que le avise del problema.
    - Es tan simple como pedirle que ingrese los datos correctos para evitar que la aplicación se caiga.

4. Una vez tengas los cambios actualizados en tu repositorio de __GitHub__, sube el enlace del mismo al nodo por medio de un archivo __.txt__

----------
__Se adjunta imagen de referencia del diseño__

![](https://i.imgur.com/3vTummI.png)