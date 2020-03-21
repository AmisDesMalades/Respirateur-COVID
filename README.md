# Respirateur-COVID

Prototype de respirateur d'urgence basé sur l'automatisation de la compression d'un ambubag (fork d'Helpful Engineers).

![Respirateur](/assets/images/respirateur-ambubag-2.png "Respirateur")

## Partie éléctronique

![Composants](/assets/images/composants.png "composants")

Ces composants sont les composants standards d'une imprimante 3D et sont largement disponibles dans le commerce et en ligne. (livraison prime)
KIT 3D à 69€ comprenant 3 moteurs: <https://www.amazon.fr/Professional-printer-arduino-Kuman-Shield/dp/B06Y2BSCL7/>


- Moteur NEMA 17
- Carte Arduino
- Shield GRBL
- Potentiomètre de réglage de la vitesse
- Bouton marche/arrêt

## Alimentation électrique

![Alimentation 12V](/assets/images/composants.png "alimentation")

- Alimentation stabilisée 12V 10A dédiée à 17€: <https://www.amazon.fr/KeeYees-Convertisseur-Commutation-Alimentation-110V-220V/dp/B07GZP31JK/>
- Alimentation type PC largement disponible.

## Code arduino

- Le code devra exécuter une boucle d'envoi d'instruction G-CODE au shield GRBL en variant la vitesse de compression de l'ambubag avec l'entrée du potentiomètre.

## Composants imprimés 3D

- Facade simple Arduino/GRBL imprimée en 3D
- Charnières

## Composants extérieurs

- Barre filetée M8
- Ecrou M8
- Liaison NEMA17 - M8 (métal ou imprimé)
