# chispa-iot
Chispa, indicador visual para atracado de barcos. Ahora con GPS y geofencing.

## ¿Por qué?

La Isla del Coco por estar dedicada a la conservación, no cuenta con muelle por lo que los barcos deben atracar en boyas flotantes conocidas como fondeo.

Para mantener el control de los barcos en la noche, actualmente se utilizan unas luces que parpadean indicando de forma visual la posición del barco, y de esta forma detectar si se encuentra a la deriva.

Un problema que ha traído esta solución a la Isla, es el **consumo extenso de baterías** las cuales deben ser desechadas; teniendo en mente que los desechos de la Isla son removidos de forma esporádica por barco hacia el continente, por lo que podrían ser una **fuente importante de contaminación**.

Se desea crear una nueva solución que haga uso de nuevas tecnologías de baterías recargables con alternativas como pueden ser **celdas solares, carga inalámbrica y supercapacitores**.

Adicionalemente para mejorar la detección de barcos a la deriva, se ofrece utilizar la existente infraestructura de Internet of Things (IoT) que ha sido instalada en la Isla del Coco por [Greencore Solutions](https://www.greencore.co.cr/), con el producto comunitario de [The Things Network](https://www.thethingsnetwork.org/) (TTN), y enviar la posición de los barcos por medio de localizadores GPS, y utilizar los datos para realizar la función de **GeoFencing**


## Etapas

Para la creación de prototipos y de un producto mínimo viable (MVP) vamos a manejar etapas donde aumentamos la complejidad:

|Etapa|Descripción|Resumen de hardware|
|[Chispa](https://github.com/fede2cr/chispa-iot/blob/master/Chispa.md)|Luz y baterías recargables|Led, micro mínima, transistor, batería recargable, carga inalámbrica, caja de epoxy, indicador visual de batería|
|IoT|Luz y reporte GPS|Se agrega micro ESP con GPS y LoRa, se reporta posición y carga de batería|
|Alarma|Panel de control|Se agrega una interfaz de control, para en las noches activar geofencing independiente para cada barco|
