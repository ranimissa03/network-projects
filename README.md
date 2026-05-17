# network-projects
Réseau d'entreprise simulé — Cisco Packet Tracer
# 🌐 Réseau d'Entreprise — Cisco Packet Tracer

## 📋 Description
Simulation d'un réseau local d'entreprise multi-départements
configuré sur Cisco Packet Tracer 8.x.

## 🏢 Départements
| Département | Appareils | Connexion |
|-------------|-----------|-----------|
| Server Room | 1 Serveur + 1 Laptop Admin | Filaire |
| Caisse Room | 3 PCs | Filaire |
| Secrétaire Room | 4 PCs | Filaire |
| Président Room | 3 Laptops | WiFi |
| Balcon | 2 Laptops | WiFi |
| Direction Room | 3 PCs | Filaire |

## 🛠️ Équipements
- 3 Switches Cisco 2960-24TT
- 1 Routeur Cisco 2911
- 2 Access Points WiFi
- 1 Serveur multi-services
- PCs et Laptops

## ⚙️ Services déployés
| Service | Description | Port |
|---------|-------------|------|
| DHCP | Attribution automatique des IPs | — |
| DNS | Résolution de noms de domaine | 53 |
| HTTP | Serveur web interne | 80 |
| FTP | Transfert de fichiers | 21 |

## 📡 Adressage réseau
| Appareil | IP |
|----------|----|
| Routeur | 192.168.10.1 |
| Serveur | 192.168.10.100 |
| PCs/Laptops filaires | 192.168.10.x (DHCP) |
| Laptops WiFi | 192.168.10.x (statique) |
| Masque | 255.255.255.0 |

## 📸 Screenshots
### Topologie complète
![Topologie](screenshots/topologie.png)

### Services
![DHCP](screenshots/dhcp.png)
![HTTP](screenshots/http.png)
![FTP](screenshots/ftp.png)
![Ping](screenshots/ping.png)

## ✅ Tests effectués
- [x] Ping entre tous les appareils
- [x] Attribution IP automatique (DHCP)
- [x] Navigation web interne (HTTP)
- [x] Connexion FTP réussie
- [x] Résolution DNS

## 🧰 Technologies
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=flat&logo=cisco&logoColor=white)

- Cisco Packet Tracer 8.x
- Protocoles : TCP/IP, DHCP, DNS, HTTP, FTP
- Adressage IPv4, VLANs

## 👤 Auteur
**Ranim Ben Issa** — Étudiante ingénieure ENSISA (Groupe INSA)  
[GitHub](https://github.com/ranimissa03)
