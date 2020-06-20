layout: default
title: Fragmentación
nav_order: 15
permalink: /fragmentacion
---
##### **Autores:**
José Manuel Hernández Castro

##### **Fecha de creación:**
Junio 19, 2020

##### **Revisiones: Sin revisión** 
{: .no_toc }

##### **Fecha de revisión: Sin fecha de revisión** 
{: .no_toc }

# Fragmentación
{: .no_toc }

#### Contenido:
{: .no_toc }

1. ¿Qué es Unicast?
2. ¿Qué es Multicast?
3. Unicast vs Multicast
{:toc}

---

## ¿Qué es Unicast?
Unicast es un tipo de transmisión en la que el envío de paquetes se produce desde un único emisor a un único receptor, sin importar si tiene lugar en ambas direcciones. Entonces, en los escenarios en los que exista un intercambio de información entre soló dos usuarios de la red, diremos que es **unicast**. La mayor parte del tráfico en el Internet, funciona por medio de unicast. Cuando un **Host A** quiere acceder a una página web, se produce una conexión **"cliente y el servidor"**. El envío de e-mails, en términos generales, también funciona mediante el uso de unicast. Otro ejemplo muy claro es la transferencia directa de archivos, como por ejemplo envío de un archivo por medio de FTP o la descarga de un archivo de un link.

![Unicast](Unicast.png)

## ¿Qué es Multicast?
Multicast es un método de transmisión y este esta diseñado para el envío de datagramas a un grupo específico de receptores. Cuando un grupo de hosts están interesados en recibir un mismo flujo de tráfico (por ejemplo, streaming de video o música), el mismo puede ser enviado en una única transmisión de datagramas, que se replicará en los routers más cercanos al destino para armar un árbol de distribución. La ventaja principal de este mecanismo es que permite un gran ahorro de los recursos de red, y además mejora la transmisión del contenido multimedia.

![Multicast](Mutlicast.jpg)