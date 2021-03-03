# Especificación de requisitos 
## Del proyecto <project name>

Versión 0.1  
Generada por <author>  
<organización>  
<fecha creación>  

Índice
=================
* [Versiones](#versiones)
* 1 [Introducción](#1-introducción)
  * 1.1 [Objetivo del documento](#11-objetivo-del-documento)
  * 1.2 [Ámbito del proyecto](#12-ámbito-del-proyecto)
  * 1.3 [Definiciones, acrónimos y abreviaturas](#13-definiciones-acrónimos-y-abreviaturas)
  * 1.4 [Referencias](#14-referencias)
  * 1.5 [Resumen del documento](#15-resumen-del-documento)
* 2 [Vista general del producto](#2-vista-general-del-producto)
  * 2.1 [Perspectiva del producto](#21-perspectiva-del-producto)
  * 2.2 [Funciones del producto](#22-funciones-del-producto)
  * 2.3 [Restricciones del producto](#23-restricciones-del-producto)
  * 2.4 [Perfiles de usuario](#24-perfiles-de-usuario)
  * 2.5 [Suposiciones y dependencias](#25-suposiciones-y-dependencias)
* 3 [Interfaces externas](#3-interfaces-externas)
    * 3.1 [Interfaces con el Usuario](#31-interfaces-con-el-usuario)
    * 3.2 [Interfaces con el Hardware](#32-interfaces-con-el-hardware)
    * 3.3 [Interfaces con el Software](#33-interfaces-con-el-software)
* 4 [Requisitos](#4-requisitos)
  * 4.1 [Precedencia y prioridad](#41-precedencia-y-prioridad) 
  * 4.2 [Funcionales](#42-funcionales)
  * 4.3 [Calidad de Servicio](#43-calidad-de-servicio)
    * 4.3.1 [Rendimiento](#431-rendimiento)
    * 4.3.2 [Seguridad](#432-seguridad)
    * 4.3.3 [Fiabilidad](#433-fiabilidad)
    * 4.3.4 [Disponibilidad](#434-disponibilidad)
  * 4.4 [Normativas aplicables](#44-normativas-aplicables)
  * 4.5 [Diseño e implementación](#45-diseño-e-implementación)
    * 4.5.1 [Instalación](#451-instalación)
    * 4.5.2 [Distribución](#452-distribución)
    * 4.5.3 [Mantenimiento](#453-mantenimiento)
    * 4.5.4 [Reusabilidad](#454-reusabilidad)
    * 4.5.5 [Portabilidad](#455-portabilidad)
    * 4.5.6 [Coste](#456-coste)
    * 4.5.7 [Fecha de Entrega](#457-fecha-de-entrega)
* 5 [Verificación](#5-verificación)
* 6 [Apendices](#6-apendices) 
  
## Versiones
| Name | Date    | Reason For Changes  | Version   |
| ---- | ------- | ------------------- | --------- |
|      |         |                     |           |
|      |         |                     |           |
|      |         |                     |           |

## 1. Introducción
Esta sección debe proporcionar una visión general de todo el documento.

### 1.1 Objetivo del documento
Describa el propósito del SRS y su público objetivo.

### 1.2 Ámbito del proyecto
Identifique el producto cuyos requisitos de software se especifican en este documento, incluida la revisión o el número de versión actual. Explique qué hará el producto especificado en este SRS. No olvide señalar si este SRS describe solo una parte del sistema o un subsistema que será integrado en otro sistema. Proporcione una breve descripción del software que se especifica y su propósito, incluidos los beneficios, objetivos y metas relevantes. Relacione el software con los objetivos corporativos o las estrategias comerciales.

### 1.3 Definiciones, acrónimos y abreviaturas

### 1.4 Referencias
Enumere y enlace cualquier otro documento o dirección web a la que se refiera este SRS. Estos pueden incluir guías de estilo de la interfaz de usuario, contratos, estándares a seguir, especificaciones de requisitos del sistema, documentos de casos de uso o un documento de visión y alcance. Proporcione suficiente información para que el lector pueda acceder a una copia de cada referencia, incluido el título, autor, número de versión, fecha y fuente o ubicación.

### 1.5 Resumen del documento
Describa lo que contiene el resto del documento y cómo está organizado. Dependiendo del proyecto, algunas subsecciones de las secciones 2 y 3 serán eliminadas.

## 2. Vista general del producto
Esta sección debe describir los factores generales que afectan el producto que se va a generar y sus requisitos de usuario o negocio. Esta sección no establece requisitos de sistema. En cambio, proporciona la base para entender estos requisitos de sistema, los cuales serán definidos en la sección 3.

### 2.1 Perspectiva del producto
Describa el contexto (quién, cómo y para qué) y el origen del producto (el proyecto surge ...) que se especifica en este SRS. Por ejemplo, indique si este producto es continuación o extensión de una familia de productos, un reemplazo para ciertos sistemas existentes o un producto nuevo. Si el SRS define un componente de un sistema más grande, relacione los requisitos del sistema más grande con la funcionalidad de este software e identifique las interfaces entre los dos. Puede ser útil incluir un diagrama de bloques simple que muestre los componentes principales del sistema general, las interconexiones del subsistema y las interfaces externas.

### 2.2 Funciones del producto
Resuma las funciones principales que el producto debe realizar o debe permitir que el usuario realice. Los detalles se proporcionarán en la Sección 3, por lo que aquí solo se necesita un resumen de alto nivel (como una lista de los requisitos a nivel de usuario principales con un breve resumen de cada uno de ellos). Organice las funciones para que sean comprensibles para cualquier lector del SRS. Cómo extensión, un diagrama de casos de uso puede ayudar a entender esas funcionalidades.

### 2.3 Restricciones del producto
Esta subsección debe proporcionar una descripción general de cualquier otro elemento que limitará las opciones del desarrollador. Estos pueden incluir:

* Interfaces para usuarios, otras aplicaciones a usar (versiones mínimas) o limitaciones hardware.
* Restricciones de calidad de servicio.
* Cumplimiento de normas.
* Restricciones en torno al diseño o implementación.

### 2.4 Perfiles de usuario
Identifique los diversos perfiles de usuarios que usarán este producto. Los perfiles de usuario pueden diferenciarse según la frecuencia de uso, el subconjunto de funciones del producto utilizadas, la experiencia técnica, los niveles de seguridad o privilegio, el nivel educativo o la experiencia. Describa las características pertinentes de cada perfil de usuario. Ciertos requisitos pueden concernir solo a ciertos perfiles usuarios. Priorize los perfiles de usuarios de este producto para concer los requisitos que son más necesarios satisfacer.

Un actor en un caso de uso pertenecerá al menos a un perfil de usuario (podría englobar más). 

### 2.5 Suposiciones y dependencias
Enumere todos los factores asumidos que podrían afectar los requisitos establecidos en el SRS. Estos podrían incluir componentes comerciales o de terceros que planea utilizar, problemas relacionados con el entorno operativo o de desarrollo, o restricciones. El proyecto podría verse afectado si estos supuestos son incorrectos, no se comparten o cambian. Identifique también cualquier dependencia que el proyecto tenga de factores externos, como los componentes de software que pretende reutilizar de otro proyecto, a menos que ya estén documentados en otro lugar (por ejemplo, en el plan del proyecto).

### 3 Interfaces externas
Esta subsección define todas las interfaces de entrada y salida del sistema de software. Esta sección facilita la comprensión de los requisitos. Cada interfaz definida puede incluir el siguiente contenido:
* Nombre del artículo
* Fuente de entrada o destino de salida
* Rango válido, precisión y / o tolerancia
* Unidades de medida
* Sincronización
* Relaciones con otras entradas / salidas
* Formatos de pantalla / organización
* Formatos de ventana / organización
* Formatos de datos
* Formatos de comando
* Fin de mensajes

#### 3.1 Interfaces con el usuario 

Defina los componentes de software para los que se necesita una interfaz de usuario. Describa las características de cada interfaz entre el producto de software y los usuarios. Esto puede incluir imágenes de pantalla de muestra, cualquier estándar de GUI o guías de estilo de familia de productos que se deben seguir, restricciones de diseño de pantalla, botones y funciones estándar (por ejemplo, ayuda) que aparecerán en cada pantalla, métodos abreviados de teclado, estándares de visualización de mensajes de error y pronto. 

#### 3.2 Interfaces con el Hardware
Describa las características de cada interfaz entre el producto de software y los componentes de hardware del sistema. Esto puede incluir los tipos de dispositivos que deben ser compatibles, la naturaleza de los datos y las interacciones de control entre el software y el hardware, y los protocolos de comunicación que se utilizarán.

#### 3.3 Interfaces con el Software
Describa las conexiones entre este producto y otros componentes de software específicos (nombre y versión), incluidas bases de datos, sistemas operativos, herramientas, bibliotecas y componentes comerciales integrados. Identifique los elementos de datos o mensajes que entran y salen del sistema y describa el propósito de cada uno. Describa los servicios necesarios y la naturaleza de las comunicaciones. Consulte los documentos que describen los protocolos detallados de la interfaz de programación de aplicaciones. Identifique los datos que se compartirán entre los componentes de software. Si el mecanismo de intercambio de datos debe implementarse de una manera específica (por ejemplo, memoria compartida, ficheros, en la nube, etc), especifique esto como una restricción de implementación.


## 4. Requisitos
Esta sección especifica los requisitos del producto a nivel de sistema y desglosa estos en diferentes categorías. El conjunto de requisitos se debe validar y estos deben ser:
* Vigentes: Los requisitos reflejan las necesidades actuales de los usuarios del sistema, estos han podido cambiar con el tiempo, por tanto se debe revisar que sigen estando vigentes.
* Consistentes: Los requisitos no deben tener conflicto entre ellos. De tenerlo se puede establecer prioridades (obligatorio, deseable o opcional sería una opción).
* Completos: El conjunto de los requisitos define todas las funciones y restricciones deseadas por los stakeholders.
* Viables: Los requisitos pueden ser implementados dentro del presupuesto y tiempo planeado.
* Verificables: Los requisitos pueden ser comprobables (verificables) mediante tests.

Para cada requisito se debería especificar, su ID, nombre del requisito, descripción del requisito, dependencias, prioridad y justificación de su espeficación (stakeholder, derivado de un caso de uso, una interfaz necesaria, etc). Un estilo formateado facilitará la lectura. Podéis usar el siguiente formato(dependiendo de la sección se añadiran más o menos almohadillas para ponerlo en su subsección correspondiente):

### ID - Nombre del requisito
Descripción
#### Dependencias 
#### Prioridad
#### Justificación

### 4.1 Precedencia y prioridad
Esta sección está compuesta por una tabla que resumirá todos los requisitos especificados en las secciones siguientes. Se debe detallar un ID único, un nombre de requisito, su descripción, la prioridad de ese requisitos (es algo **Fundamental** a desarrollar; es **Deseable** tenerlo para que el cliente esté satisfecho; o es algo **Opcional** que estaría bien desarrollar si el tiempo lo permite), su precedencia (requisitos que deberán ser implementados antes) y el tipo (funcional o no funcional).

Esta tabla se generará en paralelo a las secciones correspondientes, y se completará cuando todas las secciones estén terminadas. Os recomiendo hacerla en excel e importarla en https://www.tablesgenerator.com/markdown_tables para generar la tabla en formato Markdown. Meter retornos de carro para que no se alarge mucho la tabla y usad la opción *_line break as <br>_* para que esos retornos de carro sean efectivos al copiarlos.


| Id 	| Nombre 	| Descripción 	| Priodidad 	| Precedencia 	| Tipo 	|
|:--:	|:----------------------------:	|:----------------------------------------------------------------------------------------------------------------------------------------------------------------:	|:-------------------:	|:-----------:	|-----------	|
| R3 	| Datos de clientes 	| El sistema deberá registar los datos de los clientes<br>para su posterior tratamiento. Estos incluirán su <br>nombre, DNI, fecha de nacimiento, género y e-mail. 	| <br>Fundamental<br> 	|  	| Funcional 	|
| R4 	| Modificar datos <br>clientes 	| El sistema permitirá modificar el e-mail del cliente. 	| Fundamental 	| R3 	| Funcional 	|
|  	|  	|  	|  	|  	|  	|
	


### 4.2 Funcionales
Esta sección especifica los requisitos funcionales de sistema que el futuro software debe tener en su entorno. Se aconseja inclur al final de esta subsección, tras describir los requisitos funcionales, un enlace al documento de casos de uso generado por magic draw para que el lector tenga una vista general de las funcionalidades del producto a generar.



### 4.3 Calidad de Servicio
Esta sección establece requisitos no funcionales relacionados con la calidad que deben presentar las funcionales del software.
 
#### 4.3.1 Rendimiento
Si existen requisitos no funcionales de rendimiento para el producto en varias circunstancias, indíquelos aquí y explique sus razones, para ayudar a los desarrolladores a comprender la intención y tomar las decisiones de diseño adecuadas. Especifique las restricciones de tiempo. Haga tales requisitos tan específicos como sea posible. Es posible que deba indicar los requisitos de rendimiento para requisitos funcionales o características individuales.

#### 4.3.2 Seguridad
Especifique los requisitos no funcionales relacionados con los problemas de seguridad o privacidad relacionados con el uso del producto. 
* Protección de los datos utilizados o creados por el producto.
* Requisitos de autenticación de identidad de usuario. 
* Políticas o regulaciones externas que contengan problemas de seguridad que afecten al producto. 
* Certificaciones de seguridad o privacidad que deben cumplirse.

#### 4.3.3 Fiabilidad
Especifique los requisitos no funcionales necesarios para establecer la fiabilidad requerida del sistema de software al momento de la entrega.

#### 4.3.4 Disponibilidad
Especifique los requisitos no funcionales necesarios para garantizar un nivel de disponibilidad definido para todo el sistema, tiempo mínimo disponible por día, máximos de reinicios permitidos por tiempo, etc.

### 4.4 Normativas aplicables
Especifique los requisitos no funcionales derivados de las normas o regulaciones existentes, que incluyen:
* Formato de informe
* Nombre de datos
* Procedimientos contables
* Seguimiento de auditoría

### 4.5 Diseño e implementación

#### 4.5.1 Instalación
Restricciones para garantizar que el futuro software se ejecutará sin problemas en la plataforma de implementación de destino.

#### 4.5.2 Distribución
Restricciones en los componentes de software para adaptarse a la estructura distribuida geográficamente de la organización en la que se va a instalar el software, la distribución de datos a procesar o la distribución de dispositivos a controlar.

#### 4.5.3 Mantenimiento
Especifique los atributos del software que se relacionan con la facilidad de mantenimiento del software en sí. Estos pueden incluir requisitos para cierta modularidad, interfaces o limitación de complejidad. Los requisitos no se deben colocar aquí solo porque son buenas prácticas de diseño.

#### 4.5.4 Reusabilidad
Software externo que deberá usarse.

#### 4.5.5 Portabilidad
Especifique los atributos del software que se relacionan con la facilidad de portar el software a otras máquinas host y / o sistemas operativos.

#### 4.5.6 Coste
Especifique las limitaciones en el costo del producto de software.

#### 4.5.7 Fecha de entrega
Especifique, si tiene, fecha de entrega del producto.

## 5. Verificación
Esta sección proporciona los enfoques y métodos de verificación planeados para calificar el software. Se recomienda que los elementos de información para verificación se proporcionen de manera paralela con los elementos de requisitos en la Sección 4. El propósito del proceso de verificación es proporcionar evidencia objetiva de que un sistema o elemento del sistema cumple con los requisitos y características especificados.


## 6. Apendices
### Apéndice A: Ejemplos de este documento relleno
Incluir y referenciar en el documento tantos apéndices como sea necesario. Los siguientes, son ejemplo de este documento (con algunas modificaciones), relleno:

[Ejemplo relleno en inglés 1](https://arxiv.org/pdf/1005.0330.pdf)
[Ejemplo relleno en inglés 2](http://www.cse.chalmers.se/~feldt/courses/reqeng/examples/srs_example_2010_group2.pdf)

### Apéndice B: Generar PDF usando un fichero MD
Hay multitud de herramientas online y offline, por ejemplo: https://www.markdowntopdf.com/
