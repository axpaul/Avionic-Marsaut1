# Avionic-Marsaut1
       
## Marsaut_1 est une fusée expérimentale équipée d'une avionique (électronique de bord) créée par Mines Space. La version n°2 a été lancée au C'space 2022.

> *© 2022 Paul Miailhe, all rights reserved.*  
> *Material licensed under [→ CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0)*

![alt tag](https://github.com/axpaul/Avionic-Marsaut1/blob/main/Image/MS1-3D%20n%C2%B02%20V2.png)

Grabcad :
- https://grabcad.com/library/avionics-system-for-marsaut-1-rocket-mines-space-1
- https://grabcad.com/library/marsaut-1-fusex-2022-1

La première itération du séquenceur, conçue par Arthur Chassande (plus tard abandonnée), était équipée d'un microcontrôleur Stm32H7. La deuxième version, par Paul Miailhe, utilise directement un Nucléo STM32F411. Ce séquenceur comprenait deux cartes électroniques supplémentaires, une carte d'interface intégrée dans le lanceur, qui abritait l'ensemble des connecteurs, et une carte IHM indépendante concu par Quentin Bakrim, qui pouvait afficher à l'utilisateur l'état actuel de la fusée. Sur la carte mère, on trouve :

## Capteurs de base
- Un assortiment de capteurs de base permettant de collecter les paramètres d'altitude (GPS, IMU, baromètre, température).
- Un "acelerocontact" pour détecter le décollage 

## Enregistrement de données
- Une mémoire flash et une carte SD pour l'enregistrement des données.

## Transmission de données
- Un émetteur de modulation de fréquence à 868 MHZ, fonctionnant en FSK pour la transmission en temps réel des données de vol

## Indicateurs d'état
- Un buzzer et une LED pour indiquer l'état de la carte

## Contrôle des systèmes de déploiement
- Des drivers en pont en H pour contrôler les différents systèmes de déploiement (parachute, drone et nez de cône)


| 3D | Routing  | Description |
|:---:|:---:|:---:|
| ![alt text](https://github.com/axpaul/Avionic-Marsaut1/blob/main/Image/MS1-3D%20V1.png) | ![alt text](https://github.com/axpaul/Avionic-Marsaut1/blob/main/Image/MS1-routage%20V1.png) | V°1 of avionics for Marsaut 1, 6 layers, creator Arthur Chassande |
| ![alt text](https://github.com/axpaul/Avionic-Marsaut1/blob/main/Image/MS1-3D%20V2.png) | ![alt text](https://github.com/axpaul/Avionic-Marsaut1/blob/main/Image/MS1-routage%20N%C2%B03%20V2.png) | V°2 of avionics for Marsaut 1, 4 layers, fly model, creator Paul Miailhe |
| ![alt text](https://github.com/axpaul/Avionic-Marsaut1/blob/main/Image/MSA-IHM-3D.png)  |  ![alt text](https://github.com/axpaul/Avionic-Marsaut1/blob/main/Image/MS1-IHM-routage.png) | V°1 of IHM for Marsaut 1, 4 layers, fly model, creator Quentin Bakrim |

## Licence 

![alt tag](https://github.com/axpaul/Avionic-Marsaut1/blob/main/Cc-by-nc-sa_icon.svg.png)
