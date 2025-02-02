# Simulation d'Attaques DoS avec Kali Linux 💻

## 🚀 Description :
Ce projet simule des attaques de type **Déni de Service (DoS)** sur un réseau informatique à l'aide de **Kali Linux**. Nous utilisons **hping3** pour mener une attaque DoS, **nmap** pour scanner les ports ouverts, et **Wireshark** pour analyser le trafic réseau. L'architecture du réseau est simulée avec **GNS3**.

## 🧰 Technologies et Outils :
- **Kali Linux** : Système utilisé pour mener l'attaque avec hping3.
- **hping3** : Outil de ligne de commande utilisé pour réaliser des attaques DoS telles que **flooding** et **ping-flood**.
- **nmap** : Outil pour scanner les ports ouverts sur la machine cible.
- **Wireshark** : Logiciel pour analyser le trafic réseau et observer les effets de l'attaque.
- **GNS3** : Utilisé pour simuler une architecture réseau entre les différentes machines et serveurs.

## 🧑‍💻 Scénario du TP :
1. **Scan des Ports** : Utilisation de `nmap` pour découvrir les ports ouverts de la machine cible.
2. **Lancement d'Attaques DoS** : Utilisation de `hping3` pour réaliser des attaques de type **flooding** et **ping-flood** sur un serveur web cible.
3. **Analyse du Trafic** : Capturer et analyser le trafic réseau avec **Wireshark** pendant les attaques pour observer l'impact sur le serveur cible.
4. **Simulation Réseau** : Architecture réseau simulée avec **GNS3** pour reproduire un environnement réaliste d'attaque et de défense.

## 📸 Captures d'écran :
 quelques captures d'écran illustrant les attaques simulées et l'analyse du trafic réseau se touve au niveau de la fichier jointe:


## 🔧 Installation et Configuration :

1. **Clonez ce dépôt** :
   
    git clone https://github.com/Awa-LO/DoS-Attacks-Simulation.git
  

2. **Prérequis** :
   - **Kali Linux** : Pour exécuter l'outil **hping3**.
   - **nmap** : Outil pour le scan des ports (disponible par défaut sur Kali).
   - **Wireshark** : Pour l'analyse du trafic réseau.
   - **GNS3** : Pour simuler l'architecture réseau et configurer les machines virtuelles.

3. **Configurer le réseau dans GNS3** :
   - Créez une topologie réseau avec des machines virtuelles représentant l'attaquant et la machine cible.
   - Assurez-vous que les machines peuvent communiquer via un réseau interne simulé.

4. **Lancer l'attaque** :
   - Utilisez la commande `nmap` pour scanner la machine cible.
   - Lancez une attaque DoS avec `hping3` en utilisant des commandes comme `hping3 -S -p 80 --flood <IP_CIBLE>` pour un flood TCP.
   - Analysez le trafic en temps réel avec **Wireshark**.

## 🔧 Exécution des Attaques :
- **Flooding Attack** : Utilisation de `hping3` pour envoyer des paquets en grand nombre vers le serveur cible afin de saturer ses ressources.
- **Ping-Flood Attack** : Envoi d'une grande quantité de pings à la machine cible pour l'empêcher de répondre à d'autres requêtes.

## 📈 Résultats :
Les résultats de l'attaque sont capturés et analysés à l'aide de **Wireshark**. L'impact de l'attaque sur la machine cible est illustré par les pics de trafic et l'incapacité du serveur à répondre aux requêtes légitimes.

## 📝 Conclusion :
Ce projet démontre comment un attaquant peut exploiter des vulnérabilités dans un réseau pour mener des attaques DoS. L'utilisation d'outils comme **hping3** et **Wireshark** aide à comprendre l'impact des attaques et à se préparer aux mesures de défense.

## 🔗 Références :
- [hping3](http://www.hping.org/)
- [nmap](https://nmap.org/)
- [Wireshark](https://www.wireshark.org/)
- [GNS3](https://www.gns3.com/)

## 📢 Auteurs :
- Awa Lo


## 📬 Contact :
Pour toute question ou collaboration, vous pouvez me contacter via GitHub 
