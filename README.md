#Avionic-Marsaut1
Marsaut_1 experimental rocket avionic (On-board electronics) created by Mines Space, Version 2022 launched at C'space

The first iteration of the sequencer designed by Arthur Chassande (later abandoned) was equipped with a Stm32H7 microcontroller. This sequencer included two additional electronic cards, an interface card integrated into the launcher, which housed the connector assembly, and an independent IHM card, which could display the current status of the fuse to the user. On the motherboard, we find :

- An assortment of basic capteurs allowing to collect the parameters of the altitude (GPS, IMU, barometer, temperature).
- An "aérocontact" to detect the collapse
- A flash memory and an SD card for the registration of the data.
- An 868 MHZ frequency modulation transmitter, operating in FSK for real-time flight data transmission
- A buzzer and an LED for indicating the card status
- H-bridge drivers to control the various deployment systems (parachute, drone and nose cone)

| Routing | 3D | Description |
|:---:|:---:|:---:|
| ![alt text](https://github.com/axpaul/Avionic-Marsaut1/blob/main/Image/MS1-3D%20V1.png) | ![alt text](https://github.com/axpaul/Avionic-Marsaut1/blob/main/Image/MS1-routage%20V1.png) | V°1 of avionics for Marsaut 1 |
| ![alt text](https://github.com/axpaul/Avionic-Marsaut1/blob/main/Image/MS1-3D%20V2.png) | ![alt text](https://github.com/axpaul/Avionic-Marsaut1/blob/main/Image/MS1-routage%20V2.png) | V°2 of avionics for Marsaut 1 |

