# Práctica 10 - Temporización con Timer1 y Monitoreo de Voltaje

En esta práctica se utilizó el módulo **Timer1** del microcontrolador PIC16F887 para implementar funciones de temporización y medición de tiempo. El objetivo fue analizar el funcionamiento de este temporizador y compararlo con el uso previo de Timer0, reforzando el manejo de temporizadores internos para aplicaciones de cronometraje. Además, se integró nuevamente la lectura de señales analógicas para combinar la medición de tiempo con la visualización de variables externas.

_Hardware utilizado_
- Microcontrolador PIC16F887
- Programador PICkit
- Display LCD 16x2
- Potenciómetro
- Protoboard
- Resistencias
- Cables de conexión

_Software utilizado_
- MPLAB X IDE
- Compilador XC8
- Proteus Design Suite

# Ejercicios realizados

1. Conteo de tiempo con Timer1: Se implementó un sistema de cronometraje utilizando el Timer1 del PIC16F887 para llevar la cuenta de los segundos y minutos transcurridos desde el encendido del circuito. La información fue mostrada en tiempo real en el display LCD, permitiendo observar la operación del temporizador y su aplicación en sistemas de medición de tiempo.

2. Conteo de tiempo y monitoreo de voltaje: Se amplió el sistema anterior incorporando la lectura de un potenciómetro mediante el convertidor analógico-digital del microcontrolador. Además del conteo de segundos y minutos, el display LCD mostraba el valor de voltaje generado por el potenciómetro, el cual podía modificarse en tiempo real. Este ejercicio permitió integrar el uso de Timer1 con el ADC para desarrollar aplicaciones más completas de monitoreo y visualización.


Repositorio desarrollado para la materia de Microprocesadores.
