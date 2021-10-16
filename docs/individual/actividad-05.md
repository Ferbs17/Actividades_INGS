### Actividad 5

# JSON & XML

## Definiciones 

<div style="text-align: justify">
JSON significa Notación de objetos de JavaScript, este ayuda a intercambiar datos entre varias plataformas. Es fácil de leer y escribir. JSON se utiliza principalmente con JavaScript asíncrono (AJAX) y para desarrollar servicios web RESTful. También se puede utilizar con muchos lenguajes como Java, C, C ++, Python. La sintaxis de JSON es usar los pares de valores clave y los datos están separados por una coma
</div>
&nbsp;
<div style="text-align: justify">
XML significa Lenguaje de marcado extensible. Tiene una sintaxis basada en etiquetas que es muy similar a HTML, pero no es un reemplazo de HTML. HTML permite crear la estructura de la página web. XML es el propósito más general. La principal ventaja de XML es que permite a los programadores crear etiquetas por su cuenta. XML es una base de muchas tecnologías web. Algunos de ellos son XHTML, AJAX y Servicios Web.XML se puede leer tanto en el lado del cliente como en el lado del servidor. Puede ser utilizado en muchos idiomas. El programador puede usar XML con C #, Visual Basic, Python y JavaScript.
</div>
&nbsp;

## Características 

**XML**

- XML es un subconjunto de SGML que incorpora las tres características más importantes de este:
    - Extensibilidad 
    - Estructura
    - Validación
- Basado en texto.
- Orientado a los contenidos no presentación.
- Las etiquetas se definen para crear los documentos, no tienen un significado preestablecido.
- No es sustituto de HTML.
- No existe un visor genérico de XML
 &nbsp;

**JSON** 

- JSON es solo un formato de datos.
- Requiere usar comillas dobles para las cadenas y los nombres de propiedades. 
- Las comillas simples no son válidas.
- Una coma o dos puntos mal ubicados pueden producir que un archivo JSON no funcione. 
- Puede tomar la forma de cualquier tipo de datos que sea válido para ser incluido en un JSON, no solo arreglos u objetos. 
- En JSON solo las cadenas entre comillas pueden ser utilizadas como propiedades.
&nbsp;

## Usos

**JSON** se utiliza principalmente para transferir datos entre un servidor y un cliente. El archivo es básicamente una alternativa más simple y liviana al XML; Los desarrolladores usan JSON para trabajar con AJAX (JavaScript asíncrono y XML, por sus siglas en inglés). Estos formatos funcionan bien juntos para lograr la carga asincrónica de los datos almacenados, lo que significa que un sitio web puede actualizar su información sin actualizar la página.

Uno de los objetivos fundamentales de **XML** es permitir la posibilidad de intercambiar datos de forma estructurada entre diferentes sistemas. Al tratarse de un formato de texto plano y ser un lenguaje estandarizado, hace que esta transferencia sea muy ágil e independiente de la plataforma utilizada; XML permite guardar datos de forma estandarizada para luego poder ser tratados por multitud de lenguajes diferentes. 


&nbsp;

## Ventajas y Desventajas

**XML** 
 
 Ventajas:

- Tiene un formato estructurado y fácil de comprender.
- Separa radicalmente la información o el contenido de su presentación o formato.
- Está diseñado para ser utilizado en cualquier lenguaje o alfabeto.
- Su análisis sintáctico es fácil debido a las estrictas reglas que rigen la composición de un documento.
- Tiene soporte a cualquier tipo de datos.
- Se pueden definir estructuras complejas y reutilizables.
 
 Desventajas: 

- El formato es sumamente estricto.
- Lleva más tiempo procesarlo.
- Complejidad de analizador (parser).
- Un error en cualquier parte del formato puede hacer que todo el documento sea inválido.

**JSON** 
 
 Ventajas: 

- Es autodescriptivo y fácil de entender.
- Su sencillez le ha permitido posicionarse como alternativa a XML.
- Es más rápido en cualquier navegador.
- Es más fácil de leer que XML.
- Es más ligero (bytes) en las transmisiones.
- Velocidad de procesamiento alta.
- Puede ser entendido de forma nativa por los analizadores de JavaScript.

Desventajas:

- Algunos desarrolladores encuentran su escueta notación algo confusa.
- No cuenta con una característica que posee XML: extensibilidad.
- No soporta grandes cargas, solo datos comunes.
- Para la seguridad requiere de mecanismos externos como expresiones regulares.

&nbsp;

## Tabla comparativa 

| Caracteristica | JSON | XML |
| --- | --- | --- |
| TIPO | Meta-lenguaje | Lenguaje marcado |
| COMPLEJIDAD | Simple y fácil de leer | Complejo y estricto en sintaxis |
| ORIENTACIÓN | Orientado a datos | Orientado a documentos |
| ARRAYS  | Soporte de matrices | Soporta arreglos sencillos (vectores) | 
| EXTENSIÓN DE ARCHIVOS | .json | .xml |

**Similitudes**

- Ambos pueden ser utilizados para describir datos.
- Ambos se pueden utilizar para compartir datos.
- Ambos tienen cambios de plataforma de soporte.
- Ambos pueden ser utilizados por muchos lenguajes de programación.

&nbsp; 

## Ejemplos

<div style="text-align: justify">
El siguiente enlace abre dos ejemplos (1 de JSON y 1 de XML), solo imágenes; Para visualizar directamente los archivos vaya a la carpeta "actividad5"(ruta: "Ejemplos/actividad 5") donde se encontrarán los documentos fuente.  
</div>

[Ejemplos](http://127.0.0.1:8001/individual/Ejemplo5/ "Ejemplo de XML y JSON")

Enlace ejemplo 1 XML: <span style="color:blue">C:\Users\user\Desktop\Repositorios\ingsoft-actividades\Ejemplos\actividad 5\Ejem1_xml.xml </span>

Enlace ejemplo 2 XML: <span style="color:blue">
C:\Users\user\Desktop\Repositorios\ingsoft-actividades\Ejemplos\actividad 5\Ejem2_xml.xml </span>

Enlace ejemplo 3 XML:
<span style="color:blue"> C:\Users\user\Desktop\Repositorios\ingsoft-actividades\Ejemplos\actividad 5\Ejem3_xml.xml</span>.

Enlace ejemplo 1 JSON: <span style="color:blue">file:///C:/Users/user/Desktop/Repositorios/ingsoft-actividades/Ejemplos/actividad%205/Ejem1_json.html </span>

Enlace ejemplo 2 JSON: <span style="color:blue">file:///C:/Users/user/Desktop/Repositorios/ingsoft-actividades/Ejemplos/actividad%205/Ejem2_json.html</span>

Enlace ejemplo 3 JSON: <span style="color:blue">file:///C:/Users/user/Desktop/Repositorios/ingsoft-actividades/Ejemplos/actividad%205/Ejem3_json.html </span>


&nbsp;

## Referencias 

- *Barrera, A. (2019, 10 noviembre). JSON: ¿Qué es y para qué sirve? NextU LATAM. https://www.nextu.com/blog/que-es-json/*
- *Cueva Lovelle, J. M. (2005). XML: eXtensible Markup Languaje [Diapositivas]. PDF, Lenguajes para internet. http://di002.edv.uniovi.es/~cueva/xml/xml.pdf*
- *Diferencia entre JSON y XML / Programación. (2014). La diferencia entre objetos y términos similares. https://es.sawakinome.com/articles/programming/difference-between-json-and-xml.html*


