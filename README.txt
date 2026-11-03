KREDITAS — PROTOTYPE DE SITE
============================

Fichiers
- index.html : page d'accueil
- formulaire.html : formulaire de démonstration (aucune transmission)
- connexion.html : écran visuel de connexion administrateur
- admin.html : aperçu statique du tableau de bord
- style.css : mise en page responsive bleu/blanc
- langues.js : textes en français, anglais, lituanien, allemand, espagnol, italien, portugais et néerlandais
- script.js : changement de langue et interactions de démonstration

IMPORTANT — LIMITES DE SÉCURITÉ
Ce dossier est un prototype statique. Il ne contient AUCUN backend, aucune authentification réelle,
aucun stockage de dossiers et aucune protection d'espace administrateur. Les champs de démonstration
ne transmettent ni n'enregistrent de données. Ne demandez pas à des clients d'y saisir leurs vraies
informations personnelles, bancaires ou d'identité. Ne publiez pas admin.html comme espace privé.

Pour un lancement réel, il faut notamment :
1. un backend sécurisé et une authentification côté serveur (jamais un mot de passe secret dans JavaScript) ;
2. des rôles/permissions, limitation des tentatives, récupération sécurisée, journalisation et sauvegardes ;
3. chiffrement en transit et au repos, politique de confidentialité et conformité RGPD ;
4. examen juridique/réglementaire de l'activité de crédit en Lituanie et confirmation des autorisations ;
5. affichage précontractuel correct : TAEG, coût total, frais, durée, échéancier, conditions et risques.

Le taux de 2 % par mois fourni pour la maquette ne constitue pas une offre. À titre mathématique,
2 % mensuel correspond à 24 % nominal annuel et environ 26,82 % effectif annuel si les intérêts
sont composés chaque mois, avant frais. La légalité et l'applicabilité doivent être vérifiées.

Publication GitHub
- Déposer les fichiers dans un dépôt GitHub.
- Activer GitHub Pages dans Settings > Pages, branche et dossier racine.
- GitHub Pages héberge uniquement le frontend statique : il ne sécurise pas un espace admin
  et ne doit pas recevoir de données sensibles.
- Avant toute collecte réelle, connecter et tester un backend sécurisé et faire vérifier le projet.
