# F09 — Information, données et outils de gestion

## Préambule — Pourquoi une "unité Professionnelle" F09, et pour qui

  

L'écosystème MEDEGNAN a changé de nature le 21 novembre 2026. L'architecture V2.3 adoptée ce jour-là transforme le Portail en infrastructure d'exécution de conseil ouverte à deux publics distincts : d'une part les consultants et cabinets du Réseau MEDEGNAN (statuts S1 à S4), d'autre part les consultants et cabinets externes qui souscrivent la plateforme SaaS MEDEGNAN sans être certifiés par le cabinet. Les douze fonctions CORE (F01 à F12) ne sont plus seulement une taxonomie méthodologique : elles deviennent des périmètres de commercialisation, des unités de travail et des points d'habilitation.

  

F09 Information, données et outils de gestion appartient à la couche transversale du modèle. Sans F09, F08 pilote un chiffrage sans socle, F03 vend sans fichier client, F05 déplace du stock sans visibilité, F06 produit sans traçabilité, F07 gère des personnes sans historique. F09 n'est pas la fonction de ce que l'entreprise fait, c'est la fonction de ce qu'elle sait sur ce qu'elle fait. Un diagnostic F09 bien conduit est souvent le préalable invisible qui rend les autres fonctions exécutables.

  

Le piège de F09 est permanent et il doit être rappelé en tête. L'informatique attire les recommandations spectaculaires et inutiles. Un consultant qui débarque sur un terrain PME africain et recommande un ERP à vingt millions sans avoir vérifié où est le courant, qui saisit, comment on sauvegarde et combien coûte la connexion a produit une solution qui n'en est pas une : c'est une panne différée. La doctrine permanente du protocole F09 adoptée le 28 septembre 2026 pose trois verrous de périmètre, à mémoriser avant tout entretien : (R1) l'engine ne vend pas de logiciel — il établit un besoin, chiffre un coût de non-qualité et définit des critères de choix ; les noms de produits changent vite et varient par pays, aucun outil ne se cite comme recommandation ferme, aucune commission d'éditeur n'est acceptée. (R2) Le problème est rarement technique — dans la très grande majorité des PME visées, ce qui manque n'est pas un logiciel, c'est une règle : qui saisit quoi, quand, sous quel format, et qui vérifie. (R3) Toute recommandation doit survivre au terrain — électricité intermittente, connexion instable ou coûteuse, compétence rare, support éditeur inexistant localement ; une solution qui suppose du courant continu et une connexion permanente n'est pas une solution.

  

Le contexte africain impose un rappel supplémentaire. La PME que F09 rencontre majoritairement marche aujourd'hui sur un trépied : Excel, un cahier, la mémoire du gérant. Ce trépied tient par la personne du dirigeant ; il tombe le jour où le dirigeant tombe. Le registre MEDEGNAN d'échecs africains documente abondamment les entreprises perdues parce que leur fichier client vivait dans la tête d'une seule personne, parce que la liasse comptable vivait dans un ordinateur volé, parce que les formules vivaient dans un carnet brûlé. F09 travaille sur ce point faible-là, plus que sur le manque d'ERP : rendre le patrimoine informationnel de l'entreprise survivable à la perte de l'une de ses personnes.

  

Le présent dossier s'adresse à trois lectorats distincts, dans cet ordre. Un Licencié Spécialiste ou Expert Global du Réseau MEDEGNAN (S3 principalement, S2 sous supervision) qui doit vendre et exécuter une mission F09 chez un client. Un Consultant Intégré (S1) ou Partenaire (S2) qui prend en charge pour le compte du cabinet une mission F09 dispatchée par le Portail. Un cabinet externe souscripteur la plateforme SaaS MEDEGNAN (SX) qui mobilise l'infrastructure pour exécuter sa propre mission F09 chez son client, sous sa marque, sans être partie à un contrat de licence MEDEGNAN.

  

Le document ne couvre pas la fourniture d'équipement, la prestation d'hébergeur, le développement sur mesure d'un logiciel vendu à l'extérieur du cabinet, et il ne traite des données personnelles que dans leur articulation technique à F09 ; l'obligation juridique proprement dite reste de la main de F10.

  

Doctrine permanente rappelée en tête : (1) la comparaison entre deux documents se fait sur le contenu, pas sur la référence ; cette V1 absorbe le protocole MC-PROTO-F09-V1.2 et le MUDCF parce qu'elle les enveloppe dans la forme d'unité professionnelle, pas parce qu'elle les remplace — ils restent, chargés en méthode texte, et le consultant les mobilise à leur phase. (2) Ce que F09 identifie et chiffre, c'est le moteur qui le fait, sous le regard et avec le jugement du consultant — règle du 26 septembre 2026 : le consultant ne saisit jamais lui-même les fuites, il peut en revanche introduire les montants oraux du dirigeant quand les pièces n'existent pas. (3) Chaque mission F09 place ou crée un module CORE : jamais de prescription "Excel" quand un module propriétaire existe ou peut être construit — doctrine des 16 et 17 novembre 2026, le catalogue CORE est une bibliothèque vivante que chaque mission fait grandir.

  

Enfin, deux règles de méthode propres à F09 sont rappelées avant toute mission. Première règle : F09 commence toujours par un audit des DÉCISIONS que le dirigeant doit prendre, puis des DONNÉES qu'il lui faut pour les prendre — jamais par le catalogue d'outils dont il pourrait disposer. Un consultant qui ouvre une mission F09 en demandant "avez-vous un ERP ?" a inversé la pyramide et a perdu le dossier. L'ouverture correcte est : "quelle décision n'avez-vous pas pu prendre ce mois-ci faute d'information fiable ?". Deuxième règle : F09 ne construit jamais pour la techno la techno. Un outil qui ne sert aucune décision concrète du dirigeant, aussi beau soit-il dans sa démonstration, est un coût, pas un actif. Le test de ce principe est simple et inscrit en contrôle qualité : pour chaque outil retenu, nommer la décision du dirigeant qu'il sert ; si aucune décision ne se nomme, l'outil n'entre pas.

  
  

## Item 1 — Fiche de Présentation

  

Nom officiel et code

  

Nom officiel : F09 — Information, données et outils de gestion. Libellé en base (table public.fonction\_core, code F09, ordre 9). Dans l'écosystème professionnel V2.3, F09 est la neuvième des douze fonctions CORE, en position transversale : elle est appelée par F01 (quand la gouvernance exige un tableau de bord), par F03 (quand la vente a perdu son fichier client), par F05 (quand le stock n'est pas visible), par F06 (quand la production n'a pas sa traçabilité), par F07 (quand la paie est encore à la main), par F08 (quand la comptabilité est en retard de six mois) et par F10 (quand la donnée personnelle demande une mise en conformité technique). Elle appelle de son côté F08 pour le chiffrage du coût de non-qualité et F07 pour la conduite du changement humain.

  

Raison d'être

  

F09 aide une entreprise à savoir ce qu'elle sait, à savoir où ce savoir est, à savoir ce qu'il vaut, à savoir qui peut le perdre, et à construire les outils qui permettent au dirigeant de décider sans se tromper. Cette phrase, directement reprise du PROTO F09 V1.2, décompose cinq verbes qui commandent cinq prestations distinctes.

  

Savoir ce qu'elle sait : c'est l'audit du système d'information. Pas un audit technique au sens des grands cabinets internationaux, qui part des infrastructures : un audit au sens MEDEGNAN qui part de la donnée réellement utilisée pour décider. On suit une information de bout en bout — par exemple une commande, depuis l'appel du client jusqu'au dépôt sur le compte bancaire — et l'on note où elle vit, comment elle change de main, qui la connaît, qui ne la connaît pas. La méthode de cartographie du PROTO F09 phase T1 est l'outil doctrinal de cette prestation.

  

Savoir où ce savoir est : c'est la cartographie des outils de gestion. Elle recense non seulement les logiciels installés mais aussi le téléphone personnel du dirigeant qui concentre les commandes WhatsApp, le cahier du magasinier, les fichiers Excel renommés chaque mois, les groupes WhatsApp qui servent de messagerie commerciale, les comptes personnels utilisés pour l'activité professionnelle. Le terrain a ceci de particulier que la moitié du système d'information de la PME africaine vit dans des outils non déclarés comme tels.

  

Savoir ce qu'il vaut : c'est la hiérarchisation des données vitales. Une donnée vitale, selon le PROTO F09 phase T1.3, est une donnée dont la perte provoquerait un arrêt ou une perte irrattrapable : fichier client, formule, historique de prix d'achat, dossier patient, livre de paie, factures non payées. Hors des données vitales, le reste est remplaçable. F09 produit cette hiérarchie parce que c'est elle qui commande la politique de sauvegarde, la politique de sécurité et, le cas échéant, la décision d'investir dans un outil propriétaire ou de rester sur un tableur.

  

Savoir qui peut le perdre : c'est la politique de sécurité, de sauvegarde et d'accès. La règle des trois copies, le test de restauration, la fermeture des comptes des personnes parties, la séparation des rôles qui ne laisse jamais à une seule personne le pouvoir de masquer une fraude, la protection physique contre la foudre, la chaleur, l'humidité et les nuisibles — tout ce que le PROTO F09 phase T3 traite en détail.

  

Décider sans se tromper : c'est le tableau de bord dirigeant. Pas une page Excel à vingt indicateurs qui ne sera jamais regardée, mais un socle de pilotage à trois ou quatre indicateurs qui engagent une décision. Le PROTO F09 phase T4 pose la règle : partir de l'indicateur, jamais de l'outil ; définir la donnée minimale viable ; établir le référentiel (produits, clients, catégories) ; fixer le rythme et le responsable.

  

Périmètre d'intervention

  

F09 couvre, sans restriction : (a) l'audit du système d'information existant — cartographie, qualité, continuité, sécurité, accès ; (b) la définition et la mise en œuvre d'un socle de données de pilotage — tableau de bord dirigeant, référentiels produits/clients/catégories ; (c) le choix et le déploiement d'un logiciel métier — ERP léger, logiciel de caisse, CRM, outil de gestion comptable, logiciel de paie ; (d) la politique de données — collecte (MUDCF), qualité, sécurité, sauvegarde, accès ; (e) la digitalisation pas-à-pas d'une PME — par paliers, du moins coûteux au plus lourd ; (f) la conduite du changement et la formation à l'usage des outils ; (g) la protection technique des données personnelles au sens des législations UEMOA, CEMAC et, pour les flux diaspora ou export, du RGPD européen.

  

Exclusions

  

F09 ne couvre pas, par construction :

  

– La vente d'un logiciel. F09 fait le besoin, le cahier des charges et le critère de choix. La fourniture du logiciel est faite par un éditeur ou un intégrateur tiers, facturée directement au client (modèle à 3 factures V2.3). L'exception strictement bornée est le module MEDEGNAN CORE propriétaire du cabinet (la branche sectorielle MEDEGNAN (pharmacie) pour la pharmacie, modules sectoriels à venir), qui se place sous abonnement et dont le premier client paie la construction via sa mission, les suivants payant l'abonnement — doctrine du 17 novembre 2026.

  

– La prestation d'hébergeur. F09 établit où doivent vivre les données (hors ligne d'abord, en ligne ensuite, choix de juridiction), mais le cabinet n'est pas hébergeur et ne contractualise jamais un hébergement en son nom pour un tiers.

  

– La maintenance curative d'infrastructure informatique dans la durée. Le PROTO F09 phase T5.5 pose la règle : la dépendance à un prestataire se traite par l'exigence de documentation, de réversibilité et par la formation de plusieurs personnes en interne chez le client — F09 ne se substitue pas au prestataire courant du client.

  

– La réalisation d'actes juridiques liés aux données personnelles. Les mentions légales, la politique de confidentialité, la déclaration éventuelle à l'autorité de protection, la rédaction des clauses contractuelles de sous-traitance sont affaire de F10 avec appui d'un avocat spécialisé.

  

– La fourniture de matériel informatique. F09 recommande le dimensionnement, les critères, la stratégie de parc (réparer avant de remplacer, PROTO F09 phase T5.6), mais ne vend ni ordinateur, ni routeur, ni onduleur.

  

Fonction dans l'écosystème professionnel V2.3

  

F09 est de rang 9, positionnée en transverse. Elle peut être vendue seule (sous l'appellation "Audit SI" ou "Tableau de bord dirigeant") mais elle est, le plus souvent, un sous-ensemble d'une mission plus large — un diagnostic 360 PME qui agrège F01+F08+F09 est le pack le plus fréquent. Elle peut également être appelée à n'importe quel moment d'une mission qui révèle un trou documentaire que le client ne peut plus ignorer. F09 est la fonction qui transforme une mission ponctuelle en relation durable, parce qu'elle laisse derrière elle un outil et un abonnement que le client exploite au quotidien — logique d'ancrage du cabinet que la doctrine de distribution du 16 novembre 2026 inscrit dans l'ADN du réseau.

  

Cas d'ouverture typiques

  

La demande qui ouvre un dossier F09 se présente, dans l'expérience du cabinet et dans la base des leads entrés depuis septembre 2026, sous l'une des huit formes suivantes : "je ne sais pas combien j'ai en stock", "je n'ai pas de tableau de bord, je décide à l'instinct", "je veux informatiser mais je ne sais pas par où commencer", "j'ai acheté un logiciel il y a deux ans, personne ne l'utilise", "j'ai perdu mon fichier client quand mon disque a lâché", "mon banquier me demande un reporting mensuel que je n'arrive pas à produire", "je veux mettre en ligne et je ne sais pas quoi publier", "je viens d'embaucher quelqu'un qui me pose cent fois la même question parce qu'il n'y a rien d'écrit". Ces huit formes sont la grille d'écoute de pré-qualification F09 détaillée à l'Item 5.

  
  

## Item 2 — Catalogue des Prestations Commercialisables sous F09

  

Le catalogue F09 comporte huit prestations principales. Il assume la logique du PROTO F09 phase T0.1 — la saisine arrive sous l'une des cinq entrées documentées A à E —, prolongée par trois prestations transverses qu'une saisine amène rarement en direct mais qu'un diagnostic élémentaire révèle presque toujours (politique de données, protection des données personnelles, conduite du changement). Chaque prestation est déclinée en quatre niveaux tarifaires (Essentiel, Complet, Premium, Sur devis), conformément à la grille MC-GRILLE-TARIFAIRE-V3.2 et à l'inscription en base (table public.offre\_catalogue). Les prix présentés ci-dessous combinent les lignes actuellement inscrites en base (F4-ERP, F4-TRANSFORMATION-DIGITALE, F6-DIGITALISATION-INSTITUTION — confirmées) et des lignes "hypothèse à calibrer" que le fondateur doit valider à la session de calibrage V3.3 prévue en PHASE 2.

  

Note préalable obligatoire pour toute prestation F09 : l'Audit Flash à 250 000 FCFA (MC-GRILLE-TARIFAIRE-V3.2, produit d'entrée systématique pour toute entreprise de moins de cinquante salariés) est le passage préalable à toute prestation F09, sauf pour la prestation P1 (Audit SI complet) qui, dès qu'elle est vendue en direct, inclut en son sein un volet Audit Flash — le client ne paie pas deux fois. L'arbitrage du 28 octobre 2026 est rappelé : l'Audit Flash n'est plus obligatoire pour toute entreprise de moins de cinquante salariés, il faut écouter le prospect ; sur F09 toutefois, la pratique du cabinet démontre que s'en passer conduit à vendre un outil à côté du vrai problème, donc on le propose comme règle et on ne s'en écarte qu'en connaissance de cause.

  

Prestation P1 — Audit SI complet

  

Objet : diagnostic de bout en bout du système d'information existant, y compris les systèmes invisibles. Produit un rapport qui qualifie la situation parmi les quatre cas du PROTO F09 phase T1.4 (rien / sous-exploité / fragmenté / abandonné), recense les données vitales, pointe les ruptures de continuité, les failles d'accès, les expositions à la fraude facilitée, et trie les urgences en six critères (PROTO phase T0.2).

  

Niveau Essentiel : PME de moins de 10 salariés, mono-site, mono-logiciel. Audit sur site d'une journée, livré sous huit jours. Prix : 600 000 FCFA.

Niveau Complet : PME de 10 à 50 salariés, mono-site ou deux sites proches, parc logiciel standard (deux à quatre outils). Audit sur site de deux jours, livré sous quinze jours. Prix : 1 500 000 FCFA.

Niveau Premium : ETI de 50 à 250 salariés, multi-site ou parc hétérogène, exigences de reporting bancaire ou de conformité. Audit sur site de quatre à cinq jours, livré sous trente jours. Prix : 4 500 000 FCFA.

Niveau Sur devis : groupes, entreprises à plus de 250 salariés, missions d'audit avec contrainte de certification externe. Prix sur devis, plancher 8 000 000 FCFA.

  

Livrables : rapport d'audit SI structuré selon les 7 phases du PROTO F09 (T0 à T7 reportés en chapitres), fiche de hiérarchie des données vitales, registre des cinquante-trois contrôles exécutés avec écart, fiche des trois priorités d'action du mois qui suit.

  

Prestation P2 — Tableau de bord dirigeant

  

Objet : construire, chez le client, un socle de pilotage à trois ou quatre indicateurs engageant une décision du dirigeant. Pas un reporting à vingt courbes qui ne sera pas regardé. La prestation applique la discipline de MC-REGLE-INDICATEUR-PROUVE-V1 (un indicateur favorable ne naît pas de l'absence d'un signal défavorable) et la doctrine de présentation du chiffrage arrêtée le 19 septembre 2026 (jamais un total général, toujours trois sous-totaux : sorti de caisse, dû non payé, non gagné).

  

Niveau Essentiel : trois indicateurs, un seul produit/service, rythme hebdomadaire. Modèle Excel verrouillé + une journée de formation. Prix : 500 000 FCFA.

Niveau Complet : cinq indicateurs, trois à cinq axes d'analyse (produit, canal, zone), rythme hebdomadaire et mensuel. Modèle Excel verrouillé + une journée de calibrage avec le dirigeant + deux journées d'accompagnement sur un mois. Prix : 1 200 000 FCFA.

Niveau Premium : tableau de bord instancié dans un module CORE propriétaire du cabinet (quand le secteur est couvert, par exemple la branche sectorielle MEDEGNAN (pharmacie) pour la pharmacie) ou dans un outil du marché calibré, intégration des règles d'alerte, accompagnement de trois mois. Prix : 3 500 000 FCFA plus abonnement mensuel du module CORE.

Niveau Sur devis : groupe multi-filiales, consolidation croisée, reporting au bailleur.

  

Livrables : rapport de calibrage (indicateurs retenus, formule de calcul, source de la donnée, seuils d'alerte), modèle verrouillé, cahier de rituel de revue (qui regarde quoi, quand), fiche de gouvernance de la donnée (qui saisit, qui contrôle).

  

Prestation P3 — Choix de logiciel métier

  

Objet : conduire un choix d'outil sur la base de critères (PROTO F09 phase T5.2), non sur un nom. Déroule les neuf critères C1 à C9 — fonctionne hors ligne, support dans le pays, conforme au droit local, données exportables, coût total sur trois ans, simplicité, intégration aux moyens de paiement réellement utilisés, cohérence avec l'existant, utilisable au téléphone quand c'est l'outil réel — et produit un verdict pondéré.

  

Niveau Essentiel : un besoin ciblé (caisse, facturation, paie), trois à cinq éditeurs comparés. Prix : 400 000 FCFA.

Niveau Complet : deux à trois besoins croisés (ERP léger, CRM, caisse), cinq à huit éditeurs comparés, atelier de restitution avec le dirigeant. Prix : 1 100 000 FCFA.

Niveau Premium : ERP complet, inclut la définition du besoin, l'appel d'offres informel auprès de cinq éditeurs, la négociation, la rédaction du contrat de licence et d'intégration avec clauses de réversibilité et de documentation. Prix : 3 000 000 FCFA.

Niveau Sur devis : appel d'offres formel, groupe multi-filiales.

  

Livrables : cahier des charges, grille comparative pondérée, fiche de préconisation, projet de contrat (clauses techniques ; le contrat juridique lui-même part chez l'avocat).

  

Prestation P4 — Déploiement et conduite du changement

  

Objet : déployer un outil déjà choisi (ou acheté par le client sans que F09 ait conduit le choix) selon la discipline du PROTO F09 phase T5.4. Cadence par cycles courts (T5.4 ter), reprise des données nettoyées, procédure dégradée écrite, rattrapage, formation adaptée à qui saisit vraiment et à son aisance à l'écrit (règle T5.4 — observer avant de former).

  

Niveau Essentiel : un outil, moins de cinq utilisateurs, moins d'un mois de déploiement. Prix : 700 000 FCFA.

Niveau Complet : deux outils ou cinq à vingt utilisateurs, un à trois mois. Inclut reprise des données, procédure dégradée, formation. Prix : 2 000 000 FCFA.

Niveau Premium : ERP complet, vingt à cent utilisateurs, trois à six mois. Prix : 6 000 000 FCFA.

Niveau Sur devis : intégration multi-sites, interfaçages lourds.

  

Livrables : plan de déploiement, procès-verbal du test de vérité (annoncé avant, formulé sur le résultat), journal des incidents avec responsable nommé, calendrier d'entretien.

  

Prestation P5 — Politique de données

  

Objet : écrire la politique de données de l'entreprise : classification des données (vitale, sensible, courante, publique), règles de collecte (MUDCF appliqué), règles de saisie (qui, quand, format), règles de qualité et contrôles périodiques, règles d'accès et de séparation des rôles, règles de sauvegarde (trois copies dont une hors site déconnectée, test de restauration), règles d'export, règles de suppression en fin de vie du matériel.

  

Niveau Essentiel : politique écrite sur gabarit, un atelier avec le dirigeant, une page de procédure par règle. Prix : 500 000 FCFA.

Niveau Complet : politique écrite, trois ateliers (dirigeant, chefs de pôle, saisie quotidienne), accompagnement de la première application sur un mois. Prix : 1 500 000 FCFA.

Niveau Premium : politique écrite, articulation à la conformité OHADA/UEMOA/CEMAC, articulation au RGPD pour flux diaspora, revue annuelle intégrée au contrat. Prix : 4 000 000 FCFA annuel.

Niveau Sur devis : groupe, filiales, flux transfrontaliers lourds.

  

Livrables : politique de données MEDEGNAN datée et signée par le dirigeant, cahier des procédures (une par règle), registre des traitements, fiche des trois copies, cahier du test de restauration.

  

Prestation P6 — Protection des données personnelles — mise en conformité technique

  

Objet : mise en conformité technique du traitement des données personnelles. F09 en pose la part technique ; la part juridique (déclaration à l'autorité, rédaction des mentions légales, clauses contractuelles de sous-traitance, politique de confidentialité) reste de la main de F10. La frontière est explicite : F09 fait les gestes (minimisation, journalisation, chiffrement, cloisonnement), F10 fait les actes.

  

Niveau Essentiel : petit traitement, un fichier client, un bulletin de paie. Prix : 450 000 FCFA.

Niveau Complet : trois à cinq traitements, articulation UEMOA (loi-type et transpositions nationales) ou CEMAC, cartographie des flux, fiches de traitement. Prix : 1 400 000 FCFA.

Niveau Premium : ajoute l'articulation au RGPD européen pour flux diaspora ou export, due diligence des sous-traitants, clauses contractuelles types rédigées par F10. Prix : 3 800 000 FCFA.

Niveau Sur devis : traitements sensibles (santé, finance, biométrie), transferts transfrontaliers multiples.

  

Livrables : cartographie des flux, fiches de traitement, carte des données personnelles et des secrets (format inspiré de LOT3\_\_CARTE\_DONNEES\_PERSONNELLES\_ET\_SECRETS déjà connu du cabinet), journal des accès, plan de mise en conformité priorisé, renvoi de dossier à F10 pour la part actes.

  

Prestation P7 — Digitalisation pas-à-pas d'une PME

  

Objet : accompagner une PME qui marche encore sur Excel + cahier + mémoire vers un socle numérique complet, par paliers successifs (PROTO F09 phase T5.1 — cinq paliers, du moins coûteux au plus lourd). Palier 0 : supprimer avant d'outiller (ce que le gérant écrit deux fois, trois fois, à retirer). Palier 1 : un tableur verrouillé bien construit. Palier 2 : un outil ciblé (caisse ou facturation). Palier 3 : un outil intégré (ERP léger). Palier 4 : un module métier propriétaire (CORE) ou un ERP complet.

  

Niveau Essentiel : paliers 0 et 1, trois mois. Prix : 1 200 000 FCFA.

Niveau Complet : paliers 0 à 2, six mois. Prix : 3 500 000 FCFA.

Niveau Premium : paliers 0 à 3 ou 4, neuf à douze mois, avec installation d'un module CORE quand le secteur est couvert. Prix : 8 000 000 FCFA, plus abonnement mensuel du module CORE.

Niveau Sur devis : transformation digitale complète d'une ETI.

  

Le prix d'entrée de cette prestation est articulé à la ligne F4-TRANSFORMATION-DIGITALE déjà inscrite en base (800 000 / 1 800 000 / 4 000 000 FCFA), avec une recommandation de recalibrage V3.3 vers le haut pour aligner sur le périmètre réel (paliers 0 à 4).

  

Livrables : cahier des paliers (ce que chaque palier achève et ce qu'il laisse en suspens), tableau de bord d'avancement (indicateur par palier), plan de formation étalé, plan de sauvegarde activé dès le palier 1, plan de reprise d'activité activé dès le palier 2.

  

Prestation P8 — Développement ERP sur mesure (prestation complémentaire ; en pratique dérivée d'un module CORE propriétaire)

  

Objet : développer ou adapter un outil de gestion complet et sectorisé. Ligne inscrite en base sous F4-ERP (4 000 000 / 10 000 000 / 30 000 000 FCFA). Attention de méthode : la doctrine du 17 novembre 2026 et l'architecture MC-ARCHI-CORE-V2 recommandent de capitaliser dans un module CORE propriétaire plutôt que de construire un ERP ad hoc par client. En pratique, P8 signifie le plus souvent "instancier un module CORE pour ce client, en finançant via la mission la part de développement qui manque et en facturant un abonnement récurrent au-delà". La prestation reste au catalogue pour les cas où aucune mutualisation n'est possible (secteur isolé, exigences contractuelles de propriété intellectuelle exclusive).

  

Niveau Essentiel : adaptation d'un module CORE existant, paramétrage client. Prix : 4 000 000 FCFA plus abonnement.

Niveau Complet : construction d'un module CORE sectoriel nouveau à partir d'un besoin révélé par la mission (premier client finance, suivants paient l'abonnement). Prix : 10 000 000 FCFA plus abonnement.

Niveau Premium : ERP sectoriel profond avec intégrations multiples. Prix : 30 000 000 FCFA plus abonnement.

Niveau Sur devis : développement spécifique sans mutualisation.

  

Zones à préciser avec le fondateur sur les tarifs — toutes à calibrer en session V3.3 :

  

Prestation P1 — tarifs Essentiel/Complet/Premium (actuellement hypothèse ; aucune ligne F09 pure n'est inscrite en base).

Prestation P2 — tarifs et modèle d'abonnement des modules CORE associés (dépend de la grille Famille 8 en cours de finalisation).

Prestation P3 — tarifs des niveaux Essentiel et Complet (hypothèse).

Prestation P5 — tarif annuel du niveau Premium (hypothèse, dépend du modèle de revue annuelle).

Prestation P6 — ventilation UEMOA/CEMAC vs RGPD (hypothèse de prix différencié à trancher).

Prestation P7 — recalibrage V3.3 : la ligne F4-TRANSFORMATION-DIGITALE en base est sous-tarifée pour le périmètre réel.

Prestation P8 — ratio mission versus abonnement récurrent du module CORE (hypothèse 70/30 à 50/50 selon secteur).

  
  

## Item 3 — Référentiel des Problématiques Traitées

  

Les problématiques F09 inscrites en base (table public.fuite\_referentiel) sont au nombre de huit, de F09-1 à F09-8. Toutes sont classées par gravité et par type. Elles sont rappelées ici dans leur libellé de base et chacune est enveloppée dans son cadre d'analyse propre : le signal qui la fait apparaître dans un entretien, le signal plus faible qui la fait apparaître dans les pièces, la fuite chiffrable qu'elle entraîne (en FCFA par mois, pour que le consultant puisse l'articuler à la grille MC-REGLE-INDICATEUR-PROUVE-V1), le levier F09 qui la traite, et le pack de prestations qui s'y applique. Rappel permanent : le consultant ne saisit jamais une fuite par lui-même ; il apporte la matière (entretien, pièces, montants oraux), et c'est le moteur qui qualifie et chiffre, avec revue humaine à partir du grade N5 (doctrine du 19 septembre 2026).

  

F09-1 — Décisions prises sans données — tableaux de bord absents. Type : technologique. Gravité : CRITIQUE. Cause-type : pas d'investissement outils, résistance au changement. Signal entretien : le dirigeant répond à toutes les questions chiffrées par "je dirais" ou "autour de", sans produire la pièce. Signal pièce : le compte de résultat annuel est le seul document chiffré exhibé, aucun tableau mensuel n'est détenu. Fuite typique : décisions d'investissement mal calibrées (surstock, souscapacité), perte d'opportunités commerciales faute de signal, dérive inaperçue d'un indicateur jusqu'au point de rupture. Chiffrage : selon logique économique (L1 à L6 du Module Métier), l'ordre de grandeur se situe entre deux et huit pour cent du chiffre d'affaires annuel, à affiner par cas. Levier F09 : prestation P2 (Tableau de bord dirigeant) préalable à P5 (politique de données). Pack recommandé : P2 Essentiel ou Complet selon taille.

  

F09-2 — Données dispersées — Excel, cahier, mémoire — non centralisées. Type : technologique. Gravité : MAJEURE. Cause-type : absence de système central, outils multiples non intégrés. Signal entretien : chaque donnée demandée amène le dirigeant à appeler une personne différente ou à chercher dans un fichier différent. Signal pièce : le même produit porte deux codes différents dans deux fichiers du même service ; le même client porte deux noms différents sur deux factures ; le livre des ventes et le compte bancaire ne se recoupent pas sans effort. Fuite : temps perdu en recherche et en réconciliation (évaluable par la règle T2.1 du PROTO F09 — six défauts à chercher), décisions prises sur la base d'un fichier périmé, erreurs de facturation. Levier F09 : prestation P5 (politique de données) et prestation P2 (socle de pilotage) ; en cas d'engagement budgétaire, P7 (digitalisation palier 1 puis 2). Pack recommandé : P5 Essentiel avec option P7 palier 1.

  

F09-3 — Logiciel de caisse mal utilisé — fonctionnalités inexploitées. Type : comportementale. Gravité : MAJEURE. Cause-type : pas de formation, utilisation minimale. Signal entretien : le dirigeant détient un logiciel de caisse ou de gestion de point de vente, mais ses états mensuels proviennent du cahier manuscrit de la vendeuse. Signal pièce : le relevé du logiciel montre des ventes très inférieures aux encaissements bancaires. Fuite : fonctionnalités payées non utilisées (gâchis d'abonnement), absence de visibilité sur les ventes par produit (impossibilité de piloter l'assortiment), vol facilité par l'absence de rapprochement ventes/caisse. Levier F09 : prestation P4 (déploiement et conduite du changement, phase de reprise), prestation P2 (socle de pilotage branché sur la caisse). Pack recommandé : P4 Essentiel + P2 Essentiel.

  

F09-4 — Absence de sauvegarde données — risque perte totale. Type : technologique. Gravité : CRITIQUE. Cause-type : non-priorité, manque de culture data. Signal entretien : à la question "que se passe-t-il si votre ordinateur tombe en panne demain matin ?", le dirigeant répond "j'ai tout dedans". Signal pièce : aucun test de restauration n'a été fait, aucun support de sauvegarde n'est présenté, les fichiers vitaux (fichier client, formules, compta) sont localisés sur un seul poste. Fuite : perte totale à l'horizon statistique d'un incident matériel, avec reconstitution impossible du fichier client (donnée vitale indisponible). Levier F09 : règle des trois copies (PROTO F09 phase T3.1), test de restauration daté. Pack recommandé : P5 Essentiel, en urgence si CRITIQUE classé rang 1.

  

F09-5 — Réseaux sociaux non connectés aux outils de vente. Type : technologique. Gravité : CRITIQUE. Cause-type : absence de stratégie digitale intégrée. Signal entretien : le commerce se fait majoritairement sur WhatsApp Business, Facebook ou Instagram, et aucune trace n'est reversée dans un outil de gestion. Signal pièce : les commandes WhatsApp vivent sur le téléphone personnel du dirigeant, les leads Facebook ne sont pas rappelés, la facturation est faite à la main sur un cahier différent. Fuite : taux de conversion faible (lead non rappelé), fichier client qui ne survit pas à la perte du téléphone, impossibilité de mesurer la rentabilité par canal. Levier F09 : cartographie des canaux (PROTO F09 phase T1.6), outillage CRM léger ou intégration des réseaux sociaux à un socle. Pack recommandé : P3 Essentiel (choix CRM compatible mobile) + P4 Essentiel + P5 Essentiel.

  

F09-6 — Commandes manuelles — saisie répétitive chronophage. Type : systémique. Gravité : MAJEURE. Cause-type : pas d'automatisation, culture papier dominante. Signal entretien : la commande passe par trois personnes qui la ressaisissent chacune (téléphone, bon manuscrit, saisie compta). Signal pièce : les trois saisies du même événement divergent (prix, quantité). Fuite : temps de saisie multiplié par trois, erreurs cumulatives, retard de facturation. Levier F09 : règle T2.1 du PROTO F09 — une donnée se saisit une seule fois à la source ; conception du palier 2 avec outil intégré. Pack recommandé : P7 paliers 0 à 2.

  

F09-7 — Absence de CRM — historique client perdu. Type : technologique. Gravité : MAJEURE. Cause-type : pas d'investissement, complexité perçue. Signal entretien : le dirigeant ne sait pas dire quand il a servi un client pour la dernière fois, quel est le panier moyen, quel est le taux de réachat. Signal pièce : les factures sont classées par ordre chronologique, pas par client ; le relancement des impayés est fait en recherchant dans les boîtes mail. Fuite : perte du client dormant (clientèle qui existe mais n'est plus relancée), impossibilité d'offres ciblées, perte de valeur à la cession (le fichier client est l'actif principal selon la logique L2 du Module Métier). Levier F09 : prestation P3 (choix CRM) + P4 (déploiement) ou instanciation d'un module CORE quand le secteur est couvert. Pack recommandé : P3 + P4 Essentiel pour les très petites structures ; P3 Complet + P4 Complet au-dessus.

  

F09-8 — Sécurité données négligée — vulnérabilité. Type : technologique. Gravité : SECONDAIRE. Cause-type : pas de politique mot de passe, accès non contrôlés. Signal entretien : le dirigeant utilise le même mot de passe sur tous ses comptes, aucune authentification à deux facteurs n'est activée, les comptes des personnes parties ne sont pas fermés. Signal pièce : la liste des utilisateurs du logiciel contient des noms qui ne sont plus dans l'entreprise. Fuite : vol de données (fichier client revendu à un concurrent), fraude facilitée (changement de RIB fournisseur par usurpation — PROTO F09 phase T3.6.1, "la plus coûteuse et la plus simple à prévenir"), exposition réglementaire. Levier F09 : six gestes à coût nul du PROTO F09 phase T3.6.2 avant toute recommandation payante. Pack recommandé : P5 Essentiel assorti de l'exécution immédiate des six gestes à coût nul.

  

Zone à préciser avec le fondateur : la fuite F09-5 porte la gravité CRITIQUE dans la base, ce qui est cohérent avec le contexte africain où le commerce passe massivement par les réseaux sociaux ; à confirmer la cohérence avec les autres fonctions CORE qui pourraient porter le même signal (F03 commercial notamment).

  
  

## Item 4 — Catalogue des Diagnostics Disponibles

  

F09 mobilise trois niveaux de diagnostic. Chacun est articulé au moteur du Portail (CORE-DX) et à la revue humaine du consultant.

  

Diagnostic D1 — Pré-diagnostic F09 (sortie du questionnaire d'orientation)

  

Lancé par le consultant porteur du prospect dès la soumission du questionnaire d'orientation sur le site ou dans le Portail (doctrine du 5 octobre 2026 : le pré-diagnostic se fonde uniquement sur les réponses, aucune pièce n'y est connectée, on ne liste pas de documents au prospect). Durée : trois à sept jours de battement, publication programmée (doctrine du 7 octobre 2026). Contenu : qualification parmi les quatre situations du PROTO F09 phase T1.4 (rien / sous-exploité / fragmenté / abandonné), signalement des trois premiers signaux critiques identifiés (F09-1, F09-4, F09-5 sont les plus récurrents dans la base de leads), orientation vers l'une des huit prestations P1 à P8.

  

Grade minimal pour lire et valider : N1.

  

Diagnostic D2 — Audit SI terrain

  

Déroule l'intégralité du PROTO F09 phases T0 à T7, sur une à cinq journées selon le périmètre, avec visite sur site. Produit un rapport de 20 à 60 pages selon niveau. Enveloppé dans la prestation P1.

  

Grade minimal pour vendre et exécuter : N2 sous supervision ; N3 en autonomie. Pour le niveau Premium et au-dessus, N5 obligatoire sur la partie "systèmes critiques" (PROTO F09 — verrou de sécurité des personnes rang 1, cas de chaîne du froid, alarmes, contrôle d'accès, équipement de production).

  

Diagnostic D3 — Audit de conformité technique des données personnelles

  

Audit ciblé sur la part technique de la conformité au corpus UEMOA / CEMAC et, pour les flux diaspora/export, RGPD. Appuie la prestation P6. Travaille sur la cartographie des traitements, la journalisation, la minimisation, le chiffrement, les sous-traitants. Articulation obligatoire à F10 pour la part juridique.

  

Grade minimal : N3, avec badge "Protection des données" (à créer en PHASE 2 — zone à préciser).

  

Exemple d'application. Un cas récent d'une pharmacie à Niamey (dossier F09 ouvert à l'Académie en octobre 2026) a mobilisé D1 sur le questionnaire d'orientation et a qualifié la situation en "sous-exploité" sur une échelle M1 : logiciel de caisse acheté, un quart des fonctions utilisées, pas de tableau de bord mensuel, pas de sauvegarde. Le pré-diagnostic D1 a produit en sept jours une orientation vers P4 Essentiel (reprise de l'outil existant) + P5 Essentiel (politique de données en urgence sur la sauvegarde), évitant une recommandation prématurée d'un ERP de pharmacie plus lourd. La bascule vers D2 n'a eu lieu qu'après la signature du contrat P4, respectant la discipline du pré-diagnostic sans pièces jointes.

  

Articulation D1 / D2 / D3. Les trois diagnostics s'enchaînent dans une mission structurante et ne se substituent pas l'un à l'autre : D1 oriente, D2 pose le constat terrain, D3 expose la part réglementaire quand elle existe. Un dossier simple peut se contenter de D1 + une prestation ciblée (P2 ou P5 Essentiel). Un dossier lourd traverse les trois.

  
  

## Item 5 — Questionnaires de Pré-Diagnostic

  

Les questionnaires F09 sont conçus pour le moteur du Portail et non pour un formulaire papier du consultant ; leur raison d'être est d'alimenter le pré-diagnostic D1. Ils s'articulent à l'orientation initiale du questionnaire d'acquisition (doctrine du 5 octobre 2026 : le questionnaire est adaptatif, une orientation initiale détermine le moteur qui fera l'analyse). F09 reçoit en entrée les réponses à huit questions d'orientation ouvertes et vingt-quatre questions fermées de qualification.

  

Les huit questions d'orientation ouvertes sont celles de l'Item 1 ("je ne sais pas combien j'ai en stock", etc.). Elles permettent au moteur de choisir la grille suivante.

  

Les vingt-quatre questions fermées de qualification sont groupées en six blocs de quatre questions, un par phase T0 à T5 du PROTO F09 (les phases T6 et T7 ne se pré-qualifient pas : elles s'évaluent au terrain). Voici les blocs.

  

Bloc Q0 — Aiguillage. Q0.1 L'entreprise vient-elle pour (A) un échec identifié d'un outil existant, (B) un besoin exprimé par un financeur, (C) un passage d'échelle, (D) un signal d'incident, (E) une revue complète ? Q0.2 La situation a-t-elle un caractère d'urgence à moins d'un mois ? Q0.3 L'entreprise détient-elle au moins un outil numérique métier ? Q0.4 L'entreprise sait-elle où vivent ses données vitales ?

  

Bloc Q1 — Cartographie. Q1.1 Combien de sites ? Q1.2 Les données sont-elles centralisées sur un serveur ou dispersées sur plusieurs postes ? Q1.3 Un fichier client formalisé existe-t-il ? Q1.4 Quel canal porte la majorité des commandes (WhatsApp, Facebook, appel, email, boutique physique) ?

  

Bloc Q2 — Qualité. Q2.1 Les codes produits sont-ils uniformes entre les services ? Q2.2 Le taux d'erreur de saisie observé par le dirigeant dépasse-t-il cinq pour cent ? Q2.3 Un contrôle périodique des données est-il fait ? Q2.4 La saisie quotidienne repose-t-elle sur une personne unique ?

  

Bloc Q3 — Continuité. Q3.1 Existe-t-il une sauvegarde ? Q3.2 Une restauration a-t-elle déjà été testée ? Q3.3 L'entreprise détient-elle ses propres accès administrateur (et non ceux d'un prestataire) ? Q3.4 Les accès des personnes parties sont-ils fermés ?

  

Bloc Q4 — Pilotage. Q4.1 Existe-t-il un tableau de bord revu à cadence fixe ? Q4.2 Le dirigeant a-t-il trois indicateurs chiffrés qu'il regarde chaque semaine ? Q4.3 Une source de vérité unique est-elle désignée pour chaque donnée clé ? Q4.4 Un référentiel produit/client/catégorie est-il établi ?

  

Bloc Q5 — Outillage. Q5.1 Quels outils numériques l'entreprise détient-elle (logiciel de caisse, de facturation, de paie, de compta, CRM, ERP, autres) ? Q5.2 L'un de ces outils est-il contrefait ou utilisé sans licence valide ? Q5.3 Qui saisit réellement au quotidien ? Q5.4 Ces personnes maîtrisent-elles l'écrit à l'aisance requise par l'outil ?

  

Les règles d'analyse du pré-diagnostic par le moteur, à titre doctrinal :

  

Si Q0.1 répond E et que Q1.1 répond ≥ 2 sites et que Q4.1 répond non, qualification probable "fragmenté", prestation d'entrée P1 Complet.

  

Si Q3.1 ou Q3.2 répond non, signal F09-4 positionné CRITIQUE, propose Audit Flash et prestation P5 Essentiel en urgence.

  

Si Q1.4 répond WhatsApp/Facebook/Instagram et Q4.3 répond non, signal F09-5 positionné CRITIQUE, pack P3 + P4 proposé.

  

Si Q5.2 répond oui, signal F09 complément non répertorié (contrefaçon) activé ; rappeler règle T3.6.3 du PROTO F09 — la migration comporte elle-même un risque, à traiter avant la décision.

  

Si Q5.4 répond non, proposition de conception de l'outil adaptée au niveau réel et non au niveau souhaité — règle T2.4 du PROTO F09 ne jamais concevoir un système qui exige une compétence que l'entreprise ne peut ni payer ni retenir.

  
  

## Item 6 — Grilles d'Analyse

  

F09 mobilise six grilles doctrinales, toutes issues du PROTO F09 V1.2 et étoffées ici par leur articulation à la vente.

  

Grille G1 — L'échelle de maturité du système d'information

  

Six niveaux (du moins au plus mûr) : M0 Rien — l'entreprise ne détient aucun outil numérique de gestion métier, elle marche sur Excel non verrouillé, cahier et mémoire. M1 Sous-exploité — l'entreprise détient un outil mais n'en utilise que 20 % des fonctions, le reste est passé à côté. M2 Fragmenté — l'entreprise détient plusieurs outils qui ne se parlent pas ; chaque équipe a son fichier, chaque fichier a son code. M3 Abandonné — l'entreprise a tenté un outil, l'a abandonné après l'arrivée d'un prestataire sans suite, et vit désormais sur un Excel palliatif et un ressentiment contre l'informatique. M4 Instrumenté — l'entreprise détient un outil intégré qui couvre l'essentiel, revu à cadence, avec un référentiel. M5 Piloté — l'entreprise vit sur son outil ; les décisions passent par son tableau de bord ; la sauvegarde est testée ; les accès sont administrés ; le système est documenté.

  

Sortie d'analyse : chiffrage du niveau actuel, cible atteignable à douze mois, chiffrage du coût de l'écart (gap chiffré en FCFA par mois).

  

Grille G2 — Les six défauts de qualité de donnée à chercher

  

Issue de PROTO F09 phase T2.1. Les six défauts : (1) la même information existe à plusieurs endroits sous plusieurs formes ; (2) une donnée est saisie plusieurs fois (par plusieurs personnes ou plusieurs outils) ; (3) une donnée n'a pas de source de vérité unique ; (4) une donnée vieille ne meurt pas ; (5) une donnée est entrée au mauvais format (date texte, nombre texte) ; (6) un champ obligatoire est vide ou rempli par convention (0, N/A, point).

  

Sortie d'analyse : liste des défauts avec leur fréquence observée, chiffrage du coût de non-qualité en temps et en erreurs, préconisation de traitement.

  

Grille G3 — La règle des trois copies et le test qui n'est jamais fait

  

Issue de PROTO F09 phase T3.1. Les trois copies : la copie de travail (sur le poste ou le serveur), la copie de proximité (sur disque externe gardé dans l'entreprise), la copie hors site déconnectée (disque, support pivot, service tiers pays-sûr). Le test que personne ne fait : la sauvegarde a-t-elle déjà été restaurée ? Combien de temps a-t-il fallu ? Est-ce que la copie restaurée est bien celle que l'on croyait ?

  

Sortie d'analyse : positionnement de l'entreprise sur trois copies (trois / deux / une / aucune), date du dernier test de restauration, écart.

  

Grille G4 — Les cinq paliers de l'outillage

  

Issue de PROTO F09 phase T5.1. Palier 0 : supprimer avant d'outiller. Palier 1 : un tableur verrouillé bien construit. Palier 2 : un outil ciblé. Palier 3 : un outil intégré. Palier 4 : un module métier propriétaire ou un ERP complet.

  

Sortie d'analyse : palier actuel, palier recommandé, chiffrage du coût de la bascule.

  

Grille G5 — Les neuf critères de choix d'outil

  

Issue de PROTO F09 phase T5.2. C1 hors ligne d'abord, C2 support dans le pays, C3 conforme au droit local, C4 données exportables, C5 coût total trois ans, C6 simplicité, C7 intégration aux moyens de paiement, C8 cohérent avec l'existant, C9 utilisable au téléphone.

  

Sortie d'analyse : grille de notation pondérée 0-5 par critère, par éditeur candidat, synthèse en matrice à l'Item 7.

  

Grille G6 — Les cinq agressions physiques du matériel

  

Issue de PROTO F09 phase T7.1 et 7.2. Chaleur, poussière, humidité, foudre et surtensions, nuisibles.

  

Sortie d'analyse : check des cinq agressions sur site, identification de la plus critique selon le local observé, préconisation proportionnée.

  
  

## Item 7 — Matrices de Décision

  

F09 mobilise quatre matrices de décision principales. Trois sont des grilles pondérées classiques du métier, la quatrième — la plus structurante — intègre le référentiel propriétaire MUDCF.

  

Matrice M1 — Choix d'outil (prestation P3)

  

Table à double entrée. Lignes : les éditeurs candidats (cinq à huit maximum). Colonnes : les neuf critères C1 à C9 de la grille G5. Cellule : note 0-5 justifiée par la pièce (capture d'écran, ligne de contrat, test terrain). Pondération par défaut : C1 hors ligne et C4 exportabilité en 1,5 ; C7 intégration aux paiements en 1,3 ; les autres en 1,0. Verdict : l'éditeur retenu doit totaliser au moins trois cinquièmes du score maximum pondéré. Un éditeur qui notes 0 sur C1 (pas de mode hors ligne) est éliminé d'office, sauf si l'entreprise est dans une zone à connexion garantie — rare.

  

Matrice M2 — Palier et priorité (prestation P4 et P7)

  

Table à double entrée. Lignes : les cinq paliers P0 à P4. Colonnes : les trois dimensions (coût total sur trois ans en FCFA, temps à atteindre en mois, risque de résistance utilisateur en haut/moyen/bas). Cellule : estimation. Verdict : le palier retenu est celui dont le coût est inférieur à la capacité de financement, le temps compatible avec la contrainte du dirigeant, et le risque de résistance acceptable avec les moyens de formation disponibles. Règle T5.1 du PROTO F09 : ne jamais sauter un palier — un palier 3 posé sur une entreprise au palier 0 est une panne différée.

  

Matrice M3 — Les cinq agressions physiques et leur traitement

  

Table à double entrée. Lignes : les cinq agressions (chaleur, poussière, humidité, foudre, nuisibles). Colonnes : observé sur site (oui/non/partiel), gravité au vu de la donnée vitale exposée (critique/majeure/secondaire), parade à coût nul (ventilation, nettoyage, surélévation, onduleur, pièges), parade à coût engagé (climatisation, local dédié, cage de Faraday de postes critiques). Verdict : la stratégie matérielle privilégie protéger et faire durer plutôt que remplacer vite (PROTO F09 T7.3 "le coût du matériel et ses conséquences stratégiques").

  

Matrice M4 — MUDCF appliqué (prestation P5 et P7)

  

Le référentiel MUDCF (MC-RÉFÉRENTIEL-UNIVERSEL-COLLECTE-DONNÉES-V1.0) est le référentiel propriétaire de collecte de données du cabinet. Il est l'instrument qui transforme la politique de données écrite en matrice de décision exécutable. Son principe doctrinal : avant d'outiller, il faut savoir quelles données l'entreprise collecte, lesquelles elle ne collecte pas et pourrait, lesquelles elle collecte en double, et lesquelles elle collecte sans droit. Le MUDCF, inscrit en base comme chantier primaire du cabinet, a livré ses Lots 1 et 2 sous forme de documents institutionnels complets ; il attend le double-codage en aveugle et le Lot 3 pour atteindre sa V1 pleine. Le présent dossier F09 le mobilise au niveau Lots 1-2 et signale que son achèvement reste un chantier à prioriser en PHASE 2 — à articuler avec l'équipe opérations (Floriane) et informatique (Adama). MUDCF organise cette carte selon deux axes transversaux applicables à toutes les logiques L1 à L6 du Module Métier.

  

Axe 1 — Nature de la donnée. Dix familles : données d'identification (clients, fournisseurs, salariés), données d'activité (ventes, achats, production, stocks), données financières (flux, soldes, dettes, créances), données de performance (rendements, écarts, retards), données réglementaires (autorisations, agréments, échéances), données RH (paie, congés, formation), données de qualité (contrôles, non-conformités, réclamations), données techniques (équipements, maintenance, consommation), données de pilotage (plans, budgets, prévisions), données externes (concurrents, marché, cours).

  

Axe 2 — Valeur et exposition de la donnée. Quatre niveaux. N1 Courante — la perte est inconfortable mais rattrapable. N2 Sensible — la perte expose l'entreprise à un préjudice chiffrable. N3 Vitale — la perte arrête tout ou endommage durablement l'activité. N4 Personnelle — la donnée nomme une personne physique ou la rend identifiable par recoupement ; elle est soumise au corpus UEMOA / CEMAC et, pour les flux transfrontaliers vers l'Union européenne, au RGPD. La gradation N1 à N4 est articulée au gate de non-réidentification posé dans MC-ARCHI-CORE-V2 le 1er octobre 2026 : le passage d'un niveau N3 au niveau N4 (remontée au moteur de connaissance) est contrôlé et exige un consentement écrit, une anonymisation réelle et une vérification de conformité aux autorités locales (règle déjà posée par MC-ARCHI-PLAT-V1 — "une base construite sur des données mal consenties ne se nettoie pas, elle se jette").

  

La matrice MUDCF croise les deux axes et produit par cellule : la méthode de collecte recommandée, le format de la donnée, la fréquence, le responsable de la saisie, la règle de qualité, la politique de sauvegarde (positionnement sur la règle des trois copies), la politique d'accès (qui lit, qui modifie, qui exporte), la durée de conservation, le mode de suppression en fin de vie, les textes applicables (loi nationale, loi-type UEMOA/CEMAC, RGPD selon flux).

  

Dans une mission F09, MUDCF n'est pas un livrable que l'on remet au client ; c'est l'instrument interne du consultant pour instruire la prestation P5 (politique de données) et P7 (digitalisation pas-à-pas). Le livrable au client est la politique de données elle-même (Item 10), écrite dans le langage du dirigeant et non celui du référentiel.

  
  

## Item 8 — Protocoles d'Intervention

  

F09 déroule un seul protocole doctrinal exécutable : MC-PROTO-F09-V1.2, qui fait foi en base (table public.protocole, nature doctrine, grade minimum N1, adopté le 28 septembre 2026). Ce dossier F09 unité professionnelle n'absorbe pas le protocole : il l'enveloppe et renvoie à lui pour l'exécution. Rappel de la règle de version : le présent dossier est plus profond que le protocole seul, puisqu'il l'articule à la commercialisation, aux tarifs, aux grades et aux limites ; mais il reprend intégralement la matière doctrinale du protocole sans la modifier.

  

Le protocole est structuré en huit sections exécutables en séquence :

  

Section T0 — Aiguillage. Trois tâches : T0.1 identifier d'où vient la saisine (une des cinq entrées A à E), T0.2 trier les urgences par six critères, T0.3 relier la fuite détectée par CORE-DX à l'entrée A03 de l'accélérateur, T0.4 positionner sur l'échelle de maturité du système d'information (grille G1 du présent dossier).

  

Section T1 — Cartographie réelle. Six tâches : T1.1 suivre une information de bout en bout, T1.2 inventorier ce qui existe (y compris outils invisibles), T1.3 identifier les données vitales (avec sous-tâche T1.3 ter "le savoir qui n'existe que dans une tête"), T1.4 diagnostiquer parmi les quatre situations (rien / sous-exploité / fragmenté / abandonné), T1.5 lire l'entreprise à plusieurs sites, T1.6 recenser les canaux réellement utilisés comme sources de données.

  

Section T2 — Qualité de la donnée. Quatre tâches : T2.1 chercher les six défauts, T2.2 exécuter le test de vérité (règles strictes : annoncer avant, formuler sur le résultat, pas sur la personne), T2.3 instaurer un contrôle périodique proportionné, T2.4 identifier la compétence qu'on ne pourra pas retenir — règle de conception la plus importante du volet.

  

Section T3 — Continuité, sécurité et accès. Six tâches : T3.1 règle des trois copies, T3.2 continuité face aux coupures, T3.3 accès et séparation des rôles, T3.4 protection des données sensibles (avec T3.4 bis lieu d'hébergement), T3.5 fraude interne facilitée, T3.6 menaces externes et budget de sécurité (en quatre sous-tâches : vecteurs par fréquence, gestes à coût nul, logiciels contrefaits, dimensionnement du budget par exposition maximale).

  

Section T4 — Socle de données pour piloter. Quatre tâches : T4.1 partir de l'indicateur jamais de l'outil, T4.2 donnée minimale viable, T4.3 référentiel préalable invisible, T4.4 rythme et responsable.

  

Section T5 — Outillage. Huit tâches : T5.1 cinq paliers du moins coûteux au plus lourd, T5.2 neuf critères de choix, T5.3 contrats et négociation avec sous-tâches T5.3 bis cohérence outil-usage téléphone et règle d'export propre, T5.4 déploiement (sous-tâche T5.4 ter cycles courts), T5.5 dépendance au prestataire, T5.6 gestion du parc matériel, T5.7 résistance des utilisateurs, T5.8 après le déploiement exploiter changer réparer.

  

Section T6 — Quand le système d'information est le produit (logique L5). Cinq tâches : T6.1 propriété de l'actif numérique, T6.2 dépendance au développeur unique, T6.3 dette technique, T6.4 disponibilité comme engagement commercial, T6.5 données des utilisateurs.

  

Section T7 — Contraintes exogènes. Cinq tâches : T7.1 électricité (première cause de mortalité du matériel), T7.2 connexion coût débit disponibilité, T7.3 coût du matériel et conséquences stratégiques, T7.4 interruptions dépassant l'entreprise, T7.5 risque de change sur abonnements.

  

À la clôture du protocole : signalement de la cause profonde (sept signaux dont le PROTO documente la lecture), raccordement à l'horizon J+90 (ce qui doit vivre après la mission), contrôle final par la liste des 53 vérifications.

  

Trois règles invariables de l'exécution rappelées à chaque phase :

  

R1 Cet engine ne vend pas de logiciel.

R2 Le problème est rarement technique.

R3 Toute recommandation doit survivre au terrain.

  

Quatre verrous de périmètre rappelés aussi à chaque phase :

  

Verrou de sécurité des personnes en rang 1 : si un système informatique commande un équipement dont la défaillance mettrait quelqu'un en danger, sa fiabilité relève du rang 1 et non de l'optimisation.

  

Verrou de la compétence qu'on ne pourra pas retenir (T2.4) : ne jamais concevoir un système qui exige, pour fonctionner au quotidien, une compétence que l'entreprise ne peut ni payer ni retenir.

  

Verrou de la sauvegarde hors site déconnectée : la seule parade réelle au rançongiciel et à l'incendie est la sauvegarde hors site et déconnectée entre deux sauvegardes.

  

Verrou du test de restauration : une sauvegarde qui n'a pas été restaurée n'existe pas.

  
  

## Item 9 — Procédures Opérationnelles

  

Six procédures opérationnelles sont à portée du consultant F09. Elles sont rédigées pour être tenables même quand le consultant n'est plus sur place, conformément à la doctrine du 16 novembre 2026 (les moteurs et outils doivent savoir distinguer, analyser, réfléchir, noter — reprendre ce que le gardien fait aujourd'hui à la main).

  

Procédure PRO-F09-01 — Ouverture d'une mission F09 au Portail

  

Déclencheur : saisine (une des cinq entrées A à E). Étapes : (1) qualifier la mission dans le Portail selon la typologie MC-SPEC-PCONS (type A diagnostic, B structuration, C redressement, D abonnement), (2) exécuter la fiche de qualification d'activité (sept questions fermées), (3) poser ICM et jalons, (4) vérifier qu'aucun doublon de fiche n'existe (doctrine du 20 octobre 2026), (5) attribution par le Dispatcher, (6) notifications.

  

Procédure PRO-F09-02 — Visite sur site d'audit

  

Déclencheur : lancement de la prestation P1. Prérequis : rendez-vous confirmé, pièces préalables demandées, grille G1 à G6 en main. Étapes : (1) ouvrir par le MC-MODULE-METIER, (2) exécuter T1.1 suivre une information de bout en bout en commençant par un cas réel (une commande, une facture, un bulletin de paie), (3) relever les six défauts de qualité G2, (4) check des cinq agressions G6, (5) recenser les systèmes invisibles, (6) clore par la liste des données vitales validée avec le dirigeant.

  

Procédure PRO-F09-03 — Test de restauration

  

Déclencheur : toute prestation qui touche la continuité (P1, P4, P5, P7). Prérequis : au moins une sauvegarde identifiée. Étapes : (1) poser le périmètre du test, (2) demander au dirigeant d'exécuter lui-même le geste (ou de regarder le consultant le faire sur une copie), (3) chronométrer le temps de restauration, (4) ouvrir le fichier restauré et vérifier qu'il est bien celui que l'on croyait, (5) consigner la date dans le cahier du test de restauration.

  

Procédure PRO-F09-04 — Test de vérité d'un outil

  

Déclencheur : toute prestation P3 ou P4 qui porte un verdict. Prérequis : échantillon de données réelles, outil candidat, scénario pré-écrit. Étapes : (1) annoncer le test avant, (2) exécuter le scénario, (3) formuler le résultat sur l'outil et les données, pas sur la personne, (4) consigner le verdict sous le format défini par MC-REGLE-INDICATEUR-PROUVE-V1 (une preuve positive ou rien).

  

Procédure PRO-F09-05 — Fermeture des accès d'une personne partie

  

Déclencheur : départ confirmé d'un collaborateur (information F07) ou découverte d'un compte dormant d'une personne partie. Étapes : (1) lister tous les comptes de la personne (poste, logiciel métier, messagerie, outils tiers, comptes bancaires avec droit de signature électronique), (2) demander au dirigeant d'exécuter la fermeture compte par compte, (3) vérifier par connexion impossible, (4) consigner la fermeture et sa date.

  

Procédure PRO-F09-06 — Dépose d'un livrable F09 dans l'espace client du Portail

  

Déclencheur : clôture d'un diagnostic, d'un rapport ou d'un tableau de bord livrable. Doctrine du 3 octobre 2026 : plus de livraison en vrac par courriel, le client se connecte à son espace et télécharge ; le consultant y a accès et lit en direct. Étapes : (1) vérifier la version qui fait foi, (2) déposer dans l'espace du client, (3) notifier la direction et le consultant porteur, (4) signaler au client dans son espace (jamais lui demander d'arbitrer ce qui relève du métier du cabinet, règle du 21 octobre 2026).

  

Procédure PRO-F09-07 — Lecture d'un journal d'incidents en revue mensuelle

  

Déclencheur : revue mensuelle d'un dossier client sous abonnement F09 (prestation type D). Prérequis : L10 Registre des incidents à jour. Étapes : (1) lister les incidents du mois, (2) classer par origine (humain, outil, infrastructure, extérieur), (3) identifier les récurrences (même incident à deux reprises déclenche une analyse de cause profonde), (4) proposer des contremesures à inscrire au cahier des procédures, (5) consigner la revue dans le dossier client du Portail et en informer le dirigeant avec la liste des trois actions du mois qui suit.

  

Procédure PRO-F09-08 — Signalement d'une donnée vitale indétectée

  

Déclencheur : au cours d'une mission quelconque, un consultant détecte qu'une donnée vitale du client n'est protégée par aucune règle, aucune sauvegarde, et vit chez une personne unique. Étapes : (1) ne pas attendre la fin de la mission, (2) formuler le signal au consultant porteur et à la direction dans l'heure, (3) inscrire la donnée dans la liste des données vitales du dossier, (4) exécuter la règle des trois copies dans la journée si la perte serait critique, (5) consigner la correction. Règle du 7 octobre 2026 : chercher la même erreur chez les autres clients et la corriger partout.

  
  

## Item 10 — Modèles de Livrables

  

F09 produit onze modèles de livrable. Chacun est à version unique en base (table methode\_texte) et chargé au Portail pour que le moteur puisse l'instancier avec les données de la mission.

  

Livrable L1 — Rapport d'audit SI

  

Produit par la prestation P1. Plan standard aligné sur les sept phases T0 à T7 du PROTO F09. Longueur : 15 pages (Essentiel), 30 pages (Complet), 55-70 pages (Premium). Contient obligatoirement : la qualification parmi les quatre situations, la hiérarchie des données vitales, le registre des 53 contrôles exécutés avec écart, les trois priorités d'action du mois qui suit chiffrées en FCFA selon la discipline des trois sous-totaux (sorti de caisse, dû non payé, non gagné). Standard de restitution : résumé exécutif de deux pages selon MC-STANDARD-RESTITUTION-CLIENT-V2 ; détail en annexe. Rappel : le consultant ne saisit jamais les fuites, le moteur les sort, le consultant les commente.

  

Livrable L2 — Tableau de bord dirigeant (socle)

  

Produit par la prestation P2. Modèle Excel verrouillé ou instance du module CORE sectoriel. Comporte : la feuille d'entrée (les trois ou quatre indicateurs, leur valeur du jour, leur valeur cible, l'écart, le seuil d'alerte), la feuille de suivi hebdomadaire (douze semaines glissantes), la feuille de suivi mensuel (douze mois glissants), la feuille des règles (formule de calcul, source de la donnée, qui saisit, qui contrôle). Interdiction des totaux généraux : chaque indicateur financier se présente en trois lignes (sorti de caisse, dû non payé, non gagné).

  

Livrable L3 — Politique de données MEDEGNAN

  

Produit par la prestation P5. Document de 10 à 25 pages selon niveau. Plan : objet et périmètre, classification des données (N1 à N4 de MUDCF), règles de collecte, règles de saisie, règles de qualité, règles d'accès, règles de sauvegarde (trois copies), règles d'export, règles de suppression, régime applicable (UEMOA / CEMAC / RGPD selon flux), rôles et responsabilités (RSI nommé selon MC-NOM-RSI-V1 quand la taille le justifie). Signée par le dirigeant.

  

Livrable L4 — Cahier des procédures F09

  

Produit par la prestation P5 et P7. Une page par procédure. Format uniforme : objet, déclencheur, étapes, responsable, délai, preuve. Exemples : procédure de sauvegarde, procédure de test de restauration, procédure de fermeture des accès, procédure de vérification du RIB fournisseur (PROTO F09 phase T3.6.1 — fraude au changement de RIB, "la plus coûteuse et la plus simple à prévenir"), procédure d'inventaire du parc matériel, procédure d'effacement avant sortie de parc.

  

Livrable L5 — Cahier des charges de logiciel

  

Produit par la prestation P3. Plan standard : besoin métier (ce que l'entreprise cherche à faire), contraintes de terrain (critères C1 à C9), volumes et données reprises, intégration à l'existant (grille G2 et T5.3 bis), budget et calendrier, critères de réversibilité, obligations contractuelles (documentation, formation, propriété des données, SLA).

  

Livrable L6 — Grille comparative pondérée

  

Produit par la prestation P3. Instance de la matrice M1 du présent dossier. Format : un onglet par éditeur, un onglet synthèse pondérée, un onglet verdict et pièces justifiant chaque note.

  

Livrable L7 — Plan de déploiement

  

Produit par la prestation P4. Plan standard : phasage par cycles courts (deux à quatre semaines par cycle), reprise des données nettoyées, procédure dégradée écrite, rattrapage, formation adaptée au niveau réel des utilisateurs, test de vérité, mise en production, exploitation (après le déploiement : exploiter, changer, réparer — PROTO F09 T5.8).

  

Livrable L8 — Carte des données personnelles et des secrets

  

Produit par la prestation P6. Format inspiré de LOT3\_\_CARTE\_DONNEES\_PERSONNELLES\_ET\_SECRETS déjà connu du cabinet. Lignes : les traitements. Colonnes : finalité, base légale, catégories de personnes, catégories de données, destinataires, durée de conservation, lieu d'hébergement, mesures techniques (minimisation, pseudonymisation, chiffrement, journalisation), mesures organisationnelles, texte applicable (UEMOA / CEMAC / RGPD).

  

Livrable L9 — Cahier du test de restauration

  

Produit par toute prestation qui touche la continuité. Une ligne par test. Colonnes : date, périmètre, personne qui a exécuté, temps de restauration, fichier restauré conforme à l'attente (oui/non), écart à traiter. Doctrine : jamais un total général, mais un signalement visuel des tests en retard.

  

Livrable L10 — Registre des incidents

  

Produit par toute prestation qui laisse derrière elle un système en exploitation. Une ligne par incident. Colonnes : date, type, périmètre, origine présumée, action prise, délai de résolution, cause profonde. Mis en place avec responsable nommé, règle T5.8 du PROTO F09 — "sans journal, l'incident se répète et son coût ne se voit pas".

  

Livrable L11 — Rapport de restitution final (standard MC-STANDARD-RESTITUTION-CLIENT-V2)

  

Plan : résumé exécutif portant la décision, annexes lourdes (L1 à L10 selon mission), lettre de clôture, planning du suivi post-mission (abonnement module CORE quand applicable, revue annuelle de P5 quand applicable). Signé par la direction du cabinet, jamais au nom personnel du fondateur (règle de signature des courriels clients, doctrine permanente).

  
  

## Item 11 — Tableaux de Bord Spécifiques F09

  

Trois tableaux de bord sont propres à la fonction F09 et instanciés par le Portail.

  

Tableau de bord TDB-F09-A — Tableau de bord dirigeant du client (chez le client)

  

Ce n'est pas un tableau du cabinet, c'est le livrable L2 lui-même, installé chez le client et consultable par lui dans son espace Portail. Il porte au maximum quatre indicateurs. Pour une PME standard, les quatre indicateurs recommandés par défaut (à adapter selon logique économique) : chiffre d'affaires de la semaine (en trois sous-totaux), position de trésorerie, délai client moyen, taux de rupture de stock sur les cinq produits phares. Chaque indicateur porte sa règle d'alerte.

  

Tableau de bord TDB-F09-B — Tableau de bord mission du consultant (cockpit consultant)

  

Ce tableau accompagne le consultant tout au long d'une mission F09. Il porte : avancement par phase (T0 à T7) avec taux d'exécution par tâche, registre des 53 contrôles avec statut (fait / écart / non applicable), liste des données vitales identifiées, liste des trois priorités en cours, position sur l'échelle de maturité G1 (avant/après), chiffrage cumulé de l'écart en FCFA (mission à mission). Rappel : le consultant lit, le moteur agrège.

  

Tableau de bord TDB-F09-C — Carte F09 du cabinet (cockpit direction)

  

Agrégat au niveau cabinet. Lignes : les missions F09 ouvertes et closes. Colonnes : niveau de maturité moyen avant/après, nombre de données vitales mises en sauvegarde, nombre de tests de restauration réalisés, montant de non-qualité évité en FCFA, revenu F09 par trimestre (ventilation P1 à P8). Alimenté automatiquement, accessible aux trois administrateurs du Portail (direction, opérations, informatique).

  

Quatre indicateurs au centre du tableau direction sont tenus à jour en permanence et commandent trois décisions récurrentes. Indicateur I1 — nombre de missions F09 en cours par palier (M0 à M5) ; commande la décision d'ouverture d'un module CORE sectoriel quand la masse se constitue sur un même palier d'un même secteur (par exemple cinq pharmacies en M2, déclenchement du module la branche sectorielle MEDEGNAN (pharmacie)). Indicateur I2 — taux d'exécution du contrôle C10 (test de restauration) sur l'ensemble des missions F09 en exploitation ; commande la mise en revue d'urgence quand ce taux descend sous 80 % — un taux bas signifie que le cabinet laisse derrière lui des illusions de sauvegarde. Indicateur I3 — revenu F09 cumulé des douze derniers mois par prestation ; commande l'arbitrage du catalogue (quelle prestation sous-vendue doit être relancée, quelle prestation sur-vendue doit être outillée davantage). Indicateur I4 — nombre de dossiers SX (souscripteur la plateforme SaaS MEDEGNAN) qui exécutent F09 sous leur marque ; commande la décision de maintenir ou d'enrichir les contrôles bloquants que le cabinet exporte à travers la plateforme SaaS MEDEGNAN.

  

Règle de mise à jour : les trois tableaux de bord F09 vivent dans le Portail ; aucune version Excel parallèle n'est tolérée. Une version Excel parallèle est un retour au désordre F09-2 (données dispersées) que le cabinet traite chez ses clients et qu'il ne peut accepter chez lui.

  
  

## Item 12 — Critères de Contrôle Qualité

  

Le contrôle qualité d'une mission F09 passe par la liste des 53 contrôles du PROTO F09 V1.2. Ces 53 contrôles sont la mesure doctrinale et ne sont pas réécrits ici ; ils sont chargés en base (table methode\_texte, référence MC-PROTO-F09-V1.2). La liste va du contrôle C1 ("le MC-MODULE-METIER a-t-il été exécuté, et la logique déterminée avant toute analyse ?") au contrôle C53 ("les réparateurs locaux ont-ils été mobilisés, avec retrait ou sauvegarde préalable des données ?") et couvre les sept phases T0 à T7 et les deux logiques L5 et T6-T7. À chaque contrôle est associé un verdict (fait / écart / non applicable) et, en cas d'écart, une action corrective nommée.

  

Deux règles de classement s'appliquent au verdict d'un contrôle :

  

Classement BLOQUANT ou SIGNALEMENT. Un contrôle non classé est bloquant par défaut (règle de MC-REGLE-INDICATEUR-PROUVE-V1, 28 septembre 2026). Un contrôle bloquant touche l'intégrité de la mission (verrou de sécurité des personnes, règle des trois copies et test de restauration, fermeture des accès des personnes parties, propriété des données du client L5, respect de la législation sur les données personnelles) ; sa non-satisfaction interdit la clôture de la mission. Un contrôle de signalement touche l'appréciation (confort de la saisie, esthétique du tableau de bord) ; sa non-satisfaction est consignée et donne lieu à une recommandation, pas à un blocage.

  

Double contrôle. Chaque contrôle est porté à la fois par un autocontrôle intégré à la tâche (le consultant exécute et répond) et par un contrôle séparé relançable (revue par un consultant d'un grade supérieur ou par la direction). La bascule du verdict se fait sur les deux à la fois.

  

Six contrôles sont classés bloquants systématiquement : C1 (MODULE METIER exécuté avant toute analyse), C9 (règle des trois copies dont une hors site), C10 (test de restauration réalisé et daté), C13 (le dirigeant détient-il ses propres accès administrateur), C14 (les accès des personnes parties sont-ils fermés), C31 (règle de vérification des coordonnées bancaires par un canal différent avant tout changement de RIB).

  

Quatre contrôles sont classés bloquants au cas par cas selon la logique économique : C27 et C28 en L5 (propriété du code et des comptes techniques), C29 en L5 (dépendance au développeur unique), C50 (migration hors d'un logiciel contrefait — la contrefaçon est traitée avant la migration pour ne pas créer deux risques en même temps).

  

Rappel doctrinal du 7 octobre 2026 : quand une erreur est corrigée dans une mission F09, chercher si la même erreur existe ailleurs dans le portefeuille et la corriger partout d'un seul coup, pour ne plus avoir à y revenir. Un écart détecté sur C14 (comptes dormants d'une personne partie) chez un client doit déclencher une revue des mêmes comptes chez tous les clients F09 ouverts.

  
  

## Item 13 — Compétences Requises pour Vendre et Exécuter F09

  

F09 est une fonction technique dans sa pratique mais rarement dans son diagnostic : le consultant F09 n'a pas besoin d'être informaticien, il a besoin de savoir regarder, écouter, lire une facture et tenir une grille. La règle R2 du PROTO F09 est rappelée : le problème est rarement technique, ce qui manque est une règle. Les grades et profils requis par prestation sont les suivants.

  

Prestation P1 — Audit SI complet

– Niveau Essentiel : N2 sous supervision ou N3 autonome.

– Niveau Complet : N3 ou N4.

– Niveau Premium : N5 obligatoire, avec revue par un N5 ou N6 sur les systèmes critiques (verrou de sécurité des personnes).

– Niveau Sur devis : N6.

  

Prestation P2 — Tableau de bord dirigeant

– Essentiel/Complet : N2 sous supervision ou N3 autonome.

– Premium : N4 avec appui F08 pour la discipline des trois sous-totaux.

  

Prestation P3 — Choix de logiciel métier

– Essentiel/Complet : N3.

– Premium : N4 avec appui F10 pour la rédaction des clauses contractuelles.

  

Prestation P4 — Déploiement et conduite du changement

– Essentiel : N2 sous supervision.

– Complet : N3 ou N4.

– Premium : N5 avec appui F07 pour la conduite du changement.

  

Prestation P5 — Politique de données

– Essentiel/Complet : N3 ou N4.

– Premium : N4 avec appui F10 pour l'articulation RGPD et avec F08 pour l'articulation des règles comptables.

  

Prestation P6 — Protection des données personnelles — technique

– Tous niveaux : N3 avec badge "Protection des données" à créer en PHASE 2 (zone à préciser avec le fondateur).

  

Prestation P7 — Digitalisation pas-à-pas d'une PME

– Essentiel : N3.

– Complet : N4.

– Premium : N5 avec co-pilotage N4 côté client, et appui F07 pour la conduite du changement humain.

  

Prestation P8 — Développement ERP sur mesure (ou module CORE sectoriel)

– Tous niveaux : N5 obligatoire sur la partie conception fonctionnelle, avec appui du responsable informatique du cabinet pour la partie réalisation technique.

  

Un cabinet souscripteur la plateforme SaaS MEDEGNAN (SX) qui exécute F09 sous sa propre marque n'est pas soumis à la grille de grades MEDEGNAN ; il est en revanche soumis aux règles invariables R1 à R3 et aux contrôles bloquants (C1, C9, C10, C13, C14, C31) parce que ces contrôles protègent le client final, pas la marque qui livre.

  

Compétences transverses attendues chez un consultant F09, quel que soit le grade : (a) savoir tenir une grille — les six grilles G1 à G6 du présent dossier doivent être exécutables sans effort ; (b) savoir lire une pièce — facture, bulletin de paie, relevé bancaire, bon de commande ; (c) savoir écouter le dirigeant quand il décrit un parcours de donnée, sans l'interrompre pour nommer tout de suite un outil ; (d) savoir résister à la tentation de recommander l'outil que l'on connaît par préférence personnelle — règle R1 ; (e) savoir dire au dirigeant que ce qu'il demande (un ERP à vingt millions) n'est pas ce dont il a besoin (une règle écrite et une sauvegarde) — doctrine permanente du 3 octobre 2026 sur l'ingénierie d'affaires légale ; (f) savoir refuser toute commission d'éditeur — règle R1 rappelée.

  

Savoir-faire techniques minimaux par niveau. Pour N2 à N3 : manipuler un tableur à un niveau avancé (tableau croisé dynamique, fonctions de recherche, mise en forme conditionnelle, verrouillage de feuille), paramétrer un logiciel de caisse ou de facturation standard du marché local, savoir tester une restauration de sauvegarde, savoir fermer un compte dans les logiciels les plus courants, savoir configurer une authentification à deux facteurs. Pour N4 à N5 : mener un appel d'offres informel auprès de cinq éditeurs, négocier un contrat de licence avec clause d'exportabilité, concevoir un socle de pilotage à partir d'une décision du dirigeant (pas d'un outil), conduire un déploiement en cycles courts, articuler la paie aux conventions locales, articuler les règles de protection des données personnelles au corpus UEMOA ou CEMAC. Pour N5 à N6 : concevoir un module CORE sectoriel à partir d'un besoin révélé en mission, arbitrer la stratégie d'hébergement entre hors ligne et cloud, dimensionner un budget de sécurité à partir du coût d'exposition maximale, concevoir une politique de continuité d'activité.

  

Savoir-être attendus. F09 est une fonction où la tentation de briller technologiquement est permanente et quasi toujours délétère : le consultant ne nomme pas un outil par préférence, ne jargonne pas devant le dirigeant, ne se moque pas d'un gérant qui marche sur un cahier (en Afrique, ce cahier a parfois tenu quinze ans là où trois logiciels ont échoué). Le consultant qui ouvre un diagnostic F09 par "vous n'avez pas de SIRH, c'est grave" a brûlé le dossier. Le bon ouvrage : "quelles décisions vous ont manqué d'information ce trimestre ?" ; puis écouter.

  

Parcours Académie F09. La promotion 00001 de l'Académie MEDEGNAN n'a pas de filière F09 dédiée aujourd'hui ; les candidats qui prennent F09 viennent le plus souvent de filières F08 (administration-finance) ou F07 (RH) et montent progressivement sur F09 en co-pilotant deux missions P2 Essentiel ou P5 Essentiel sous supervision d'un N5 F09, puis en portant une mission P1 Essentiel en autonomie. Le badge "Protection des données" (zone à préciser Annexe A) vient se superposer à ce parcours quand la mission appelle la prestation P6.

  
  

## Item 14 — Collaborations avec les Autres Fonctions

  

F09 travaille rarement seule. Les collaborations suivantes sont posées en règle de méthode.

  

Avec F01 — Stratégie et gouvernance. F01 appelle F09 chaque fois qu'un cap stratégique exige une information que l'entreprise n'a pas (par exemple : décider d'ouvrir un troisième site exige un tableau de bord par site, que F09 pose). F09 appelle F01 chaque fois qu'un trou documentaire révèle un désalignement stratégique (par exemple : un fichier client vieilli qui révèle que l'entreprise ne sait plus qui elle sert). La convention : F01 dit où l'on va, F09 pose ce qu'il faut savoir en chemin.

  

Avec F02 — Marketing et communication. F09 cartographie les canaux réellement utilisés comme sources de données (phase T1.6) ; F02 décide quels canaux porter. La convention : F09 montre ce qui existe et son coût de non-visibilité ; F02 priorise l'investissement de visibilité. Jamais F09 ne recommande une stratégie digitale marketing à la place de F02.

  

Avec F03 — Commercial et ventes. La collaboration la plus fréquente : le fichier client est l'actif central du métier négoce (logique L2) et le CRM est son instrument. Convention : F03 définit le cycle de vente et les règles d'activation du client ; F09 pose l'outil et ses règles de saisie. Signal F09-5 (réseaux sociaux non connectés aux outils de vente) presque toujours remonte à F03 et reste parfois chez F03 pour la part cycle de vente.

  

Avec F04 — Approvisionnement et achats. Collaboration ponctuelle : F04 définit la politique achats et de référencement ; F09 pose le fichier fournisseur, le référentiel article, la règle de contrôle des RIB (contrôle C31 bloquant).

  

Avec F05 — Logistique et stock. Collaboration systématique en logique L2 et L1. F05 définit la politique de stock et les règles de rotation ; F09 pose la visibilité (code article unique, source de vérité unique, cadence d'inventaire). Signal F09-6 (commandes manuelles) remonte souvent à F05 pour la part flux logistique.

  

Avec F06 — Production et services. Collaboration en logique L1 (traçabilité des lots, formules, recettes — la perte d'une formule est une perte d'actif irremplaçable — PROTO F09, logique L1). F06 définit la production ; F09 pose la traçabilité et la sauvegarde des formules en lieu sûr.

  

Avec F07 — Ressources humaines et organisation. Deux axes. (1) Conduite du changement : chaque fois que F09 pose un outil, F07 accompagne les personnes. La résistance des utilisateurs (PROTO F09 T5.7) est une information, pas un obstacle. (2) Paie et dossier du personnel : F09 pose le logiciel ; F07 définit la règle (grille de paie, convention collective).

  

Avec F08 — Administration et finance. Collaboration systématique. F08 chiffre le coût de non-qualité en FCFA (discipline des trois sous-totaux) ; F09 pose les outils qui alimentent F08 (compta, caisse, facturation). Un diagnostic F09 pur ne clôt jamais sans un retour à F08 pour le chiffrage final.

  

Avec F10 — Juridique et conformité. Articulation obligatoire sur la prestation P6 (protection des données personnelles) et sur les clauses contractuelles de la prestation P3 (choix de logiciel). Convention : F09 fait les gestes (minimisation, journalisation, chiffrement, cloisonnement), F10 fait les actes (déclaration à l'autorité, mentions légales, clauses).

  

Avec F11 — Ressources, déchets et impact social. Collaboration ponctuelle : F11 porte le reporting RSE ; F09 pose l'outil et la cadence de collecte. Pour une ONG ou une entreprise soumise à bailleur, F09 appuie F11 sur la fiabilité des données de bénéficiaires (logique L6 Mission).

  

Avec F12 — Innovation, partenariats et diversification. Collaboration spécifique en logique L5 (le système d'information est le produit). F09 passe en phase T6 du protocole ; F12 porte la stratégie de partenariat et de propriété intellectuelle.

  

Packs standards agrégeant F09 avec d'autres fonctions. Trois packs sont inscrits comme combinaisons recommandées, chacune avec sa raison d'être.

  

Pack D-360-PME (F01 + F08 + F09). Diagnostic 360 PME : cap, finance, information. Vendu sous une seule entrée commerciale, mobilise P1 F09 Essentiel ou Complet + le diagnostic F01 + le diagnostic F08 ; les trois rapports sont consolidés dans un livrable unique L11 qui porte une décision stratégique unique. Pack le plus fréquent du cabinet, typiquement entre 2 500 000 et 6 000 000 FCFA selon la taille de l'entreprise, avec ligne de produit P2 F09 (tableau de bord dirigeant) souvent vendue à la suite.

  

Pack DIGI-PAS (F07 + F09). Digitalisation pas-à-pas avec conduite du changement humain. Vendu pour une PME qui marche sur Excel + cahier + mémoire. Mobilise P7 F09 + un volet F07 de conduite du changement. Durée : 6 à 12 mois. Prix : 3 500 000 à 10 000 000 FCFA selon niveau.

  

Pack DP-RGPD (F09 + F10). Mise en conformité technique et juridique à la protection des données personnelles. Mobilise P6 F09 + le volet actes F10. Pertinent pour les clients diaspora, les entreprises qui exportent sur l'Union européenne, les acteurs santé et fintech. Prix : 1 800 000 à 5 500 000 FCFA selon périmètre.

  

Un quatrième pack, non figé, est en construction : Pack L5-PLATFORM (F09 + F12) pour les entreprises de la logique L5 où le système d'information EST le produit — levée de fonds, cession, structuration de la propriété intellectuelle technique. Prix sur devis.

  
  

## Item 15 — Limites et Conditions d'Habilitation

  

Trois familles de limites bornent F09. Elles ne sont pas des précautions rhétoriques, elles sont des règles de refus.

  

Limites de périmètre

  

F09 ne construit jamais un système qui met une personne en danger sans classer sa fiabilité en rang 1. Verrou de sécurité des personnes du PROTO F09 — un système qui commande une chaîne du froid de produits de santé, une alarme, un contrôle d'accès ou un équipement de production ne se traite pas en optimisation. S'il n'est pas tenable en rang 1, il n'est pas tenable.

  

F09 ne vend jamais un logiciel. R1 du PROTO F09. Un consultant qui accepte une commission d'un éditeur détruit l'indépendance du cabinet et fait basculer la mission dans une autre nature. Aucune exception.

  

F09 ne se substitue jamais au métier du client. Un dirigeant qui demande à F09 d'arbitrer à sa place "je garde quel logiciel" sans lui donner son métier et ses contraintes, se verra dire qu'il manque la donnée. F09 pose la matière, le client tranche, le consultant éclaire — jamais l'inverse.

  

F09 ne ferme jamais une mission sans test de restauration daté. Contrôle C10 bloquant. Une sauvegarde qui n'a pas été restaurée n'existe pas, et une mission qui ne l'a pas vérifiée a livré une illusion.

  

F09 ne recommande jamais une solution qui suppose un courant continu et une connexion permanente dans une zone où l'un ou l'autre est intermittent. R3 du PROTO F09. C'est une panne différée.

  

Limites de grade et d'habilitation

  

Un consultant S1 (intégré) sans grade N3 ne porte pas en autonomie une mission P1 Complet ou au-dessus ; il travaille sous supervision d'un N4 minimum.

  

Un consultant S2 (partenaire) sans grade N3 ne porte pas en autonomie une mission P1 Complet ; il peut porter une mission P2 Essentiel ou P5 Essentiel.

  

Un consultant S3 (licencié spécialiste) titulaire d'un badge F09 porte toutes les prestations de son niveau de badge. Un licencié non spécialiste F09 ne vend pas F09 en direct sans appui d'un S3 F09 ou de la direction.

  

Un consultant S4 (franchisé, modèle à construire) est traité comme S3 pour ce qui concerne F09.

  

Un cabinet souscripteur la plateforme SaaS MEDEGNAN (SX) exécute F09 sous sa propre marque sans certification MEDEGNAN. Il n'est pas tenu à la grille de grades, il est tenu aux contrôles bloquants du présent Item 12 (C1, C9, C10, C13, C14, C31) parce que ces contrôles protègent le client final. Un audit externe pourra être demandé par le cabinet à tout moment sur ces six contrôles, sans intrusion sur le reste du dossier.

  

Badge Protection des données — à créer en PHASE 2. Condition de certification à préciser avec le fondateur : passage d'un contrôle MUDCF + étude d'un cas réel UEMOA + un cas réel CEMAC + un cas réel diaspora RGPD, avec correction par un N5 porteur du badge. En attendant la création du badge, la prestation P6 au niveau Premium est portée par un N5 avec revue systématique de la direction.

  

Limites de responsabilité du cabinet

  

F09 n'engage jamais la responsabilité du cabinet au-delà de ce qui est signé dans son contrat. Rappel impératif de la règle de gestion de la responsabilité : avant tout acte qui engage la responsabilité du cabinet vis-à-vis d'un tiers (reconnaître une erreur, attribuer au cabinet la cause d'un incident, accorder une dérogation, annuler ou neutraliser un document signé par un tiers), Claude ou le consultant informe la direction et obtient l'accord exprès avant l'envoi. Une instruction du type "réponds-lui" ou "envoie le mail" ne vaut pas autorisation d'engager la responsabilité du cabinet dans ce courriel — le contenu qui engage se fait valider séparément.

  

F09 ne reçoit jamais directement par courriel un livrable d'un consultant ou d'un client. Doctrine du 5 octobre 2026 : plus rien ne transite par courriel avec les consultants et membres du réseau ; le message vit dans leur compte au Portail, le courriel ne sert qu'à notifier. Un livrable F09 arrive dans l'espace du consultant au Portail, est lu par la direction au Portail, et est publié dans l'espace du client au Portail.

  

F09 n'assure jamais la maintenance curative d'un outil tiers. Si un outil posé par F09 tombe en panne, le client s'adresse à l'éditeur ou à l'intégrateur selon le contrat ; F09 peut en revanche être saisi pour un diagnostic de la panne et une orientation, dans une mission type D (abonnement) séparée.

  

F09 ne traite jamais une donnée personnelle du client au Portail hors du Portail. Les carte des données personnelles L8 vit dans le Portail et pas dans la messagerie, pas dans un drive personnel, pas sur un poste local de consultant. Tout export hors du Portail exige un motif, un responsable nommé, une échéance de suppression.

  

F09 ne construit jamais un module CORE sectoriel sans validation préalable de la direction. Le pivot de la doctrine du 17 novembre 2026 — "chaque mission peut développer un nouveau module de CORE que le besoin révèle, le premier client finance via sa mission, les suivants paient l'abonnement" — est une opportunité, pas une automaticité. La décision d'ouvrir un module CORE nouveau relève de la direction (décision stratégique) et doit traverser l'arbitrage : le secteur est-il représentable par plus d'un client à horizon raisonnable ? Le module peut-il être mutualisé sans violer la confidentialité du client-pionnier ? Les règles du gate N0-N4 de non-réidentification sont-elles respectables ? Sans ces trois réponses positives, le livrable P8 reste un développement ad hoc facturé en direct, pas un module CORE au catalogue.

  

F09 ne livre jamais à un tiers (banquier, bailleur, acheteur) un document du client sans la demande écrite du client. Le registre des incidents, la carte des données personnelles, la cartographie des traitements, la grille comparative des éditeurs ne quittent pas l'espace client du Portail sauf sur demande écrite. Un consultant qui reçoit la demande d'un tiers (un banquier qui veut voir le tableau de bord, un acheteur qui demande la cartographie en due diligence) la relaie au client pour autorisation explicite et ne transmet qu'ensuite, à travers l'espace du client au Portail, sans copie dans sa messagerie personnelle.

  
  

## Annexe A — Ce qui Reste à Préciser avec le Fondateur

  

Zones ouvertes identifiées au moment de la rédaction. Chacune doit être tranchée en PHASE 2 ou à la session de calibrage V3.3. Elles sont rangées par poids décisionnel.

  

1\. Tarifs P1 à P8 (hors ceux déjà inscrits en base). Les lignes F4-ERP, F4-TRANSFORMATION-DIGITALE et F6-DIGITALISATION-INSTITUTION font foi aujourd'hui et couvrent P7 et P8 essentiellement. Les prix de P1, P2, P3, P4, P5, P6 sont donnés ici en hypothèse et attendent la session de calibrage V3.3 du fondateur. Décideur : fondateur.

  

2\. Badge "Protection des données" à créer. Critères de passage, grille de correction, nombre de cas demandés, responsable du badge. Décideur : fondateur.

  

3\. Module CORE F09 tableau de bord sectoriel. Le Portail doit être en capacité d'instancier un module CORE à partir du livrable L2 Niveau Premium ; cela dépend des connecteurs F08 et F09 à construire, chantier confié à Adama Ben Bah en PHASE 2. Décideur : fondateur / responsable informatique.

  

4\. Articulation MUDCF / Portail. Le MUDCF (MC-RÉFÉRENTIEL-UNIVERSEL-COLLECTE-DONNÉES-V1.0) est connu de la mémoire du cabinet comme chantier de collecte en cours (Lots 1 et 2 délivrés comme documents institutionnels ; double-codage et Lot 3 restants). L'articulation précise du référentiel au Portail (schéma de base, instance par mission, export par client) reste à définir. Décideur : fondateur / Adama Ben Bah.

  

5\. Articulation F09 / F10 sur la protection des données personnelles. Le présent dossier pose une convention de répartition (gestes / actes). La frontière exacte sur certains dossiers (sous-traitance, transferts internationaux, biométrie) demande une revue conjointe F09+F10 en PHASE 2. Décideur : fondateur avec appui de F10.

  

6\. Révision de la gravité de F09-5. La fuite F09-5 (réseaux sociaux non connectés aux outils de vente) porte CRITIQUE en base ; cohérence à vérifier avec F03 et F02. Décideur : fondateur.

  

7\. Modèle de rémunération P8 (module CORE). Ratio mission / abonnement récurrent du module CORE, en lien avec la grille Famille 8 en cours de finalisation. Décideur : fondateur.

  

8\. Intégration du PROTO F09 V1.2 et du présent dossier en base. Le PROTO V1.2 fait foi en base (statut adopté) ; le présent dossier V1 est proposé et attend adoption par le fondateur via l'éditeur SQL en impersonation du compte cabinet. Décideur : fondateur.

  

9\. Articulation F09 / SystémoFlux IA. Le dossier SystémoFlux IA (confié à Claude en octobre 2026, principe directeur du 26 octobre 2026 : distinguer envisagé / spécifié / développé / testé / validé / en production) est le lieu de convergence possible entre le moteur F09 (diagnostic SI) et un outillage IA externe. L'articulation reste à définir : quelles briques de SystémoFlux renforcent F09, quelles briques F09 enrichissent SystémoFlux, quelle est la frontière entre ce qui reste propriétaire MEDEGNAN et ce qui peut passer open-source au titre de MEDEGNAN CORE. Décideur : fondateur, en co-pilotage Claude.

  

10\. Statut du présent dossier dans la souche MC-CORE / MC-FONCTION. La mémoire du cabinet signale la coexistence de deux souches de nommage pour les dossiers d'unités professionnelles (MC-CORE-F01 d'une part, MC-FONCTION-F03/F10/F11 d'autre part). Le présent dossier prend la souche MC-CORE conformément au gabarit F01 et au préavis de V3. L'harmonisation complète des noms reste une zone à trancher pour V3. Décideur : fondateur.

  
  

## Annexe B — Glossaire Court

  

Audit Flash — produit d'entrée du cabinet, à 250 000 FCFA (MC-GRILLE-TARIFAIRE-V3.2), passage préalable recommandé à toute mission F09 sous cinquante salariés.

  

Carte du patrimoine — index des documents du cabinet (table document\_source), tenue par la direction avec inscription via public.inscrire\_document\_moi ; un document n'est actif qu'une fois adopté.

  

CORE — MEDEGNAN CORE, méthodologie publique open-source du cabinet (12 fonctions F01 à F12), distincte du Portail (plateforme) et de la plateforme SaaS MEDEGNAN (plateforme SaaS externe) ; doctrine du 21 novembre 2026.

  

CORE-DX — moteur de diagnostic du Portail, qui lit les pièces et le questionnaire du prospect, détecte les fuites et chiffre, sous revue humaine à partir de N5.

  

Donnée vitale — donnée dont la perte provoque un arrêt ou une perte irrattrapable ; définition PROTO F09 phase T1.3.

  

Fiche de qualification d'activité — sept questions fermées et horodatées que toute mission ouverte au Portail doit remplir (lieu de fabrication, site de production, effectif du site, nature des achats, gérant et dirigeant, associés, activité parallèle), verrou de la chaîne de mission.

  

Fonction CORE — un des douze périmètres F01 à F12 du modèle MEDEGNAN CORE, chacun ouvert à une habilitation de consultant (badge).

  

Logiques économiques L1 à L6 — classification MEDEGNAN du Module Métier (L1 Transformation, L2 Négoce, L3 Service, L4 Actif, L5 Plateforme, L6 Mission) ; détermine la lecture F09 d'une entreprise.

  

MC-PROTO-F09-V1.2 — protocole doctrinal d'exécution F09 (IT / Systèmes Engine), 28 septembre 2026, grade minimum N1, adopté.

  

MEDEGNAN VERIFIED — infrastructure de confiance du Portail (sceau, QR, page publique), 30 septembre 2026.

  

Module Métier (MC-MODULE-METIER v2.2) — chargement préalable obligatoire à toute analyse F09 : logique économique, modulateurs, contexte, qualité de lecture, arbitrages.

  

la plateforme SaaS MEDEGNAN — MEDEGNAN Professional Operating System, SaaS commercial du Portail à destination des cabinets externes (statut SX), doctrine du 21 novembre 2026.

  

MUDCF — MC-RÉFÉRENTIEL-UNIVERSEL-COLLECTE-DONNÉES-V1.0, référentiel propriétaire MEDEGNAN de collecte de données, instance de travail interne de la prestation P5 et P7.

  

Non-réidentification (gate N0 à N4) — règle MC-ARCHI-CORE-V2 du 1er octobre 2026 : le passage d'une donnée N3 (vitale, propre au client) à N4 (remontée au moteur de connaissance) est contrôlé et exige consentement écrit + anonymisation vérifiée + conformité autorité locale.

  

Portail — plateforme MEDEGNAN d'exécution (portail.medegnan.com) ; distincte du site vitrine (www.medegnan.com) ; héberge la direction, les consultants, les candidats de l'Académie, les clients et, en V2.3, les souscripteurs la plateforme SaaS MEDEGNAN.

  

Règle des trois copies — PROTO F09 phase T3.1 : trois copies dont une hors site et déconnectée entre deux sauvegardes.

  

Règle de version — doctrine permanente du cabinet : la comparaison entre deux documents se fait sur le contenu, pas sur la référence ; le document qui absorbe est celui qui est plus profond, pas celui qui est plus récent.

  

Six gestes à coût nul — PROTO F09 phase T3.6.2 : mots de passe uniques, authentification à deux facteurs, fermeture des comptes des personnes parties, antivirus à jour, règle de vérification du RIB fournisseur par canal différent, sauvegarde hors site déconnectée. À exécuter avant toute recommandation payante.

  

Souscripteur la plateforme SaaS MEDEGNAN (SX) — cabinet ou consultant externe au Réseau MEDEGNAN, abonné au SaaS Portail, sans certification MEDEGNAN, sans Dispatcher, hors marque MEDEGNAN VERIFIED personne.

  

Test de restauration — contrôle qu'une sauvegarde est bien restaurable ; une sauvegarde non testée n'existe pas (PROTO F09 phase T3.1).

  

Test de vérité — contrôle qu'un outil fait bien ce qu'il annonce sur un échantillon réel ; annoncé avant, formulé sur le résultat, pas sur la personne (PROTO F09 phase T2.2).

  

Verrou de sécurité des personnes — PROTO F09 arbitrages rang 1 : un système qui met une personne en danger ne se traite pas en optimisation, mais en fiabilité au plus haut rang.

  
  

FIN DU DOCUMENT MC-CORE-F09-UNITE-PROFESSIONNELLE-V1


---

**Édité par MEDEGNAN CONSULTING, Cotonou (Bénin).** Licence Apache 2.0. Dernière mise à jour : 22 novembre 2026.
