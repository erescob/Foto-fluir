# Foto-fluir
Prototipo de seguidor solar automatizado de 2 ejes con Arduino

## Componentes de Hardware (BOM)
* Placa base Arduino para el sistema de control.
* Sensores de luz (LDR) para el seguimiento automatizado de dos ejes.
* Servomotores para el control de movimiento y posicionamiento de los paneles.
* Concentradores solares con geometría V-planar (Diseño en CAD) acoplados a un panel solar de 1W.
* Sensor de corriente INA219 para medición de potencia y telemetría.
* Módulo de carga TP4056 con regulador boost para la gestión de energía.
* Pantalla OLED para la visualización de datos en tiempo real.

## Diagrama del Circuito


## Funcionamiento
El sistema lee los valores analógicos de 4 sensores LDR posicionados en forma de cruz. El algoritmo calcula la diferencia de intensidad de luz entre los ejes vertical y horizontal, y ajusta la posición de los servomotores para mantener el panel perpendicular a la fuente de luz.
