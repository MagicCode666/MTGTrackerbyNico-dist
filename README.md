# MTGTrackerbyNico

Compagnon pour MTG Arena, pour Windows. Il lit le `Player.log` d'Arena (aucun accès au jeu, aucune donnée envoyée) et affiche, dans sa propre fenêtre :

- les cartes qui restent à piocher, avec leurs probabilités ;
- les cartes vues de l'adversaire, ses couleurs et la taille de son deck ;
- l'historique de vos parties (victoires/défaites par deck, par adversaire, mains de départ).

## Installation

1. Téléchargez `MTGTrackerbyNico.exe` depuis la [dernière release](../../releases/latest).
2. Placez-le où vous voulez et lancez-le (créez un raccourci si besoin).
3. Dans Arena : *Options → Compte → « Detailed Logs (Plugin Support) »*, puis relancez Arena.

Windows SmartScreen peut afficher un avertissement au premier lancement (l'exe n'est pas signé) : « Informations complémentaires » puis « Exécuter quand même ».

## Mises à jour

L'application vérifie ce dépôt au lancement puis toutes les 6 heures. Quand une version est disponible, un bandeau propose « Mettre à jour » : l'exe est téléchargé, son empreinte SHA-256 est contrôlée, puis l'application se relance. Rien de personnel n'est envoyé.

Les données (historique, journal) sont dans `%AppData%\MTGTrackerbyNico`.

---

Ce dépôt ne contient que les versions publiées.
