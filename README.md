### Bot

Offres Gen-Bot V18:
*   ✉️ Vous pouvez crée vos propre compte
*   🇫🇷 Marche que sur un seul salon pour évité le spam
*   ⚙️ Chaque compte généré et directement supprimer
*   🛰️ Une interface a coupé le souffle 
+   🌟 Un système de VIP et de FREE dans un seul bot

### Commandes

* gen (Nom du service) - Générer des comptes
* gen+ (Nom du service) - Générer des comptes VIP
* create (Nom du service) - Créer un service
* restock (Nom du service) (Nombre de compte 1 Ligne = 1 comptes) OU (Un fichier qui comporte les comptes) - Notifier les restocks de compte
* unstock (Nom du service) - Enlevé le stock d'un service
* stock - Afficher les stocks si yan n'a
* gen-acc (ping la personnes) - Ajouter le rôle VIP a l'utilisateurs
* set-channel (add+/remove+) (mentions du salon des générations VIP) - Ajouter le salon de génération pour la commande gen+
* set-channel (add/remove) (mentions du salon des générations FREE) - Ajouter le salon de génération pour la commande gen
* set-logs (add/remove) (mentions du salon des Logs) - Ajoute le salon des logs pas encore optimisé bientôt dans la V30 du bot
* slowmode (mentions du salon des Logs) (Raison) - Ajoute un cooldown dans un salon
* membercount - voir le nombre de membre qui a dans le serveur
* reload - Redémarrer le bot
* unban - Unban un utilisateur 
* ban - Ban un utilisateur 
* nuke - Nuke un salon discord
* clear - Clear des messsage dans un salon
* lock - Lock un salon pour les perms everyone
* unlock - Unlock un salon pour les perms everyone

## Installation

* Aller dans le fichier `config.json` et mettez le token de votre bot
* Toujours dans le fichier `config.json` dans `logs`mettez l'id du salon ou seul le bot pourras fonctionner sinon il vas jamais vous répondre 0
* ```
  {
    "VIP_ID":"VIP ID ROLE",
    "token": "TOKEN BOT DISCORD",
    "prefix": "PREFIX",
    "genCooldown": "5000",
    "restockchannel":"PING RESTOCK ID CHANNEL",
    "pingrole":"PING ROLE ID CHANNEL",
    "gen_role":"ID ROLE",
    "helper":"ID ROLE FOURNISSEUR",
    "logs":"LOGS DU BOT ID CHANNEL SI SES PAS CONFIG LE BOT MARCHE PAS !",
    "bot": {
        "owner1": "1123637251331608637",
        "owner2": "726077529479315466",
        "owner3": "1121165974851289198",
        "owner4": "AJOUTER ICC VOTRE ID",
        "owner5": "AJOUTER ICC VOTRE ID",
        "owner6": "AJOUTER ICC VOTRE ID",
        "owner7": "AJOUTER ICC VOTRE ID",
        "owner8": "AJOUTER ICC VOTRE ID",
        "owner9": "AJOUTER ICC VOTRE ID",
        "owner10": "AJOUTER ICC VOTRE ID"

    },
    "color": {
        "green": "0x43B581",
        "yellow": "0xFAA61A",
        "red": "0xF04747",
        "default": "0x7289DA"
    }
  }

* Ensuite allez dans CMD et faite `node index.js`
