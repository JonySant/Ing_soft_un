#JSON y XML
##Definición de JSON
corresponde a las siglas JavaScript Object Notation o Notación de Objetos de JavaScript, es un formato ligero de intercambio de datos, que resulta sencillo de leer y escribir, simple de interpretar y generar para las máquinas derivado del lenguaje de encriptación de JavaScript.

## Usos, ventajas, y desventajas
- Transferencia de datos entre sistemas

Una base de datos de sitio web tiene la dirección postal de un cliente, pero la dirección debe verificarse a través de una Interfaz de Programación de Aplicaciones para asegurarse de que es válida. Envío de los datos de dirección en formato JSON a la API de servicio de validación de direcciones.

- Configuración de datos para aplicaciones

Al desarrollar aplicaciones, cada aplicación necesita las credenciales para conectarse a una base de datos, así como una ruta de acceso de archivo log. Las credenciales y la ruta de acceso al archivo se pueden especificar en un archivo JSON.

- Simplificar modelos de datos complejos

JSON simplifica los documentos complejos hasta los componentes que se han identificado como significativos mediante la conversión del proceso de extracción de datos en un archivo JSON predecible y legible por humanos.

- Se usa en los servicios web REST.

Desventajas: 

- Dificil de entender a simple vista.

- No cuenta con una característica que posee XML: extensibilidad.

- Para la seguridad requiere de mecanismos externos como expresiones regulares

##Tipos de datos Jason
- Cadena
- Número
. Booleano
- Nulo
- Objeto
- Serie

## Ejemplo

Para una barra de menu en JSON se puede hacer:


	{
    "menu": {

        "id": "file",

        "value": "File",

        "popup": {

            "menuitem": [

                {
                    "value": "New", "onclick": "CreateNewDoc()"
                },{
                    "value": "Open", "onclick": "OpenDoc()"
                },{
                    "value": "Close", "onclick": "CloseDoc()"
                }
            ]
        }
    }
}

Ejemplo para crear una serie

	{

	"Influencers" :   [ 
	{

 	"name" : "Jaxon", 

 	"age" : 42, 

 	"Works At" : "Tech News"

	}

	{

 	"name" : "Miller", 

 	"age" : 35

 	"Works At" : "IT Day"

	}

	]
	
	}


Ejemplo 3


	{
    “pieza”: {
        “tipo”: “A”
        “nombre”: “Tornillo”,
        “descripcion”: “Cilindro mecánico con una cabeza utilizado en la fijación temporal de unas piezas con otras”,
        “caracteristica”: {
            “tipo”: “metal”
            “tamanyo”: 10
        },
        “vacio”: “”
     }
	}


##XML
También llamado "Lenguaje de Marcado Extensible" usado para para el diseño y el texto de sitios web que define un conjunto de reglas para la codificación de documentos usado en carios sitios.Tanto es así que hay sistemas destinados a ayudar en la definición de lenguajes basados ​​en XML. El lenguaje XML proporciona una plataforma para definir elementos para crear un formato y generar un lenguaje personalizado.

Un archivo XML se divide en dos partes: prolog y body. La parte prolog consiste en metadatos administrativos, como declaración XML, instrucción de procesamiento opcional, declaración de tipo de documento y comentarios. La parte del body se compone de dos partes: estructural y de contenido (presente en los textos simples).

##Ventajas de XML

- Separa datos de HTML
Si necesitas mostrar datos dinámicos en tu documento HTML, tendrias que dedicarle mucho trabajo cada vez que los datos cambien. Con el XML, los datos se pueden almacenar en archivos XML separados

- XML simplifica el intercambio de datos

El intercambio de datos como XML reduce en gran medida esta complejidad porque los datos pueden ser leídos por diferentes aplicaciones incompatibles.

- Simplifica el cambio de plataforma

La actualización a nuevos sistemas (plataformas de hardware o software) lleva mucho tiempo. Se deben convertir grandes cantidades de datos y los datos incompatibles a menudo se pierden. Los datos XML se almacenan en formato de texto. Esto facilita la expansión o actualización a nuevos sistemas de información, nuevas aplicaciones o nuevos navegadores sin pérdida de datos.

- Aumenta la disponibilidad de datos

Con el XML, tus datos pueden estar disponibles para todos los tipos de «máquinas de lectura».

- El XML se puede utilizar para crear nuevos idiomas de Internet

Algunos idiomas que se usan que fueron creados son:

- XHTML
- WSDL
- WAP y WML
- RSS (utilizado en noticias)
- RDF y OWL
- SMIL

##Desventajas

- Se trata de un formato muy complicado de trabajar por las personas.

- Es muy estricto, por lo que necesita un tiempo prolongado de procesamiento.

- Tener un simple error con el namespace ya es suficiente para invalidar todo el documento.

## Ejemplo

Para una barra de menu en JSON se puede hacer:
  
  	< menu id="file" value="File">
    <popup>

      <menuitem value="New" onclick="CreateNewDoc()" />

      <menuitem value="Open" onclick="OpenDoc()" />

      <menuitem value="Close" onclick="CloseDoc()" />
    </popup>
 	< /menu>

Ejemplo 2
Este es el mismo ejemplo 3 del codigo de JSON, pero en XML.

	<pieza tipo="A">
    <nombre>Tornillo</nombre>
    <descripcion>Cilindro mecanico con una cabeza utilizado en la fijación temporal de unas piezas con otras 
    </descripcion>
    <caracateristica>
        <tipo>metal</tipo>
        <tamanyo>10</tamanyo>
    </caracateristica>
    <vacio></vacio>
	</pieza>

Ejemplo 3
Codigo completo de un documento XML con tan solo dos items como contenido

	<?xml version="1.0" encoding="ISO-8859-1" ?>
	<rss version="2.0">

	<channel>

	<title>Titulo del Canal de RSS</title>

	<link>http://www.tudominio.com</link>
	
	<description>Descripción del canal de tu sitio</description>
	
	<language>es-ES</language>
	
	<image>

    <title>Título de la Imagen</title>
    <url>http://www.tudominio.com/logotipo-del-rss.png</url>
    <link>http://www.tudominio.com</link>
    <width>90</width>
    <height>36</height>
	
	</image>
	
	<item>

    <title>Titulo del primer artículo</title>
    <link>http://www.tudominio.com/ruta/articulo/primero.html</link>
    <description>
      Breve descripción del contenido de este artículo concreto. Puedes usar un
      par de líneas para crear esta descripción, aunque no hay ningún tope máximo.     </description>

	</item>

	<item>

    <title>Título de un segundo artículo</title>
    <link>http://www.tudominio.com/ruta/articulo/segundo.html</link>
    <description>
      Breve descripción del contenido del otro artículo. Puedes usar un
      par de líneas para crear esta descripción, aunque no hay ningún tope máximo.     </description>
	</item>

	</channel>
	</rss>

## Diferencias entre JSON y XML

Se muestra un cuadro comparativo para indicar las diferencias de los lenguajes entre JSON y XML:

| JSON| XML |
| ---------|:--------:|
| Fácil de procesar, no requiere de grandes procesos|Capacidad de crear mensajes más complejos|
|Se basa en una serie de pares de nombre y valor |Se basa en etiquetas, ya sean vacíos o no(abre con "<>" y cierra con "</>)" |
|Su estructura es dificil de entender a simple vista|Facilita la definición de estructuras complejas|
|Tarda menos en en procesar, es decir, trata de un formato que trabaja con una velocidad de procesamiento alta|Necesita un tiempo prolongado de procesamiento|

Referencias:

Oracle México. (2021). ¿Qué es JSON?. 20 de octubre de 2021, de Oracle Sitio web: https://www.oracle.com/mx/database/what-is-json/

Ivan. (2019). XML: ¿qué es y para qué sirve este lenguaje de marcado?. 20 de octubre de 2021, de rockcontent Sitio web: https://rockcontent.com/es/blog/que-es-xml/

XML vs JSON Servicio Web: Cuál es la mejor opción?. 20 de octubre de 2021, de Arnold Gutierrez Sitio web: https://www.arnoldgutierrez.com/xml-vs-json-servicio-web-cual-ellos-mejor-opcion/#:~:text=XML%20(Lenguaje%20de%20Marcado%20Extensible,un%20lenguaje%20de%20marcado%20familiar.&text=JSON%20(JavaScript%20Object%20Notation)%20es,lenguaje%20de%20encriptaci%C3%B3n%20de%20JavaScript.

Luis del Valle Hernández. XML y JSON: Intercambiar información. 20 de octubre de 2021, de Programarfacil Sitio web: https://programarfacil.com/blog/xml-y-json-intercambiar-informacion/

IMF. (2021). JSON y XML: las principales diferencias en lenguajes de programación. 21 de octubre de 2021, de Blog de tecnología Sitio web: https://blogs.imf-formacion.com/blog/tecnologia/json-y-xml-las-principales-diferencias-202102/

Ejemplo de archivo XML completo. 21 de octubre de 2021, de comocreartuweb Sitio web: https://comocreartuweb.com/promocion-de-webs/sindicar-contenidos/ejemplo-completo.html