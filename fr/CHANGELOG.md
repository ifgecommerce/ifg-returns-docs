# Journal des modifications — IFG Returns & Withdrawals

[🇬🇧 English](../README.md) · [🇮🇹 Italiano](../it/CHANGELOG.md) · [🇩🇪 Deutsch](../de/CHANGELOG.md) · 🇫🇷 **Français** · [🇪🇸 Español](../es/CHANGELOG.md)

Un historique continu des nouveautés et améliorations. L'application est mise à jour fréquemment à mesure que nous affinons le flux de traitement des retours et du droit de rétractation européen.

## 0.3.207 – 0.3.220 — Juillet 2026
- **Ajout** — Le chat d'assistance intégré à l'application fonctionne désormais avec une véritable IA conversationnelle (Claude, avec repli sur Gemini), se souvient de la conversation au lieu de répondre message par message, et répond dans la langue que vous utilisez.
- **Ajout** — Lorsque vous demandez à parler à une personne, la conversation reste ouverte et la réponse du marchand apparaît désormais directement dans le même chat — fini le « nous vous répondrons par e-mail ».
- **Amélioration** — La page d'assistance a été repensée autour de 20 questions fréquentes clairement expliquées (contre 10 auparavant), entièrement traduites dans les 30 langues ; le chat lui-même se trouve désormais uniquement dans le widget flottant, disponible depuis chaque page.
- **Ajout** — Nouveau paramètre pour définir qui prend en charge les frais d'expédition du retour (client ou marchand), automatiquement indiqué au client sur le formulaire de retour et dans l'e-mail de confirmation.
- **Ajout** — Un rappel juridique suit désormais le délai de remboursement de l'UE à partir de la date de la demande initiale du client, et non à partir du moment où le marchand l'approuve.
- **Correction** — Une commande à colis multiples ne voit plus sa période de retour bloquée simplement parce qu'un colis est encore en transit ; la période démarre désormais une fois que tous les colis sont arrivés.
- **Correction** — Les demandes de retour sur des commandes plus anciennes (périodes de retour supérieures à 60 jours) sont désormais vérifiées correctement au lieu d'afficher « commande introuvable ».
- **Modification** — Les nouvelles installations de l'application démarrent désormais en anglais par défaut, y compris tout au long de la configuration guidée ; la langue de l'interface et des e-mails peut toujours être changée à tout moment vers l'une des 30 langues prises en charge.

## 0.3.206 — Juillet 2026
- **Amélioration** — La vue d'ensemble Statistiques a été repensée en un résumé plus clair à 6 cartes : nombre de retours, taux d'approbation, délai de traitement moyen, remboursements émis, valeur moyenne des articles, et répartition complet/partiel.

## 0.3.205 — Juillet 2026
- **Correction** — Résolution d'une page qui ne se chargeait pas correctement lors du rafraîchissement de session intégrée de l'admin Shopify.
- **Correction** — Les boutons correspondant à des actions déjà effectuées deviennent désormais visiblement inactifs au lieu de conserver une couleur d'action.
- **Amélioration** — Précision accrue du texte de référence juridique décrivant le droit de rétractation de l'UE, dans l'application et sur le formulaire de la boutique en ligne.
- **Correction** — Un graphique à catégorie unique sur la page Statistiques ne s'affiche plus comme une seule barre surdimensionnée ; la mise en page et les étiquettes de catégorie de produit s'adaptent désormais correctement sur les petits écrans.

## 0.3.203 – 0.3.204 — Juillet 2026
- **Amélioration** — Le formulaire de retour de la boutique en ligne est désormais disponible pour les acheteurs partout, avec la même logique de 30 langues et de texte juridique appliquée de façon cohérente.
- **Correction** — Précision de la clause juridique intégrée au formulaire afin de citer avec exactitude la directive sur le droit de rétractation de l'UE et son amendement de 2026.

## 0.3.198 – 0.3.202 — Juin–juillet 2026
- **Ajout** — Refonte du flux de traitement des dossiers : Approuver la demande → Confirmer la réception → sélectionner les articles et le montant → Rembourser, avec une étape de confirmation avant l'émission de tout remboursement.
- **Ajout** — Couleurs de statut distinctes pour chaque étape (en attente, approuvé, partiellement approuvé, remboursé, partiellement remboursé, rejeté), affichées de façon cohérente dans le tableau de bord, la liste des dossiers et la vue détaillée d'un dossier.
- **Amélioration** — Statistiques reconstruites avec des cartes de résumé plus claires et des répartitions par statut/motif.
- **Amélioration** — Le chat d'assistance répond désormais dans la même langue que celle utilisée par le marchand.

## Versions précédentes
Introduction du cœur de l'application : configuration guidée avec paramétrage de l'entité légale et de l'adresse de retour, les trois blocs de retour pour la boutique en ligne (intégré, pop-up et flottant), remboursements directs dans l'application sur les offres éligibles, reçus PDF et export CSV, Restrictions produits, et localisation complète en 30 langues — y compris la mise en page de droite à gauche pour l'arabe et l'hébreu.

---
IFG Returns & Withdrawals — développé par IFG eCommerce. Une question sur une version spécifique ? [info@ifgecommerce.com](mailto:info@ifgecommerce.com)
