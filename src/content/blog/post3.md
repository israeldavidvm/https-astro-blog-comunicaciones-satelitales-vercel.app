---
title: 'ÁNGULOS VISUALES DE UNA ANTENA'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Jul 15 2022'
heroImage: '/img/fig18-9.png'
---

Para optimizar el funcionamiento de un sistema de comunicaciones por satélite, la dirección de ganancia máxima de una antena de estación terrestre (que a veces se llama la mira) se debe apuntar directamente al satélite. 
Para asegurar que esté alineada la antena de la estación terrestre,deben determinar dos ángulos: el azimut, y la elevación. El ángulo de azimut y el de elevación se llaman, en conjunto, ángulos de visual de la antena. Con los satélites geosíncronos, los ángulos de visual de las antenas terrestres sólo se deben ajustar una vez, porque el satélite permanece siempre en determinada posición, salvo pequeñas variaciones ocasionales.
La ubicación de un satélite se suele especificar en términos de latitud y longitud, en forma parecida a como se ubica un punto sobre la Tierra; sin embargo, como un satélite está en órbita a muchas millas sobre la superficie terrestre, no tiene latitud ni longitud. En consecuencia, su lugar se identifica con un punto en la superficie terrestre directamente abajo del satélite. Este punto se llama punto subsatelital (SSP, de subsatellite point), y para los satélites geosíncronos SSP debe caer en el ecuador. Estos puntos subsatelitales, y las ubicaciones de las estaciones terrestres se especifican con coordenadas normales de latitud y longitud. La convención normal especifica los ángulos de longitud entre 0° y 180° al este o al oeste del meridiano de Greenwich.
Las latitudes del Hemisferio Norte son ángulos de 0° a 90° N, y las del Hemisferio Sur son de 0° a 90° S. Como los satélites geosíncronos están directamente arriba del ecuador, todos tienen latitud 0°. Por consiguiente, las ubicaciones de los satélites geosíncronos se suelen especificar en grados de longitud al este o al oeste del meridiano de Greenwich, por ejemplo, 122° Oeste 78° E.   
La fig. 18-9 muestra la posición de un vehículo satelital geosíncrono hipotético (GSV, de geosynchronous satellite vehicle, su respectivo punto subsatelital (SSP) y una estación terrestre (ES) arbitraria, todos ellos con relación al geocentro. El SSP del satélite de la fig. 18-9 es 30°de longitud y 0° de latitud. La estación terrestre tiene una ubicación de 30° O de longitud20° N de latitud.

![Orbita satelites](/img/fig18-9.png "orbitas satelites")

# Ángulo de elevación
El ángulo de elevación es el ángulo vertical que se forma entre la dirección de movimiento de una onda electromagnética irradiada por una antena de estación terrestre que apunta directa- mente hacia un satélite, y el plano horizontal. Mientras menor es el ángulo de elevación, la distancia que debe recorrer una onda propagada a través de la atmósfera terrestre es mayor.
Como en el caso de cualquier onda propagada por la atmósfera terrestre, sufre absorción,también se puede contaminar mucho con ruido. En consecuencia, si el ángulo de elevación es muy pequeño y la distancia que la onda viaja por la atmósfera terrestre es demasiado grande, la onda se puede deteriorar hasta el grado de ya no proporcionar una calidad aceptable de transmisión. 
En general, se considera que 5° es el ángulo de elevación mínimo aceptable. 

![Orbita satelites](/img/fig18-10.png "orbitas satelites")

La fig. 8-10 muestra la manera en que el ángulo de elevación afecta la intensidad de señal de una onda electromagnética propagada, debido a la absorción atmosférica normal, la cual causada por la niebla espesa y la lluvia intensa. Se puede ver que la banda de 14/12 GHz defig. 18-10b se afecta más que la banda de 6/4 GHz de la fig. 18-10a, debido a las menores longitudes de onda asociadas con las mayores frecuencias. También se ve en la figura que en ángulos de elevación menores que 5°, la cantidad de potencia de señal perdida aumenta mucho. 

La fig. 18-11a ilustra el ángulo de elevación de una antena de estación terrestre con respectoun plano horizontal.

![Orbita satelites](/img/fig18-11.png "orbitas satelites")


# Ángulo de azimut
El azimut es la distancia angular horizontal a una dirección de referencia, que puede ser el punto sur o el norte del horizonte. El ángulo de azimut se define como el ángulo horizontal de apuntamiento de una antena de estación terrestre. Para fines de navegación, el ángulo de azimut se suele medir en grados a partir del norte verdadero, en el sentido de las manecillas del reloj. Sin embargo, para las estaciones terrestres del Hemisferio Norte con satélites en órbitas geosíncronas, la referencia en general del ángulo de azimut es la dirección del sur verdadero (es decir, 180°). 
La fig. 18-11b muestra el ángulo de azimut referido a la dirección norte (0°) y a la direc- ción sur (180°), y la fig. 18-11c muestra los ángulos de elevación y de azimut de una antena de estación terrestre que apunta a un satélite.
Los ángulos de elevación y de azimut dependen de la latitud y la longitud de la estación terrestre, y del satélite en órbita. Para un satélite geosíncrono en una órbita ecuatorial, el proce- dimiento para determinar los ángulos de elevación y de azimut es el siguiente: en un buen ma- pa, determinar la longitud y la latitud de la estación terrestre.

# Calcular la diferencia, en grados ( L), entre la longitud del satélite y la de la estación terrestre.
Con la tabla 18-1 determinar la longitud del satélite de interés.

![Orbita satelites](/img/tab18-1.png "orbitas satelites")


Calcular la diferencia, en grados ( L), entre la longitud del satélite y la de la estación terrestre. A continuación, con la fig. 18-12, determinar el ángulo  azimut, y con la fig. 18-13 determinar el ángulo de elevación. Las figs. 18-12 y 18-13 son para satélites geosíncronos en órbitas ecuatoriales.

![Orbita satelites](/img/fig18-12.png "orbitas satelites")


![Orbita satelites](/img/fig18-eje-1.png "orbitas satelites")


# Límites de visibilidad
Para una estación terrestre en determinado local, la curvatura de la Tierra establece los límites de visibilidad, es decir, los límites de la línea de vista, que determina el máximo alejamiento del satélite que se puede ver en dirección este u oeste de la longitud de la estación. Teóricamente se alcanza la distancia máxima de línea de vista cuando la antena de la estación terrestreta en el plano horizontal (ángulo de elevación cero). Sin embargo, en la práctica el ruido que capta de la Tierra, y la atenuación de la señal por la atmósfera terrestre con ángulo de elevación cero, son excesivos. Por consiguiente, se suele aceptar que 5° es el ángulo mínimo de elevación útil. Los límites de visibilidad dependen, en parte, de la elevación del satélite y de la latitud y longitud de la estación terrestre.

Autor: Israel David Villarroel Moreno
