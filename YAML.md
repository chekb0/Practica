#  _¿Qué es YAML?_

YAML es un lenguaje de serialización de datos que las personas pueden comprender y suele utilizarse en el diseño de archivos de configuración. Para algunas personas, YAML significa otro lenguaje de marcado más; para otras, es un acrónimo recursivo que quiere decir _"YAML no es un lenguaje de marcado"_, lo que enfatiza la idea de que se utiliza para los datos, no para los documentos.


Es un lenguaje de programación popular porque está diseñado para que sea fácil de leer y entender. También se puede utilizar junto con otros lenguajes de programación. Gracias a la flexibilidad y la accesibilidad que caracterizan a YAML, [Ansible®](https://www.redhat.com/es/technologies/management/ansible/content-tools) lo utiliza para crear procesos de automatización en forma de playbooks de Ansible.

---


## Sintaxis de YAML

YAML utiliza una extensión de archivos .yml o .yaml y sigue reglas de sintaxis específicas.

Tiene características que provienen de Perl, C, XML, HTML y otros lenguajes de programación. También se basa en JSON, por lo que los archivos JSON son compatibles con YAML.

No hay símbolos de formato habituales, como llaves, corchetes, etiquetas de cierre o comillas, y los archivos son más sencillos para su lectura, ya que utilizan la sangría al estilo Python para determinar la estructura e indicar la incorporación de un elemento de código dentro de otro. Está diseñado para que no se admitan los caracteres de tabulación y así se mantenga la portabilidad en todos los sistemas, por lo que se usan los espacios en blanco, que son los caracteres de espacio.

Los comentarios se pueden definir con una almohadilla o símbolo numeral (#) y su uso es una práctica recomendada, ya que describen la intención del código. YAML no es compatible con los comentarios que tienen varias líneas, por lo cual el carácter de almohadilla se debe utilizar como sufijo de cada una.

La duda más común entre los principiantes es qué significan los tres guiones (---). Se utilizan para señalar el inicio de un documento mientras que cada uno termina con tres puntos (…).

Este es un ejemplo muy básico de un archivo YAML:

``` yaml
 #Comentario: esta es una lista de supermercado que utiliza YAML #Nota - el carácter representa la lista --- comida: - vegetales: tomates #primer elemento de la lista - frutas: #segundo elemento de la lista cítricos: naranjas tropicales: bananas nueces: maní dulces: pasas
 ```

[Consulte la página YAML for beginners](https://www.redhat.com/sysadmin/yaml-beginners)

## Los usos de YAML

Uno de los usos más comunes es la creación de archivos de configuración. Se recomienda utilizar YAML en lugar de JSON para escribir los archivos de configuración porque es un lenguaje más fácil de comprender, aunque ambos pueden usarse de manera indistinta en la mayoría de los casos.

Además de Ansible, hay otros elementos que utilizan YAML, como las implementaciones y los recursos de Kubernetes.

Una de las ventajas de utilizarlo es que se pueden agregar los archivos a un control de versiones, como Github, para rastrear y auditar los cambios.

## Ventajas y desventajas

A continuacion vamos a destacar las principales ventajas y desventajas del uso de YAML:

| Ventajas | | Desventajas|
 | --- | --- | --- |
 | Legibilidad humana |  | Sensibilidad a la sangría|
 | Sintaxis minimalista |  | Complejidad con datos binarios |
 | Facilidad de uso en configuraciones |  | Limitaciones en expresiones condicionales |
 | Soporte multiplataforma |  | Falta de esquemas formales |
 | Extensibilidad |  | Escaso soporte para comentarios |

 ### Comparacion de YAML con JSON y XML

 ![Comparacion](https://ipcisco.com/wp-content/uploads/2020/05/json-versus-xml-versus-yaml-1.jpg)



