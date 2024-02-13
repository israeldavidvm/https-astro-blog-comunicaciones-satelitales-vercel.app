---
title: 'PATRÓN DE RADIACION DE ANTENAS SATELITALES: HUELLAS'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Jul 15 2022'
heroImage: '/img/fig18-17.png'
---

El área que cubre un satélite en la Tierra depende de la localización del satélite en su órbita,frecuencia de portadora y la ganancia de su antena. 
Los técnicos de satélites seleccionan la antena y la frecuencia de portadora para determinado satélite, de modo que concentre la potencia limitada de transmisión en un área específica de la superficie terrestre. La representación geográfica del patrón de radiación de la antena de un satélite se llama huella, o a veces mapa de huella. En esencia, una huella de un satélite es la zona, sobre la superficie terrestre, desde donde el satélite puede recibir o hacia donde puede transmitir. La forma de la huella de un satélite depende de su trayectoria orbital, su altura y el tipo de antena que se use. 
Mientras más alto esté el satélite, podrá abarcar más superficie terrestre. En la fig. 18-17 se ve una huella típica de satélite.
![Orbita satelites](/img/fig18-17.png "orbitas satelites")

Las curvas de nivel representan límites de igual densidad de potencia recibida.
Las antenas satelitales de enlace de bajada emiten señales en frecuencias de microondas, hacia una región geográfica seleccionada, dentro de la línea de vista del satélite. La potencia efectiva transmitida se llama potencia irradiada efectiva isotrópica (EIRP, de effective isotropic radiated power) y se expresa, en general, en dBm o dBW. 
Se traza un mapa de huella dibujando lineas continuas entre todos los puntos que tengan EIRP iguales. Un mapa característico de huella es en esencia, una serie de curvas de nivel sobre un mapa geográfico de la región servida. Podríadistintos mapas de huella para cada haz de radiación de cada satélite de comunicaciones.
La figura de las curvas de nivel y los niveles de potencia de una huella quedan determinados por detalles precisos del diseño de la antena de enlace de bajada, al igual que por el valor de potencia de microondas generadas por cada canal de a bordo. 
Si bien cada transpondedor es un circuito electrónico físicamente separado, las señales de varios transpondedores se suelen enlazar de bajada a través de la misma antena. Como es de esperarse, los niveles de potencia de recepción son mayores en las áreas hacia las que apunta la mira de la antena de bajada, y más débiles fuera de esas áreas. 
Un plato de antena receptora cerca de la orilla del área de cobertura de un satélite debe ser mayor que los que estén en el centro o cerca del centro del mapa de huella. Son necesarias antenas de estación terrestre con diámetros extremadamente grandes para recibir emisiones satelitales en áreas geográficas a grandes distancias de la mira de la antena de enlace de bajada. 
En forma característica, hay variaciones en los mapas de huella de distintos satélites. Por ejemplo, el satélite europeo de banda Ku tiene en general distribuciones de radiación en huellas que son circularmente simétricas, con niveles que disminuyen en forma lineal en áreas progresivamente alejadas del centro de la mira del satélite. 
Los satélites estadounidenses de banda C suelen tener niveles de potencia relativamente planos sobre la región de cobertura, con bajadas bastante pronunciadas de potencia fuera de las orillas. Los satélites lanzados en fecha reciente, como el DBS-1 (de emisión directa) estadounidenses han empleado antenas más complicadas de conformación de haz, en el enlace de bajada, que permiten a los diseñadores conformar las huellas para llegar sólo a áreas específicas y, por lo mismo, no desperdician potencia en areas no planeadas.
Es posible diseñar antenas satelitales de enlace de bajada que puedan difundir señales de microondas para cubrir áreas sobre la Tierra cuyo tamaño va desde ciudades extremadamente pequeñas hasta a un 42% de la superficie terrestre. 
El tamaño, forma y orientación de estas antenas,potencia generada por cada transpondedor, determinan la cobertura geográfica y los EIRP. Las distribuciones de radiación de una antena satelital se suelen caracterizar como localizados,zonales, hemisféricas o globales. Estas distribuciones de radiación se muestran en la fig. 18-18.

![Orbita satelites](/img/fig18-18.png "orbitas satelites")


# Haces locales y zonales
Los haces más pequeños son los haces localizados, y les siguen los haces zonales. Los localizados concentran su potencia en áreas geográficas muy pequeñas y, en consecuencia, suelen EIRP mayores que los que abarcan áreas mucho mayores, porque determinada potencia de salida se puede concentrar más. 
Los haces localizados y los zonales cubren menos del 10% de lacie terrestre. Mientras mayor sea la frecuencia del enlace de bajada, un haz puede ser enfocado con más facilidad hacia una zona más pequeña. 
Por ejemplo, la nueva generación de satélites de alta potencia de banda Ku puede tener varios haces localizados que mandan las mismas frecuencias, transmitiendo distintas señales a áreas dentro de determinado país. En general, la mayor parte huellas de banda Ku no cubren áreas continentales completas y tienen cobertura geográfica mas limitada que sus contrapartes de banda C. Por lo anterior, es importante tener un conocimiento detallado de la EIRP local, para tratar de recibir emisiones de satélites de banda Ku.
# Haces hemisféricos
Las antenas de enlace descendente hemisférico abarcan en forma característica hasta ella superficie terrestre y, por consiguiente, tienen EIRP 3 dB o 50% menores que las transmiti-das por haces localizados que abarcan el 10% de la superficie terrestre.
# Haces globales
Las distribuciones de radiación de las antenas de cobertura mundial o global tienen unaproximado de banda de 17°, y son capaces de abarcar hasta un 42% de la superficie terrestre, que es la visual máxima de cualquier satélite geosíncrono. Los niveles de potencia son menores en los haces globales que en los localizados, zonales o hemisféricos, y son necesarios grandes platos receptores para detectar en forma adecuada emisiones de video, audio y datos
# Reuso
Cuando se llena una banda asignada de frecuencias, se puede obtener una capacidad adicional reusando el espectro de frecuencias. Si se aumenta el tamaño de una antena (es decir, si aumenta la ganancia de la antena), también se reduce su ancho de banda. Así, se pueden dirigir distintos haces de la misma frecuencia a distintas áreas geográficas de la Tierra. A esto se le llama reuso de frecuencia. Otro método de reuso de frecuencia es la polarización dual. Se transmiten distintas señales de información hacia distintos receptores en Tierra usando la misma banda de frecuencias, tan sólo con orientar sus polarizaciones electromagnéticas ortogonalmente desfasadas 90°). La polarización dual es menos efectiva, porque la atmósfera terrestre tiene una tendencia a reorientar, o repolarizar, una onda electromagnética que pase por ella. El reuso es más que otro modo de aumentar la capacidad de un ancho limitado de banda. 

Autor: Israel David Villarroel Moreno
