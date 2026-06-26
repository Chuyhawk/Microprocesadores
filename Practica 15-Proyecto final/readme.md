# Proyecto Final - Juego con Comunicación entre PIC16F887

En el proyecto final se desarrolló un sistema de comunicación entre dos microcontroladores PIC16F887 en colaboración con otro equipo, implementando un juego interactivo en tiempo real. El objetivo fue aplicar protocolos de comunicación entre microcontroladores, así como integrar periféricos de entrada y salida para crear una aplicación funcional y dinámica. El proyecto permitió combinar múltiples conceptos vistos a lo largo del curso, incluyendo comunicación serial, manejo de LCDs, lectura de joysticks y sincronización entre sistemas embebidos.

_Hardware utilizado_
- 2 Microcontroladores PIC16F887
- 2 Programadores PICkit
- 2 Displays LCD 16x2
- 2 Joysticks analógicos
- Protoboard
- Resistencias
- Cables de conexión

_Software utilizado_
- MPLAB X IDE
- Compilador XC8
- Proteus Design Suite

# Desarrollo del proyecto

Se implementó un videojuego de dos jugadores utilizando dos sistemas independientes, cada uno conformado por un PIC16F887, un joystick y un display LCD. En cada pantalla se mostraba un personaje controlado por el jugador mediante el movimiento del joystick.

Al presionar el joystick, el jugador disparaba un proyectil representado como una bolita, la cual era enviada al sistema del jugador contrario mediante la comunicación establecida entre ambos microcontroladores. Una vez recibido el disparo, este aparecía en la pantalla opuesta y el segundo jugador debía mover su personaje para evitar el impacto.

Si el jugador no lograba esquivar el proyectil, se determinaba su derrota, finalizando la partida. Este proyecto integró conceptos de transmisión de datos, control de eventos, lectura analógica y representación gráfica básica en LCD.

# Imágenes 
<img width="242" height="616" alt="image" src="https://github.com/user-attachments/assets/467fe74d-4330-4b12-a580-f7bc977baad9" />
<img width="988" height="463" alt="image" src="https://github.com/user-attachments/assets/6dcf0e74-9dfc-44ad-a191-51b6d75b6e67" />
