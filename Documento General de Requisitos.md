<h1>Cuidea</h1>
<h4>Grupo 4</h4>

- - -

<h3>Índice<h4/>

- [1. Introducción](#1-introducción)
  - [1.1 Objetivos](#11-objetivos)
  - [1.2 Alcance](#12-alcance)
  - [1.3 Definiciones, acrónimos y abreviaturas](#13-definiciones-acrónimos-y-abreviaturas)
  - [1.4 Resumen](#14-resumen)
- [2 Directivas del proyecto](#2-directivas-del-proyecto)
  - [2.1 Descripción del problema](#21-descripción-del-problema)
  - [2.2 Descripción del producto](#22-descripción-del-producto)
  - [2.3 Perfiles de usuarios](#23-perfiles-de-usuarios)
  - [2.4 Alternativas y competencia](#24-alternativas-y-competencia)
- [3 Visión general del producto](#3-visión-general-del-producto)
  - [3.1 Entorno de despliegue](#31-entorno-de-despliegue)
  - [3.2 Resumen de características](#32-resumen-de-características)
  - [3.3 Precio y coste](#33-precio-y-coste)
  - [3.4 Licencias e instalación](#34-licencias-e-instalación)
- [4 Requisitos funcionales](#4-requisitos-funcionales)

## 1. Introducción

### 1.1 Objetivos

El objetivo de este documento es recoger, analizar y definir las características y necesidades de alto nivel del sistema Cuidea. Se centrará en describir las expectativas de cada una de las partes del proyecto y de los usuarios finales y por qué estas necesidades existen. Los detalles de cómo Cuidea cumple estas necesidades se detallan en los casos de uso y en las especificaciones adicionales.

### 1.2 Alcance

El documento está relacionado con el sector servicios ya que el principal objetivo es comunicar a personas que necesitan servicios (demandantes) con personas que ofrecen distintos servicios (ofertantes). Por lo tanto, para poder facilitar esta comunicación es necesario el desarrollo de un proyecto software.
Hay que destacar que está enmarcado en el contexto del Grupo de Desarrolladores de la Universidad de Málaga. Concretamente este grupo está organizado por el Consejo de Estudiantes de la Escuela de Informática de la Universidad de Málaga, si bien participan personas de otros grados que no están relacionados con la informática

### 1.3 Definiciones, acrónimos y abreviaturas

**Flutter:** es un SDK para desarrollo de aplicaciones móviles creado por Google. Suele usarse para desarrollar interfaces de usuario para aplicaciones en Android, iOS y Web.
**Firebase:** es una plataforma para el desarrollo de aplicaciones web y aplicaciones móviles desarrollada por Google, que proporciona una gran cantidad de utilidades tales como autenticación con redes sociales, base de datos a tiempo real, y otras muchas funcionalidades.
**IOS:** es un sistema operativo móvil desarrollado por Apple, presente en Iphone, Ipad y otros productos de Apple.
**UMA:** Universidad de Málaga.
**Figma:** es un editor de gráficos vectoriales enfocado principalmente al diseño y prototipado de páginas web.

### 1.4 Resumen

Este documento se encuentra estructurado según como se explica en el índice. El punto 2 define el problema que se presenta, así como la solución que planteamos. En el apartado 3 se describen los participantes y los usuarios propios del proyecto. La sección 4 cubre el funcionamiento y las características de la aplicación. El apartado 5 describe todos los requisitos funcionales del proyecto. El punto 6 trata acerca de la preferencia y la prioridad que se establecerá en el proyecto. La sección 7 cubre todo lo relacionado con los requisitos no funcionales. En el apartado 8 se describe el dominio en el que se encontrará la aplicación.

## 2 Directivas del proyecto

### 2.1 Descripción del problema

Actualmente, España es uno de los países con una población más envejecida de toda Europa. Es por ello, que las nuevas generaciones  necesitan, cada vez más,  de la ayuda de otras personas para cuidar a sus mayores. Cuidea nace con la idea de solventar este problema y proporcionar a los jóvenes una plataforma que les permita encontrar profesionales en el sector que puedan ofrecer cualquier tipo de servicios relacionados con la atención y cuidados de personas de tercera edad.
Además, cada vez es más complicado conciliar el trabajo con el cuidado de los más pequeños de la casa, y de personas dependientes. Cuidea surge también con el fin de tratar en la medida de lo posible solventar este problema.

### 2.2 Descripción del producto

Para aquellas personas que por motivos de trabajo y falta de tiempo no pueden cuidar de sus mayores, hijos o personas dependientes. Cuidea les ofrece una aplicación móvil, en un principio para Android, y en un futuro para IOS.
Dicha aplicación consta de una interfaz simple e intuitiva, en la cual profesionales del sector podrán publicitar sus servicios, filtrado por intereses, campos especializados, ubicación donde podría llevar acabo los servicios...
Por parte del cliente, podrá filtrar sus preferencias, al igual que revisar comentarios de los servicios escritos por otros clientes.

### 2.3 Perfiles de usuarios

Podemos disitnguir dos perfiles de usuarios:
**1. Cuidador:** este perfil está diseñado para aquellas personas que usan cuidea para ofertar sus servicios. Podrá gestionar su perfil incluyendo en el su curriculum y referencias, así como reseñas de aquellos que ya han recurrido a sus servicios.
**2. Solicitante:** orientado a quien necesita de un cuidador. En su perfil podrá indiciar que tipo de cuidado precisa asi como el horario, si es ocasional o a largo plazo, y demás características del servicio que necesita.

### 2.4 Alternativas y competencia

En competencia a nuestro proyecto, podemos encontrar muchas apps enfocadas al cuidado o servicios, sin embargo señalaremos las siguientes ya que parecen ser bastante conocidas:
**1. Webel:** es una aplicación de servicios a domicilio. Dispone de diferentes servicios ofertados por profesionales que puedes contratar de manera sencilla, rápida y segura.
**2. Yocuido:** es una aplicación que ofrece servicios domésticos o de cuidados sociosanitarios. En ella podrás encontrar servicios según el punto geográfico donde te encuentres, tu disponibilidad horaria y todo esto de manera rápida y eficaz.
**3. Confio:** es una plataforma que pone en contacto a usuarios con ofertantes de servicios de manera rápida y eficaz. Lo destacable de esta aplicación es que los ofertantes o profesionales, tienen la posibilidad de pasar por un proceso de selección donde se les hace una entrevista y se comprueban sus referencias.
También tienen diferentes planes para los usuarios, en el que pagando conseguirá las ofertas de más calidad e incluso asistencia telefónica; e incluso ofrecen formación.
**4. Workuu:** es un buscador y recomendador de servicios locales. Los usuarios de una forma rápida y sencilla encuentran los servicios más cercanos y mejor valorados y de cualquier tipo.

Hay que tener en cuenta que todas estas aplicaciones están disponibles para Android, IOS y página web.

## 3 Visión general del producto

### 3.1 Entorno de despliegue

Inicialmente, *Cuidea* será una aplicación principalmente para dispositivos móviles, tanto Android como IOS, ya que se desarrollará con *Flutter*. Por otro lado, debido a la gran portabilidad de *Flutter*, la aplicación también estará disponible en la web, y será accesible fácilmente desde ordenadores. Cabe destacar que la aplicación se apoyará en un backend con *Firebase*, que proporcionará la base de datos y la autenticación.

### 3.2 Resumen de características

|Funcionalidad | Beneficio para el usuario|
|:----|:-----|
|Publicar tus servicios de cuidado de personas en diversas situaciones |Para el demandante el beneficio es encontrar a alguien que le ayuda a suplir una necesidad, cuidado de mayores, niños… Y para el ofertante el beneficio es dar a conocer sus servicios a gente interesada en ellos.|
|Una vez contratado los servicios de otro usuario, poder evaluar y dejar una opinión de tu experiencia |Para el demandante el beneficio es poder encontrar a alguien que ya haya sido valorado con anterioridad, haciendo que pueda elegir a quién contratar para un determinado servicio en base a las opiniones que otros usuarios tengan sobre él. En el caso del ofertante sirve para que si hace bien su trabajo, este pueda ser valorado positivamente y así que más gente quiera sus servicios, ya que alguien que busca un servicio preferirá a alguien con buenas valoraciones.|
| Preguntar tus dudas o conversar con otro usuario mediante un chat privado |Permite al usuario preguntar y/o resolver dudas en tiempo real, lo que hará que pueda tener un servicio “instantáneo” si así lo necesita.|
|Búsqueda personalizada de servicios según localización, necesidades, etc...|Permite al usuario poder filtrar mejor su búsqueda para así no tener que perder tiempo buscando entre anuncios de servicios que no le son relevantes.|

### 3.3 Precio y coste

Cuidea está pensada para que sea totalmente gratuita, y que sea un servicio disponible y accesible para todo el mundo. Por un lado, se podrá descargar gratuitamente desde la Google Play Store de Android o la App Store de IOS, y en el caso de poseer ordenador, se podrá acceder desde el navegador. Por otro lado, existirá una cuenta premium, con un coste de 5€/mes, con la que se obtendrán más privilegios de usuario, como por ejemplo, tener más prioridad y visibilidad en tus anuncios.
En cuanto al coste del proyecto, teniendo en cuenta que se desarrolla en el ámbito del Grupo de Desarrollo UMA, siendo este voluntario, y que el software utilizado es gratuito, el proyecto no conlleva ningún tipo de coste.

### 3.4 Licencias e instalación

Durante el desarrollo del proyecto siempre usaremos entornos de trabajo gratuitos, o software con licencias proporcionadas gratuitamente por la UMA.

-**Editores de código o IDE:** utilizaremos Visual Studio Code, IntelliJ IDEA o Android Studio, según las necesidades del momento y a elección del desarrollador.
-**Diseño de componentes, vistas e interfaces:** se utilizará Figma para estas funcionalidades, ya que nos proporciona la capacidad de trabajar colectivamente en un mismo proyecto, cada uno desde nuestro ordenador personal.
-**Diseño y esquematización de la base de datos:** se volverá a utilizar Figma en este ámbito, simplemente porque nos permite tener todos los diseños visuales de la aplicación en un mismo programa.
-**Persistencia del código y tareas:** se utilizará GitHub para la persistencia del código en un repositorio y para la asignación de tareas y discusión de problemas y dudas colectivas.
-**Reuniones y organización:** para la organización de reuniones y para comentar aspectos e información importante se utilizará Discord.

## 4 Requisitos funcionales

|ID |Nombre|Descripción|Precedencia|Prioridad|
|:----|:----|:----|:----|:----|
|0|Tutorial básico|Tutorial básico del uso de la aplicación (creación del usuario, navegación entre pantallas...)|Ninguna|Opcional|
|1|Sign Up|Crear una cuenta de Cuidea|Ninguna|Fundamental|
|2|Log in|Poder iniciar sesión con tus credenciales|1|Fundamental|
|3|Crear un Servicio|Publicar un post para ofrecer tus servicios|1 2|Fundamental|
|4|Contratación Servicio|Contratar los servicios de otro usuario|1 2|Fundamental|
|5|Review|Dejar una review de tu experiencia al contratar un servicio|1 2 4|Fundamental|
|6|Chat Privado|Crear un chat privado para consultar tus dudas a otro usuario|1 2|Opcional|
|7|Log in Google |Poder loguearte con tu cuenta de Google|Ninguna|Opcional|
|8|Eliminar un Servicio|Poder eliminar un servicio que estés ofreciendo|1 2 3|Fundamental|
|9|Editar un Servicio|Editar las características de un servicio que has creado anteriormente|1 2 3|Fundamental|
|10|Buscador de Servicios|Poder buscar un servicio que demandes|Ninguna|Fundamental|
|11|Búsqueda por localización|Acceder a la ubicación del dispositivo, para recomendar en función de la cercanía al mismo|10|Opcional|
|12|Búsqueda por precio|Poder filtrar la búsqueda mediante rangos de precio deseados|10|Opcional|
|13|Búsqueda por tipo de servicio|Poder filtrar la búsqueda en función del tipo de servicio que se oferta|10|Opcional|
|14|Buscador de Usuarios|Poder buscar a usuarios|Ninguna|Fundamental|
|15|Visualización de perfiles|Poder visualizar los perfiles de otros usuarios, como también los servicios que ofrecen|14|Fundamental|
|16|Tipo de usuario|En los perfiles de usuario se muestra la categoría del mismo, ya sea alguien que demanda u oferta un servicio|15|Opcional|
|17|Valoración ★|Si el usuario no quiere dejar una review escrita, puede opinar con  ★-★★★★★|1 2 4|Fundamental|
|18|Editar tu perfil|Poder editar tu perfil después de haber creado tu cuenta|1 2 |Fundamental|
|19|Métodos de pago|Elección del método de pago, Efectivo / Tarjeta Bancaria / ¿Bizum? / ¿Paypal?|1 2 4|Fundamental|
|20|Servicio de pagos online|Disponibilidad de un servicio de pago mediante tarjeta bancaria|1 2 4 19|Fundamental|
