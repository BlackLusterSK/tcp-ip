---
layout: default
title: Diseño de Protocolos de Red
nav_order: 11
permalink: /diseno-protocolos-red
---
##### **Autores:** 
{: .no_toc }
[Jimmy Morales](https://github.com/jimmymorales), [Herbert Dávila](https://github.com/hjdgua), [Santiago Wever](https://github.com/sweverG)

##### **Fecha de creación:** 
{: .no_toc }

##### **Revisiones:**  
{: .no_toc }

##### **Fecha de revisión:** 
{: .no_toc }

# Diseño de Protocolos de Red
{: .no_toc }

#### Contenido:
{: .no_toc }

1. TOC
{:toc}

---


## Resumen
There are two ways to add data in Firestore.

## Protocolos
El objetivo de las redes es lograr comunicar diferentes equipos entre sí, y las computadoras son dispositivos que tienen la capacidad de ejecutar múltiples procesos simultáneamente. ¿Cómo deben los hosts (equipos finales) ponerse de acuerdo para intercambiar mensajes?

Un protocolo es un conjunto de reglas que determina todos los aspectos de una comunicación. Son convenciones que permite que la comunicación entre dos hosts se de. Los protocolos pueden ser implementados tanto en hardware, software o una comunicación de ambos.

## Estandares y organizaciones
Internet Engineering Task Force (IETF):es el primer organismo de normas de Internet que desarrolla estándares  abiertos a través de procesos abiertos para hacer que Internet funcione  mejor

Institute of Electrical and Electronics Engineers(IEEE): es una asociación mundial de ingenieros dedicada a la normalización y el desarrollo en áreas técnicas

International Standards Organization (ISO): es una organización para la creación de estándares internacionales compuesta por diversas organizaciones nacionales de normalización.



## Arquitectura en capas
Es un diseño de una arquitectura de tipo cliente-servidor que se encuentra separada por capas, las cuales tienen definido sus funciones y la manera de que se comunicaran entre ellas.

La capa de presentación es la que muestra resultados, recibidos por medio de la capa de negocio, al usuario de una manera gráfica y/o entendible.

La capa de negocio es donde se ejecuta todas las "transacciones", como mostrar resultados a la capa de presentación y mandar a guardar datos a la capa de datos.

La capa de datos es en donde se encuentran todos los datos guardados y la capa de negocios le solicita accesar y/o guardar un dato.

La ventaja de este diseño es que se pueden detectar errores en algún módulo específico e implementar nuevos cambios al diseño no afecta todas las capas.

## Encapsulamiento
Create model object and add values to it and `save()` the model. After saving model **model id** and 
**model key** is attached with model object.


## Preguntas

### Pregunta 1
Create model object and add values to it and `save()` the model. After saving model **model id** and 
**model key** is attached with model object.

### Pregunta 2
Create model object and add values to it and `save()` the model. After saving model **model id** and 
**model key** is attached with model object.
