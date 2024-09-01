# Sistema de Transacciones Bancarias

Vamos a culminar los ejercicios de __Kotlin consola__ con un último integrador en el que tendrás que simular parte de un _sistema bancario_.

1. Esta vez debes crear dos archivos por separado; __un Main__ dónde se realicen las transacciones y __una CuentaBancaria__ que almacene las funciones a utilizar.

2. El archivo denominado _CuentaBancaria_ debe ser de tipo __clase__.
    - Debe tener dos _atributos_ en su constructor: __nombreCuenta__ y __saldoDisponible__.
    - Al momento de crear un nuevo objeto de tipo _CuentaBancaria_, es importante que se genere una __lista de texto__ que funcionará como historial para las transacciones.

3. Dentro de la clase debes crear __cuatro funciones__:
    - __deposito:__ Permite realizar un depósito a la cuenta bancaria, por ende, el saldo se verá afectado.
    - __retiro:__ Permite realizar un retiro de la cuenta bancaria, siempre y cuando se tenga saldo disponible.
    - __mostrarSaldo:__ Permite ver el saldo disponible.
    - __mostrarHistorial:__ Muestra la totalidad de transacciones que se han realizado en la cuenta bancaria.

4. Una vez tengas toda la lógica lista, es hora de volver al archivo __Main__ y realizar las pruebas correspondientes.
    - Crea __mínimo tres__ cuentas bancarias.
    - Ingresa __al menos cinco__ transacciones para cada una de las cuentas.
    - En __al menos una__ de ellas realiza un retiro fallido.
    - Imprime el historial __de cada una__ de las cuentas.

5. Como se trata de un nuevo proyecto, debes subir el repositorio a tu cuenta de __GitHub__ y el proporcionar el enlace por medio de la plataforma. Recuerda que el enlace debe estar dentro de un archivo _.txt_

----------
__Se adjunta imagen de referencia de la consola__

![](https://i.imgur.com/Zc7YD9o.png)
