# ProyectoFinalKevinBenavides21000771

Este proyecto, de la materia introducción a la programación, consiste en elaborar un pequeño programa con JavaScript, que simula los cálculos que se realizan en la cotización de un seguro. El seguro cuenta con un monto base, sobre ello se suman recargos en relación con diversos criterios que se describen a continuación:

1)	Según la edad del cotizante del seguro, el porcentaje de recargo sobre el monto base varía. (Entre 18 y 24 años el 10%, entre 25 y 49 el 20% y para 50 o más el 30%)
2)	En caso el cotizante posea conyugue, el porcentaje de recargo se aplica de la misma manera como en el numeral anterior, basándose en la edad de la pareja.
3)	Si el cotizante posee hijos, se aplica un recargo fijo sobre el monto base por cada hijo. (20%)
4)	Por cada propiedad que posee el cotizante, también se aplica un recargo fijo sobre el monto base. (35%)
5)	Finalmente, se aplica un porcentaje fijo sobre el salario del asegurado. (5%)

Cuando el cliente ingresa los datos y el programa ya cuenta con toda la información necesaria, este último procede a realizar todos los cálculos pertinentes, finalizados estos anteriores, arroja el monto que corresponde a recargos y el total a pagar.
Por último, en caso se desea realizar un nuevo cálculo de cotización para otro cliente, el programa se reitera automática e indefinidamente hasta que se le indique que se desea salir.

Dentro de las consideraciones que hay que tener con el problema es que, cada vez que se le pida ingresar un dato, procure apegarse lo mas posible a lo que se le solicita. Por ejemplo, cuando se le pude ingresar “SI” no ingrese variantes que posean tildes; cuando el programa le solicite ingresar un dato numérico, favor ingresar solo números. Dado que las estructuras condicionales “If” se ejecutan estrictamente acorde a como están programadas, por lo que cualquier error al seguir las indicaciones sobre los datos que se le consultan, podría ocasionar un mal funcionamiento.

Dentro de las posibles mejoras que pueden realizarse sobre este programa, sería ver la manera de robustecer los controles contra lo que el usuario ingresa, en caso de una entrada totalmente a la que se le pide. Con lo anterior se lograría no tener que estar reiterando todo el programa en caso se cometió un error. También, fuese posible ingresar la opción a que el cliente decida que seguro quiere contratar, dado que el programa actual se limita al que tiene como base 2000 quetzales.
