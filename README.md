# 🛰️ ft_irc - Internet Relay Chat

## 📌 Description
`ft_irc` est un serveur **IRC** écrit en **C++98** permettant aux clients de communiquer via le protocole IRC en **TCP/IP**.  
Il respecte les standards et offre les fonctionnalités essentielles pour créer et gérer des salons de discussion en temps réel.

## 🚀 Fonctionnalités principales
- 📡 **Connexion multi-utilisateurs** en simultané (sans blocage)
- 🔐 **Authentification** avec mot de passe
- 🎭 **Gestion des utilisateurs** (nicknames, usernames)
- 💬 **Salons de discussion** (join, message public & privé)
- 🔧 **Commandes opérateurs** (`KICK`, `INVITE`, `TOPIC`, `MODE`)
- 🌍 **Support IPv4 / IPv6**
- 🛠️ **Poll() unique** pour gérer les entrées/sorties

## 🛠️ Installation & Lancement
1. **Cloner le repo**  
   ```sh
   git clone https://github.com/FastaLaPasta/ft_irc.git
   cd ft_irc
    ```
2. **Compiler avec Makefile**  
   ```sh
    make
    ```
3. **Lancer le serveur**  
   ```sh
   ./ircserv <port> <password>
    ```
4. **Se connecter avec un client IRC**  
   ```sh
   /connect localhost <port> <password>
    ```

## 📜 Commandes IRC supportées
| 📝 Commande  | 🔍 Description |
|-------------|--------------|
| `/nick`     | Changer son pseudo |
| `/user`     | Définir son username |
| `/join`     | Rejoindre un channel |
| `/msg`      | Envoyer un message privé |
| `/kick`     | Expulser un utilisateur |
| `/invite`   | Inviter un utilisateur |
| `/topic`    | Changer ou afficher le sujet d'un channel |
| `/mode`     | Gérer les permissions des channels |

---

## 🎯 Objectifs du projet
✅ Implémenter un **serveur IRC minimaliste** **sans client**  
✅ **Respecter la norme C++98**  
✅ Utiliser **epoll()** pour gérer les connexions de manière **non bloquante**  

---

## 🏆 Bonus effectués
- 📁 **Transfert de fichiers entre utilisateurs**  
- 🤖 **Ajout d'un bot IRC interactif**  
