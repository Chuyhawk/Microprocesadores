# Descripción

En esta práctica se amplió el uso del convertidor analógico-digital (ADC) del microcontrolador PIC16F887 mediante la lectura de múltiples señales analógicas provenientes de potenciómetros. El objetivo fue visualizar distintos valores de entrada en un display LCD y desarrollar un sistema de navegación mediante botones para cambiar entre canales y modos de representación. Esta práctica permitió reforzar conceptos de multiplexación de entradas analógicas, procesamiento de señales y diseño de interfaces básicas con el usuario.

_Hardware utilizado_ 
- Microcontrolador PIC16F887
- Programador PICkit
- Display LCD 16x2
- 2 potenciómetros
- 2 botones pulsadores
- Protoboard
- Resistencias
- Cables de conexión

_Software utilizado_ 
- MPLAB X IDE
- Compilador XC8
- Proteus Design Suite

# Ejercicios realizados 

1. Visualización de dos voltajes: Se implementó un sistema de lectura de dos entradas analógicas independientes utilizando dos potenciómetros. Los valores de voltaje obtenidos fueron mostrados simultáneamente en el display LCD, colocando el primer voltaje en la línea superior y el segundo voltaje en la línea inferior. Este ejercicio permitió trabajar con múltiples canales ADC y su representación simultánea.

2. Cambio de canal y modo de visualización: Se desarrolló una interfaz de control utilizando dos botones. El primer botón permite alternar entre la visualización del voltaje correspondiente al potenciómetro 1 o al potenciómetro 2. El segundo botón cambia el formato de visualización de la señal seleccionada, permitiendo mostrar el valor en volts, porcentaje o en su valor digital crudo (ADC). Este ejercicio permitió combinar entradas digitales con señales analógicas para crear un sistema de visualización más dinámico e interactivo.

# Imágenes
<img width="403" height="662" alt="image" src="https://github.com/user-attachments/assets/3d46424f-7804-404a-9835-2777086cb8dc" />
<img width="416" height="706" alt="image" src="https://github.com/user-attachments/assets/3bfc8f4d-4028-49fd-b938-e12fc11d275c" />
