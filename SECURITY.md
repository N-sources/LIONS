# Security Policy
45+oi58 j(<77-((éé j
## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |  
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.
## 1.0.36 - 2026-04-24

-Le sélecteur de sous-commandes affiche un indicateur de sélection (❯) à côté de l’élément surligné
-Message d’erreur plus clair avec un lien direct lorsque plusieurs licences de Copilot sont détectées
-Correction d’un problème où preToolUse.matcher était ignoré. Après la mise à jour, les hooks avec matcher ne s’exécutent que pour les noms d’outils correspondant entièrement au regex.
- `/keep-alive' est disponible sans mode expérimental pour empêcher la veille du système tant que le Copilot CLI est actif
-La commande /remote affiche l’état actuel et supporte /remote on et /remote off pour basculer la télécommande
-Les compétences désactivées n’apparaissent plus dans la liste de commandes barrière
-Ajoutez un bouton « change » la ligne de statut pour afficher les décomptes de lignes ajoutés/supprimés pour la session
-Les fichiers d’instructions personnalisés dans les répertoires .gitignored (par exemple, .github/instructions/) se chargent désormais correctement
-Nécessite un double Esc pour annuler le travail en vol, évitant ainsi les interruptions accidentelles
-L’enregistrement des journaux de débogage ou des bundles de rétroaction ne remplace plus les fichiers d’archive existants
-Les agents personnalisés, compétences et commandes de ~/.claude/ ne sont plus chargés par le Copilot CLI
-Claude Opus 4.6 utilise désormais par défaut un effort de raisonnement moyen

## 1.0.35 - 2026-04-23
