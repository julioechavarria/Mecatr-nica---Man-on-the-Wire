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
