ng-bee
======

angularJS, jquery mobile and html5 for android

DYNAMIC MOBILE UI 

El objetivo de defaultandroid.htm es introducir el patron ui de model view viewmodel bajo el framework angularJS de google.
Asi comprobar la compatibilidad de html5 junto con jquery mobile y la historieta del web semantic.
El codigo lo hice en ingles y como era de esperar, vuelvo a la tematica de las abejas a modo de ejemplificar.

El objetivo lo cumpli. En una unica spa con un embeded javascript que funciona como una suerte de viewmodel o javascript controller ( ctrl como lo llama google )
pude hacer el doble-binding de los "campos" con el html, asi evitar incomodos jqueries que interactuen con el DOM.

Las responsabilidades estan claras. El ioc de angular es bastante flexible.

El desacoplamiento es bastante neat, aunque quedaron pendientes como custom validations, loggers, test driven development... bien gracias...
Aparentemente es posible hacer un mock del $scope, y asi pegar los asserts con los toBe de js. dynamic weird.

Me quedaron pendientes por investigar cosas como jquery mobile angular adapter y leer un poco mas sobre las extensions.

Lo de los tipos callbacks async? GENIAL... aca lo llaman promises y deferred.

MVVM over MVC... seguia demostrando ser el ui pattern por excelencia en 2013, hasta la llegada de flux por facebook en 2015.

Foro? mmm... na.
