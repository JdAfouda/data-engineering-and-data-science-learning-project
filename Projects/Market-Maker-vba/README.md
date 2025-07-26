📊 Market Maker VBA
Ce projet a pour but de simuler un mini market maker en utilisant Excel/VBA, pour comprendre les mécanismes de formation des prix bid/ask, la tenue de carnet d’ordres, et le suivi d’un PnL dynamique. 
Il permet d’explorer de manière interactive les bases du market making, sans infrastructure de marché en temps réel.

⚙️ Fonctionnalités principales
Génération dynamique de prix bid/ask autour d’un mid-price configurable
Interface utilisateur avec boutons de trading (achat / vente)
Suivi automatique du PnL non réalisé et réalisé
Carnet de position mis à jour après chaque transaction
Détection de dépassement de risque (position ou perte max)
Paramétrage des spreads et tailles de lots via l’interface Excel

🖼️ Aperçu
<img width="811" height="550" alt="{2CA5BD2E-248E-4E04-BD24-5482E3E8A5B2}" src="https://github.com/user-attachments/assets/c46637d3-b259-4019-9bcd-5775f805cabd" />
<img width="529" height="431" alt="{1A013C14-FC4C-4451-9A18-0D508132ECDD}" src="https://github.com/user-attachments/assets/d92800e7-39b5-4dc1-8036-b120f1ba9591" />

Exemple :
![Interface Excel du Market Maker](./screenshots/market_maker_excel_interface.png)
🧰 Outils & technologies
Excel : Interface utilisateur + calculs

VBA : Logique métier (pricing, exécution, mise à jour des positions/PnL)

🗂️ Structure du projet
market-maker-vba/
│
├── MarketMaker.xlsm         # Fichier Excel avec macros activées
├── README.md                # Présentation du projet
└── screenshots/             # (optionnel) Captures d'écran de l'interface
