---

# TARS from Interstellar x Local AI

## Overview
This project aims to build a replica of TARS from Interstellar integrated with ChatGPT functionalities. The build involves 3D printing parts, assembling hardware, and running software components for AI, text-to-speech, speech-to-text, and image classification.

## 3D Printing
All parts are printed on Creality Ender 3. Use TPU for "Flexor" parts and PETG for others.

## Modifications
- Modifing 3d files for fit other hardware. For example the servos and room for SD card.
- Design file: `Chassis Bottom (Mod SD CARD).stl`

## Software Components
- **LLM**: [TabbyAPI](https://github.com/theroyallab/tabbyAPI)
- **TTS**: [xtts-api-server](https://github.com/daswer123/xtts-api-server)
- **SST**: VOSK
- **SD**: Automatic1111
- **Vision**: Image Classifier

## Hardware Components
- **Rods**: [Link](https://www.amazon.com/gp/product/B01MAYQ12S/ref=ox_sc_act_title_1?smid=ATVPDKIKX0DER&psc=1)
- **Servos**: [Link](https://www.amazon.com/gp/product/B0CGRP59HJ/ref=ox_sc_act_title_3?smid=A3F3CVCOVVNP2J)
- **Bolts**: [Link](https://www.amazon.com/gp/product/B0CR6DY4SS/ref=ox_sc_act_title_4?smid=A1ZRRCZIF57JQ9)
- **Springs**: [Link](https://www.amazon.com/gp/product/B076M6SFFP/ref=ox_sc_act_title_8?smid=A1THAZDOWP300U&psc=1)
- **Bearings**: [Link](https://www.amazon.com/gp/product/B07FW26HD4/ref=ox_sc_act_title_9?smid=ATVPDKIKX0DER&psc=1)
- **Servo Driver**: [Link](https://www.amazon.com/gp/product/B00EIB0U7A/ref=ox_sc_act_title_10?smid=AAEX2EKCSXB7D&psc=1)
- **RPI Mic**: [Link](https://www.amazon.com/gp/product/B086DRRP79/ref=ox_sc_act_title_11?smid=A1DWLG2LHSJB8R)
- **Linkage**: [Link](https://www.amazon.com/gp/product/B0CRDRWYXW/ref=ox_sc_act_title_12?smid=A1NR50YASSZD11&psc=1)
- **Buck Converter**: [Link](https://www.amazon.com/gp/product/B07SGJSLDL/ref=ox_sc_act_title_13?smid=A3CX4TQNUXMB0L)
- **RPI 5**: [Link](https://www.amazon.com/Raspberry-Pi-Quad-core-Cortex-A76-Processor/dp/B0CTQ3BQLS/ref=sr_1_2_sspa?sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1)
- **3" LCD**: [Link](https://www.amazon.com/OSOYOO-3-5inch-Display-Protective-Raspberry/dp/B09CD9W6NQ/ref=sr_1_8?sr=8-8)
- **Servo Wires**: [Link](https://www.amazon.com/OliYin-7-87in-Quadcopter-Extension-Futaba/dp/B0711TBZY2/ref=sr_1_7?sr=8-7)
- **Audio Amp**: [Link](https://www.amazon.com/dp/B0BTBS5NW2)
- **Audio Speaker**: [Link](https://www.amazon.com/dp/B07GJ4GH67)
- **Camera**: [Link](https://www.amazon.com/dp/B07GJ4GH67)

## Software Demo
[![Video Title](https://img.youtube.com/vi/4YObs8BV3Mc/0.jpg)](https://www.youtube.com/watch?v=4YObs8BV3Mc)

## Original Fork Info
- Original article: [TARS from Interstellar x ChatGPT](https://www.hackster.io/charlesdiaz/how-to-build-your-own-replica-of-tars-from-interstellar-224833#comments)

## Files
- TARS v3_10 - Fix Case Clip
  - [Download](https://uploadnow.io/f/MPLCGwg) | [Alternative Download](https://fastupload.io/9f3621ef4afe07cc)

## Additional Resources
- **Fusion 360**: [Autodesk Fusion 360](https://www.autodesk.com/ca-en/products/fusion-360/personal)
- **Raspberry Pi Projects**: [Getting Started with the Pico](https://projects.raspberrypi.org/en/projects/getting-started-with-the-pico/2)
- **OS Pi**: [Raspberry Pi Software](https://www.raspberrypi.com/software/)
- **Tutorials**: [Setup Raspberry Pi](https://www.tomshardware.com/how-to/set-up-raspberry-pi)
- **Adafruit 16-Channel PWM HAT**: [Video](https://www.youtube.com/watch?v=bB-xymRI8BY), [Documentation](https://learn.adafruit.com/adafruit-16-channel-pwm-servo-hat-for-raspberry-pi)
- **Without HAT**: [Video 1](https://www.youtube.com/watch?v=ea6tSppgZlY), [Video 2](https://www.youtube.com/watch?v=9jcEwn7GzNs), [Documentation](https://learn.adafruit.com/adafruits-raspberry-pi-lesson-8-using-a-servo-motor/overview)
- **3D Printing Services**: [Forge Labs](https://forgelabs.ca/), [JLC3DP](https://jlc3dp.com/3d-printing-quote)

## Python Scripts
- **Servo Abstractor**: Automates walking functions by combining basic servo movements.
- **TARS Runner**: Initializes TARS, handles communication with the Bluetooth remote.
- **Servo Controller**: Manages basic movements of servos, communicates with Adafruit PCA9685 servo driver.

---
