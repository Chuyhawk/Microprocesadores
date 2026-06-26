# Práctica 9 - Temporización con Timer0 y Monitoreo de Voltaje

En esta práctica se utilizó el módulo **Timer0** del microcontrolador PIC16F887 para implementar funciones de temporización y medición de tiempo. El objetivo fue comprender el funcionamiento de los temporizadores internos y su aplicación en sistemas embebidos para llevar un conteo preciso del tiempo transcurrido. Además, se integró la lectura de señales analógicas mediante un potenciómetro para combinar tareas de temporización y adquisición de datos en un mismo sistema.

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

_Ejercicios realizados_

1. Conteo de tiempo con Timer0: Se implementó un sistema de cronometraje utilizando el Timer0 del PIC16F887 para llevar la cuenta de los segundos y minutos transcurridos desde el momento en que se energiza el circuito. La información se mostró en tiempo real en el display LCD, permitiendo observar el funcionamiento del temporizador como base para aplicaciones de medición de tiempo.

2. Conteo de tiempo y monitoreo de voltaje: Se amplió el sistema anterior integrando la lectura de un potenciómetro mediante el ADC del microcontrolador. Además de mostrar los segundos y minutos transcurridos, el display LCD también presentaba el valor de voltaje generado por el potenciómetro, el cual podía variar en tiempo real según su posición. Este ejercicio permitió combinar periféricos internos como temporizadores y convertidores analógico-digitales en una sola aplicación.

# Imágenes 
<img width="437" height="647" alt="image" src="https://github.com/user-attachments/assets/ca678dac-45c6-473a-857a-ca85af6ed1fa" />
