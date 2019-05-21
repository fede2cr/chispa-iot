# Primera Etapa: Chispa

Indicador visual para atracado de barcos con Leds y baterías recargables

## Descripción

La chispa va a topar condiciones de clima variadas donde puede recibir bajas temperaturas de agua durante la noche, altas temperaturas por radiación solar durante el día, golpearse contra el casco del barco así como con piedras y otros objetos, por lo cual debe ser construído para:

- Resistencia a golpes
- Resistencia a agua

Esto complica tareas como el reprogramado de la tarjeta por necesidad de acceso al puerto USB, y recarga de la batería. Se proponen las soluciones de una caja en exopy, y carga inalámbrica.

## Caja en epoxy

En lugar de utilizar una caja protectora construida con la impresora 3D, madera o cajas de tipo IP, se propone utilizar un [epoxy transparente](https://www.amazon.com/ArtResin-Epoxy-Resin-Respirator-Needed/dp/B01BX6893Y/) y con un molde de cartón rellenar el molde de epoxy, desmoldar, y luego probar pulir los lados para acceso visual a la microcontroladora, así como también **lijar** la porción del epoxy donde se encuentra el LED, de forma que actúe como un **difusor**.

Esta caja epoxy también protege de golpes y humedad.

Desventajas: Es necesario buscar epoxy resistente a UV, dado que la exposición contínua al sol podría causar una degradación evidente luego de uso prolongado.Se recomienda utilizar esta versión de epoxy para etapas siguientes.

## Carga inalámbrica

La [carga inalámbrica](https://www.crcibernetica.com/wireless-charging-module-5v-output/) permite refrescar la potencia de las baterías luego de uso regular, acercando con cierta precisión las dos bobinas de carga inductiva. De esta forma podemos recargar estado dentro de la caja en epoxy.

## Resultados esperados

Evaluar en períodos de 1 y 3 meses:

- [ ] Estado general
- [ ] Estado del epoxy
- [ ] Eficacia de caja de epoxy
- [ ] Estado de batería
- [ ] Duración de la batería
- [ ] Duración de recargas
- [ ] Eficacia de carga inalámbrica
- [ ] Retroalimentación por Guardaparques

## Componentes

- Led
- micro mínima
- transistor
- batería recargable
- carga inalámbrica
- caja de epoxy
- indicador visual de batería
