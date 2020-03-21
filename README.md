# Respirateur-COVID

Prototype de respirateur d'urgence basé sur l'automatisation de la compression d'un ambubag (fork d'Helpful Engineers).

![Respirateur](/assets/images/respirateur-ambubag-2.png "Respirateur")

## Partie éléctronique

![Composants](/assets/images/composants.png "composants")

Ces composants sont les composants standards d'une imprimante 3D et sont largement disponibles dans le commerce et en ligne. (livraison prime)
Ils peuvent fonctionner 24h/24 sans trop chauffer et sont fiables.
KIT 3D à 69€ comprenant 3 moteurs: <https://www.amazon.fr/Professional-printer-arduino-Kuman-Shield/dp/B06Y2BSCL7/>

- Moteur NEMA 17+
- Carte Arduino
- Shield GRBL
- Microstepper
- cable USB PC - Arduino
- Potentiomètre de réglage de la vitesse
- Bouton marche/arrêt

## Alimentation électrique

L'alimentation se fera sur secteur 220v avec un bloc d'alimentation dédiée.
![Alimentation 12V](/assets/images/alimentation.png "alimentation")

- Alimentation stabilisée 12V 10A dédiée à 17€: <https://www.amazon.fr/KeeYees-Convertisseur-Commutation-Alimentation-110V-220V/dp/B07GZP31JK/>
- Alimentation type PC largement disponible.

## Code arduino

- Le code devra exécuter une boucle infinie d'envoi d'instruction [GCODE GRBL](https://github.com/gnea/grbl/wiki/Grbl-v1.1-Commands) au shield GRBL permettant de varier la vitesse de compression de l'ambubag avec l'entrée du potentiomètre.
- Le code sera téléversé sur l'arduino depuis un PC avec [Arduino IDE](https://www.arduino.cc/en/main/software)


## Composants imprimés 3D

- Facade simple Arduino/GRBL imprimée en 3D
- Charnières

## Composants extérieurs

- Barre filetée M8
- Ecrou M8
- Liaison NEMA17 - M8 (métal ou imprimé)
