# Modelos de los sistemas de comunicaciones
* Emisor -- Medio (canal) --> Receptor 
* * El emisor y la fuente es el mismo. Ej. Comunicacion humana

* Fuente -> Emisor -- Medio --> Receptor -> Destinatario
* * El emisor es el encargado de codificar
* * El receptor es el encargado de decodificar

> A traves del medio se transmite un mensaje

Informacion =(Codificacion)=> Mensaje

## Codigo
* Emisor y Receptor lo comparten
* Debe tener una estructura definida
* Inequivoco (que no sea ambiguo)
* Relacion con el medio (canal)

> Hay codigos que son mas eficientes en ciertos tipos de medios (canales)

## Utilizacion de Sistemas de comunicacion
Depende por lo general de la necesidad y la eficiencia posible dentro del presupuesto permitido

## Interface
Conexion entre el emisor o receptor y el medio

> Fuente -> Emisor -[Interfaz]- Medio -[Interfaz]-> Receptor -> Destinatario

*Ejemplos:*
* Antena (Conexiones inalambricas)
* Led Infrarrojo (Control Remoto)
* Conector RJ45 (Ethernet)
* Conector BNC (Cable Coaxil)
* etc..

## Generacion de Señal
* Potencia (maximo transmitible/minimo perceptible)
* Ruido

## Sincronismo
Tanto el emisor como el receptor deben estar alerta en el mismo momento para lograr
una comunicación efectiva

* Sincronica
* * Clock compartido
* * Sincronismo Embebido (Ej. Cod Manchester)
* * c/Reloj Patron
* Asincronica
* * Bit de start/stop

## Manejo del intercambio de la informacion
Establecer una forma en la cual la informacion que yo envio de la fuente al receptor
sea interpretado de la forma correcta

## Deteccion y/o Correcion de Errores
*Ejemplos:*
* Paridad - deteccion
* Redundancia - correcion

## Formato
Informacion acerca del tipo de la informacion transmitida

## Control de flujo
Manejo de la cantidad de informacion que el receptor (o la red) puede aceptar

## Direccionamiento
Forma de identificar al emisor y al receptor. Por Ej.: En telefonia, el numero de telefono

## Enrutamiento
Toma de decisiones del medio para llegar de un origen a un destino

## Recuperacion
Forma de comunicar al emisor que hay cierta informacion faltante y necesita ser retransmitida

## Seguridad
Forma de mantener la comunicacion "privada" (entendible) entre la fuente y el destino

## Manejo de Red
La forma de mantener la red de la forma mas eficientemente posible
