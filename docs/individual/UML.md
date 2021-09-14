##UML
#Definición de UML
UML, por sus siglas en inglés, Unified Modeling Language: es el lenguaje de modelado de sistemas de software más conocido y utilizado en la actualidad. Es un lenguaje gráfico para visualizar, especificar, construir y documentar un sistema de software.

Es importante resaltar que UML es un "lenguaje" para especificar y no para describir métodos o procesos. Se utiliza para definir un sistema de software, para detallar los artefactos en el sistema y para documentar y construir. Otra forma de decirlo es que nos muestra como esta conformado el sistema de forma rapida en un diagrama donde cada simbolo tiene un significado. UML no puede compararse con la programación estructurada, pues UML significa (Lengua de Modelación Unificada), no es programación, solo se diagrama la realidad de una utilización en un requerimiento.

##Tipos de diagrama
Existen distintos tipos de diagramas como:

1. Diagrama de clases

2. Diagrama de objetos

3. Diagrama de casos de uso

4. Diagrama de secuencia

5. Diagrama de colaboración

6. Diagrama de estados

7. Diagrama de actividades

8. Diagrama de componentes

9. Diagrama de despliegue

Para cada uno de estos diagramas usa "Relaciones" para relacionar o conectar sus elementos estos son:

![Relaciones](/archivos/individual/actividad-04/relaciones.png)

##Ventajas
Algunas de la ventaja al usar este tipo de diagramas son:

* Tiempo reducido en la realización del proyecto.
* Visualización rápida del proyecto.
* Descripción del proyecto dinámica.
* Fácil entendimiento.
* Permite plantear proyectos de distintos tipos.

A continuación, se explicará tres tipos de diagrama:

#Diagrama de Objetos
El diagrama de objetos representa un conjunto de objetos y sus relaciones. Se utiliza para describir la estructura de datos.
Un objeto es una instancia de una clase en tiempo de ejecución. Por ejemplo, el vehículo con la placa de identificacion"xxx-xxx" es una instancia de clase general de autos (con un atributo placa de identificación). Los objetos se uyilizan muchas veces en el análisis para representar los numerosos artefactos e ítems que existen en cualquier negocio-papeles, faxes, información, etc.

##Elementos
Los elementos que usa este tipo de diagrama son:

![Elementos](/archivos/individual/actividad-04/elementos.png)

##Ejemplo

![Ejemplo](/archivos/individual/actividad-04/ejemplo.png)

En este ejemplo observamos que iniciamos con el elemento actor que representara al usuario y como interactuaría con un programa:

Lo primero que puede observar es la Pantalla principal con un reporte de notas dado con el elemento "límite" que nos índica que se detentra hasta no tener una instrucción y segun lo que presione el usuario es donde se dirigira el programa, puede salir o Generar un reporte (ambos con el elemento límite), si el usuario decidiera salir se obseva que se dirigira al elemento "control" que nos ayudara a finalizar el programa, sino ira a validar combos que también usa el elemento "control" y continuaria. El ultimo elemento que se ve en este ejemplo es el de la entidad que nos permite designar conceptos del mundo real con una existencia independient dentro de nuestro diagrama como los son: 
* Alumno
* Sección
* Asignatura
* Oferta Académica

#Diagrama de paquetes
Este tipo de diagramas muestra un conjunto de comportamiento y sus relaciones, es decir, se
utiliza para describir la vista de implementación estática de un sistema. Los simbolos que usa son los siguientes:

##Elementos

![Ejemplo](/archivos/individual/actividad-04/comp_elementos.png)

##Ejemplo:

![Ejemplo](/archivos/individual/actividad-04/comp_ejemplo.png)

En este ejemplo se observa que este está contenido en el elemento "Paquete" que es donde este contenido los elementos del diagrama e inicia la "interfaz" animacion.html donde de aqui baja al "componente" Animación disponible y de aqui se divide en otros elementos con la relación de dependencia, es decir que "Animación disponible depende de los otros elementos que lo rodean.

#Diagrama de Tiempo

Una línea de vida es la ruta que toma un objeto a lo largo de una medida de tiempo, como lo
indica el eje x.
Una línea de vida de estado sigue transiciones discretas entre estados, que se definen a lo largo
del eje y de la línea de tiempo. Cualquier transición tiene atributos opcionales de restricción de
tiempo, restricciones de duración y observaciones.

##Elementos

El diagrama de tiempos incluye los siguientes elementos: Líneas de vida, Estados, Restricciones de duración y Restricciones de tiempo.

![Ejemplo](/archivos/individual/actividad-04/com_ti.png)

##Ejemplo

![Ejemplo](/archivos/individual/actividad-04/ejemplo_ti.png)

Referencias:
-UML. 13 de septiembre de 2021, de Ecured Sitio web: https://www.ecured.cu/UML

Eslava G. (2020) Analisis y dIseño con UML. https://sea.acatlan.unam.mx/

Maria Eugenia Arevalo Lizardo. (2010). UML Modelado Dinámico: Diagramas de Distribución. 13 de septiembre de 2021, de - Sitio web: https://arevalomaria.wordpress.com/2010/12/02/uml-modelado-dinamico-diagramas-de-distribucion/