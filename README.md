![temporisation_alim_esp](https://github.com/user-attachments/assets/a1d4ae18-6458-4484-a4fb-025e5c4b30cf)

Suite à des plantages de l'ESP32 lors de faible luminosité en début et fin de journée j'ai ajouté cette temporisation à 555et 2N2222 sur l'alimentation 5VDC de l'ESP32.
La faible luminosité provoque des battements de l'alimentation du cirduit ESP32 et plantage de la lecture du BH1750.
L'alimentation est réalisée à partir des panneaux solaires avec l'aide d'un convertisseur 22V-290V vers 5V.
Convertisseur Aliexpress DC-DC Abati eur Buck Convertisseur Tech Haute Tension 22V-290V Dstress3.6 V-15V Réglable DC Isolation.
Le capteur de lux est un BH1750 et la mesure du courant en sortie des panneaux solaires est réalisée avec des WCS1600.
