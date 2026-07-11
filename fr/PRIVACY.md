# Confidentialité et gestion des données — IFG Returns & Withdrawals

[🇬🇧 English](../README.md) · [🇮🇹 Italiano](../it/PRIVACY.md) · [🇩🇪 Deutsch](../de/PRIVACY.md) · 🇫🇷 **Français** · [🇪🇸 Español](../es/PRIVACY.md)

Cette page décrit comment l'application elle-même collecte, utilise et conserve les données. Elle documente le comportement technique de l'application — elle ne remplace pas la politique de confidentialité globale d'IFG eCommerce, et ne constitue pas un conseil juridique.

## Données collectées

Lorsqu'un client soumet un retour via le formulaire de la boutique en ligne : prénom, nom, adresse de livraison, e-mail, numéro de commande, et facultativement numéro de téléphone et notes. L'application lit également les données de commande depuis Shopify (numéro de commande, e-mail, date de la commande, statut d'exécution) pour vérifier l'authenticité de la demande.

Les marchands fournissent également leurs propres informations légales d'entreprise et leur adresse de retour lors de la configuration guidée, utilisées pour générer des avis de rétractation et des reçus conformes.

## Pourquoi ces données sont collectées

- Pour vérifier qu'une demande de retour correspond à une commande réelle (prévention de la fraude).
- Pour traiter le retour/remboursement et générer les e-mails de confirmation et les reçus PDF.
- Pour respecter les obligations européennes en matière de droits des consommateurs (Directive 2011/83/UE et son amendement 2023/2673), qui exigent l'identification du client et du contrat.

## Avec qui elles sont partagées

- **Shopify** — pour vérifier les commandes et, sur les offres éligibles, émettre directement les remboursements (Shopify Admin API).
- **Envoi d'e-mails** (Nodemailer / Resend) — pour envoyer au client les e-mails de confirmation, de reçu et de mise à jour de statut.
- **Fournisseurs d'IA (Anthropic – Claude ; alternativement Google – Gemini)** — alimentent le chat d'assistance intégré à l'application, utilisé par les marchands pour poser des questions sur l'application. Ils traitent le texte des questions d'assistance du marchand (et non les données de commande des clients) pour générer les réponses. Cela peut impliquer un traitement en dehors de l'UE (États-Unis) dans le cadre de garanties contractuelles appropriées (clauses contractuelles types).

Les données ne sont ni vendues ni utilisées à des fins publicitaires.

## Conservation

Si un marchand désinstalle l'application, ou demande l'effacement des données, les données personnelles du client (nom, e-mail, téléphone, notes) sont anonymisées. Les champs comptables au niveau de la commande (numéro de commande, résolution, montants) sont conservés, anonymisés, car leur conservation est une obligation comptable et fiscale standard (jusqu'à 10 ans) — les enregistrements anonymisés ne peuvent plus être rattachés à une personne identifiable.

## Sécurité

- L'accès à Shopify utilise des jetons d'accès hors ligne à expiration, renouvelés automatiquement — aucun identifiant de longue durée.
- La base de données (Firestore) n'est accessible que via l'identité du service backend propre à l'application ; aucun accès public en lecture ou en écriture n'est possible.

## Questions ou demandes

Pour exercer une demande d'accès ou d'effacement de données, contactez le marchand auprès duquel vous avez passé commande, ou écrivez à [info@ifgecommerce.com](mailto:info@ifgecommerce.com).
