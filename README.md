# packet-tracer-mini-lab-vlan
MiniLab Packet Tracer – VLAN, Trunk, DHCP, Router-on-a-Stick
# MiniLab Packet Tracer – VLAN & Inter-VLAN Routing

## Objectif
Mettre en place un mini réseau d’entreprise avec :
- segmentation en VLAN
- routage inter-VLAN
- serveur DHCP sur routeur
- tests de connectivité

## 🧰 Matériel utilisé
- 1 routeur Cisco 1941
- 3 switch Cisco 2960
- 3 points d’accès Wi-Fi
- 6 PC fixes
- 3 PC portables
- 3 téléphones IP Cisco 7960

## 🗂️ VLAN configurés

| VLAN | Usage | Réseau |
|----|------|-------|
| 1 | VoIP | 192.168.0.0/24 |
| 10 | WiFi | 192.168.10.0/24 |
| 20 | PC fixes | 192.168.20.0/24 |
| 30 | Administration | 192.168.30.0/24 |

## 🔗 Architecture
- Les switchs sont interconnectés en **trunk 802.1Q**
- Le routeur utilise le principe **Router-on-a-Stick**
- DHCP centralisé sur le routeur

## 🧪 Tests effectués
- Ping entre machines du même VLAN
- Ping inter-VLAN
- Ping vers les passerelles VLAN

Tous les tests sont concluants.

## 📁 Contenu du dépôt
- Fichier Packet Tracer (.pkt)
- Configurations routeur et switchs
- Captures d’écran des tests
