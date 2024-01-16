# YAML

**YAML** es un **lenguaje de serialización** de datos que las personas pueden comprender y suele utilizarse en el diseño de **archivos de configuración**. Para algunas personas, YAML significa otro **lenguaje de marcado más**; para otras, es un acrónimo recursivo que quiere decir "_YAML no es un lenguaje de marcado_", lo que enfatiza la idea de que **se utiliza para los datos**, no para los documentos.
Es un lenguaje popular porque está diseñado para que sea **fácil de leer y entender**. También se puede utilizar junto con otros lenguajes de programación.

> Es un **lenguaje de serialización popular** porque está diseñado para que sea **fácil de leer y entender**. _También se puede utilizar junto con otros lenguajes de programación._

![Logo posible de YAML.](https://user-images.githubusercontent.com/965439/27257445-8791ea14-539c-11e7-8f5a-eec6cdfababa.png)

## Sintaxis de YAML

YAML utiliza una extensión de archivos .yml o .yaml y sigue reglas de sintaxis específicas. 

Tiene características que provienen de Perl, C, XML, HTML y otros lenguajes de programación. También se basa en JSON, por lo que los archivos JSON son compatibles con YAML.

No hay símbolos de formato habituales, como llaves, corchetes, etiquetas de cierre o comillas, y los archivos son más sencillos para su lectura, ya que utilizan la sangría al estilo Python para determinar la estructura e indicar la incorporación de un elemento de código dentro de otro. Está diseñado para que no se admitan los caracteres de tabulación y así se mantenga la portabilidad en todos los sistemas, por lo que se usan los espacios en blanco, que son los caracteres de espacio.

Los comentarios se pueden definir con una almohadilla o símbolo numeral (#) y su uso es una práctica recomendada, ya que describen la intención del código. YAML no es compatible con los comentarios que tienen varias líneas, por lo cual el carácter de almohadilla se debe utilizar como sufijo de cada una.

La duda más común entre los principiantes es qué significan los tres guiones (---). Se utilizan para señalar el inicio de un documento mientras que cada uno termina con tres puntos (…).  

**Este es un ejemplo muy básico de un archivo YAML:**

```
#Comentario: esta es una lista de supermercado que utiliza YAML #Nota - el carácter representa la lista --- comida: - vegetales: tomates #primer elemento de la lista - frutas: #segundo elemento de la lista cítricos: naranjas tropicales: bananas nueces: maní dulces: pasas
```
## Webgrafía

[¿Qué es YAML?](https://www.redhat.com/es/topics/automation/what-is-yaml)
