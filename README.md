# Análisis de viajes realizados por las principales compañías de taxis en Chicago para la empresa de viajes compartidos ZUBER

## Introducción
Zuber es una nueva empresa de viajes compartidos que se está lanzando en Chicago. Esta nueva modalidad de viajes compartidos se conoce como carpooling que consiste en compartir un auto de uso particular con varias personas que van a realizar el mismo trayecto, dividiendo los costos del viaje entre todos los pasajeros. El viaje tendrá una fecha y barrio específico de salida, y a su vez, una fecha y barrio específico de llegada.

Al ser una empresa relativamente nueva, Zuber está tratando de encontrar patrones en la información disponible sobre las preferencias de sus clientes y cómo ciertos factores externos pueden influir en los viajes. Para poder encontrar estos patrones, se va a analizar la información disponible sobre viajes de los competidores de diferentes agencias de taxis en Chicago.

Previamente se trabajó con bases de datos relaciones en SQL, que contenían información sobre cada viaje realizado por un taxi de cada compañía de la competencia, detallando la duración del viaje y los barrios de llegada o salida en noviembre de 2017. A su vez, se obtuvo información del clima en Chicago en la misma época a través de recursos en línea.

En base a estos datos, se creó un dataset con la información del número de viajes por compañía de taxis el 15 y 16 de Noviembre, y otro dataset con las condiciones climáticas y duración de viajes los días sábados desde Loop hasta el Aeropuerto Internacional O'Hare. A partir de los cuales se podrá establecer patrones en las preferencias de los clientes. También se analizará la información de un tercer dataset que contiene el promedio de viajes que terminaron en cada barrio de Chicago.

## Objetivos
Establecer los 10 barrios principales de Chicago en términos de finalización de viajes.
Establecer las empresas con el mayor número de viajes.
Determinar si el clima influye en la frecuencia de viajes en taxi.

## Hipótesis
La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare cambia los sábados lluviosos.
