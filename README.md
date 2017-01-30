# DES

Repositorio creado para la asignatura Desarrollo y Evaluación de Sistemas Software Interactivos del máster en Ingeniería Informática que se imparte en la Escuela Técnica Superior de Ingenierías Informática y de Telecomunicación.

## Introducción


GoPark es el nombre que se le ha dado al sistema software que vamos a desarrollar como proyecto para la asignatura Desarrollo y Evaluación de Sistemas Software Interactivos.  De entre todas las ideas que han surgido durante el proceso de Brainstorming finalmente hemos seleccionado la que se presenta en este documento por ser la más creativa, innovadora, funcional y muy útil ya que resuelve el gran problema que supone en ciertas ocasiones aparcar en una determinada zona ya sea por el bullicio o el desconocimiento del lugar entre otros. 
Cabe mencionar que la metodología que se va a usar en el desarrollo de esta aplicación va a ser centrada en el usuario.

## Descripción

GoPark (Ve y aparca), se trata de una aplicación web y una aplicación dirigida a dispositivos móviles las cuales tendrán como principal funcionalidad mostrar en tiempo real los aparcamientos libres de diversos parkings que se encuentran en la zona o en las cercanías en la que el usuario de la aplicación desee ir. 

Tras conocer el parking al que el usuario se va a dirigir, la aplicación irá indicando la ruta más cercana y óptima al parking hasta llegar a él. 
Además, llevará a cabo un análisis de todos lo datos almacenados hasta la fecha con el fin de proponerle al usuario una predicción lo más fiable posible de la disponibilidad del parking en el momento en el que vaya a necesitarlo.

Los datos obtenidos podrán ser finalmente analizados para su explotación por las administraciones públicas las cuales podrán realizar los reajustes que se crean convenientes en las instalaciones basándose en el uso de unos y otros parkings.

Esta aplicación estará disponible tanto en aplicación Web cómo en aplicación móvil y permitirá el pago de del ticket del parking remotamente desde nuestro dispositivo.

## Descripción de la solución.

GoPark es una aplicación web y móvil que se encargará de proporcionar al usuario información de los parkings que tiene a su alrededor, indicando no sólo la ruta más cercana, sino también le proporcionará información sobre la disponibilidad de aparcamiento en ellos.

El funcionamiento de la aplicación se basa en mostrar en tiempo real los plazas libres de diversos parking de la ciudad a través de un mapa. Una vez seleccionado el parking al que irá, el usuario lo selecciona y así se le indicará la ruta más cercana para llegar a él, indicando también la disponibilidad de plazas libres.

Para la consulta de disponibilidad de plazas libres, se realizará un análisis de todos los datos almacenados hasta la fecha, y así proporcionarle al usuario una predicción lo más fiable posible de la disponibilidad del parking en el momento en el que vaya a necesitarlo. Estos datos podrán ser analizados para su explotación por las administraciones públicas, y así disminuir los colapsos en algunas vías de la ciudad, proporcionando información útil a nivel estratégico para la gestión de los parking.
Como comentamos al inicio, esta aplicación estará disponible tanto en aplicación Web cómo en aplicación móvil, y permitirá el pago del ticket del parking remotamente.

-[Mapa mental]()

![Mapa mental](https://github.com/STiago/DES/blob/master/Practicas/Practica1/mapa_mental.png)

-[Analisis de mercado](https://github.com/STiago/DES/blob/master/Practicas/Practica1/Practica1.pdf)

## Documento de vision

### 1.1. Propósito

Este documento proporciona una visión sobre el proyecto GoPark, desarrollado para todos los usuarios que necesiten estacionar su vehículo, ya sea en tiempo real o con antelación a estacionamientos futuros.
Pero no solamente va dirigido a los usuarios finales que como anteriormente se ha mencionado usarán la aplicación únicamente con la finalidad de encontrar estacionamiento, sino que también va dirigida a las empresas que gestionan los parkings de la ciudad y al Ayuntamiento ya que estos pueden obtener numerosos beneficios de nuestra aplicación los cuales se van a desarrollar en los correspondientes apartados de este documento.
### 1.2. Alcance

Nuestro sistema software va a intentar tener el máximo alcance posible, ya que está orientado a un uso público, y el hecho de ser multiplataforma hace que aumente la accesibilidad de uso para el usuario.
Por otro lado, el alcance previsto no solo va dirigido a nivel de usuario particular. Nuestra intención con esta aplicación es también poner a disposición de administraciones  y parkings públicos los datos y así poder explotarlos para beneficio de ellos. Este hecho hace que el alcance de este software aumente y pueda abarcar un mayor número de visitas.
### 1.3. Definición, Acrónimos, y Abreviaciones

GoPark: Sistema software de apoyo al conductor para facilitar información de parkings públicos y disponibilidad de los mismos.
Stakeholder: Persona o grupo de ellas que intervendrán, directa o indirectamente, en el desarrollo de un proyecto y en la elaboración del producto final asociado al mismo.

### 1.4. Resumen

GoPark (Ve y aparca), consiste en una aplicación dirigida a dispositivos móviles la cual tendrán como principal funcionalidad mostrar en tiempo real los aparcamientos libres de diversos parkings que se encuentran en la zona o en las cercanías en la que el usuario de la aplicación desee ir.
Tras conocer el parking al que el usuario se va a dirigir, la aplicación irá indicando la ruta más cercana y óptima al parking hasta llegar a él.
Además, llevará a cabo un análisis de todos lo datos almacenados hasta la fecha con el fin de proponerle al usuario una predicción lo más fiable posible de la disponibilidad del parking en el momento en el que vaya a necesitarlo.
Los datos obtenidos podrán ser finalmente analizados para su explotación por las administraciones públicas las cuales podrán realizar los reajustes que se crean convenientes en las instalaciones basándose en el uso de unos y otros parkings.
Esta aplicación estará disponible para dispositivos móviles , además como extra, permitirá el pago de del ticket del parking remotamente desde nuestro dispositivo.


### 2.  Posicionamiento
### 2.1. Oportunidad de Negocio

En la actualidad existen numerosas aplicaciones destinadas al apoyo del ciudadano para buscar aparcamiento y así poder facilitar esta labor, en ocasiones tan complicada.
Con GoPark no solo queremos cumplir la misma labor que ya pueden realizar dichas aplicaciones, sino intentar ir más allá realizando los siguientes puntos a destacar:
Proporcionar al usuario una aplicación tanto web como móvil, facilitando el acceso a GoPark.
Informar al usuario de los parkings que tiene alrededor, evitando pérdidas de tiempo innecesarias.
Informar al usuario de las plazas libres que hay en cada uno de los parkings que tiene alrededor.
Indicarle que plazas libres se estima que habrá en el momento de su llegada.
Proporcionar datos a entidades públicas, y así favorecer la explotación de estos datos para futuras necesidades.

### 2.2. Declaración del Problema

El siguiente cuadro detalla el problema así como los afectados por este.

El problema de:

Eencontrar plaza de aparcamiento en parkings públicos, hecho que a menudo resulta frustrante para conductores, especialmente en grandes ciudades.

Afecta:

Personas que necesiten saber si existen plazas libres de aparcamiento en  parkings públicos , o bien turistas que no sepan donde se encuentran estos parkings en la ciudad visitada.

El impacto del problema es:

Debido al ritmo de vida actual en las grandes ciudades, donde el tráfico es muy abundante y el tiempo perdido en busca de aparcamientos es muy elevado, resulta imposible dejar nuestro vehículo en un lugar seguro y cerca de nuestro destino.

Una solución exitosa sería:

Contar con una aplicación que nos ayude a encontrar parkings públicos cercanos con disponibilidad de aparcamiento, de forma sencilla y con una buena funcionalidad.

### 2.3. Solución propuesta

Con el tedioso problema de encontrar estacionamiento libre en el centro de una ciudad de fondo, son varias las alternativas que hemos encontrado y que se proponen como solución, abarcando desde medidas innovadoras y creativas a mejoras y adaptaciones de los sistemas ya existentes. Las alternativas quedan principalmente agrupadas en tres partes externas interesadas; las personas, los negocios y las entidades públicas. 

Desde el punto de vista de las personas, mas de una vez se ha dado la situación de llegar a un parking después de varios minutos de búsqueda acompañados de un intenso tráfico y encontrarse con el cartel de que el parking está completo y no quedan plazas libres, lo que supone el esfuerzo de ir en busca de otro parking que puede tener una peor accesibilidad o que incluso se de el mismo caso al llegar. Es por eso que el conocer en tiempo real las plazas que están libres actualmente o tener una estimación previa en base una recopilación de datos sobre ese parking en ese dia y a esa misma hora, evita que se puedan dar este tipo de situaciones ya que el usuario sabe hacia donde debe de ir directamente sin correr el riesgo de equivocarse.

El documento de vision se encuentra para tratar a mas profundidad [aqui](https://github.com/STiago/DES/blob/master/Practicas/Practica2/Practica2/DocumentoVision.pdf)


## Escenarios y personajes

Se han realizado una serie de escenarios los cuales identifican a usuarios que daran usos a la aplicacion.
Los escenarios se encuentran en el siguiente [enlace](https://github.com/STiago/DES/blob/master/Practicas/Practica2/Practica2/PlantillaEscenarios.pdf)

Y los personajes [aquí](https://github.com/STiago/DES/blob/master/Practicas/Practica2/Practica2/PlantillaPersonajes.pdf)

## Iteraciones

A continuación se explica el diagrama de conceptos de la aplicacin movil y de la aplicación web con sus correspondientes diagramas de flujo, hta, mapas de flujo, bocetos y las evaluaciones heurísticas.

Consultar dicha información [aquí]()

## Cuestionario para usuarios e Informe de evaluación

A continuación se muestran las tareas realizadas de la última práctica:

-[Cuestionario de usuarios de la aplicacion web](https://github.com/STiago/DES/blob/master/Practicas/Practica4/Cuestionario_APP_WEB.pdf)

-[Informe de evaluación](https://github.com/STiago/DES/blob/master/Practicas/Practica4/Informe_de_evaluacion_APP_WEB.pdf)


DES (C) 2013 María Victoria Santiago Alcalá. This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details. You should have received a copy of the GNU General Public License along with this program. If not, see .

