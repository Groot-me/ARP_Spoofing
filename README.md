# ARP_Spoofing
### script ARP Spoofing en python

#### Description

- activer/désactiver automatiquement l'ipforwarding au lancement/fin du script
- récupérer automatiquement l'adresse MAC d'une IP sur le réseau grâce à Scapy
- Une fonction spoofing qui va envoyer des requêtes ARP craftées pour l'occasion grâce à Scapy et ainsi corrompre la table ARP de notre victime
- Une fonction restore qui va aussi envoyer des requêtes ARP à la victime mais cette fois-ci pour restaurer sa table ARP.

#### Utilisation :

  pythonX arp_spoofing.py "ip_address_victim" "ip_address_gateway"
  
  
