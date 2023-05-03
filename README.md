# Arduino-RC-Remote-Bluetooth
RC Car/Tank menggunakan Mikorkontroler Arduino Uno. <br>
**Catu daya menggunakan  Baterai Lipo 2S (7,4v)** 

## Bahan-bahan Utama
- Arduino Uno
- Modul Bluetooth Hc-05
- Motor Driver L298N
- Lampu LED

## Pin Config Arduino
### 🔻 Arduino 👉 L298N
- 5  => IN1
- 6  => IN2
- 10 => IN3
- 11 => IN4

### 🔻 Arduino 👉 Bluetooth HC05
- 0 RX => TXD
- 1 TX => RXD

### 🔻 Arduino 👉 LED
- 13 => VCC Led
