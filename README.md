# Locaqia pour Claude

Locaqia (https://locaqia.fr) est une application française de gestion locative pour les propriétaires bailleurs, les SCI et les petits gestionnaires : suivi des loyers, quittances, baux, charges et impôts.

Ce plugin relie Claude à votre compte Locaqia et ajoute trois savoir-faire :

- **point-des-loyers** : le point des loyers d'un mois (payés, partiels, impayés, à venir) ;
- **suivi-impayes** : les locataires qui doivent de l'argent, et un brouillon de relance amiable à relire ;
- **bilan-travaux** : les travaux en cours et les demandes des locataires non résolues.

## Ce que fait le plugin

- Il déclare un seul serveur : le connecteur Locaqia, `https://locaqia.fr/api/mcp` (HTTPS).
- La connexion se fait par OAuth : vous vous connectez à Locaqia et vous acceptez. Vous pouvez retirer l'accès à tout moment.
- **Lecture seule** : Claude lit vos logements, locataires, loyers, travaux et demandes. Il ne modifie rien, n'envoie aucun message et ne déplace pas d'argent.
- Aucun script, aucune commande exécutée, aucun autre service contacté.

## Installation

Dans l'application Claude : Personnaliser › Plugins, puis cherchez Locaqia.

Dans Claude Code :

```
/plugin install locaqia --marketplace toqia-app/locaqia-claude-plugin
```

## Prérequis

Un compte Locaqia avec un espace propriétaire (essai gratuit de 30 jours, puis abonnement).

## Données personnelles

Voir https://locaqia.fr/confidentialite#claude. Aide et mode d'emploi : https://locaqia.fr/connecteur-claude. Contact : contact@locaqia.fr.

## English

Locaqia is a French rental management app. This plugin connects Claude to the landlord's Locaqia account through Locaqia's read-only remote MCP server (OAuth) and adds three skills: monthly rent check, unpaid rent follow-up with draft reminders for the landlord to review, and a works and tenant requests summary. It runs no scripts and sends data nowhere else.

Éditeur : DJO EVENT, Le Havre, France.
