# Práctica 4 - Entradas Digitales y Control de Displays

En esta práctica se trabajó con entradas digitales mediante botones y con la visualización de información utilizando displays de 7 segmentos. El objetivo fue comprender la lectura de señales externas a través de los puertos del microcontrolador PIC16F887 y su utilización para controlar diferentes salidas. Las actividades permitieron reforzar conceptos relacionados con el manejo de entradas digitales, la detección de eventos y la representación de datos en dispositivos de visualización.

_Hardware utilizado_ 
- Microcontrolador PIC16F887
- Programador PICkit
- 3 botones pulsadores
- 3 LEDs
- 2 displays de 7 segmentos
- Protoboard
- Resistencias limitadoras de corriente
- Cables de conexión

_Software utilizado_ 
- MPLAB X IDE
- Compilador XC8
- Proteus Design Suite

# Ejercicios realizados 

1. Control de LEDs mediante botones: Se implementó un sistema de control utilizando tres botones conectados a las entradas RB0, RB1 y RB2 del microcontrolador. Cada botón controla el estado de un LED específico, permitiendo encender o apagar la salida correspondiente mediante la interacción directa del usuario. Este ejercicio permitió practicar la lectura de entradas digitales y la respuesta inmediata de las salidas.

2. Contador con dos displays de 7 segmentos: Se desarrolló un contador visualizado mediante dos displays de 7 segmentos. El primer display se conectó al puerto C y el segundo al puerto D. El sistema fue controlado mediante tres botones: RB0 reinicia el contador a cero, RB1 incrementa el valor en una unidad y RB2 lo decrementa en una unidad. Este ejercicio permitió integrar la lectura de entradas digitales con la visualización de valores numéricos en múltiples dispositivos de salida.
