<div align="center">

# Obstacle Detector & Distance Meter — Arduino

[![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](https://isocpp.org)
[![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)](https://arduino.cc)

*Ultrasonic distance sensing with real-time obstacle detection — the building block of autonomous robot navigation.*

</div>

---

## How it works

```
HC-SR04 trigger pulse → Echo return time → Distance = (time × 340 m/s) / 2
                                         → Below threshold → Obstacle alert (buzzer / LED)
                                         → Serial + LCD display of distance
```

---

## Features

- HC-SR04 ultrasonic sensor for distance measurement (2 cm – 4 m)
- Real-time obstacle detection with configurable threshold
- Distance displayed on serial monitor and/or LCD
- Alert output (buzzer / LED) when obstacle is too close

---

## Hardware

`Arduino` · `HC-SR04 Ultrasonic Sensor` · `LCD / Serial Monitor` · `Buzzer` · `LEDs`

---

## Tech stack

`C++` · `Arduino IDE`

---

<div align="center">
<a href="https://github.com/Yami1106">Ashish Sukumar</a>
</div>
<!-- -->
