Rapport de Séance
==
Séance 1 01/09/2022
-
Choix du projet: modem LoRa/GSM

* Installation du git, création d'un repository, du fichier rapport de séance et du fichier markdown afin d'écrire l'avancé du projet au fil des séances.

* Prise en main de github et premier aperçu du projet via les différent fichiers/diapos à notre disposition.

* Recherche d'un modem 3G/4G/5G à faibe coût. 

Séance 2 02/09/2022
-
Choix entre 2 modem:
* https://www.digikey.fr/fr/products/detail/nimbelink,-llc/NL-SWN-LTE-NRF9160-B/13545238?utm_adgroup=RF%20Transceiver%20Modules&utm_source=google&utm_medium=cpc&utm_campaign=Shopping_Product_RF%2FIF%20and%20RFID&utm_term=&productid=13545238&gclid=CjwKCAjwsMGYBhAEEiwAGUXJaf7u7tiFCuqfYCbA0xugxWerXDCulKu48h5bCE_3MJ1FdUXBXE_tzxoCh5cQAvD_BwE
 
* https://www.digikey.fr/fr/products/detail/nimbelink,-llc/NL-SW-LTE-QBG95-B/13930379?utm_adgroup=RF%20Transceiver%20Modules&utm_source=google&utm_medium=cpc&utm_campaign=Shopping_Product_RF%2FIF%20and%20RFID&utm_term=&productid=13930379&gclid=CjwKCAjwsMGYBhAEEiwAGUXJaeWaWl2KfGZscGHEM1nGFe_TdwtNunfvPOaDJgOhnZRvBooB_zY8shoCOlwQAvD_BwE

Choix d'une antenne pour le modem:
https://www.digikey.fr/fr/products/detail/linx-technologies-inc/ANT-GNCP-C106L160/15294131

Création d'un tableau excel pour comparer les différents modem

Séance 3 09/09/2022
-
Finalisation du tableau et envoie de celui-ci au référent

Manuel d'utilisateur du SIM7000G https://usermanual.wiki/SIMCom-Wireless-Solutions/SIM7000G-4050964.pdf

Manuel de commande du SIM7000G https://cdn.geekfactory.mx/sim7000g/SIM7000%20Series_AT%20Command%20Manual_V1.06.pdf

Séance 4 15/09/2022
-
Prise en main de la LILYGO T-SIM7000G (schématique présente sur https://github.com/Xinyuan-LilyGO/LilyGO-T-SIM7000G/blob/master/schematic/SIM7000G_20200415.pdf et de l'environnement de travail) trouvé sur le site https://randomnerdtutorials.com/lilygo-t-sim7000g-esp32-lte-gprs-gps/

Séance 5 03/10/2022
-
Prise en main du modem

* téléchargement de l'IDE ARDUINO, installation des bibliothèques pour l'ESP32, édition d'un soft de test de communication entre l'ESP32 et le SIM7000G (scan wifi de la pièce)

* édition d'un soft pour tester l'envoie d'un SMS et la position GPS (réussi avec succès)

* test de mise en veille du modem

* essai de reception de sms et lecture sur le terminal (https://docs.arduino.cc/library-examples/gsm-library/GSMExamplesReceiveSMS)

Séance 6 13/10/2022
-

* ajout de la batterie et essai d'envoie SMS sans lien physique avec le PC

* essai de reception SMS et lecture de ce dernier sur le terminal
