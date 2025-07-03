# Mecatronica - Man on the Wire

Este proyecto consiste en la construcción de un robot alto con la capacidad de equilibrarse por sí solo, inspirado en un equilibrista de cuerda floja. El sistema funciona como un péndulo invertido, controlado por un microcontrolador (Arduino), motores paso a paso y sensores de inclinación.

🔧 Componentes Principales:

- Motor NEMA 17 x2.
- Driver EasyDriver A3967.

- Sensor GY-521 (MPU6050) — Acelerómetro + Giroscopio.
- Arduino UNO.
- Placa PCB.
- Estructura impresa.

🧠 Principio de Funcionamiento:

El sensor MPU6050 mide la inclinación y velocidad angular del robot en tiempo real. El Arduino utiliza estos datos para calcular una corrección y enviar señales a los motores paso a paso, que se activan mediante los EasyDriver, estabilizando la estructura como si el robot estuviera haciendo equilibrio.

- Modelo CAD
- Esquema de control
- Presentación PDF

## Modelo CAD.

![Imagen de WhatsApp 2025-07-02 a las 21 22 01_f767eded](https://github.com/user-attachments/assets/979ad0fc-b36f-4965-9ff8-e02a87e7e38f)



## Esquema PID.

![Imagen de WhatsApp 2025-07-02 a las 19 19 14_75edd3cd](https://github.com/user-attachments/assets/92a5c314-905e-4e12-a656-631b654fa783)


## Esquema Circuito.

![Schematic_DiseñoProyectoManontheWire_2025-07-02](https://github.com/user-attachments/assets/8bcc8a7a-bbed-45ae-b6d3-c9331c7381b1)

