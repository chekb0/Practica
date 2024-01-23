#  _JSON_

JSON es un formato de texto que forma parte del sistema de JavaScript y que se deriva de su sintaxis, pero no tiene como objetivo la creación de programas, sino el acceso, almacenamiento e intercambio de datos. Usualmente es conocido como una alternativa al lenguaje XML.

Un archivo JSON es un documento digital creado en este lenguaje que almacena información organizada, con el fin de hacer más simple su búsqueda y acceso. La ventaja de este formato es que permite obtener código legible para las personas con nombres y valores que funcionan como indicadores de la información que contienen.

[Sintaxis](#sintaxis)

[Donde se utliza](#donde-se-utiliza)

[Estructura](#estructura-del-json)

[Como abrir archivo JSON](#¿cómo-abrir-un-archivo-json)


## Sintaxis

La sintaxis de JSON funciona de modo similar a JavaScript. Por ejemplo:

* El arreglo de información se hace mediante claves (keys).

* La información se separa por comas.

* Las llaves agrupan objetos.

* Los corchetes agrupan arreglos de datos.

Sin embargo, JSON se distingue de JavaScript porque sus claves tienen que ser strings (o secuencias de caracteres), mientras que sus valores deben ser strings, números, objetos, arreglos, boleados o null.

## Donde se utiliza

Como hemos visto, los archivos JSON permiten obtener un código legible de almacenamiento y también son útiles para manipular la información de un programa a la hora de crear un software.

Originalmente, JSON era utilizado únicamente bajo la notación basada en objetos de JavaScript. Actualmente, debido a su popularidad, muchos lenguajes de programación son compatibles con el formato JSON.

Los archivos en este formato suelen tener la terminación **.json** y son especialmente provechosos para intercambiar o transferir información a lo largo de diferentes tipos de dispositivos digitales.

El caso más común de uso de JSON está en el diseño de sitios web. Al crear páginas en línea queremos asegurarnos de que el sitio lea correctamente la información contenida en el servidor y que la muestre de forma óptima. Además, es deseable que el programador pueda modificar el código durante la marcha para corregir errores.

Pero esta no es su única función. Por ejemplo, podemos emplear JSON para la creación de aplicaciones móviles y programas computacionales o incluso para la transferencia de documentos. Esta herramienta es tan versátil que podríamos asegurar que está prácticamente en todos lados.

## Estructura del JSON

Debido a que JSON es utilizado principalmente por desarrolladores de software, podría pensarse que estos archivos son muy complejos y tediosos. Pero en realidad son relativamente simples en comparación con otros métodos de administración de datos.

Veamos algunos ejemplos de cómo luce el código de estos archivos para diferentes tipos de información.

**Strings**

En JSON los strings siempre deben ir entre comillas dobles y la key debe ser una secuencia de caracteres:

``` json
{“Nombre”:“Juan”}Números
```
En el caso de los números, estos siempre deberán ser enteros o decimales:

 ``` json
{“Edad”:“30”}
 ```

**Objetos**

Por su parte, cuando asignamos objetos a un valor necesitamos emplear signos de llave para contener la información del conjunto. La información contenida debe mantener el mismo formato, lo que da una apariencia mucho más simple y limpia:

``` json
{“Empleado”:{“Nombre”:“Juan”, “Edad”:“30”, “Ciudad”:“Madrid”}}
 ```

**Booleanos**

Los valores booleanos se utilizan cuando la información solo puede ser verdadera (true) o falsa (false). Por ejemplo, cuando una venta ha sido concretada o se requiere autenticación:

``` json
{“Venta”:true}
```

Puedes leer mas informacion sobre ejemplos de Json en el siguiente enlace [Developer](https://developer.mozilla.org/es/docs/Learn/JavaScript/Objects/JSON)

## ¿Cómo abrir un archivo JSON? ##

Debido a que JSON está estructurado básicamente como un formato de texto (motivo por el que solo puedes trabajar con strings y números en él) únicamente necesitas un programa capaz de leer estos datos.

¿Estos programas son software especializado? Claro que no. Programas tan simples como el bloc de notas o un editor de textos son ideales para leer estos archivos. Veamos algunos de los más populares:

1. [Windows Notepad](https://apps.microsoft.com/detail/9MSMLRH6LZF3?hl=es-mx&gl=mx) :
Es un editor de texto muy simple creado por Windows especialmente para su propio software. Pero debido a la gran simplicidad de los archivos JSON, el Notepad de Windows no tendrá ningún problema para abrirlos ni editarlos.


1. [Notepad++](https://notepad-plus-plus.org/) : Otro programa realmente simple para visualizar y alterar código fuente es Notepad++. Esta herramienta se distingue del Windows Notepad porque es mucho más flexible para la edición. Debido a que el programa está optimizado para C++, puede procesar archivos JSON sin mayor complicación.


1. [Visual Studio Code](https://code.visualstudio.com/) : Una herramienta mucho más potente que las anteriores es Visual Studio Code. Este programa es un complejo editor de texto que interactúa con diferentes tipos de información y lenguajes de programación. Por ello es tan útil a la hora de abrir y editar archivos JSON.

![JSON](https://alexwebdevelop.com/wp-content/uploads/2018/03/json.jpg)
