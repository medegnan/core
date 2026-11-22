# F03 — Commercial et ventes

## 1. Fiche d'identité

**Libellé officiel** : F03 Commercial et ventes.

**Mission** : rendre l'entreprise maîtresse de ses clients et de son prix — savoir qui rapporte vraiment, à quel prix vendre, comment vendre plus à ceux qui restent, et comment ne pas prêter son argent à ses clients.

**Protocole principal** — MC-PROTO-F02-F03-V1.0 « Sales & Marketing Engine » : de l'attention à l'encaissement. **Mutualisé avec F02 Marketing et communication**. Les deux fonctions se vendent séparément mais s'exécutent couplées.

**Périmètre** : fonction opérationnelle de rang 1. Point d'entrée commercial fréquent après F08 (quand l'entreprise découvre qu'elle ne gagne pas d'argent sur ses clients).

## 2. Problématiques prises en charge (9 fuites)

| Code | Fuite | Type | Gravité |
| :-: | :-: | :-: | :-: |
| F03-1 | Politique de crédit client sans critères ni plafonds | systémique | CRITIQUE |
| F03-2 | Taux de recouvrement < 80 % | visible | CRITIQUE |
| F03-3 | Ticket moyen stagnant — absence d'upsell et cross-sell | stratégique | MAJEURE |
| F03-4 | Clients rentables non identifiés — énergie égale sur tous | systémique | MAJEURE |
| F03-5 | Prix sous-évalués — braderie inconsciente | comportementale | CRITIQUE |
| F03-6 | Pipeline commercial non suivi — opportunités perdues | systémique | MAJEURE |
| F03-7 | Absence d'offres packages ou formules | stratégique | SECONDAIRE |
| F03-8 | Créances > 90 jours non provisionnées | visible | CRITIQUE |
| F03-9 | Offres complémentaires évidentes non développées | stratégique | CRITIQUE |

Cinq fuites CRITIQUE, trois MAJEURE, une SECONDAIRE. La CRITIQUE la plus silencieuse : F03-5 (braderie inconsciente), à révéler par calcul de marge par client (croisement F08).

## 3. Types de clients éligibles

- Entreprise B2B ou B2C avec portefeuille clients identifiable (≥ 20 clients actifs).
- Pharmacies, officines, cliniques, boutiques, hôtels, restaurants, services aux entreprises.
- Projet de création qui structure sa politique commerciale avant le lancement.
- Pack récurrent avec F08 pour toute entreprise où le dirigeant « travaille pour ses clients et ne gagne pas d'argent ».

Hors périmètre : artisan monoclient (gros donneur d'ordre unique — relève de F12 diversification en priorité), freelance solo.

## 4. Conditions d'intervention

- Audit Flash obligatoire avant F03.
- Fiche de qualification remplie.
- Pièces minimales : journal des ventes 6 mois, fichier clients (même informel), échéancier des créances, grille tarifaire actuelle ou absence de grille documentée, exemples de devis/factures.
- Entretien de position 60 min + revue du cahier des ventes avec le dirigeant.
- ICM calculé.

## 5. Catalogue des prestations commercialisables

Sept prestations types en 4 niveaux :

1. **Diagnostic marge par client et par produit** — Pareto 20/80, clients toxiques identifiés. Déclenche F03-4, F03-5. Interaction forte avec F08 Costing.
2. **Mise en place politique de crédit client** — critères, plafonds, scoring, conditions de paiement. Déclenche F03-1, F03-2, F03-8.
3. **Grille tarifaire recalibrée et braderie éliminée** — révision des prix, formules, options. Déclenche F03-5, F03-7.
4. **Dispositif de suivi du pipeline commercial** — étapes, taux de conversion, cadence de relance. Déclenche F03-6.
5. **Programme upsell / cross-sell** — offres complémentaires systématiques, ticket moyen. Déclenche F03-3, F03-9.
6. **Dispositif de recouvrement structuré** — procédure, lettres types, dépôt juridique seuil. Déclenche F03-2, F03-8.
7. **Packaging commercial (formules, bundles, options)** — abonnements, forfaits, sur-mesure encadré. Déclenche F03-7, F03-9.

Mapping :

- 1, 4 : A (diagnostic) et B (structuration).
- 2, 3, 5, 6, 7 : B et C (redressement).
- Prestation 6 peut évoluer en D (abonnement de suivi de recouvrement).

## 6. Protocoles d'exécution

**MC-PROTO-F02-F03-V1.0** — Sales & Marketing Engine, couplé avec F02. Passes : cadrage, bilan client, bilan produit/service, croisement marge-prix, cadences commerciales, recouvrement.

Chantier identifié : scission éventuelle F02/F03 en deux protocoles distincts à instruire en PHASE 2 bis (F02 à produire après l'ouverture V3). Pour l'instant, F03 travaille sur le volet aval (vente, prix, recouvrement) du protocole mutualisé ; F02 travaillera sur le volet amont (attention, notoriété, acquisition) le moment venu.

## 7. Questionnaires et matrices

- Questionnaire ultra-profond F03 — ~50 questions, chronométré.
- Matrice marge-client (reconstitution) — modèle d'import des ventes et affectation des coûts.
- Grille de scoring crédit client — critères de solvabilité par type de client.
- Grille de cadence de relance — jours, voies (SMS/mail/appel/visite), seuils d'escalade.

## 8. Outils

- Moteur d'analyse — passe d'analyse globale.
- Moteur de raisonnement de dossier.
- Branche sectorielle pharmacie déjà opérationnelle : portefeuille de tables prêtes pour la vente, le ticket, le recouvrement et les créances — directement exploitables pour F03.
- Module CORE F03 à instancier : CRM léger + tableau de bord commercial, transposable au-delà de la pharmacie (clinique, boutique, services).

## 9. Modèles de livrables

- Rapport diagnostic marge-client, avec Pareto 20/80 chiffré.
- Politique de crédit client — procédure + grille scoring.
- Grille tarifaire révisée.
- Dispositif recouvrement — procédure + lettres types.
- Plan upsell/cross-sell.
- Module CORE F03 installé chez le client.

## 10. Contrôles qualité

- Chaque chiffre de marge vient d'une pièce justificative, niveau de preuve explicite.
- Règle des trois réalités : trois sous-totaux (cash sorti, dû non encaissé, non gagné) sur toute restitution.
- Pas de recommandation de hausse de prix brute sans analyse de marché local (risque perte clientèle).
- La révision tarifaire n'est jamais recommandée sans scénario de rebond chiffré (combien de clients perdus tolérable).
- Visa N3 minimum pour type B et C.
- Pour les secteurs sous régulation des prix (pharmacie, carburant, banque, télécoms) : vérification complémentaire des tarifs réglementés.

## 11. Compétences requises pour la vente

- Certification Académie du cabinet valide.
- Licence Spécialiste (avec F03 dans le périmètre) ou Expert Global.
- **Vendable par Licencié** : oui, sous marque MEDEGNAN.
- **Vendable par cabinet externe sous abonnement SaaS** : oui, sous sa propre marque, avec mention technique « Produit avec MEDEGNAN CORE ». Les six conditions des professions réglementées s'appliquent de plein droit pour les pros réglementés souscripteurs externes.

## 12. Conditions d'habilitation

- Habilitation ACTIVE sur F03.
- Grade minimum N1 (A), N2 (B), N3 (C et D).
- Prestation 6 (recouvrement) : grade N3 obligatoire (risque contentieux sur mises en demeure).

## 13. Relations avec les autres fonctions

- **F08 Administration et finance** : dépendance mécanique. F03 produit la matière brute (ventes, créances), F08 mesure la marge réelle par client. Pack récurrent F03+F08.
- **F02 Marketing et communication** : jumelle. F02 amène l'attention, F03 convertit. Pack naturel.
- **F06 Production et services** : F03 vend ce que F06 produit. Coupler prix de vente à costing réel F06.
- **F10 Juridique et conformité** : dépendance pour les contrats clients (fuite F10-1), les conditions générales de vente, les lettres de mise en demeure.

## 14. Limites

- F03 ne rédige pas de contrat client (relève de F10 + avocat tiers).
- F03 ne poursuit pas en justice un client (relève d'un avocat).
- F03 ne force pas une hausse de prix sans marge de manœuvre marché.
- F03 ne recommande jamais de pratique commerciale trompeuse (droit de la consommation).
- Pas de prestation distance pure sur la 2 (politique de crédit) : revue des clients effectifs sur site recommandée.

## 15. Compétences et certifications réglementées exigées

Secteurs à vérification complémentaire :

- **Pharmacie** : prix réglementés par les autorités sanitaires selon pays.
- **Télécoms, carburant, banque, assurance** : tarifs encadrés par régulateurs sectoriels.
- **Pro réglementés hors Réseau (avocats, EC, notaires)** souscripteurs externes : F03 vendable sous les six conditions des professions réglementées, zéro commission sur honoraires, sous leur propre marque.


---

**Édité par MEDEGNAN CONSULTING, Cotonou (Bénin).** Licence Apache 2.0. Dernière mise à jour : 22 novembre 2026.
