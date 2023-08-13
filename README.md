<div align="center" markdown="1">

  <h1>ODROID H3(+) mITX adapter</h1>

  <img src=./build/3D.png alt="3D PCBA" width="60%" height=auto />

  A feature rich mITX adapter for the ODROD H3(+) <br>
  Designed for the [NaSFW project](https://github.com/IoannisP-ITENG/NaSFW)

</div>

## Features

- 1x12 header exposing ODROID GPIO
  - I2C1
  - I2C2
  - HDMI_CEC
  - UART_RTS
  - UART_CTS
- 1x10 header exposing ESP32 GPIO
  - GPIO4
  - GPI36
  - GPIO14
  - GPIO14 5V OUT
  - GPIO12
- 1x6 header exposing ESP32 programming
  - Pin conmpatible with FT232 boards
  - 3V3
  - RX
  - TX
- Front IO
  - 2xUSB2.0 header
  - Front IO header
    - Power LED connected to +5V_RUN
    - HDD connected to ESP32 GPIO4
    - PWR button connected to ODROID
    - RESET button connected to ESP32 GPI39
- On board USB2.0 A connector to ODROID (USB1)
- All USB
  - D+/D- ESD protection
  - VBUS protection
  - VBUS switchable by eitgher
    - ESP32
    - +5V_RUN
- ESP32 with Ethernet
  - Remote UART terminal (BIOS access)
  - 3x USB power control
  - Reset button input
  - PWR_ON button controll of ODROID via optocoupler
  - Always-on, powered by +5V_STBY or USB Type-C PD input

## Manufacturing

Designed for ordering and assembly by JLCPCB
