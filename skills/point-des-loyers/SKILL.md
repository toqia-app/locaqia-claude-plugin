---
name: point-des-loyers
description: Faire le point des loyers d'un mois dans Locaqia (payés, partiels, impayés, à venir) quand un propriétaire demande « où en sont mes loyers », « qui a payé ce mois-ci » ou un bilan mensuel.
---

# Point des loyers du mois

1. Si le propriétaire ne précise pas le mois, prends le mois en cours. Un mois s'écrit AAAA-MM.
2. Appelle l'outil `loyers_du_mois` du connecteur Locaqia avec ce mois.
3. Présente d'abord les totaux : dû, reçu, reste à encaisser.
4. Puis un tableau court : logement, locataire, dû, reçu, statut. Mets les impayés et les paiements partiels en haut.
5. Termine par une phrase simple : combien de loyers restent à suivre.

Règles :
- Montants en euros, à la française (1 250,00 €).
- Lecture seule : ne propose jamais de modifier Locaqia depuis Claude. Pour enregistrer un paiement ou envoyer une quittance, renvoie vers locaqia.fr.
- Si le connecteur n'est pas relié, explique qu'il faut se connecter à Locaqia dans les connecteurs de Claude.
