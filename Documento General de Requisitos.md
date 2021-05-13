<h1>Cuidea</h1>
<h4>Grupo 4</h4>

- - -

<h3>Índice<h4/>

- [1. Introducción](#1-introducción)
  - [1.1 Objetivos](#11-objetivos)
  - [1.2 Alcance](#12-alcance)
  - [1.3 Definiciones, acrónimos y abreviaturas](#13-definiciones-acrónimos-y-abreviaturas)
  - [1.4 Referencias](#14-referencias)
  - [1.5 Resumen](#15-resumen)
- [2 Directivas del proyecto](#2-directivas-del-proyecto)
  - [2.1 Descripción del problema](#21-descripción-del-problema)
  - [2.2 Descripción del producto](#22-descripción-del-producto)
  - [2.3 Perfiles de usuarios](#23-perfiles-de-usuarios)
  - [2.4 Alternativas y competencia](#24-alternativas-y-competencia)
- [3 Visión general del producto](#3-visión-general-del-producto)
  - [3.1 Entorno de despliegue](#31-entorno-de-despliegue)
  - [3.2 Resumen de características](#32-resumen-de-características)
  - [3.3 Precio y coste](#34-precio-y-coste)
  - [3.4 Licencias e instalación](#35-licencias-e-instalación)
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

### 1.4 Referencias

### 1.5 Resumen
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

### 3.3 Precio y coste
Cuidea está pensada para que sea totalmente gratuita, y que sea un servicio disponible y accesible para todo el mundo. Por un lado, se podrá descargar gratuitamente desde la Google Play Store de Android o la App Store de IOS, y en el caso de poseer ordenador, se podrá acceder desde el navegador. Por otro lado, existirá una cuenta premium, con un coste de      ? €, con la que se obtendrán más privilegios de usuario, como por ejemplo, tener más prioridad y visibilidad en tus anuncios.
En cuanto al coste del proyecto, teniendo en cuenta que se desarrolla en el ámbito del Grupo de Desarrollo UMA, siendo este voluntario, y que el software utilizado es gratuito, el proyecto no conlleva ningún tipo de coste.

### 3.4 Licencias e instalación
Durante el desarrollo del proyecto siempre usaremos entornos de trabajo gratuitos, o software con licencias proporcionadas gratuitamente por la UMA.

-**Editores de código o IDE:** utilizaremos Visual Studio Code, IntelliJ IDEA o Android Studio, según las necesidades del momento y a elección del desarrollador.
-**Diseño de componentes, vistas e interfaces:** se utilizará Figma para estas funcionalidades, ya que nos proporciona la capacidad de trabajar colectivamente en un mismo proyecto, cada uno desde nuestro ordenador personal.
-**Diseño y esquematización de la base de datos:** se volverá a utilizar Figma en este ámbito, simplemente porque nos permite tener todos los diseños visuales de la aplicación en un mismo programa.
-**Persistencia del código y tareas:** se utilizará GitHub para la persistencia del código en un repositorio y para la asignación de tareas y discusión de problemas y dudas colectivas.
-**Reuniones y organización:** para la organización de reuniones y para comentar aspectos e información importante se utilizará Discord.

## 4 Requisitos funcionales

| ID  | Nombre | Descripción | Precedencia | Prioridad |
| --- | ------ | ----------- | ----------- | --------- |
|     |        |             |             |           |

<<<<<<< HEAD
=======

>>>>>>> afcaa4e3aaa99b52ec1a3751acc67123976cbd7c
