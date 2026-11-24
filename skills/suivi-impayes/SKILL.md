---
name: suivi-impayes
description: Lister les locataires qui doivent de l'argent dans Locaqia et préparer, si on le demande, un brouillon de relance amiable à relire, quand un propriétaire parle d'impayés, de retards ou de relances.
---

# Suivi des impayés

1. Appelle l'outil `impayes` du connecteur Locaqia.
2. Classe les locataires du plus gros solde au plus petit : nom, logement, solde dû, mois concernés.
3. Donne le total dû.
4. Si le propriétaire le demande, rédige un brouillon de relance amiable, courtois et factuel, pour un locataire à la fois : montant, mois concernés, demande de régularisation ou de prise de contact.

Règles :
- Tu ne fais que rédiger : n'envoie jamais rien au locataire. Le propriétaire relit et envoie lui-même, par exemple depuis Locaqia.
- Pas de menace ni de ton juridique dans une relance amiable. Pour une mise en demeure ou un commandement de payer, conseille de se rapprocher d'un commissaire de justice.
- N'invente aucun montant : utilise seulement ceux renvoyés par Locaqia.
