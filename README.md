# Sistema-Alimentacion-Solar-ESP32
# Sistema de Alimentación Solar con ESP32

## Descripción

Este proyecto consiste en el diseño e implementación de un sistema de alimentación basado en energía solar. El sistema utiliza un panel solar para capturar energía del Sol, almacenarla en una batería de litio 18650 y alimentar un microcontrolador ESP32.

El objetivo principal es demostrar el funcionamiento de una fuente de energía renovable aplicada a la electrónica, integrando conocimientos de energías renovables, diseño electrónico y programación.

## Objetivos

* Captar energía solar mediante un panel fotovoltaico.
* Almacenar energía en una batería recargable.
* Alimentar un ESP32 utilizando energía renovable.
* Monitorear el estado del sistema.
* Diseñar una PCB profesional utilizando KiCad.

## Componentes Principales

* ESP32 DevKit V1
* Panel Solar 5V 2W
* TP4056
* Batería 18650
* Pantalla OLED I2C
* AMS1117-3.3
* Resistencias
* Capacitores
* Diodo 1N5819

## Estructura del Proyecto

### Carpeta 3D

Contiene modelos 3D de la caja, soportes y piezas mecánicas.

### Carpeta Hardware

Contiene esquemáticos, diseño PCB, archivos Gerber y hojas de datos.

### Carpeta Software

Contiene el código fuente del ESP32 y las librerías utilizadas.

## Funcionamiento

El panel solar genera energía eléctrica cuando recibe luz solar. El módulo TP4056 controla la carga de la batería 18650. La energía almacenada alimenta al ESP32, que puede mostrar información en una pantalla OLED y controlar distintas funciones del sistema.

## Herramientas Utilizadas

* KiCad
* Arduino IDE
* ESP32
* GitHub

## Autor

Kevin Jason Guzmán Condori

## Licencia

Proyecto educativo desarrollado con fines académicos.
