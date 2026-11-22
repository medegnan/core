# F05 — Logistique et stock

## Préambule — Pourquoi une "unité Professionnelle" F05, et pour qui

  

Un stock qui ne tourne pas ne fait aucun bruit. Il ne produit ni ligne comptable d'alerte, ni réclamation client, ni appel du banquier. La comptabilité le porte à sa valeur d'achat jusqu'au jour de sa destruction, où il passe d'un coup de cent pour cent à zéro. Entre ces deux dates, il a mangé la trésorerie mois après mois, occupé de la place qu'une marchandise rentable aurait pu prendre, immobilisé un découvert bancaire qui coûte toutes les nuits, et le dirigeant n'a reçu aucun signal. L'objet du présent dossier est de doter MEDEGNAN d'une unité professionnelle qui empêche cette disparition silencieuse.

  

F05 Logistique et stock est la cinquième des douze fonctions CORE de MEDEGNAN. Elle couvre tout ce qui est physique dans l'entreprise : les marchandises et matières, leurs mouvements, leurs emplacements, leurs décotes, leurs ruptures, leurs écarts, leurs vols, leurs pertes, leurs transports, leurs douanes, et le dernier kilomètre qui les amène au client. Dans l'économie des PME et ETI d'Afrique francophone, F05 est la fonction où se cachent les pertes les mieux dissimulées et les économies les plus rapides à encaisser. Un diagnostic F05 bien conduit identifie, chez une entreprise de négoce, d'agro-industrie, de pharmacie ou de distribution, entre 5 % et 15 % de son coût de matière en pertes évitables (ordre de grandeur F05-1 inscrit en base), et entre 10 % et 20 % de son chiffre d'affaires en ventes perdues sur rupture (ordre de grandeur F05-2). Ce sont des chiffres de masse qui, chez une PME de 500 à 1 500 millions de FCFA de chiffre d'affaires, tombent sur la ligne du résultat net sans dilution.

  

Pour que F05 serve de périmètre commercial et professionnel et pas seulement de case taxonomique, elle doit être documentée à un niveau qui permette à un consultant qui ne la connaît pas de l'ouvrir et d'y travailler sans rien chercher ailleurs. C'est l'objet du dossier à 15 items. Un dossier de fonction est à la fonction ce qu'un pack de spécialité est à un médecin : la liste exhaustive de ce qu'il vend, comment il diagnostique, quels outils il mobilise, quels livrables il rend, où il s'arrête, et comment il travaille avec les autres spécialités.

  

F05 est, parmi les fonctions opérationnelles, celle qui est à la fois la plus facilement observable sans archive — on peut toujours peser une matière, compter un stock, chronométrer un cycle, observer un circuit — et la plus riche en modules propriétaires du cabinet. Elle intègre en son item 8 le module STOCK FONDANT, instrument propriétaire inscrit sous la référence MC-STOCK-FONDANT-V1, dont la logique s'inspire de la monnaie fondante de Silvio Gesell et qui fait fondre, mois après mois, la valeur de pilotage d'un stock à risque pour forcer la décision du dirigeant avant la perte.

  

Ce document s'adresse à trois lectorats distincts, dans cet ordre :

  

– Un Licencié Spécialiste ou Expert Global du Réseau MEDEGNAN (S3 principalement, S2 sous supervision) qui doit vendre et exécuter une mission F05 chez un client. Il y trouve le catalogue des prestations commercialisables, la grille tarifaire, les protocoles, et les règles de limite qui lui disent où il doit relayer à un autre spécialiste.

  

– Un Consultant Intégré (S1) ou Partenaire (S2) qui prend en charge pour le compte du cabinet une mission F05 dispatchée par le Portail. Il y trouve les procédures opérationnelles pas à pas, les grilles de lecture, et les règles de preuve qui permettent de produire un livrable qui résiste au contrôle qualité.

  

– Un cabinet externe souscripteur la plateforme SaaS MEDEGNAN (SX) qui mobilise l'infrastructure pour exécuter sa propre mission logistique chez son client, sous sa marque, sans être partie à un contrat de licence MEDEGNAN. Il y trouve les prestations qui lui sont ouvertes, celles qui lui sont fermées, et les règles de distribution des livrables (marque, sceau, références).

  

Le document ne couvre pas la mise en œuvre d'un ERP ou d'un WMS complet pour un groupe industriel international — ce périmètre relève d'un intégrateur spécialisé que F05 peut cadrer mais pas remplacer. Il ne couvre pas non plus l'exploitation de flottes de transport comme activité principale du client — ce cas appelle une branche dédiée de MEDEGNAN CORE (voir /areas/ticketage-transport.md, idée propre du fondateur du 26/10/2026) qui dépasse la seule logistique interne.

  

Doctrine permanente rappelée en tête : (1) la comparaison entre deux documents se fait sur le contenu, pas sur la référence ; cette V1 tient lieu de seed et de dossier d'unité parce que la seed MC-FONCTION-F05 n'existe pas à ce jour, mais le principe reste : un document absorbant qui va plus profond que les autres fait foi. (2) Ce que F05 identifie et chiffre, c'est le moteur qui le fait, sous le regard et avec le jugement du consultant — le consultant ne saisit jamais lui-même les fuites, règle du 26/09/2026. (3) Chaque mission F05 place ou crée un module CORE : jamais de prescription "Excel" quand un module propriétaire existe ou peut être construit (doctrine distribution 16-17/11/2026). STOCK FONDANT est l'exemple paradigmatique de ce principe appliqué à F05.

  
  

## Item 1 — Fiche de Présentation

  

Nom officiel et code

  

Nom officiel : F05 — Logistique et stock. Libellé en base (table public.fonction\_core, code F05, ordre 5). Dans l'écosystème professionnel V2.3, F05 est la cinquième des douze fonctions CORE et occupe le rang 5 de l'ordre de traitement, après F01 Stratégie et gouvernance, F02 Offre et marché, F03 Commercial et ventes, F04 Achats et approvisionnement, et avant F06 Production/Services, F07 Ressources humaines, F08 Administration et finance, F09 Information et données, F10 Juridique et conformité, F11 Ressources déchets et impact, F12 Innovation et diversification.

  

Raison d'être

  

F05 aide une entreprise à savoir ce qu'elle a physiquement en stock, à quel endroit, dans quel état, à quelle vitesse ce stock bouge, combien il coûte à immobiliser, combien il risque de perdre à ne pas tourner, comment il circule entre ses lieux de détention, et comment il arrive au client sans se casser, se perdre, se voler ou se périmer. Cette phrase ramasse cinq verbes qui chacun commande une prestation distincte, un protocole distinct et un contrôle qualité distinct.

  

Savoir ce qu'on a : c'est le travail d'inventaire, pris au sérieux. Dans la pratique africaine des PME, l'inventaire est l'acte le plus souvent reporté, le plus mal fait, et le plus lourd de conséquences. Un inventaire daté et signé est le socle sans lequel aucune autre prestation F05 ne peut démarrer — règle "pas de montant sans facture" héritée de MC-COREDX-V2.1-2026, appliquée au stock : pas de valeur sans inventaire physique.

  

Savoir à quelle vitesse ça bouge : c'est la mesure de rotation et de couverture. Le stock n'est pas du capital à mesurer en francs, c'est du capital à mesurer en vitesse. Un stock dont la couverture est de six mois consomme autant de trésorerie qu'un emprunt court terme — et il ne porte aucun intérêt visible.

  

Savoir ce que ça risque de perdre : c'est l'objet du module STOCK FONDANT, qui fait fondre la valeur de pilotage d'un stock à risque pour rendre la perte visible avant qu'elle ne soit consommée. STOCK FONDANT est la pièce propriétaire la plus distinctive de F05 et, avec elle, de MEDEGNAN tout entier.

  

Savoir comment ça circule : c'est la cartographie des flux — entre lieux de détention, entre modes de transport, entre acteurs de la chaîne. Dans un terrain où les routes sont variables, les infrastructures de stockage limitées et l'informel dominant, la cartographie des flux est un acte d'enquête, pas une lecture d'ERP.

  

Savoir comment ça arrive au client : c'est le dernier kilomètre, qui en Afrique de l'Ouest et du Centre passe par des motos-taxis, des zemidjans, des livreurs indépendants, et parfois par une logistique informelle de confiance. F05 traite ce dernier kilomètre non comme une sous-traitance anonyme mais comme un ensemble de réseaux à cartographier, contractualiser et piloter.

  

Périmètre d'intervention

  

F05 couvre l'ensemble des interventions nécessaires pour qu'une entreprise dispose : (a) d'un inventaire physique daté, signé, reconciliable avec les comptes ; (b) d'une politique de stock écrite — points de commande, stocks de sécurité, règles de rotation, règles de saisonnalité ; (c) d'un dispositif de détection et de traitement des stocks dormants, intégrant STOCK FONDANT pour les stocks à échéance et obsolescence ; (d) d'une cartographie des flux d'entrepôt et inter-entrepôts ; (e) d'un dimensionnement d'entrepôt aligné sur l'activité réelle ; (f) d'une politique de transport primaire (fournisseur → entrepôt) et secondaire (entrepôt → client), y compris les règles de choix entre transport propre et sous-traité ; (g) d'une gestion de la casse et des pertes documentée ; (h) d'un dispositif de dernier kilomètre adapté au contexte africain ; (i) d'un cadre de conformité OHADA et douanière UEMOA/CEMAC pour l'import-export courant.

  

Exclusions

  

F05 ne couvre pas, par construction :

  

– La fiscalité des stocks (évaluation fiscale, dépréciation fiscale, provisions comptables, régimes douaniers complexes de perfectionnement actif/passif). Ces actes relèvent de l'expert-comptable inscrit à l'Ordre et du conseil fiscal spécialisé. F05 produit la matière (ce qui est en stock, à quelle date, dans quel état, à quelle valeur de pilotage interne) ; le traitement fiscal lui-même est signé par le pro réglementé habilité (modèle à 3 factures V2.3). Rappelé expressément dans STOCK FONDANT : la valeur de pilotage ne s'écrit ni dans les comptes, ni dans une déclaration fiscale, ni dans un document remis à un tiers financier.

  

– L'exploitation d'une flotte de transport ou d'un entrepôt tiers comme activité principale. Un client dont le métier est de transporter ou d'entreposer pour le compte d'autrui relève d'une branche sectorielle MEDEGNAN CORE dédiée (branche Transport inscrite à /areas/ticketage-transport.md). F05 traite la logistique interne, pas l'exploitation logistique de tiers.

  

– L'achat d'un ERP ou WMS complet pour un groupe industriel de plus de 150 salariés. F05 pose le cahier des charges, l'arbitrage fonctionnel, la conduite du changement, mais l'intégration elle-même relève d'un intégrateur spécialisé que F05 peut cadrer mais pas remplacer. Les modules CORE F05 (STOCK FONDANT, carte de rotation, tableau de bord logistique) sont compatibles avec les ERP de marché et peuvent les compléter sans les remplacer.

  

– La rédaction d'actes juridiques liés au stock (contrat de consignation complexe, contrat de dépôt réglementé, contrat d'entrepôt douanier sous régime suspensif). F05 produit la matière, l'avocat tiers ou l'expert en douane spécialisé signe l'acte.

  

– L'assurance des marchandises. F05 peut évaluer l'exposition et conseiller le principe (quelles marchandises assurer, à quelle hauteur, contre quels risques) mais le contrat d'assurance lui-même est négocié avec un courtier.

  

– Toute action illicite présentée comme "optimisation logistique". La doctrine du 3 octobre 2026 est rappelée : un obstacle (douanier, réglementaire, fiscal) se franchit par ingénierie d'affaires légale — tuyauterie contractuelle — jamais par contournement. Pour un client qui opère en zone de tolérance douanière informelle, F05 formalise d'abord le cadre licite accessible, puis propose la transition.

  

Fonction dans l'écosystème professionnel V2.3

  

F05 est de rang 5, c'est-à-dire qu'elle s'exécute après F01 Stratégie, F02 Offre, F03 Commercial et F04 Achats pour un diagnostic complet ; en pratique, elle peut se vendre et s'exécuter en autonome dès lors qu'un Audit Flash a confirmé que l'entreprise relève bien d'une entrée F05 (voir Item 4, instrument D1). F05 est appelée par F04 (Achats) chaque fois qu'un volume de commande rencontre une contrainte de stockage ou de rotation, par F06 (Production) chaque fois qu'une rupture d'approvisionnement interne détruit la cadence d'un atelier, par F03 (Ventes) chaque fois qu'une rupture commerciale remonte comme signal de dysfonctionnement amont, et par F08 (Finance) chaque fois qu'une revue de trésorerie identifie une immobilisation de stock disproportionnée.

  

F05 est également un fournisseur d'informations pour F01 : un stock chroniquement en dérive est le signal d'une absence de cap sur les lignes à abandonner (remontée F01-1 ou F01-9 selon le cas). Le Strategy Engine F01 s'appuie sur la cartographie des stocks F05 pour instruire certains renoncements chiffrés.

  

Cas d'ouverture typiques

  

La demande qui ouvre un dossier F05 se présente, dans l'expérience du cabinet et dans la base des leads entrés depuis septembre 2026 (notamment Afokantan, Direct Santé, Pharmacie Crystal, CASOMEG, DIPRESS, les dossiers de distribution de la diaspora), sous l'une des dix formes suivantes : "mon stock a pris une valeur énorme et je ne la retrouve pas quand je vends", "je paie trop d'intérêts bancaires et je crois que c'est le stock qui me coule", "j'ai eu plusieurs ruptures de produits-clés en trois mois et j'ai perdu des clients", "mon inventaire théorique ne colle plus avec l'inventaire physique depuis des mois", "j'ai reçu un gros lot imposé par mon fournisseur et je ne sais pas si je vais l'écouler", "j'ai des références en pharmacie qui approchent de la péremption et je n'ai rien préparé", "mon entrepôt est trop petit, je dois en louer un autre mais je ne sais pas combien de mètres carrés", "mes livreurs me font des coups bas et je perds du cash en dernier kilomètre", "je ne sais pas combien me coûte ma casse", "je dois importer en provenance de Chine et je ne maîtrise ni les délais ni les droits de douane". Ces dix formes sont la grille d'écoute de pré-qualification F05 détaillée à l'Item 5.

  
  

## Item 2 — Catalogue des Prestations Commercialisables sous F05

  

Le catalogue F05 comporte dix prestations principales, chacune déclinée en trois ou quatre niveaux tarifaires (Essentiel, Complet, Premium, Sur devis), conformément à la grille MC-GRILLE-TARIFAIRE-V3.2 et à la logique d'inscription en base (table public.offre\_catalogue). À la date du présent dossier, aucune ligne F05 n'est encore inscrite dans offre\_catalogue sous le préfixe F5- (chantier d'inscription à ouvrir en PHASE 2). Les niveaux présentés ci-dessous sont des hypothèses de calibrage à valider par le fondateur à la session V3.3, en cohérence avec les lignes F1, F3 et F9 déjà en base et avec le point d'ancrage absolu des 250 000 FCFA de l'Audit Flash.

  

Note préalable obligatoire pour toute prestation F05 : l'Audit Flash à 250 000 FCFA (MC-GRILLE-TARIFAIRE-V3.2, produit d'entrée systématique) est le passage préalable à toute prestation F05 structurante (P2 à P10), sauf exception motivée écrite au dossier. L'Audit Flash balaye les 12 fonctions ; son volet F05 est porté par les instruments D1 décrits à l'Item 4.

  

Prestation P1 — Audit stock et logistique rapide (hypothèse à calibrer, code F5-AUDIT-STOCK-LOG)

  

Objectif : établir en une passe courte où en est l'entreprise sur six questions logistiques fondamentales — qualité de l'inventaire, vitesse de rotation, exposition au stock dormant, capacité de stockage utile, qualité des circuits d'entrée-sortie, exposition au risque douanier/import. L'audit P1 se distingue du diagnostic approfondi (P2) par sa durée et sa profondeur ; il n'ouvre ni le module STOCK FONDANT, ni la refonte de la politique de stock.

  

Durée indicative : 7 à 12 jours calendaires après signature. Mobilisation d'un consultant principal N2 et d'un N1 pour la collecte physique.

  

Livrable attendu : rapport d'audit logistique de 12 à 20 pages, structuré selon les six questions ; une note de deux pages pour le dirigeant (sommaire exécutif) ; une présentation de restitution de 15 à 25 slides au standard MC-STANDARD-RESTITUTION-CLIENT-V2.

  

Grille tarifaire (hypothèse à calibrer) : Essentiel 350 000 FCFA — Complet 650 000 FCFA — Premium 1 300 000 FCFA. Les trois niveaux diffèrent par la profondeur de la collecte (nombre de références échantillonnées, nombre de lieux de détention visités, nombre de jours d'observation).

  

Prestation P2 — Diagnostic logistique et stock approfondi (hypothèse à calibrer, codes F5-DIAG-LOG-MICRO, F5-DIAG-LOG-PETITE, F5-DIAG-LOG-PME, F5-DIAG-LOG-PMEC, F5-DIAG-LOG-GROUPE)

  

Objectif : produire le diagnostic complet de l'entreprise sur les cinq axes de la grille G1 F05 (voir Item 6) et sur les huit fuites référentielles F05-1 à F05-8 (Item 3). Le diagnostic approfondi applique intégralement le bloc Logistique de MC-PROTO-F05-F06-V1.0 : cadrage, inventaire physique partiel, analyse de rotation et couverture, détection des stocks à risque (déclenchement conditionnel de STOCK FONDANT), cartographie des flux, test de résistance à la rupture.

  

Durée indicative : 15 à 40 jours calendaires selon la taille de l'entreprise et le nombre de sites. Mobilisation d'un consultant principal N2 et d'un N3 pour la supervision, plus 1 à 3 N1 pour la collecte physique.

  

Livrable attendu : rapport de diagnostic logistique de 35 à 70 pages conforme au standard MC-STANDARD-RESTITUTION-CLIENT-V2 ; une présentation de restitution centrale (35 à 50 slides) qui porte la décision ; les livrables lourds (annexes complètes, tableau de rotation, matrice des stocks à risque, cartographie des flux) en annexes séparées ; un plan opérationnel associé à chaque fuite critique.

  

Grille tarifaire (hypothèse à calibrer, segmentée par taille) : Micro-entreprise (1 à 5 salariés) 300 000 FCFA ; Petite entreprise (6 à 20) 500 000 FCFA ; PME (21 à 50) 1 200 000 FCFA ; PME confirmée (51 à 150) 1 500 000 FCFA ; Groupe multi-sites (plus de 150) 3 200 000 FCFA. La segmentation par taille emporte le prix, pas l'option. Note de calibrage : les niveaux retenus sont légèrement supérieurs à ceux de F1-DIAG-STRAT pour une raison de terrain — un diagnostic logistique exige une collecte physique inachevable depuis un bureau, ce qui déporte le coût sur des journées de consultant hors cabinet.

  

Prestation P3 — Politique de stock et réglage des paramètres (hypothèse à calibrer, code F5-POLITIQUE-STOCK)

  

Objectif : produire, à partir d'un diagnostic P2 ou d'un dossier équivalent, une politique de stock écrite qui règle, référence par référence (ou par famille), les paramètres clés : point de commande, stock de sécurité, stock maximum, règle de rotation (FIFO / FEFO / LIFO selon le cas), règle de saisonnalité, règle de rupture acceptée vs non acceptée, règle de transfert inter-sites. La politique inclut la liste nominative des trois à cinq personnes habilitées à décider une commande hors paramètres, avec seuils et contreparties.

  

Durée indicative : 20 à 45 jours après livraison du diagnostic P2. Mobilisation d'un consultant principal N3 et d'un N2 pour l'intendance.

  

Livrable attendu : document "Politique de stock" de 25 à 50 pages ; grille de paramètres par référence ou famille (format importable ERP/WMS ou module CORE F05) ; procédure d'alerte en cas de dérive ; procédure de revue trimestrielle ; cas types commentés.

  

Grille tarifaire (hypothèse à calibrer) : Essentiel 800 000 FCFA — Complet 1 600 000 FCFA — Premium 3 500 000 FCFA — Sur devis au-delà de 2 000 références. Note de calibrage : la prestation P3 est systématiquement précédée d'un P2 — elle ne se vend pas isolément à un client qui n'a pas fait l'inventaire préalable.

  

Prestation P4 — Audit stock dormant avec STOCK FONDANT (hypothèse à calibrer, code F5-STOCK-FONDANT)

  

Objectif : identifier, chiffrer et traiter les stocks à risque (péremption, obsolescence, immobilisation) par application du module propriétaire STOCK FONDANT (MC-STOCK-FONDANT-V1). P4 est la prestation signature du cabinet en F05, celle qui démontre le plus visiblement la valeur méthodologique de MEDEGNAN sur un client de distribution, de pharmacie, d'agroalimentaire ou d'électronique. Elle inverse le signal : au lieu d'attendre que la perte soit consommée pour l'écrire en comptabilité, elle rend la perte visible sur un tableau de pilotage avant qu'elle n'arrive, et déclenche la décision pendant que l'écoulement reste possible.

  

Conditions d'activation du module : au moins un des quatre signaux déclencheurs décrits dans STOCK FONDANT §02 est présent — produits avec date de péremption, obsolescence rapide, références sans sortie depuis plus de deux fois leur délai d'écoulement normal, lots imposés par le fournisseur ou stock initial non atteint. En l'absence totale de ces signaux, P4 est marquée NON APPLICABLE au livrable — ce qui est en soi un résultat à écrire, pas un silence.

  

Durée indicative : 15 à 30 jours. Mobilisation d'un consultant principal N2 et d'un N3 pour la validation du chiffrage, plus un N1 pour la collecte physique sur site.

  

Livrable attendu : rapport STOCK FONDANT avec, pour chaque référence à risque, (a) sa valeur comptable officielle lue depuis les pièces, non modifiée ; (b) sa valeur de pilotage calculée par la mécanique de fonte ; (c) son capital à risque exprimé en FCFA ; (d) la décision proposée (écouler à prix dégradé, retourner au fournisseur, céder à un acteur tiers, suspendre les commandes, maintenir en l'état). Carte des stocks à risque avec drapeaux (vert / orange / rouge). Procédure de pilotage mensuel. Alerte automatique en cas de franchissement de seuil.

  

Grille tarifaire (hypothèse à calibrer) : Essentiel 500 000 FCFA — Complet 1 000 000 FCFA — Premium 2 200 000 FCFA — Sur devis au-delà de 2 000 références en portefeuille, ou en multi-sites. Note de calibrage : P4 est plus souvent vendue en abonnement continu (prestation P9 ci-dessous) qu'en mission unique, parce que le signal doit tourner pour rester utile.

  

Prestation P5 — Cartographie des flux et dimensionnement d'entrepôt (hypothèse à calibrer, code F5-ENTREPOT-DIMENSION)

  

Objectif : cartographier les flux entre fournisseurs, lieux de stockage, ateliers de production (si applicable) et clients, et produire un dimensionnement d'entrepôt aligné sur l'activité réelle, avec recommandations d'aménagement, d'implantation et d'équipement. P5 traite les fuites F05-7 (capacité insuffisante) et F05-5 (FIFO non respecté).

  

Durée indicative : 20 à 40 jours. Mobilisation d'un consultant principal N3 et d'un N2 pour la collecte terrain.

  

Livrable attendu : plan de flux (schéma annoté) ; dossier de dimensionnement avec calcul de surface utile par zone (réception, stockage courant, stockage dormant, préparation, expédition, zone de litige) ; recommandations d'aménagement et d'équipement (rayonnages, allées, signalétique, zones de température contrôlée si applicable) ; cahier des charges pour la location ou l'acquisition d'une surface complémentaire si recommandée.

  

Grille tarifaire (hypothèse à calibrer) : Essentiel 700 000 FCFA — Complet 1 400 000 FCFA — Premium 3 000 000 FCFA — Sur devis en multi-sites ou avec contraintes de température contrôlée (froid positif ou négatif).

  

Prestation P6 — Audit casse et pertes (hypothèse à calibrer, code F5-CASSE-PERTES)

  

Objectif : chiffrer les pertes non comptabilisées (casse à la manipulation, pertes au transport, vols, écarts d'inventaire non investigués) et proposer un dispositif de détection et de traitement. P6 traite les fuites F05-1 (pertes non chiffrées), F05-3 (écarts inventaire non investigués) et F05-6 (vols non détectés).

  

Durée indicative : 15 à 30 jours.

  

Livrable attendu : relevé des pertes des 12 derniers mois par type (casse, perte au transport, vol présumé, écart d'inventaire), chiffrées en FCFA avec les trois sous-totaux obligatoires (sorti de la caisse, dû non payé, non gagné) ; proposition de dispositif de détection (séparation des tâches, double contrôle entrée-sortie, inventaires tournants) ; proposition de dispositif de sanction interne (règlement, procédure de sortie de stock, traitement RH des manquements avérés).

  

Grille tarifaire (hypothèse à calibrer) : Essentiel 450 000 FCFA — Complet 900 000 FCFA — Premium 2 000 000 FCFA.

  

Prestation P7 — Audit et refonte du transport primaire/secondaire (hypothèse à calibrer, code F5-TRANSPORT-PRIMAIRE-SECONDAIRE)

  

Objectif : auditer les circuits de transport entre fournisseurs et entrepôts (primaire), et entre entrepôts et clients (secondaire), et proposer soit une refonte en interne, soit une mise en concurrence des prestataires, soit un mix. P7 couvre en particulier le dilemme "flotte propre vs transport sous-traité" selon la taille d'activité et la régularité des flux.

  

Durée indicative : 20 à 45 jours.

  

Livrable attendu : relevé des circuits actuels avec coûts complets par tonne-kilomètre (ou par livraison selon le cas) ; comparatif propre vs sous-traité chiffré ; cahier des charges pour appel d'offres transport (le cas échéant) ; tableau de bord transport ; procédure d'évaluation des prestataires.

  

Grille tarifaire (hypothèse à calibrer) : Essentiel 600 000 FCFA — Complet 1 200 000 FCFA — Premium 2 800 000 FCFA — Sur devis en multi-pays ou pour flotte propre de plus de 10 véhicules.

  

Prestation P8 — Audit et refonte du dernier kilomètre africain (hypothèse à calibrer, code F5-DERNIER-KM)

  

Objectif : auditer les circuits de livraison au client final (motos-taxis, zemidjans, livreurs indépendants, services de coursiers), et poser un dispositif aligné sur le contexte local (contractualisation, assurance basique, protocole de remise, gestion des litiges, traçabilité). P8 est spécifique à l'Afrique de l'Ouest et du Centre : on ne traite pas le dernier kilomètre d'Abidjan ou de Cotonou comme on traiterait celui d'une ville européenne, parce que les acteurs, les règles de responsabilité et les modes de contractualisation sont différents.

  

Durée indicative : 15 à 30 jours.

  

Livrable attendu : cartographie des circuits actuels avec coûts ; proposition de contractualisation (contrat type adapté au statut du livreur, règle de rémunération, règle de sanction) ; protocole de remise au client (preuve de livraison, signature, photo, code à usage unique selon le cas) ; dispositif d'assurance basique si recommandé ; procédure de traitement des litiges.

  

Grille tarifaire (hypothèse à calibrer) : Essentiel 400 000 FCFA — Complet 800 000 FCFA — Premium 1 800 000 FCFA.

  

Prestation P9 — Pilotage logistique mensuel en abonnement (hypothèse à calibrer, code F5-PILOTAGE-LOG-MENSUEL)

  

Objectif : accompagnement mensuel du dirigeant et du responsable logistique sur une cadence régulière, avec revue des indicateurs F05, pilotage des stocks à risque via STOCK FONDANT, alerte sur les dérives, recommandation d'actions. P9 est la forme d'abonnement D de F05 et peut suivre P2+P3+P4 comme suite logique naturelle.

  

Durée indicative : par abonnement — minimum 6 mois, renouvelable par tacite reconduction.

  

Livrable attendu : relevé de séance mensuel ; tableau de bord F05 à jour ; carte des stocks à risque mise à jour ; alerte en cas de dérive ; note de cap trimestrielle.

  

Grille tarifaire (hypothèse à calibrer) : Essentiel 100 000 FCFA — Complet 200 000 FCFA — Premium 450 000 FCFA. Les montants sont mensuels. Note de calibrage : les niveaux retenus sont proches du Coaching stratégique F01 P7 (F3-COACHING) ajustés légèrement à la hausse à cause de la charge d'actualisation du module STOCK FONDANT.

  

Prestation P10 — Cadrage import-export OHADA et douanes UEMOA/CEMAC (hypothèse à calibrer, code F5-IMPORT-EXPORT-OHADA)

  

Objectif : cadrer pour un client une opération ou une filière d'import-export en zone UEMOA ou CEMAC — choix du régime douanier applicable (mise à la consommation, entrepôt sous douane, admission temporaire, perfectionnement), chiffrage des droits et taxes, recommandation d'un transitaire ou d'un courtier en douane, ordonnancement des pièces et des délais. P10 produit la matière ; les actes douaniers eux-mêmes (déclarations, cautionnement) sont signés par un transitaire ou commissionnaire en douane agréé.

  

Durée indicative : 15 à 40 jours selon la complexité.

  

Livrable attendu : note de cadrage douanier ; ordonnancement des pièces et des étapes ; chiffrage des droits et taxes ; recommandation de transitaires avec motivation ; bordereau de documents à faire signer par le transitaire.

  

Grille tarifaire (hypothèse à calibrer) : Essentiel 600 000 FCFA — Complet 1 200 000 FCFA — Premium 2 500 000 FCFA — Sur devis en régime suspensif complexe, en multi-régime, ou en multi-pays.

  

Mapping prestations × type de mission × filière × grade minimum

  

Toutes les prestations F05 sont des missions au sens de la typologie O4 : A (diagnostic), B (structuration), C (redressement), D (abonnement). Le tableau ci-dessous donne le mapping utilisé en Portail pour l'attribution automatique.

  

– P1 Audit stock/log rapide : type A. Filière A ou B. Grade N1 minimum.

– P2 Diagnostic logistique approfondi : type A. Filière A ou B. Grade N2 pour PME, N3 pour PME confirmée et groupe.

– P3 Politique de stock : type B. Filière A ou B. Grade N3 minimum.

– P4 Audit stock dormant STOCK FONDANT : type B (parfois C quand les pertes à risque sont massives). Filière A ou B. Grade N2 minimum, validation N3 obligatoire du chiffrage.

– P5 Cartographie des flux et dimensionnement entrepôt : type B. Filière A ou B. Grade N3 minimum.

– P6 Audit casse et pertes : type A ou B selon le dossier. Filière A ou B. Grade N2 minimum.

– P7 Audit transport primaire/secondaire : type B. Filière A ou B. Grade N3 minimum, N5 consulté si flotte propre de plus de 10 véhicules.

– P8 Audit dernier kilomètre : type A ou B. Filière A ou B. Grade N2 minimum.

– P9 Pilotage logistique mensuel : type D. Filière A ou B. Grade N2 minimum, supervision N3 trimestrielle.

– P10 Cadrage import-export OHADA : type B. Filière A seulement pour les régimes suspensifs ; Filière A ou B pour la mise à la consommation. Grade N3 minimum + badge Douane à créer en PHASE 2.

  

Deux règles de commercialisation s'ajoutent. Première règle : un N0 (trois premiers mois) ne vend aucune prestation F05 ; il peut participer à l'exécution physique (comptage, étiquetage, observation terrain) sous supervision d'un N2+. Deuxième règle : un cabinet externe sous abonnement la plateforme SaaS MEDEGNAN (SX) peut vendre sous sa propre marque les prestations P1, P2, P3, P4, P5, P6, P8, P9 ; les prestations P7 (flotte propre significative) et P10 (régimes douaniers suspensifs) restent réservées au Réseau MEDEGNAN pour la V1 parce qu'elles engagent fortement la responsabilité éditoriale du cabinet sur des actes à forte exposition juridique.

  

Packs commerciaux récurrents

  

Trois packs commerciaux F05 sont identifiés comme devant être installés comme lignes propres dans offre\_catalogue en PHASE 2 (sous codes FP5A, FP5B, FP5C à ouvrir).

  

Pack FP5A "Reprise de stock" — P2 Diagnostic logistique approfondi + P4 STOCK FONDANT + P3 Politique de stock. Ce pack est l'entrée la plus souvent vendable chez un prospect PME de distribution, de pharmacie ou d'agroalimentaire qui constate une dérive de trésorerie liée au stock. Prix combiné proposé : 3 200 000 FCFA pour une PME de 21-50 salariés. Durée : 45 à 75 jours.

  

Pack FP5B "Entrepôt dimensionné" — P5 Cartographie + dimensionnement + P6 Audit casse/pertes + P8 Audit dernier kilomètre. Ce pack cible l'entreprise de distribution ou de négoce qui ouvre un nouvel entrepôt, déménage, ou veut reconstruire son maillage physique. Prix combiné proposé : 2 400 000 FCFA. Durée : 45 à 60 jours.

  

Pack FP5C "Chaîne import-export" — P10 Cadrage import-export OHADA + P7 Transport primaire + P2 Diagnostic volet importateur. Ce pack cible le négociant qui structure une filière d'importation (textile, électronique, intrants agricoles) ou d'exportation (cajou, karité, manioc) et qui a besoin d'une architecture logistique-douanière complète. Prix combiné proposé : 3 500 000 FCFA. Durée : 60 à 90 jours.

  

Les trois packs sont assortis d'une remise de 10 à 15 % par rapport à la somme des prestations unitaires — marge d'incitation à l'achat combiné, non négociable à la baisse.

  
  

## Item 3 — Référentiel des Problématiques Traitées

  

Le référentiel des problématiques F05 est constitué de deux étages complémentaires : les huit fuites référentielles inscrites en base (fuite\_referentiel, codes F05-1 à F05-8), et les situations types du dirigeant africain qui déclenchent typiquement l'une ou plusieurs de ces fuites. Les premières sont le langage interne du moteur ; les secondes sont le langage externe du client.

  

Étage 1 — Les huit fuites F05 inscrites en base

  

Rappel du régime : le consultant ne saisit jamais la fuite lui-même (règle 26/09/2026). C'est le moteur du cabinet, à partir des documents et de l'observation physique, qui détecte une exposition à une fuite et la propose à la revue humaine. Le consultant exerce son jugement, pas sa saisie. Un dossier F05 complet balaye obligatoirement les huit fuites référentielles — même pour conclure que l'une d'entre elles n'est pas exposée dans ce cas.

  

F05-1 — Pertes alimentaires/produits non chiffrées — inestimables. Type : invisible. Gravité : CRITIQUE. Ordre indicatif : 5-15 % du coût matière. Cause-type : absence de fiche de perte, mauvaise conservation. Signaux de détection : aucune ligne comptable "pertes" tenue régulièrement ; les matières dégradées sont jetées sans enregistrement ; le dirigeant estime oralement ses pertes mais ne les documente pas. L'invisibilité de cette fuite est son caractère le plus dangereux : ce qui n'est pas mesuré n'est jamais corrigé.

  

F05-2 — Ruptures de stock fréquentes sur produits clés. Type : visible. Gravité : CRITIQUE. Ordre indicatif : 10-20 % du chiffre d'affaires. Cause-type : stock tampon inexistant, prévision absente. Signaux de détection : plus de trois ruptures en douze mois sur une référence qui représente plus de 10 % du chiffre d'affaires ; clients qui réclament un produit non disponible ; commerciaux qui proposent "autre chose" faute du produit demandé. Visible parce qu'elle fait pleurer les ventes ; mais rarement remontée au bon niveau de priorité.

  

F05-3 — Écarts inventaire théorique vs réel non investigués. Type : systémique. Gravité : MAJEURE. Ordre indicatif : 5-10 % du stock. Cause-type : inventaire formel absent ou non réconcilié. Signaux de détection : aucune cadence d'inventaire physique tournant ; écart déclaré au dernier inventaire général mais pas traité ; valeur comptable du stock jamais rapprochée du physique.

  

F05-4 — Conditions de conservation inadéquates — pertes évitables. Type : visible. Gravité : MAJEURE. Ordre indicatif : 3-8 % matière. Cause-type : équipement insuffisant ou mal utilisé. Signaux de détection : chaîne du froid interrompue, humidité non contrôlée dans un entrepôt de riz ou de farine, exposition au soleil de produits photosensibles, absence de ventilation. Un passage de trente minutes dans l'entrepôt suffit souvent à poser le diagnostic.

  

F05-5 — FIFO non respecté — rotation stock défaillante. Type : comportementale. Gravité : MAJEURE. Cause-type : mauvaise organisation physique, habitude. Ordre indicatif : 2-5 % matière. Signaux de détection : les nouveaux arrivages sont déposés devant les anciens parce que c'est plus facile ; les équipes servent "ce qui est accessible" plutôt que "ce qui est le plus ancien" ; en pharmacie, détection par lecture des dates de péremption des références sorties la semaine précédente.

  

F05-6 — Vols de stock non détectés — absence de contrôle. Type : invisible. Gravité : MAJEURE. Ordre indicatif : 3-10 % du stock. Cause-type : aucun système de contrôle entrées/sorties. Signaux de détection : écarts d'inventaire récurrents concentrés sur des références à haute valeur ; agent unique sur l'entrée et la sortie ; absence totale de double contrôle ; témoignages diffus de l'équipe sur "des choses qui se passent".

  

F05-7 — Capacité stockage insuffisante — sous-commandes forcées. Type : visible. Gravité : MAJEURE. Ordre indicatif : 5-10 % du chiffre d'affaires. Cause-type : investissement insuffisant, contrainte infrastructurelle. Signaux de détection : marchandises stockées en zone non prévue (couloir, extérieur, chez un voisin), refus d'offres volume de la part des fournisseurs, commandes fractionnées multipliant les frais d'approche.

  

F05-8 — Absence de traçabilité lots — recalls impossibles. Type : systémique. Gravité : SECONDAIRE à CRITIQUE selon secteur. Risque principal : compliance. Cause-type : pas de système d'identification. Signaux de détection : les produits ne portent pas d'identifiant interne reliant lot fournisseur / lot stock / lot client ; en cas de crise sanitaire ou de rappel, l'entreprise est incapable d'identifier les clients ayant reçu le lot concerné. Gravité CRITIQUE pour pharmacie, agroalimentaire, cosmétique, dispositifs médicaux ; secondaire pour quincaillerie et mobilier.

  

Note doctrinale : le type et la gravité sont posés en base et ne doivent pas être modifiés par un consultant en cours de mission. Si la lecture d'un dossier suggère qu'une fuite F05 déclenchée est en réalité de gravité différente de celle inscrite, le point est remonté par note de contre-expertise à la direction, pas corrigé localement.

  

Étage 2 — Vingt situations types du dirigeant africain où F05 est la bonne entrée

  

Cette liste capitalise sur les dossiers réels du cabinet (Pharmacie Crystal, CASOMEG, Afokantan, Direct Santé, DIPRESS, GN-FROID-01, CI-MANIOC-01, les dossiers de distribution de la diaspora) et sur le registre de cas d'échecs africains.

  

Situation S1. "Mon banquier me dit que mon stock pèse trop lourd dans mon bilan et je ne sais pas quoi faire." Le dirigeant subit une pression financière liée à son besoin en fonds de roulement. Fuites typiquement déclenchées : F05-2, F05-3, F05-7. Entrée F05 appropriée : P2 puis P4 STOCK FONDANT.

  

Situation S2. "J'ai acheté un gros lot que je dois écouler avant la fin de l'année et je ne sais pas si j'arriverai." Fuites : F05-7 (anticipée). Entrée : P4 STOCK FONDANT en mode projectif, avec calcul de la date de bascule du capital à risque en perte.

  

Situation S3. "Trois de mes meilleurs clients m'ont quitté en six mois et je viens de comprendre que c'est parce qu'ils trouvaient toujours mon produit en rupture." Fuites : F05-2. Entrée : P2 puis P3 Politique de stock.

  

Situation S4. "Mes équipes me disent que l'inventaire est juste, mais quand je regarde l'écart avec mes achats, il manque trois millions." Fuites : F05-3, F05-6. Entrée : P6 Audit casse et pertes.

  

Situation S5. "Je suis pharmacien et j'ai 400 000 FCFA de références dont la péremption est à moins de trois mois." Fuites : F05-1, F05-4. Entrée : P4 STOCK FONDANT immédiat, puis P3 Politique de stock avec règle FEFO.

  

Situation S6. "Je dois choisir entre louer un deuxième entrepôt ou optimiser le premier et je ne sais pas trancher." Fuites : F05-7, parfois F05-5. Entrée : P5 Cartographie des flux et dimensionnement.

  

Situation S7. "Mon transporteur me livre toujours en retard et je perds des clients." Fuites : liées aux flux aval. Entrée : P7 Audit transport secondaire + P8 Audit dernier kilomètre selon le périmètre.

  

Situation S8. "Je veux importer de Chine mais je ne connais pas les droits de douane." Fuites : non F05 directement, F05 instrumentale. Entrée : P10 Cadrage import-export OHADA.

  

Situation S9. "Mon entrepôt sent mauvais, mes clients s'en plaignent, je ne sais pas si c'est grave." Fuites : F05-4. Entrée : P5 volet conservation.

  

Situation S10. "Les livreurs de ma plateforme me volent et je ne sais pas comment les contrôler." Fuites : adjacentes à F05-6. Entrée : P8 Audit dernier kilomètre avec dispositif de traçabilité et protocole de remise.

  

Situation S11. "Je viens de lancer mon site de e-commerce et je ne sais pas comment organiser mes livraisons." Entrée : P5 (mini-dimensionnement) + P8.

  

Situation S12. "Mes stocks tournent moins vite depuis un an et ma trésorerie se dégrade." Fuites : F05-2, F05-7. Entrée : P2 + P4.

  

Situation S13. "Mon fournisseur principal me change ses conditions et me demande d'acheter par lots de six mois." Fuites : F05-7 (anticipée). Entrée : P3 + négociation articulée F04.

  

Situation S14. "J'ai des produits qui se perdent dans mon entrepôt — je sais qu'ils existent mais je ne les trouve pas." Fuites : F05-3, F05-5. Entrée : P5 (volet implantation) + P3.

  

Situation S15. "J'ai acheté un camion de livraison et je ne sais pas si je dois le garder ou m'en séparer." Fuites : adjacentes à F05-7. Entrée : P7 avec comparatif propre vs sous-traité.

  

Situation S16. "Je viens d'ouvrir une activité de froid positif et je ne maîtrise rien." Fuites : F05-4 (anticipée). Entrée : P5 volet froid + P3.

  

Situation S17. "Mes équipes passent leur temps à chercher les produits dans l'entrepôt et je perds des heures." Fuites : F05-5 (implantation), F05-3. Entrée : P5.

  

Situation S18. "Je soupçonne du vol dans mon entrepôt mais je n'ai aucune preuve." Fuites : F05-6. Entrée : P6 Audit casse et pertes avec volet contrôle.

  

Situation S19. "Je dois préparer un rappel sanitaire d'un lot mais je ne sais pas à qui je l'ai vendu." Fuites : F05-8. Entrée : P3 (urgence) + implémentation d'identifiants lot.

  

Situation S20. "Mon entrepôt est plein à craquer pendant la saison et vide trois mois plus tard, je ne sais pas comment gérer." Fuites : F05-7 saisonnière. Entrée : P3 (volet saisonnalité) + P5 (volet modulaire).

  

Spécificités du terrain africain à prendre en compte dans le diagnostic F05

  

Cinq spécificités du terrain de l'Afrique francophone de l'Ouest et du Centre doivent être explicitement considérées par le consultant F05, parce qu'elles infléchissent l'application des méthodes logistiques internationales.

  

Spécificité T1 — Routes variables et saison des pluies. Les délais de transport primaire et secondaire ne sont pas des moyennes, ils sont des bimodaux saisonniers. Le calcul d'un stock de sécurité qui ignorerait la saison des pluies (juin à octobre selon la zone) est un calcul faux. La règle est de poser deux paramètres saisonniers par référence sensible, pas un paramètre moyen.

  

Spécificité T2 — Infrastructures de stockage limitées et humidité. Un entrepôt sans ventilation, sans contrôle d'humidité, sans protection contre l'exposition solaire directe produit des pertes qui n'existeraient pas en climat tempéré. La règle est de systématiquement regarder "comment c'est stocké" avant de regarder "combien est stocké".

  

Spécificité T3 — Informel dominant chez les livreurs. Les livreurs indépendants — zemidjans à Cotonou, taxis-motos à Lagos, coursiers libres à Abidjan — n'ont souvent pas de statut formel ni d'assurance. La contractualisation prend des formes adaptées : code à usage unique au moment de la remise, photo de preuve de livraison, dépôt de pièce d'identité au départ de l'entrepôt, assurance basique mutualisée.

  

Spécificité T4 — Culture de l'inventaire orale et approximative. Dans un grand nombre de PME africaines, l'inventaire se fait oralement ou avec des cahiers tenus à la main. La transition vers un inventaire écrit, daté et signé est une conduite du changement qui exige de la méthode et de la patience. La règle est de ne pas imposer un ERP comme préalable à la prestation : un inventaire sur cahier A4, bien tenu, vaut mieux qu'un ERP mal nourri.

  

Spécificité T5 — Pression saisonnière sur les stocks (Ramadan, Tabaski, rentrée scolaire, Noël, cultures agricoles). Les pics de ventes concentrés sur une à trois semaines sont particulièrement marqués sur le continent. La règle est de poser les stocks de pic en calendrier nominatif (date de Ramadan de l'année, date de rentrée scolaire par pays) et pas en moyenne annuelle.

  
  

## Item 4 — Catalogue des Diagnostics Disponibles

  

Un diagnostic F05 n'est pas un acte isolé : c'est une classe d'instruments dont le choix dépend de la profondeur recherchée, du délai disponible et du niveau d'engagement du client. Le cabinet dispose, au 21 novembre 2026, de quatre instruments de diagnostic logistique et de stock. Chacun est rattaché à un livrable type et à une entrée tarifaire.

  

Instrument D1 — Audit Flash logistique (volet F05 de l'Audit Flash universel 12 fonctions)

  

Nature : audit court, volet F05 de l'Audit Flash universel qui balaye les 12 fonctions CORE. Durée : 48 à 72 heures à partir de la mise à disposition des pièces. Produit d'entrée systématique, obligatoire avant toute prestation F05 structurante (P2 à P10), sauf exception motivée.

  

Méthode : lecture de six pièces minimales — dernier inventaire général daté et signé, extrait de balance comptable portant les comptes de stock, trois factures d'achat représentatives, trois bons de livraison fournisseur, extrait des ventes mensuelles sur les six derniers mois, bordereau d'achats annuels par fournisseur — puis visite d'une heure à l'entrepôt principal avec le dirigeant ou le responsable logistique. Le moteur produit un relevé des huit fuites F05, avec niveau d'exposition (confirmée, probable, non exposée, non documentée).

  

Livrable : rapport Audit Flash (3 à 5 pages pour le volet F05) ; verdict GO / GO CONDITIONNEL / NO-GO sur l'ouverture d'une mission structurante F05 ; recommandation de l'instrument de diagnostic approfondi pertinent.

  

Prix : 250 000 FCFA (grille V3.2), prix unique non segmenté — inclut l'audit des 12 fonctions, pas seulement F05.

  

Instrument D2 — Diagnostic logistique et stock approfondi (D2 = prestation P2)

  

Nature : diagnostic complet qui applique intégralement le bloc Logistique de MC-PROTO-F05-F06-V1.0, avec un volet Qualité allégé lorsque l'activité du client en réclame (agroalimentaire, pharmacie, cosmétique). Le diagnostic porte sur l'ensemble des cinq axes de la grille G1 F05 et sur les huit fuites F05.

  

Méthode : cinq passes séquentielles — cadrage, inventaire physique partiel (échantillon par stratification de valeur), analyse de rotation et couverture, détection des stocks à risque (déclenchement conditionnel de STOCK FONDANT), cartographie des flux d'entrée-sortie, test de résistance à la rupture. Collecte de 15 à 30 pièces documentaires ; entretiens avec le dirigeant, le responsable logistique, un échantillon d'équipe entrepôt, et à discrétion un ou deux fournisseurs clés et un ou deux clients clés.

  

Livrable : rapport de 35 à 70 pages, présentation de restitution, plan opérationnel pour chaque fuite critique.

  

Prix : voir prestation P2 à l'Item 2.

  

Instrument D3 — Scan STOCK FONDANT (volet autonome)

  

Nature : diagnostic ciblé sur la seule exposition aux stocks à risque (péremption, obsolescence, immobilisation), sans traiter le reste du périmètre F05. Applique intégralement MC-STOCK-FONDANT-V1.

  

Méthode : les quatre signaux d'activation sont vérifiés en premier ; si aucun n'est présent, le livrable écrit NON APPLICABLE et la mission s'arrête (le principe que NON APPLICABLE est un résultat, pas un silence, est appliqué). Si au moins un signal est présent, le module calcule la mécanique de fonte référence par référence selon la méthode §03 du protocole : rythme réel de sortie mesuré sur deux inventaires successifs, courbe de décote construite par rapport à l'échéance, capital à risque cumulé.

  

Livrable : Carte des stocks à risque avec drapeaux (vert / orange / rouge) ; proposition d'action par référence (écouler, retourner, céder, suspendre, maintenir) ; procédure de pilotage mensuel ; alertes de bascule.

  

Prix : rattaché à la prestation P4. Grille indicative Essentiel 500 000 FCFA — Complet 1 000 000 FCFA — Premium 2 200 000 FCFA (à calibrer).

  

Instrument D4 — Audit casse-écarts-vols (Décision-Scan logistique)

  

Nature : audit rétrospectif sur les 12 derniers mois des pertes non comptabilisées. Mesure la qualité des pertes sur quatre critères : traçabilité (le relevé existe-t-il), typologie (le type de perte est-il distingué entre casse, rebut, vol, écart, perte transport), responsabilité (la ligne de défense est-elle identifiée), action (une mesure corrective a-t-elle été prise). D4 est un diagnostic peu invasif, exploitable sous 10 à 15 jours, qui révèle rapidement un problème de contrôle plus large.

  

Méthode : fouille de la messagerie et des pièces internes (bons de casse, procès-verbaux d'écart, rapports du responsable logistique) ; inventaire tournant sur un échantillon de références à haute valeur ; entretiens ciblés avec l'équipe entrepôt. Un moteur dédié (à construire, à préciser avec le fondateur en PHASE 2) traite la matière.

  

Livrable : rapport Décision-Scan logistique (10 à 20 pages) ; matrice des pertes classées par type et par criticité ; cinq recommandations prioritaires.

  

Prix : hypothèse Essentiel 350 000 FCFA — Complet 650 000 FCFA — Premium 1 400 000 FCFA. À calibrer.

  

Règle d'enchaînement des diagnostics

  

– D1 (Audit Flash) est le passage obligé avant D2, D3 ou D4 sauf dérogation motivée.

– D2 se vend seul et inclut D3 en version déclenchée si un signal STOCK FONDANT est détecté au cadrage.

– D3 se vend seul quand l'entreprise est manifestement exposée aux stocks à risque (pharmacie, agroalimentaire, saisonnier) et que le dirigeant veut un signal rapide avant d'investir dans un diagnostic plus large.

– D4 est un instrument d'alerte rapide, souvent proposé en réponse à une demande du dirigeant qui soupçonne un problème de vol ou d'écarts sans savoir le dire. Il débouche typiquement sur D2 ou sur une prestation P6 selon le résultat.

  
  

## Item 5 — Questionnaires de Pré-Diagnostic

  

Le questionnaire de pré-diagnostic F05 a trois fonctions : (a) qualifier la demande du prospect pour vérifier qu'elle relève bien de F05 et pas d'une autre fonction (principalement F04 Achats, F06 Production ou F08 Finance) ; (b) préciser quelle prestation du catalogue est pertinente ; (c) donner au moteur la matière première pour proposer une liste des fuites probablement déclenchées. Le questionnaire est administré en entretien, chronométré à 60 minutes maximum, par un consultant N2 minimum, et complété obligatoirement par une visite physique d'une heure minimum de l'entrepôt principal.

  

Ce questionnaire n'est pas une grille de scoring ; le scoring est fait par le moteur à partir des réponses. Le consultant pose les questions, écoute, note ce qu'il voit, et laisse le moteur faire l'inférence. Règle MC-REGLE-INDICATEUR-PROUVE-V1 : chaque réponse est classée stated (ce que le dirigeant dit), observed (ce que le consultant voit dans l'entrepôt), inferred (ce que le consultant déduit sous responsabilité).

  

Les 15 questions de pré-diagnostic F05

  

Bloc A — Cadrage de la demande (3 questions)

  

Q1. Qu'est-ce qui vous amène à nous contacter aujourd'hui, et qu'est-ce qui a changé dans les six derniers mois ? Objectif : dater l'événement déclencheur. Variables à capter : nature du déclencheur (interne/externe), ancienneté, degré d'urgence.

  

Q2. Combien avez-vous actuellement en stock, en valeur comptable et en jours de couverture ? Objectif : mesurer la conscience quantitative du dirigeant. Un dirigeant qui ne sait pas répondre, même approximativement, est en pilotage aveugle — signal fort.

  

Q3. Quelle est la dernière perte de stock que vous avez constatée, et comment l'avez-vous découverte ? Objectif : capter le mode de détection des pertes. Révèle F05-1 et F05-6 indirectement.

  

Bloc B — Qualité et profondeur de l'inventaire (3 questions)

  

Q4. À quelle date remonte votre dernier inventaire physique complet, et qui l'a signé ? Objectif : tester la discipline d'inventaire. Un inventaire de plus de douze mois sans signature engage l'alerte F05-3.

  

Q5. Si je prends dix références au hasard dans votre informatique et que j'envoie quelqu'un les compter dans l'entrepôt, combien seront justes à plus ou moins 5 % ? Objectif : capter la confiance du dirigeant dans son propre stock théorique.

  

Q6. Avez-vous des références que vous ne voyez jamais tourner mais qui restent au bilan ? Objectif : repérer l'exposition à STOCK FONDANT.

  

Bloc C — Rotation et politique de stock (3 questions)

  

Q7. Quelles sont vos trois références principales, et combien de jours de couverture avez-vous sur chacune ? Objectif : capter la connaissance opérationnelle du dirigeant sur son portefeuille à fort enjeu. Révèle F05-2 indirectement si la couverture est inconnue ou extrême.

  

Q8. Comment décidez-vous quand recommander, et qui prend cette décision ? Objectif : tester la politique de stock effective. Révèle F05-7 (sous-commandes forcées) ou F05-5 (habitudes).

  

Q9. Quelle part de votre chiffre d'affaires venez-vous de perdre ces douze derniers mois à cause d'une rupture ? Objectif : chiffrer F05-2. Un dirigeant qui ne sait pas répondre déclenche l'instruction F05-2 par le moteur.

  

Bloc D — Conditions physiques et circuits (3 questions)

  

Q10. Comment est stocké votre produit le plus sensible (chaud/froid/humidité) ? Objectif : tester F05-4 sans attendre la visite. Révèle le niveau de maîtrise des conditions de conservation.

  

Q11. Qui peut entrer dans votre entrepôt, et comment une sortie de marchandise est-elle enregistrée ? Objectif : tester F05-6 (contrôle d'accès et traçabilité des mouvements).

  

Q12. Combien de personnes manipulent votre stock entre l'arrivée du fournisseur et la livraison au client ? Objectif : cartographie initiale des points de rupture potentielle.

  

Bloc E — Flux et transport (3 questions)

  

Q13. Comment vos marchandises arrivent-elles chez vos clients, et qui en est responsable en cas de litige ? Objectif : capter le mode de transport secondaire et le dernier kilomètre. Révèle le besoin P7/P8.

  

Q14. Avez-vous déjà eu à faire un rappel de lot, et dans ce cas comment avez-vous identifié les clients concernés ? Objectif : tester F05-8 (traçabilité lots). Question particulièrement sensible en pharmacie et agroalimentaire.

  

Q15. Si vous deviez augmenter votre volume de 30 % dans les six mois, qu'est-ce qui lâcherait en premier dans votre logistique ? Objectif : test de résistance à la croissance. Révèle les goulots structurels.

  

Observation obligatoire à la visite d'entrepôt

  

En complément des 15 questions, cinq observations obligatoires lors de la visite physique :

  

O1. Zonage effectif : y a-t-il une zone de réception, une zone de stockage courant, une zone de stockage dormant, une zone de préparation, une zone d'expédition, une zone de litige ? Si ces zones ne sont pas identifiées, F05-5 est confirmé.

  

O2. Signalétique et étiquetage : les emplacements portent-ils une référence, et les produits portent-ils un étiquetage lot ? Si l'étiquetage lot est absent sur une activité réglementée, F05-8 est confirmé.

  

O3. Dates de péremption : échantillonnage sur dix produits avec date — combien à moins de trois mois d'échéance ? Déclenche STOCK FONDANT si présence.

  

O4. Conditions physiques : température, humidité perçue, ventilation, propreté. Si inadéquates, F05-4 est confirmé.

  

O5. Contrôle d'accès : y a-t-il une porte dédiée, un registre d'entrée-sortie, une séparation entre agent recevant et agent expédiant ? Si absence, F05-6 est présumé.

  

Transposition du questionnaire pour un cabinet externe la plateforme SaaS MEDEGNAN

  

Un cabinet souscripteur la plateforme SaaS MEDEGNAN utilise les mêmes 15 questions et les mêmes 5 observations. La règle de lecture par le moteur et la cartographie des huit fuites est la même. Le livrable de pré-diagnostic porte la marque du cabinet souscripteur et non la marque MEDEGNAN (décision D-la plateforme SaaS MEDEGNAN-6 du 21/11/2026 : les livrables la plateforme SaaS MEDEGNAN ne portent pas la marque MEDEGNAN). L'empreinte de méthode (Production, Logistique & Qualité Engine version ouverte) est citée au colophon.

  
  

## Item 6 — Grilles d'Analyse

  

Trois grilles principales sont utilisées en F05, alimentées par le moteur sur la base du pré-diagnostic et des cinq passes du bloc Logistique. Elles ne sont jamais remplies manuellement par le consultant ; elles sont sorties par le moteur et lues/validées par le consultant.

  

Grille G1 — Évaluation logistique multi-axes

  

Cinq axes, chaque axe noté 0 à 5. L'objectif n'est pas un score global mais le profil : une entreprise 5-5-5-5-5 n'existe pas ; le travail logistique consiste à savoir sur quels axes elle choisit d'être forte.

  

Axe G1.1 — Qualité de l'inventaire. Mesurée par trois paramètres : fréquence (rien / annuelle / semestrielle / trimestrielle / tournante continue), fiabilité (écart constaté au dernier recomptage), traçabilité (signature, date, auteur). Score 0 à 5.

  

Axe G1.2 — Vitesse de rotation et couverture. Mesurée par la rotation moyenne pondérée par la valeur (en tours/an) et par la dispersion (coefficient de variation des rotations par référence). Score 0 à 5 : 0 rotation moyenne inférieure à 2 ou dispersion extrême, 5 rotation supérieure à 10 avec distribution saine.

  

Axe G1.3 — Exposition au stock à risque (STOCK FONDANT). Mesurée par la part de la valeur du stock exposée à péremption, obsolescence ou dormance de plus de deux fois le délai normal. Score 0 à 5 : 0 plus de 30 % exposée, 5 moins de 2 % exposée.

  

Axe G1.4 — Conditions physiques et sécurité du stock. Mesurée par la conformité des conditions de conservation aux exigences du produit, par la sécurité physique (accès, surveillance, incendie) et par la traçabilité des mouvements. Score 0 à 5.

  

Axe G1.5 — Robustesse des flux amont-aval. Mesurée par la régularité des approvisionnements fournisseurs, la robustesse des circuits de transport, la qualité du dernier kilomètre. Score 0 à 5.

  

La grille G1 n'est pas additive (on ne fait pas un total sur 25). Elle est lue comme un profil radar à cinq pointes et sert à discuter avec le dirigeant.

  

Grille G2 — Profil STOCK FONDANT du portefeuille

  

Six axes, chaque axe noté 0 à 5, spécifique à l'évaluation de l'exposition au risque stock.

  

Axe G2.1 — Présence de produits à date (péremption/DLC/DLUO). Score 0 à 5 selon la part du portefeuille concernée.

  

Axe G2.2 — Rythme d'obsolescence. Vitesse à laquelle les références perdent leur attractivité commerciale (électronique rapide / mode saisonnier / produits pérennes). Score 0 à 5.

  

Axe G2.3 — Historique de pertes documentées. Pertes des 24 derniers mois chiffrées et classées par type. Score 0 à 5.

  

Axe G2.4 — Qualité des pièces de chiffrage. Disponibilité des factures d'achat, des dates par référence, des sorties mesurables. Rappelle la règle "pas de montant sans facture" héritée de MC-COREDX-V2.1-2026. Score 0 à 5.

  

Axe G2.5 — Capital à risque chiffré. Montant en FCFA que l'entreprise perdrait si rien n'était décidé dans les douze prochains mois. Score 0 à 5 par tranches de pourcentage du chiffre d'affaires.

  

Axe G2.6 — Capacité d'écoulement alternative. Existence de canaux dégradés (promotion, soldes, cession à des tiers, retour fournisseur, destruction encadrée) et de délais associés. Score 0 à 5.

  

Grille G3 — Maturité logistique à cinq niveaux

  

C'est une grille de classement global qui synthétise G1 et G2 en cinq paliers.

  

Niveau 1 — Entreprise au cahier. Inventaire oral ou sur cahier, aucune politique écrite, décisions au feeling, aucun indicateur. Score G1 moyen inférieur à 1,5. Caractéristique : l'inventaire est à faire avant toute autre chose.

  

Niveau 2 — Entreprise à l'Excel. Inventaire tenu en tableur mais non réconcilié avec les comptes, politique de stock implicite dans la tête du responsable, indicateurs à la demande. Score G1 entre 1,5 et 2,5.

  

Niveau 3 — Entreprise équipée. ERP ou WMS en place (même basique), inventaire réconcilié, politique de stock écrite mais pas systématiquement appliquée, indicateurs produits mensuellement. Score G1 entre 2,5 et 3,5.

  

Niveau 4 — Entreprise pilotée. Politique de stock appliquée référence par référence, inventaire tournant continu, tableau de bord logistique en temps réel, STOCK FONDANT activé sur les références à risque, procédure d'alerte en place. Score G1 supérieur à 3,5 et G2 supérieur à 3.

  

Niveau 5 — Entreprise prédictive. En plus du niveau 4, prévision de demande par algorithme ou par méthode statistique, optimisation dynamique des points de commande, pilotage multi-sites. Rare en Afrique francophone au stade actuel du marché.

  

La règle commerciale associée : une entreprise de niveau 1 ou 2 ne se vend pas une refonte complète de la politique de stock P3 avant d'avoir fait un diagnostic P2 et un inventaire physique signé. L'ordre est "savoir ce qu'on a avant de dire comment on le pilote".

  
  

## Item 7 — Matrices de Décision

  

Deux matrices de décision principales servent au consultant F05 pour orienter le client vers la bonne prestation sans se tromper d'étage.

  

Matrice M1 — Diagnostic / structuration / redressement selon la situation

  

M1 croise deux axes. Axe horizontal : état actuel de l'entreprise (en croissance / stable / en difficulté / en crise). Axe vertical : horizon d'action du dirigeant (court terme, un trimestre / moyen terme, un à deux ans / long terme, trois ans et plus).

  

Cellule croissance × long terme : prestation d'entrée P2 Diagnostic approfondi suivi de P3 Politique de stock et P5 Cartographie/dimensionnement. L'enjeu est d'organiser la croissance logistique avant qu'elle ne devienne subie.

  

Cellule croissance × moyen terme : P3 + P5. L'entreprise croît mais son maillage physique ne suit pas.

  

Cellule croissance × court terme : P4 STOCK FONDANT (si exposition) ou P6 Audit casse/pertes. On traite le point de douleur immédiat.

  

Cellule stable × long terme : P2 + P3 pour installer une politique durable.

  

Cellule stable × moyen terme : P4 + P6. On regarde où le stock dormant et les pertes grignotent la marge.

  

Cellule stable × court terme : P1 Audit stock/log rapide + P4.

  

Cellule difficulté × long terme : P2 + P4 + P3 + P5. Les difficultés logistiques sont rarement isolées — on refond.

  

Cellule difficulté × moyen terme : P4 + P3 en priorité. Sauver la trésorerie immobilisée dans le stock est le premier geste.

  

Cellule difficulté × court terme : P4 en urgence, articulé à F08 pour la trésorerie.

  

Cellule crise × long terme : combinaison inhabituelle, à vérifier avec le dirigeant.

  

Cellule crise × moyen terme : P4 + P6 en pilotage de crise, articulé à F08.

  

Cellule crise × court terme : P4 immédiat (les stocks à risque sont la seule poche de cash accessible rapidement sans dette nouvelle) + P6 (chasse aux pertes).

  

Matrice M2 — Choix d'instrument selon le profil de stock et la taille

  

M2 croise la nature du stock (sans échéance / à échéance / à obsolescence rapide / mixte) et la taille de l'entreprise (micro / petite / PME / PME confirmée / groupe).

  

Les règles d'articulation sont les suivantes :

  

– Stock sans échéance × micro : P1 + P3 version allégée. STOCK FONDANT marqué NON APPLICABLE dans le livrable.

– Stock sans échéance × petite/PME : P2 + P3 + P6.

– Stock à échéance × toutes tailles : P4 STOCK FONDANT en priorité, puis P3 avec règle FEFO.

– Stock à obsolescence rapide × toutes tailles : P4 STOCK FONDANT version obsolescence + P3 avec règle de limite d'âge en portefeuille.

– Stock mixte × PME et au-delà : P2 complet + P4 + P3 + P5.

– Groupe (plus de 150) : P2 Premium + P5 Premium + P3 Premium, souvent couplé à un cahier des charges WMS et à un pilotage d'intégrateur externe.

  

La règle d'arrière-plan : la taille emporte la profondeur de la mission, pas la nature des prestations. On ne refuse jamais à un micro-entrepreneur une prestation P4 sous prétexte qu'il est petit — on l'applique en version allégée, et on sait que STOCK FONDANT est particulièrement puissant en micro parce que c'est là que la perte relative d'un lot à péremption est la plus violente pour la trésorerie.

  
  

## Item 8 — Protocoles d'Intervention

  

Les protocoles sont les séquences standardisées qui disent au consultant "voici dans quel ordre tu fais quoi". Trois protocoles principaux faisant foi, dont deux inscrits en base (protocole\_fonction, F05) et un à promouvoir en PHASE 2.

  

Protocole P-LOG — MC-PROTO-F05-F06-V1.0, bloc Logistique (Rotation et Couverture)

  

Référence en base : MC-PROTO-F05-F06-V1.0. Nature : fonction. F05 principal : à passer en true en PHASE 2 (actuellement principal = false parce que le protocole est partagé avec F06 ; en pratique, pour F05, il fait foi).

  

Le bloc Logistique applique la Gestion des Stocks par la Rotation et la Couverture, conformément à la méthode portée par le protocole : "le stock est du capital immobilisé qui se dégrade ; sa mesure n'est pas sa valeur mais sa vitesse". L'architecture enchaîne cinq passes.

  

Passe 1 — Cadrage. Identification du périmètre (références traitées, sites concernés, période d'observation), mobilisation du module métier v2.2 pour poser la logique économique, les modulateurs sectoriels et le mode N0 si applicable. Sortie : note de cadrage signée.

  

Passe 2 — Inventaire physique partiel. Échantillonnage stratifié par valeur : tiers des références représentant 80 % de la valeur (comptage exhaustif), tiers représentant 15 % (échantillonnage), tiers représentant 5 % (balayage). Comptage avec deux personnes, enregistrement, signature. Sortie : inventaire daté signé qui fait foi pour le reste de la mission.

  

Passe 3 — Rotation et couverture. Calcul par référence : rythme mensuel de sortie mesuré sur deux inventaires successifs, couverture théorique (quantité actuelle / rythme), classification ABC-XYZ (A/B/C par valeur, X/Y/Z par régularité). Sortie : carte de rotation.

  

Passe 4 — Détection des stocks à risque et déclenchement conditionnel de STOCK FONDANT. Si au moins un des quatre signaux d'activation est présent (voir §02 STOCK FONDANT), passage au protocole dédié STOCK FONDANT en passe 4 bis. Sinon, mention "NON APPLICABLE" écrite au livrable.

  

Passe 4 bis — STOCK FONDANT (conditionnelle). Application intégrale de MC-STOCK-FONDANT-V1 §03 — Mécanique de fonte. Pour chaque référence à risque, calcul du rythme réel, construction de la courbe de décote par rapport à l'échéance, calcul du capital à risque. Propriété héritée : aucune écriture comptable n'est touchée. La valeur comptable officielle est lue, jamais modifiée. La valeur de pilotage est un instrument de décision interne.

  

Passe 5 — Cartographie des flux et test de résistance à la rupture. Cartographie des flux entrée-sortie, inter-sites si applicable. Test théorique de rupture sur les trois références principales (que se passe-t-il si la référence tombe en rupture 48 h / une semaine / un mois ?). Sortie : plan opérationnel associé à chaque fuite critique.

  

Règles d'exécution P-LOG : chaque passe ferme par un livrable intermédiaire signé par le dirigeant (pas par le consultant seul). Le passage à la passe suivante exige la signature de la précédente. Durée théorique d'application complète : 15 à 35 jours. Grade minimum d'exécution : N1 pour les passes 1-2-3 et 5, N2 pour la passe 4 avec validation N3 du chiffrage.

  

Protocole P-STKF — MC-STOCK-FONDANT-V1 (module propriétaire)

  

Référence en base : MC-STOCK-FONDANT-V1. Nature : fonction. Diffusion : consultation au Espace Consultant uniquement. Propriété : MEDEGNAN CONSULTING, confidentiel. Protocole propriétaire — il ne sort pas du Portail.

  

STOCK FONDANT est le module CORE propriétaire le plus distinctif de F05 et, avec lui, du cabinet. Son nom et sa doctrine sont inspirés de la monnaie fondante de Silvio Gesell : une valeur qui se dégrade avec le temps force la circulation. Ici, elle force l'écoulement. Le module ne touche à aucune valeur comptable — cette ligne est une règle absolue, rappelée en tête du protocole (MC-STOCK-FONDANT-V1 §01, \[ATTENTION\] La ligne que le cabinet ne franchit pas). Il calcule une valeur de pilotage, qui descend mois après mois tant que la référence ne bouge pas, et qui alimente un chiffre de capital à risque exprimé en FCFA.

  

Les trois notions à ne jamais confondre, inscrites au protocole :

  

– Valeur comptable officielle. Fixée par la loi comptable et l'expert-comptable, au coût d'achat ou au coût de revient. Elle sert les comptes, le bilan, la fiscalité. Le module n'y touche jamais. Elle est lue, jamais modifiée.

  

– Valeur de pilotage. Fixée par le présent protocole, par décote progressive. Elle sert la décision du dirigeant : commander, écouler, retourner, arrêter. C'est elle que le module calcule.

  

– Capital à risque. Fixé par le présent protocole, en francs. Il dit ce que l'entreprise perdra si rien n'est décidé. C'est le chiffre que porte le diagnostic.

  

Verrou d'entrée §02. Le module ne se déclenche pas parce qu'une entreprise détient du stock. Il se déclenche quand ce stock porte une échéance, c'est-à-dire quand le temps lui fait perdre sa valeur. Les quatre signaux d'activation sont : (a) produits à date de péremption/DLC/DLUO/validité (pharmacie, agroalimentaire, cosmétique, chimie, semences, intrants) ; (b) produits à obsolescence rapide (électronique, téléphonie, informatique, mode, textile saisonnier) ; (c) références sans sortie depuis l'ouverture ou depuis plus de deux fois leur délai d'écoulement normal ; (d) achats par lots imposés par le fournisseur ou stock initial calibré sur une activité non atteinte. Hors de ces cas, le module écrit NON APPLICABLE et le livrable le porte : NON APPLICABLE est un résultat, pas un silence.

  

Pièces exigées avant de chiffrer §02. Quantité par référence à date (inventaire daté signé) — sans elle, aucun chiffrage. Date de péremption ou d'obsolescence par référence — sans elle, la référence est écartée du calcul et listée comme non datée. Prix d'achat unitaire (facture d'achat ou bon de livraison valorisé) — sans lui, la référence est comptée en unités, jamais en francs, et marquée NON CHIFFRABLE avec motif. Sorties observées sur une période (deux inventaires successifs ou registre des sorties) — sans elles, le rythme est déclaré par le dirigeant avec certitude ESTIME, base declaration\_dirigeant. Commandes en cours (bons de commande, factures fournisseur) — sans elles, le module signale qu'il ignore ce qui va entrer. Règle héritée de CORE-DX v2.1, rappelée en \[CRITIQUE\] : aucun montant sans facture. Un stock valorisé au prix de vente, au prix du marché ou à un prix que le dirigeant se rappelle n'est pas un montant, c'est une opinion.

  

Mécanique de fonte §03. Le calcul se fait référence par référence. Il ne s'applique jamais au stock pris globalement : une moyenne cache exactement ce que le module cherche. Trois étapes : (1) rythme réel de sortie — rythme mensuel calculé par différence entre deux inventaires successifs, ajustée des entrées documentées ; (2) construction de la courbe de décote — fonction du ratio entre quantité actuelle et sortie restante jusqu'à l'échéance, avec plateaux et marches selon le secteur ; (3) calcul du capital à risque — somme sur l'horizon de ce que l'entreprise perdrait si rien n'était décidé, chiffré en FCFA et exprimé en part du chiffre d'affaires.

  

Sorties du module : (a) carte des stocks à risque avec drapeaux vert/orange/rouge ; (b) propositions d'action par référence (écouler à prix dégradé, retourner au fournisseur, céder à un acteur tiers, suspendre les commandes, maintenir) ; (c) procédure de pilotage mensuel ; (d) alerte automatique au franchissement de seuil. Le module tourne mensuellement une fois installé et devient le socle de la prestation P9 (pilotage logistique en abonnement).

  

Protocole P-FLUX — MC-PROTO-F05-FLUX-V1 (à produire en PHASE 2)

  

Protocole dédié à la cartographie des flux et au dimensionnement d'entrepôt. Référence future : MC-PROTO-F05-FLUX-V1. À produire en PHASE 2 en articulation avec les cas réels du cabinet (notamment Pharmacie Crystal V2 dont la cartographie des flux a servi de référence de profondeur en 2026). Structure proposée (à valider en PHASE 2) : (1) cartographie des points physiques (lieux, zones, étagères) ; (2) cartographie des flux par volume et par fréquence ; (3) analyse ABC d'activité (références les plus mouvementées) ; (4) proposition d'implantation avec règles FIFO/FEFO ; (5) calcul de surface utile et préconisations d'équipement. Note : la rédaction de ce protocole est un chantier P-FLUX à ouvrir, à préciser avec le fondateur.

  

Protocoles courts (procédures) rattachés à F05

  

Outre les trois protocoles principaux ci-dessus, cinq protocoles courts dits "procédures" couvrent des actes opérationnels récurrents (voir Item 9).

  
  

## Item 9 — Procédures Opérationnelles

  

Les procédures sont des séquences courtes, de 1 à 3 pages chacune, qui disent au consultant comment accomplir un acte opérationnel précis. Elles sont rattachées aux prestations et aux protocoles ci-dessus.

  

Procédure PR1 — Conduite d'un inventaire physique signé (durée : 2 à 5 jours ouvrés selon le volume)

  

Objectif : conduire un inventaire physique datable, signable, qui fait foi pour le reste de la mission F05 et qui peut être réconcilié avec la comptabilité.

  

Étapes : (1) stratification préalable des références par valeur (ABC) ; (2) préparation des bordereaux de comptage avec numéro de référence, emplacement et quantité théorique masquée ; (3) comptage à deux personnes (jamais une seule, règle anti-fraude et anti-erreur) avec une tierce personne tournante pour les écarts ; (4) écarts documentés avec motif probable (vol, erreur de saisie, erreur de comptage, périmé) ; (5) signature du responsable logistique, du consultant et du dirigeant ; (6) remise d'un original à chaque signataire et d'une copie au dossier mission.

  

Règle qualité : un inventaire conduit par une seule personne n'est pas validable. Un inventaire sans écart constaté est suspect — l'absence d'écart dans une PME africaine moyenne est statistiquement anormale et appelle une vérification croisée.

  

Procédure PR2 — Déclenchement et conduite d'un module STOCK FONDANT (durée : 3 à 7 jours ouvrés après inventaire)

  

Objectif : activer le module STOCK FONDANT, conduire la première mécanique de fonte, livrer la carte des stocks à risque initiale.

  

Étapes : (1) vérification des quatre signaux d'activation §02 — au moins un présent = activation, aucun présent = NON APPLICABLE écrit au livrable ; (2) collecte des pièces exigées §02 (inventaire signé, dates par référence, factures d'achat, mesures de sortie) ; (3) application de la mécanique §03 référence par référence ; (4) validation du chiffrage par un N3 ; (5) rédaction de la carte des stocks à risque avec drapeaux ; (6) proposition d'action par référence ; (7) présentation au dirigeant avec décision écrite par référence.

  

Règle qualité : aucun chiffrage sans facture d'achat unitaire. Si une référence n'a pas de facture, elle est comptée en unités et marquée NON CHIFFRABLE avec motif. La règle est non négociable (CORE-DX v2.1). Rappel au livrable que la valeur de pilotage ne s'écrit ni dans les comptes, ni dans une déclaration fiscale, ni dans un document remis à un tiers financier — elle reste un instrument de décision interne.

  

Procédure PR3 — Animation d'une restitution logistique devant le dirigeant et le conseil (durée : séance 60 à 120 minutes)

  

Objectif : rendre une restitution F05 sobre et professionnelle devant un dirigeant et éventuellement un conseil, selon le standard MC-STANDARD-RESTITUTION-CLIENT-V2.

  

Étapes : (1) préparation d'un support de 30 à 50 slides avec les deux blocs structurants obligatoires — "ce que notre analyse a révélé que vous ne pouviez pas voir seul" et "là où nous agissons, et ce que ça rapporte" ; (2) séquencement en six blocs — contexte, inventaire et qualité, rotation et couverture, stocks à risque et STOCK FONDANT, flux et dernier kilomètre, décisions proposées ; (3) animation de la séance : le consultant ne défile pas des slides, il conduit une conversation ; (4) relevé des décisions prises en séance et des décisions reportées ; (5) envoi du relevé dans les 72 heures.

  

Règle qualité : un rapport logistique défilé page par page est l'anti-exemple. La restitution porte la décision ; les livrables lourds (annexes complètes, tableau de rotation détaillé, matrice STOCK FONDANT) restent en annexe, consultables mais non défilés.

  

Procédure PR4 — Documentation d'un sinistre logistique (durée : 2 à 5 jours ouvrés)

  

Objectif : capturer un sinistre logistique (casse massive, perte en transport, vol constaté, péremption de lot, arrêt de chaîne du froid) dans un document pérenne qui puisse servir d'apprentissage et éventuellement de pièce d'assurance.

  

Étapes : (1) entretien avec les témoins et l'équipe entrepôt ; (2) lecture des pièces associées (bons de livraison, rapports du transporteur, enregistrements de température si applicable) ; (3) rédaction d'une note de 3 à 5 pages selon un plan fixe — contexte, fait, chiffrage, cause probable, mesure corrective, enseignement rétroactif ; (4) validation par le dirigeant ; (5) inscription dans le dossier de mémoire logistique.

  

Règle qualité : un sinistre non documenté dans les 90 jours est présumé perdu. L'apprentissage rétroactif se perd avec le temps.

  

Procédure PR5 — Alertage sur une décision logistique à risque (durée : 24 à 72 heures)

  

Objectif : lorsqu'en cours de mission le consultant observe le dirigeant préparer une décision logistique qu'il juge risquée (gros achat non assuré, changement de transporteur sans contrat, ouverture d'un site sans dimensionnement), formaliser une alerte écrite.

  

Étapes : (1) formulation écrite de l'alerte, 1 page maximum, selon le plan : fait observé, risque identifié, analogues documentés, recommandation ; (2) transmission au dirigeant sous accusé de lecture ; (3) consignation dans le dossier mission ; (4) relecture du Licencié référent si le consultant est d'un grade inférieur à N3.

  

Règle qualité : l'alerte est un acte de responsabilité, pas un acte de défiance. Son ton est sobre et factuel. Aucun jugement, aucune interpellation, aucune familiarité.

  
  

## Item 10 — Modèles de Livrables

  

Les modèles de livrables F05 sont ancrés dans la table public.nature\_livrable (confirmée en base : rapport\_diagnostic, plan\_operationnel, presentation\_restitution, dossier\_financement, dossier\_digitalisation). Pour F05 spécifiquement, cinq natures sont actives, plus quatre en attente d'ajout.

  

Modèle L1 — Rapport de diagnostic logistique (nature rapport\_diagnostic)

  

Structure imposée (13 sections) :

S1. Résumé exécutif (2 pages).

S2. Contexte et raison du diagnostic.

S3. Inventaire physique partiel — méthode et résultats.

S4. Rotation et couverture par famille.

S5. Exposition au stock à risque — carte STOCK FONDANT.

S6. Cartographie des flux amont-aval.

S7. Conditions physiques et sécurité du stock.

S8. Cartographie des huit fuites F05 avec niveau d'exposition.

S9. Chiffrage des pertes et du capital à risque (trois sous-totaux obligatoires).

S10. Décisions prioritaires sur trois mois.

S11. Plan opérationnel associé (en annexe technique).

S12. Mention explicite des points non traités et renvois.

S13. Colophon, méthode, visa.

  

Règle qualité : chaque chiffre porte un lien vers sa pièce justificative. Les totaux généraux sont interdits — trois sous-totaux obligatoires (sorti de la caisse, dû non payé, non gagné). Aucune généralité, zéro jugement non argumenté.

  

Modèle L2 — Carte STOCK FONDANT (nature à créer : carte\_stock\_fondant)

  

Format : tableau par référence avec les colonnes suivantes — code, désignation, lot si applicable, quantité au comptage, date de péremption ou d'obsolescence, prix d'achat unitaire (sinon NON CHIFFRABLE), valeur comptable, rythme mensuel de sortie, couverture résiduelle à l'échéance, valeur de pilotage calculée, capital à risque, drapeau, action proposée, responsable de l'action, date cible. Une ligne par référence à risque. Vue synthétique en tête : total capital à risque, part du chiffre d'affaires exposée, nombre de drapeaux rouges, nombre d'actions en cours.

  

Règle qualité : aucune valeur de pilotage ne figure dans un document destiné à un tiers financier (banquier, bailleur, acquéreur). Rappel §01 STOCK FONDANT : la valeur de pilotage ne s'écrit ni dans les comptes, ni dans une déclaration, ni dans un document remis à un tiers financier. Elle est un instrument de décision interne.

  

Modèle L3 — Politique de stock (nature à créer : politique\_stock)

  

Document pérenne, 25 à 50 pages. Structure : (1) périmètre d'application ; (2) classification ABC-XYZ du portefeuille ; (3) règle de rotation applicable (FIFO par défaut, FEFO pour produits à date, LIFO uniquement sur cas motivé) ; (4) paramètres par référence ou famille — point de commande, stock de sécurité, stock maximum ; (5) règles saisonnières ; (6) règles de rupture acceptée vs non acceptée ; (7) règles de transfert inter-sites ; (8) liste nominative des trois à cinq personnes habilitées à commander hors paramètres, avec seuils et contreparties ; (9) procédure d'alerte ; (10) procédure de revue trimestrielle.

  

Modèle L4 — Note d'orientation logistique (nature à créer : note\_logistique)

  

Format court, 3 à 8 pages. Structure : (1) la décision posée en une phrase ; (2) la recommandation en une phrase ; (3) les trois arguments principaux ; (4) les deux objections à anticiper ; (5) le calendrier de mise en œuvre ; (6) les dispositions d'arrêt et de retour en arrière ; (7) les pièces jointes.

  

Modèle L5 — Plan opérationnel F05 (nature plan\_operationnel, en base)

  

Format importable Notion/Trello, actions numérotées par phase P1-A01 à Pn-Ann. Quatre phases standardisées : Stabilisation (mois 1-3 — inventaire, STOCK FONDANT, politique immédiate), Structuration (mois 4-6 — politique de stock complète, cartographie des flux), Accélération (mois 7-18 — refonte transport, dernier kilomètre, module CORE F05 installé), Consolidation (mois 19-36 — pilotage multi-sites, prédictif si pertinent).

  

Modèle L6 — Cahier des charges d'entrepôt (nature à créer : cahier\_charges\_entrepot)

  

Document produit en P5. Structure : (1) activité portée, volumétrie et saisonnalité ; (2) zonage requis avec surfaces et contraintes ; (3) spécifications techniques (hauteur sous plafond, portance sol, ventilation, froid, étanchéité, protection incendie) ; (4) équipement (rayonnages, allées, signalétique, matériel de manutention) ; (5) contraintes réglementaires et d'accès ; (6) critères d'évaluation d'une proposition.

  

Modèle L7 — Cahier des charges transport (nature non encore nommée)

  

Document produit en P7. Structure : (1) périmètre des flux à couvrir ; (2) volumétrie par circuit, saisonnalité ; (3) exigences de délai, de température, de protection ; (4) règles d'évaluation des prestataires ; (5) régime de responsabilité ; (6) procédure de litige.

  

Modèle L8 — Présentation de restitution F05 (nature presentation\_restitution, en base)

  

Format conforme MC-STANDARD-RESTITUTION-CLIENT-V2. Entre 30 et 50 slides pour un diagnostic P2. Deux blocs structurants obligatoires (voir Procédure PR3). Visuels alignés sur la charte MEDEGNAN. Référence de profondeur citée par le fondateur : Pharmacie Crystal V2.

  

Modèle L9 — Procédure dernier kilomètre (nature à créer : procedure\_dernier\_km)

  

Document court produit en P8. Structure : (1) cadre contractuel du livreur (statut, assurance, rémunération, sanctions) ; (2) protocole de remise au client (preuve de livraison, signature, photo, code à usage unique selon le cas) ; (3) procédure de litige ; (4) tableau de bord livreur.

  

Règle commune à tous les livrables F05 : référence MC-DOC-AAAA-NNNNN, sceau MEDEGNAN VERIFIED en bas de page, mention de la méthode (Production, Logistique & Qualité Engine — bloc Logistique — et, si applicable, STOCK FONDANT) au colophon, signature consultant + visa Licencié.

  

Règles de forme des livrables selon MC-STANDARD-RESTITUTION-CLIENT-V2 et doctrine 12/11/2026

  

Doctrine fondatrice : le client dirigeant n'a pas le temps de lire un rapport de 60 pages. Il lit un support de restitution court et présentable, qui porte la décision et le plan ; les livrables lourds restent en annexes, consultables mais non défilés. Cette doctrine s'applique à l'ensemble des modèles F05 — avec un enjeu particulier pour les cartes STOCK FONDANT, qui doivent rester lisibles alors qu'elles peuvent porter 500 à 2 000 lignes de références.

  

Règle de visualisation. Les rapports et les présentations de restitution privilégient les visuels sur le texte brut : cartes de stock avec drapeaux, histogrammes de rotation par famille, radar des cinq axes G1, chronologies de capital à risque. Le rendu est "plus attirant et moins textuel" (fondateur 12/11/2026). Référence de profondeur : Pharmacie Crystal V2.

  

Règle de deux blocs structurants. Toute restitution F05 porte deux blocs explicites, nommés en toutes lettres dans le support : "ce que notre analyse a révélé que vous ne pouviez pas voir seul" (démonstration de la valeur du cabinet par l'analyse — typiquement un capital à risque chiffré que le dirigeant ne voyait pas) et "là où nous agissons, et ce que ça rapporte" (démonstration de la valeur par les leviers chiffrés — typiquement un écoulement forcé qui libère un mois de BFR). Sans ces deux blocs, la restitution est rejetée au contrôle qualité.

  

Règle d'anonymisation. Lorsqu'un livrable F05 destiné à un client est ensuite converti en contenu de publication (étude de cas, publication sur les réseaux), l'anonymisation complète est obligatoire : aucun élément qui permettrait au porteur de se reconnaître ou à un tiers de le reconnaître (ville, secteur exact, nombre de références, cabinet cité). Le mot "anonymisation" couvre non seulement la suppression du nom mais aussi la réécriture des indices indirects.

  

Règle sur les totaux. Jamais un total général isolé ; toujours trois sous-totaux (sorti de la caisse, dû non payé, non gagné). La doctrine du 19/09/2026 s'applique particulièrement aux livrables F05 qui chiffrent des pertes et des capitaux à risque.

  

Règle sur l'origine des chiffres. Chaque chiffre porte un lien vers sa pièce justificative. Pour les montants reconstitués oralement en entretien (cas fréquent en Afrique lorsque les pièces n'existent pas), la mention "reconstitué par entretien" est explicite et le niveau de preuve est signalé stated/observed/inferred. Règle non négociable héritée de STOCK FONDANT : aucun montant sans facture.

  
  

## Item 11 — Tableaux de Bord Spécifiques F05

  

Le tableau de bord logistique F05 est à la fois un livrable (dans la prestation P3 et dans l'abonnement P9) et un outil propriétaire (module CORE F05 à instancier chez le client). Il comporte cinq blocs d'indicateurs qui répondent aux cinq verbes de la raison d'être F05.

  

Bloc T1 — Ce qu'on a (inventaire et qualité)

  

Indicateurs : (a) date du dernier inventaire physique signé ; (b) écart constaté au dernier recomptage, par valeur et par nombre de références ; (c) fréquence d'inventaire tournant (références touchées par mois) ; (d) nombre de références non datées (concerne le déclenchement STOCK FONDANT).

  

Bloc T2 — À quelle vitesse ça bouge (rotation et couverture)

  

Indicateurs : (a) rotation moyenne pondérée par la valeur (tours/an) ; (b) couverture moyenne (jours de vente dans le stock) ; (c) distribution ABC-XYZ (part de A en valeur, part de C en nombre de références, part de X/Y/Z en régularité) ; (d) nombre de références en rupture dans le mois sur les références A ; (e) nombre de références en sur-stock (couverture supérieure à 2× le point de commande).

  

Bloc T3 — Ce qui risque de se perdre (STOCK FONDANT)

  

Indicateurs : (a) capital à risque total (FCFA) ; (b) part du chiffre d'affaires annuel exposée ; (c) nombre de références en drapeau rouge, orange, vert ; (d) nombre d'actions d'écoulement en cours ; (e) nombre d'actions clôturées dans le mois ; (f) réalisé vs projeté d'écoulement.

  

Bloc T4 — Comment ça circule (flux)

  

Indicateurs : (a) nombre de transferts inter-sites dans le mois ; (b) coût complet de transport primaire (par tonne-kilomètre ou par livraison) ; (c) coût complet de transport secondaire ; (d) taux de livraison dans les délais ; (e) coût du dernier kilomètre par livraison et par zone.

  

Bloc T5 — Ce qui se perd (pertes)

  

Indicateurs : (a) pertes du mois chiffrées par type (casse, rebut, vol, écart, péremption) ; (b) pertes cumulées sur 12 mois glissants ; (c) ratio pertes/valeur stock ; (d) nombre de sinistres déclarés et traités ; (e) nombre d'alertes de dérive déclenchées et traitées.

  

Chaque bloc produit un drapeau : vert si tous les indicateurs sont dans la norme, orange si un ou deux sont hors norme, rouge si plus de deux sont hors norme ou si un indicateur critique (capital à risque \> 15 % CA, rupture sur une référence A représentant plus de 10 % CA) est détecté.

  

Module CORE F05 à instancier

  

Doctrine de distribution 16-17/11/2026 : chaque prestation P3 et chaque abonnement P9 placent un module CORE F05 chez le client, jamais un simple tableur. Le module CORE F05 intègre : connecteur vers l'ERP ou le WMS existant si présent, saisie manuelle simplifiée sinon (fallback qui n'exige pas un ERP), rendu temps réel des cinq blocs, génération du procès-verbal mensuel pré-rempli, génération d'une alerte automatique au-delà des seuils, et déclenchement conditionnel du sous-module STOCK FONDANT. Le module CORE F05 est facturé par abonnement (prestation P9 continue). La branche F05 du CORE à instancier est à préciser avec le fondateur en articulation avec la stratégie CORE open-source de MC-ARCHI-PLAT-V2.3 : le référentiel et la grille des fuites F05 vont sur github.com/medegnan/core, le module CORE F05 exécutable reste privé.

  
  

## Item 12 — Critères de Contrôle Qualité

  

Un livrable F05 est validable si et seulement si les douze critères suivants sont remplis, dans cet ordre. L'ordre est important parce qu'il reflète la priorisation décisionnelle MEDEGNAN.

  

Critère CQ1 — Standard MC-STANDARD-RESTITUTION-CLIENT-V2 appliqué. La présentation de restitution porte la décision, les livrables lourds restent en annexes. Deux blocs obligatoires présents : "ce que notre analyse a révélé" et "là où nous agissons, et ce que ça rapporte". Référence de profondeur : Pharmacie Crystal V2.

  

Critère CQ2 — Lisibilité pour un dirigeant non expert. Zéro jargon non défini dans le document. Chaque terme méthodologique utilisé (FIFO, FEFO, couverture, rotation, ABC-XYZ, STOCK FONDANT) est explicité en une phrase à sa première occurrence. Longueur des phrases contrôlée.

  

Critère CQ3 — Chiffrage en FCFA avec les trois sous-totaux. Pas de total général isolé. Chaque chiffre porte un lien vers sa pièce justificative. Règle non négociable : aucun montant sans facture d'achat unitaire (STOCK FONDANT CORE-DX v2.1).

  

Critère CQ4 — Régime de preuve explicite (MC-REGLE-INDICATEUR-PROUVE-V1). Pour chaque donnée, mention stated / observed / inferred. Aucune donnée inférée sans note de méthode. Pour une donnée reconstituée oralement, mention "reconstitué par entretien" explicite.

  

Critère CQ5 — Zéro généralité. Chaque recommandation quantifiée, datée, attribuée à un responsable nommément.

  

Critère CQ6 — Inventaire daté et signé. Un livrable F05 structurant qui n'est pas appuyé sur un inventaire daté et signé des trois derniers mois est rejeté. L'ancienneté maximale de l'inventaire d'appui est de 90 jours.

  

Critère CQ7 — Les huit fuites F05 traitées. Même pour conclure à la non-exposition d'une fuite, le livrable l'adresse explicitement.

  

Critère CQ8 — Valeur comptable jamais modifiée. Si STOCK FONDANT est activé, rappel explicite au livrable que la valeur de pilotage ne touche pas la valeur comptable et ne figure dans aucun document destiné à un tiers financier. Règle absolue, hérite de la ligne que le cabinet ne franchit pas (STOCK FONDANT §01).

  

Critère CQ9 — Visa Licencié N3 minimum pour une prestation type B ou C. Un livrable sans visa de relecture est non remis au client. Pour les livrables STOCK FONDANT, le chiffrage lui-même est validé par un N3.

  

Critère CQ10 — Signature MEDEGNAN VERIFIED en bas de chaque livrable. Référence MC-DOC unique.

  

Critère CQ11 — Articulation avec les autres fonctions documentée. Le livrable F05 nomme explicitement les interfaces avec F01, F04, F06, F08, F09, F10 pertinentes.

  

Critère CQ12 — Cohérence entre présentation de restitution et livrable détaillé. Aucune décision portée en séance qui n'apparaisse dans le livrable, et aucune décision inscrite dans le livrable qui n'ait été portée en séance.

  

Procédure de contrôle qualité

  

Tout livrable F05 fait l'objet d'une relecture par un Licencié N3 ou supérieur avant transmission au client. Pour les livrables à forte portée (P3 Politique de stock, P4 STOCK FONDANT, P7 Transport, P10 Import-export), une contre-lecture par un second consultant indépendant est obligatoire. Pour les dossiers à forte exposition (secteurs réglementés — pharmacie, agroalimentaire soumis à HACCP, cosmétique, dispositifs médicaux), un N5 est consulté avant signature.

  

Règle spécifique STOCK FONDANT : tout chiffrage de capital à risque supérieur à 50 000 000 FCFA ou supérieur à 15 % du chiffre d'affaires du client est contre-lu par un N3 habilité STOCK FONDANT (badge à créer en PHASE 2) avant transmission.

  
  

## Item 13 — Compétences Requises pour Vendre et Exécuter F05

  

La doctrine V2.1 rappelée : les 12 fonctions définissent le périmètre de vente, pas la qualification d'exécution. Le grade (N0 à N7) commande la complexité du protocole appliqué, pas le droit d'exécuter sur la fonction.

  

Compétences commerciales F05

  

Compétence CM1 — Qualifier une demande logistique en 60 minutes + 1 heure d'entrepôt. Le consultant doit pouvoir, à partir des 15 questions du pré-diagnostic et des 5 observations d'entrepôt, déterminer : (a) si la demande relève bien de F05 ou s'il faut rediriger (par exemple vers F04 Achats ou F08 Finance pour une question de BFR qui n'est pas d'origine stock), (b) quelle prestation du catalogue est pertinente, (c) quelles fuites F05 sont probablement déclenchées. Cette compétence s'acquiert à l'Académie MEDEGNAN, module "Qualification de demande logistique", 12 heures.

  

Compétence CM2 — Entrer dans un entrepôt. Un consultant F05 n'est pas un consultant de bureau. Il entre dans l'entrepôt, il touche les marchandises, il regarde les étiquettes, il sent les odeurs, il mesure les températures, il compte un échantillon. La compétence est physique autant que méthodologique. Un consultant F05 qui ne veut pas entrer en entrepôt n'est pas un consultant F05.

  

Compétence CM3 — Dire ce que le cabinet ne fait pas. Un consultant qui promet tout vend mal. En F05 particulièrement, les limites sont nombreuses : fiscalité des stocks (expert-comptable), intégration ERP/WMS complet (intégrateur spécialisé), exploitation de flotte comme métier principal (branche sectorielle MEDEGNAN CORE dédiée), actes douaniers (transitaire agréé), contrats d'assurance (courtier). Le consultant pose la chaîne de compétences avec un ton assumé.

  

Compétence CM4 — Proposer la bonne entrée commerciale. Ne pas proposer un P3 Politique de stock à une entreprise qui n'a pas fait son inventaire. Ne pas proposer un P10 Import-export à une entreprise qui n'a pas de volume d'import régulier. Ne pas proposer un P4 STOCK FONDANT à une entreprise qui n'a aucun stock à échéance (NON APPLICABLE écrit au livrable, et on respecte le résultat).

  

Compétence CM5 — Présenter la grille tarifaire sans se dérober. L'Audit Flash à 250 000 FCFA est un prix fixe, non négociable. Les grilles P1 à P10 sont ouvertes à négociation sur les paramètres (niveau, périmètre, délais, nombre de sites) mais pas sur l'existence de la prestation. La segmentation par taille pour P2 Diagnostic approfondi emporte le prix — un dirigeant de PME de 30 salariés qui demande le prix "petite entreprise" (6-20) n'obtient pas ce prix.

  

Compétences méthodologiques F05

  

Compétence ME1 — Lire et appliquer le bloc Logistique de MC-PROTO-F05-F06-V1.0. Le consultant connaît les trois méthodes constitutives (Théorie des Contraintes, Rotation et Couverture, PDCA/Coût de non-qualité), sait énoncer leur apport propre et leur complémentarité, applique les cinq passes dans l'ordre imposé.

  

Compétence ME2 — Maîtriser STOCK FONDANT. Le consultant connaît les quatre signaux d'activation, les trois notions à ne jamais confondre (valeur comptable / valeur de pilotage / capital à risque), la mécanique de fonte §03, et la règle absolue "aucun montant sans facture". Il sait écrire NON APPLICABLE au livrable quand aucun signal n'est présent, et il sait que NON APPLICABLE est un résultat, pas un silence.

  

Compétence ME3 — Conduire un inventaire physique signé. Le consultant sait stratifier par valeur, organiser le comptage à deux personnes, documenter les écarts, obtenir les signatures. Compétence qui s'acquiert par répétition supervisée, pas par cours.

  

Compétence ME4 — Interpréter les fuites référentielles sans les saisir. Règle fondamentale 26/09/2026 : le consultant n'inscrit pas de fuites en base. Il lit celles que le moteur propose, exerce son jugement, valide ou conteste par note de contre-expertise.

  

Compétence ME5 — Chiffrer en FCFA avec les trois sous-totaux. Le consultant ne présente jamais un total général ; il présente ce qui est sorti, ce qui est dû, ce qui n'a pas été gagné. Règle particulièrement sensible en F05 où les pertes ont tendance à être présentées de façon agrégée.

  

Compétence ME6 — Appliquer la règle MC-REGLE-INDICATEUR-PROUVE-V1. Pas d'indicateur favorable issu de l'absence d'un signal défavorable ; une mesure absente est "non mesuré", jamais zéro. Un inventaire qui ne trouve pas de perte n'est pas une absence de perte — c'est un inventaire potentiellement incomplet.

  

Compétence ME7 — Articuler F05 avec le module métier v2.2. Le consultant charge d'abord MC-MODULE-METIER v2.2 qui détermine la logique économique, les modulateurs sectoriels, le contexte d'exercice, la qualité de lecture et les arbitrages ; sa sortie reconfigure l'application du bloc Logistique. Compétence transversale à F05 et F06.

  

Compétences relationnelles F05

  

Compétence RE1 — Gérer la relation avec un responsable logistique souvent défensif. Dans une PME africaine, le responsable logistique est parfois en poste depuis des années, détient la mémoire physique du stock, et voit dans la mission F05 une menace. Le consultant travaille avec lui, pas contre lui, et sait que la perte de sa coopération rend la mission non exécutable. La règle est de l'associer dès l'inventaire, de lui laisser un rôle de signataire, et de ne jamais le court-circuiter devant le dirigeant.

  

Compétence RE2 — Rendre une restitution devant un dirigeant qui va voir ses pertes en face. La restitution F05 est particulièrement sensible parce qu'elle révèle au dirigeant des pertes qu'il ne voyait pas. La compétence est de les présenter avec maîtrise — ni en les édulcorant, ni en les instrumentalisant — et de proposer un chemin de traitement qui préserve la dignité du dirigeant et de son équipe.

  

Compétence RE3 — Conduire un comité stock. Comité trimestriel qui réunit dirigeant, responsable logistique, responsable commercial et responsable achats. Savoir tenir la rigueur méthodologique sans infantiliser, savoir conclure sur des décisions écrites.

  

Compétence RE4 — Gérer un sinistre en cours de mission. Un sinistre logistique (vol constaté, lot entier périmé, arrêt de chaîne du froid) qui se déclare pendant la mission exige une posture d'urgence maîtrisée. Doctrine du fondateur : on accepte ce qui est, sans se culpabiliser ni multiplier les excuses, en gardant la position de leader.

  

Compétence RE5 — Restitution sobre d'une erreur du cabinet si elle est constatée. Toute reconnaissance d'erreur ou d'incident imputé au cabinet envers un tiers passe par l'accord express préalable du fondateur (règle impérative permanente). Le consultant ne reconnaît jamais seul une faute du cabinet dans un écrit adressé à un collaborateur ou à un client.

  

Correspondance compétences × badges MEDEGNAN à instaurer

  

Deux badges existants sont pertinents pour F05 : "Certifié Académie MEDEGNAN" (prérequis général) et "Expert Global" (optionnel, couvre les 12 fonctions). Trois badges sont à créer en PHASE 2 pour F05 spécifiquement : "STOCK FONDANT" (badge d'habilitation à P4, et de contre-lecture des chiffrages \> 50 millions FCFA), "Douane OHADA" (badge d'habilitation à P10 en régime suspensif), "Froid et chaîne sensible" (badge d'habilitation aux missions avec contrainte de température contrôlée, pharmacie, agroalimentaire périssable, cosmétique, dispositifs médicaux). La création des trois badges est à préciser avec le fondateur.

  
  

## Item 14 — Collaborations avec les Autres Fonctions

  

F05 n'est pas une fonction autarcique. Elle appelle, elle est appelée, elle articule. Les ponts avec les autres fonctions sont les suivants.

  

Pont F05 → F01 (Stratégie et gouvernance)

  

Pont de signal : un stock chroniquement en dérive remonte comme signal d'absence de cap sur les lignes à abandonner (fuites F01-1, F01-9 selon le cas). Un diagnostic F05 qui révèle qu'un tiers des références n'a aucune rotation et que le dirigeant continue à les commander par habitude fournit à F01 un argument pour un renoncement chiffré. L'enchaînement standard : P4 STOCK FONDANT (F05) → remontée à F01 → P2 ou P3 F01 avec ligne de renoncement.

  

Pont F05 → F03 (Commercial et ventes)

  

Pont systématique. F05 pose la disponibilité, F03 vend. Une rupture F05-2 détruit une vente F03 ; une politique de stock F05 pensée hors de la demande commerciale réelle (saisonnalité, événements, canaux) produit des stocks dormants. L'enchaînement standard pour un diagnostic PME : P2 F05 + P2 F03 doivent se croiser avant la rédaction de la politique de stock P3. Package commercial : "F05 + F03", vendu sous l'appellation "Disponibilité et vente alignées", à hypothèse de prix combiné de 2 800 000 à 5 500 000 FCFA selon la taille.

  

Pont F05 → F04 (Achats et approvisionnement)

  

Pont le plus fréquent. F05 détecte, F04 corrige en amont. Un lot imposé par le fournisseur (signal d'activation STOCK FONDANT) est un problème F04 avant d'être un problème F05. Une négociation F04 bien menée réduit la nécessité d'un P4 F05. L'enchaînement : P4 F05 → P-ACHATS F04 pour la renégociation fournisseur → P3 F05 adapté aux nouvelles conditions.

  

Pont F05 → F06 (Production/Services)

  

Pont physique direct. F05 et F06 partagent le même protocole (MC-PROTO-F05-F06-V1.0) parce qu'elles forment une chaîne physique unique — ce qui est produit doit être stocké, ce qui est stocké doit être conforme. En entreprise manufacturière, les deux fonctions se co-diagnostiquent systématiquement. L'enchaînement standard : passe 1 et 2 du protocole conduites conjointement (cadrage, inventaire physique), puis chaque bloc poursuit son analyse propre, puis restitution croisée.

  

Pont F05 → F08 (Administration et finance)

  

Pont de trésorerie. Chaque mois de couverture de stock excessif est un mois de BFR immobilisé. Un capital à risque STOCK FONDANT est une ligne de trésorerie à l'inverse (potentiel de libération par écoulement forcé). L'enchaînement standard : P4 F05 → C1 pilotage de trésorerie F08 avec intégration du capital à risque dans le plan de cash. Le dirigeant qui comprend qu'il peut libérer 60 jours de BFR en écoulant son stock à risque devient un décideur mobilisé.

  

Pont F05 → F09 (Information, données et outils de gestion)

  

F05 identifie les indicateurs logistiques à produire ; F09 construit ou instancie le module CORE F05 ou le connecteur vers l'ERP/WMS existant. Le module CORE F05 s'appuie sur les connecteurs F09 pour collecter l'inventaire théorique de l'ERP et le confronter à l'inventaire physique de la mission F05.

  

Pont F05 → F10 (Juridique et conformité)

  

Pont systématique dès que F05 recommande des actes réglementés (régime douanier suspensif pour P10, contrat de dépôt complexe, contrat de transport multi-pays, contrat d'assurance marchandises de valeur significative). F05 produit la matière, F10 ou un pro réglementé tiers (transitaire, courtier, avocat) signe l'acte.

  

Pont F05 → F11 (Ressources, déchets et impact social — RSE)

  

F05 produit la matière des pertes et des rebuts ; F11 instruit leur traitement (filière de destruction encadrée, filière de recyclage, filière de valorisation). Pont de plus en plus fréquent en pharmacie (destruction des périmés sous contrôle d'un huissier) et en agroalimentaire (filière de valorisation des rebuts en alimentation animale).

  

Pont F05 → F12 (Innovation, partenariats et diversification)

  

F05 identifie des filières de valorisation possibles (circuit de seconde main pour électronique, filière de récupération pour emballages, filière de cession pour stocks dormants). F12 instruit la viabilité économique de ces filières comme diversification de revenus.

  

Pont F05 ← F01, F02, F03, F08 (fonctions amont)

  

Rarement appel direct mais signaux fréquents remontés : un cap stratégique qui réoriente le portefeuille (F01) déclenche une revue F05 de la politique de stock ; une étude de marché F02 qui identifie une nouvelle demande déclenche un dimensionnement de stock ; un diagnostic commercial F03 qui pointe des ruptures déclenche un audit P2 ou P4 ; un diagnostic de trésorerie F08 qui pointe un BFR anormal déclenche un P2 F05.

  
  

## Item 15 — Limites et Conditions d'Habilitation

  

Limites — quand F05 ne suffit PAS

  

Limite L1 — Fiscalité et traitement comptable des stocks. F05 produit la matière (valeur de pilotage, capital à risque, inventaire daté signé) mais ne rédige jamais de provision comptable, de dépréciation fiscale, ou de déclaration douanière. La valeur de pilotage ne s'écrit ni dans les comptes, ni dans une déclaration fiscale, ni dans un document remis à un tiers financier (STOCK FONDANT §01). L'expert-comptable inscrit à l'Ordre signe le traitement comptable ; le transitaire agréé signe la déclaration douanière.

  

Limite L2 — Intégration d'un ERP ou WMS complet. F05 pose le cahier des charges, l'arbitrage fonctionnel, la conduite du changement, mais l'intégration elle-même relève d'un intégrateur spécialisé que F05 peut cadrer mais pas remplacer. Pour un groupe de plus de 150 salariés engageant un projet ERP, F05 accompagne, ne pilote pas.

  

Limite L3 — Exploitation de flotte comme activité principale. Un client dont le métier est de transporter pour le compte d'autrui relève d'une branche sectorielle MEDEGNAN CORE dédiée (branche Transport, idée propre du fondateur 26/10/2026, voir /areas/ticketage-transport.md). F05 traite la logistique interne, pas l'exploitation logistique de tiers.

  

Limite L4 — Exploitation d'un entrepôt tiers comme activité principale. Un client dont le métier est de louer des mètres carrés d'entrepôt à d'autres (3PL) relève d'une branche sectorielle dédiée. F05 traite la logistique interne, pas l'exploitation d'entrepôt de tiers.

  

Limite L5 — Assurance des marchandises. F05 peut évaluer l'exposition et conseiller le principe (quelles marchandises assurer, à quelle hauteur, contre quels risques) mais le contrat d'assurance lui-même est négocié avec un courtier.

  

Limite L6 — Rappel sanitaire ou crise de contamination. En cas de rappel sanitaire ou de crise de contamination avérée, la mission F05 cède la main à un expert sanitaire inscrit (laboratoire d'analyse, bureau d'études accrédité) pour la part technique du rappel. F05 appuie en traçabilité (fuite F05-8) et en communication interne, pas en décision sanitaire.

  

Limite L7 — Secteurs à régulation technique forte (pharmacie hospitalière, dispositifs médicaux implantables, nucléaire, pétrole brut). F05 peut intervenir sur le volet logistique courant mais les exigences techniques spécifiques (HACCP spécialisé, ISO 13485, normes ADR) relèvent de consultants spécialisés. L'adapter pharmacie en officine simple reste au périmètre F05 ; l'hospitalier est hors périmètre.

  

Limite L8 — Entreprise en création sans flux réel. F05 ne vend pas de politique de stock complète à une entreprise qui n'a ni fournisseur ni client ni stock réel. Pour une entreprise en création, l'entrée pertinente est MC-FORMULE-FONDAMENTALE-V1 puis MC-CANEVAS-V1, et F05 reprend la main après le premier palier de flux réel.

  

Conditions d'habilitation à vendre F05

  

Pour un Consultant Intégré (S1) : couvert par la licence du cabinet, pas d'habilitation séparée. Doit respecter le grade minimum par type de prestation.

  

Pour un Consultant Partenaire (S2) : habilitation F05 à demander auprès du cabinet. Supervision d'un Licencié N3+ obligatoire si le grade du S2 est inférieur à N3. Rémunération 75/25 selon V2.1.

  

Pour un Licencié (S3) : habilitation F05 dans son périmètre contractuel (Licence Spécialiste ayant F05, ou Licence Expert Global). Liberté de vente, pas de supervision cabinet (sauf prestation P4 qui requiert le badge STOCK FONDANT, P7 avec flotte propre significative qui requiert consultation N5, et P10 en régime suspensif qui requiert le badge Douane OHADA).

  

Pour un Franchisé (S4) : non ouvert au 21/11/2026, horizon projeté.

  

Pour un Cabinet externe souscripteur la plateforme SaaS MEDEGNAN (SX) : abonnement la plateforme SaaS MEDEGNAN actif (formule SX-Pro minimum pour F05 compte tenu du volume de crédits IA requis en STOCK FONDANT). Pas de marque MEDEGNAN sur les livrables (décision D-la plateforme SaaS MEDEGNAN-6). Accès plateforme restreint. Prestations ouvertes à la vente : P1, P2, P3, P4, P5, P6, P8, P9. Prestations non ouvertes : P7 (flotte propre significative), P10 (régimes douaniers suspensifs) — contrôle qualité non formalisable à distance en V1, à reconsidérer en PHASE 3.

  

Habilitations d'exécution par type et grade minimum (rappel)

  

Type A (diagnostic) : grade N1 minimum pour P1, N2 pour P2 PME, N3 pour P2 PME confirmée et groupe.

Type B (structuration) : grade N2 minimum, validation N3 obligatoire pour P4 STOCK FONDANT, grade N3 minimum pour P3, P5, P7, P10.

Type C (redressement) : grade N3 minimum + badge STOCK FONDANT pour P4 en mode redressement (capital à risque \> 50 millions FCFA ou \> 15 % CA).

Type D (abonnement) : grade N2 minimum pour P9, supervision N3 trimestrielle.

  

Conditions d'ouverture aux professions réglementées (D4 du 21/11/2026)

  

OUI pour avocats, experts-comptables, notaires et architectes sous les six conditions §5 de l'étude juridique V2.1. La part de F05 est particulièrement adaptée aux cabinets d'expertise-comptable qui gèrent des clients multiples de distribution ou de pharmacie — F05 complète leur valeur ajoutée sur le pilotage opérationnel, qui échappe au périmètre comptable réglementé.

  

DIFFÉRÉ pour santé (pharmacie d'officine incluse, en attente), fiscal — NO-GO temporaire maintenu.

  

Cas spécifiques :

  

– Un Licencié avocat vend F05 ; la part d'actes juridiques (contrat de transport, contrat de consignation, contrat d'assurance) reste dans son périmètre, facturée séparément, non via MEDEGNAN.

  

– Un Licencié expert-comptable vend F05 ; la part comptable (valorisation des stocks au bilan, provision, dépréciation) reste dans son périmètre d'expert-comptable, hors MEDEGNAN.

  

– Un Licencié non réglementé vend F05 sans contrainte particulière mais doit renvoyer à un pro réglementé pour tout acte qui le réclame — le Portail détecte et propose automatiquement.

  

Règle impérative transversale

  

Rappel permanent : avant tout acte qui engage la responsabilité du cabinet vis-à-vis d'un tiers — reconnaissance d'erreur, attribution de la cause d'un incident, dérogation, annulation ou neutralisation d'un document signé, prise d'engagement au nom du cabinet — le consultant (y compris Claude en appui) a l'obligation d'informer le fondateur et d'obtenir sa décision avant l'envoi. Cette règle n'est pas levée par une instruction générale de type "réponds-lui" ou "envoie". Elle se lève explicitement et séparément. La règle vaut particulièrement en F05 où les capitaux à risque chiffrés peuvent déclencher des demandes de reconnaissance de pertes par des dirigeants qui ne les voyaient pas — aucune reconnaissance d'erreur imputable au cabinet n'est consentie sans accord express préalable du fondateur.

  

Verrou de sécurité des personnes (rang 1, absolu — hérité du module métier v2.2)

  

Rappel critique : aucune recommandation de ce dossier ne peut exposer un travailleur, un client ou un tiers à un risque d'atteinte à sa santé ou à sa sécurité. Ce rang prime sur tout, y compris sur la survie de l'entreprise. F05 est particulièrement sensible parce qu'elle optimise des entrepôts, des circuits de livraison et des opérations de manutention. Un rayonnage mal dimensionné, une allée mal ventilée, un circuit de livraison dangereux sont des risques de sécurité. Signalement actif obligatoire : si l'analyse révèle un risque de sécurité existant, même hors du périmètre de la mission, le consultant le signale par écrit au client en priorité absolue. Un cabinet qui voit un danger et ne le signale pas engage sa responsabilité professionnelle.

  
  

## Annexe A — Ce qui Reste à Préciser avec le Fondateur

  

Les éléments suivants, inscrits dans le présent dossier comme "hypothèse à calibrer", nécessitent une décision du fondateur avant application opérationnelle.

  

A1. Grille tarifaire complète pour les prestations P1 à P10. Les niveaux Essentiel / Complet / Premium proposés sont des points de départ, à calibrer contre des cas réels en PHASE 2. Aucune ligne F05 n'est inscrite en offre\_catalogue à la date du présent dossier — chantier d'inscription à ouvrir sous préfixe F5- en PHASE 2.

  

A2. Badges F05 à créer en PHASE 2 — "STOCK FONDANT" (habilitation P4 et contre-lecture chiffrages \> 50 M FCFA), "Douane OHADA" (habilitation P10 régimes suspensifs), "Froid et chaîne sensible" (habilitation missions à température contrôlée). Chaque badge requiert un référentiel d'habilitation (pièces à produire, test à passer, nombre de dossiers supervisés).

  

A3. Protocole MC-PROTO-F05-FLUX-V1 (cartographie des flux et dimensionnement) à rédiger en PHASE 2. Structure proposée dans l'Item 8 mais non adoptée.

  

A4. Protocole MC-PROTO-F05-F06-V1.0 — basculement du flag principal = true pour la fonction F05 en PHASE 2. Actuellement principal = false parce que le protocole est partagé avec F06 ; en pratique, pour F05, il fait foi.

  

A5. Natures de livrable à créer en base : carte\_stock\_fondant, politique\_stock, note\_logistique, cahier\_charges\_entrepot, procedure\_dernier\_km. Chantier d'inscription à ouvrir dans public.nature\_livrable.

  

A6. Instrument D4 Décision-Scan logistique. Le moteur dédié est à construire ; il n'existe pas aujourd'hui dans le corpus des moteurs Edge. Portée à préciser avec l'informatique (Adama Ben Bah).

  

A7. Module CORE F05 à instancier chez le client. Branche à construire, distincte du sous-module STOCK FONDANT qui lui est déjà disponible. Dépendance aux connecteurs F09.

  

A8. Articulation CORE open-source de MC-ARCHI-PLAT-V2.3 : à confirmer, le référentiel F05 et la grille des fuites F05-1 à F05-8 vont sur github.com/medegnan/core, le module CORE F05 exécutable et STOCK FONDANT restent privés. Décision à ratifier à la session de publication initiale (PHASE 3, semaines 51-52).

  

A9. Packs commerciaux FP5A, FP5B, FP5C — niveaux combinés à valider, remises de 10 à 15 % à arbitrer.

  

A10. Doctrine prix segmentée pour P4 STOCK FONDANT — hypothèse actuelle non segmentée par taille ; décision à prendre entre segmentation par taille (cohérence avec P2) et prix unique (cohérence avec l'Audit Flash à 250 000 FCFA).

  
  

## Annexe B — Glossaire Court

  

ABC-XYZ : double classification du portefeuille de références — A/B/C par valeur, X/Y/Z par régularité des sorties. Permet de piloter différemment les références en fonction de leur poids économique et de leur prévisibilité.

  

Audit Flash : produit d'entrée MEDEGNAN à 250 000 FCFA, 48-72 h, audit court sur les 12 fonctions CORE. Préalable obligatoire à toute mission F05 structurante.

  

Capital à risque : montant en FCFA que l'entreprise perdra si rien n'est décidé sur un stock exposé à péremption, obsolescence ou dormance. Chiffre central du module STOCK FONDANT, exprimé en FCFA et en part du chiffre d'affaires.

  

CORE-DX v2.1 : protocole de chiffrage MEDEGNAN qui pose la règle "aucun montant sans facture". Hérité par STOCK FONDANT.

  

Couverture : nombre de jours de vente actuels couverts par le stock existant. Mesure de vitesse plus que de valeur.

  

Dernier kilomètre : segment final de la livraison, entre le point d'expédition et le client. En Afrique francophone, souvent assuré par des livreurs indépendants (motos-taxis, zemidjans, coursiers).

  

Entrepôt : lieu physique de stockage. En F05, caractérisé par son zonage (réception, stockage courant, stockage dormant, préparation, expédition, zone de litige), ses conditions physiques et son contrôle d'accès.

  

FIFO / FEFO / LIFO : règles d'écoulement. FIFO (First In First Out) — on écoule d'abord les plus anciens. FEFO (First Expired First Out) — on écoule d'abord ceux dont l'échéance est la plus proche, règle obligatoire pour produits à date. LIFO (Last In First Out) — on écoule d'abord les plus récents, rare, utilisé sur quelques cas spécifiques.

  

Fuite : écart entre une valeur ou un flux attendu et la valeur ou le flux constaté, chiffré en FCFA, détecté par le moteur, validé par revue humaine. Ne se saisit pas par un consultant (règle 26/09/2026).

  

Gesell (Silvio) : économiste et marchand allemand (1862-1930), auteur de la théorie de la monnaie fondante — une monnaie qui perd de la valeur avec le temps force sa circulation. Inspiration explicite du module STOCK FONDANT.

  

Goldratt (Eliyahu M.) : auteur de "The Goal" (1984), fondateur de la Théorie des Contraintes. Référence méthodologique du bloc Production de MC-PROTO-F05-F06-V1.0.

  

Grade (N0 à N7) : échelle de maturité professionnelle du consultant, orthogonale au statut (S1-S4). N0 trois premiers mois, N1 à N3 progression standard, N5 et au-delà expertise confirmée.

  

Inventaire : relevé physique des références détenues à une date donnée. En F05, un inventaire n'a de valeur que daté et signé par au minimum deux personnes (responsable logistique, consultant) et validé par le dirigeant.

  

MC-COREDX-V2.1-2026 : protocole de chiffrage dont hérite STOCK FONDANT. Pose la règle "pas de montant sans facture".

  

MC-MODULE-METIER-V2.2 : module de cadrage préalable obligatoire à MC-PROTO-F05-F06-V1.0. Détermine la logique économique, les modulateurs sectoriels, le contexte d'exercice, la qualité de lecture et les arbitrages.

  

MC-PROTO-F05-F06-V1.0 : protocole exécutable Production/Logistique/Qualité. Référence en base, nature fonction. Bloc Logistique = protocole principal F05.

  

MC-STOCK-FONDANT-V1 : protocole exécutable propriétaire du module STOCK FONDANT. Référence en base. Diffusion : consultation au Espace Consultant uniquement.

  

MEDEGNAN VERIFIED : sceau public de vérification d'un livrable ou d'un consultant MEDEGNAN.

  

Module métier v2.2 : voir MC-MODULE-METIER-V2.2.

  

la plateforme SaaS MEDEGNAN : MEDEGNAN Professional Operating System, SaaS commercial ouvert aux cabinets externes.

  

NON APPLICABLE : résultat écrit au livrable lorsqu'un module ne se déclenche pas (typiquement STOCK FONDANT en absence des quatre signaux d'activation). NON APPLICABLE est un résultat, pas un silence.

  

OHADA : Organisation pour l'Harmonisation en Afrique du Droit des Affaires. Cadre juridique commun à 17 États, dont les 8 de l'UEMOA et les 6 de la CEMAC.

  

Point de commande : seuil de stock qui déclenche une commande fournisseur. Paramètre clé d'une politique de stock.

  

Portail : plateforme technique MEDEGNAN hébergée sur le système de persistence, utilisée par les trois façades Client, Consultant et Académie.

  

Prestation (P1 à P10) : offre commercialisable sous F05. Codée en base dans offre\_catalogue (chantier d'inscription PHASE 2, préfixe F5-).

  

Rotation : nombre de fois où la valeur moyenne du stock a été renouvelée sur une période (typiquement l'année). Mesure de vitesse plus que de valeur.

  

STOCK FONDANT : module propriétaire MEDEGNAN de décote progressive de la valeur de pilotage des stocks à risque. Référence MC-STOCK-FONDANT-V1. Inspiration : monnaie fondante de Gesell.

  

Stock de sécurité : quantité qui absorbe les variations d'approvisionnement et de demande sans provoquer de rupture.

  

SX : statut d'abonné la plateforme SaaS MEDEGNAN externe, hors de l'échelle S1-S4.

  

Théorie des Contraintes : méthode d'Eliyahu Goldratt — la performance d'un système est gouvernée par sa contrainte ; cinq étapes focalisantes.

  

Transport primaire / secondaire : primaire = fournisseur vers entrepôt ; secondaire = entrepôt vers client.

  

Trois factures : modèle contractuel V2.3 qui sépare la facturation cabinet (méthode), la facturation du professionnel réglementé (acte) et le cas échéant une troisième facturation pour coordination.

  

UEMOA / CEMAC : Union Économique et Monétaire Ouest-Africaine (8 États) / Communauté Économique et Monétaire de l'Afrique Centrale (6 États). Zones de parité FCFA fixe à 655,957 par euro.

  

Valeur comptable officielle : valeur du stock au bilan, fixée par la loi comptable et l'expert-comptable, au coût d'achat ou au coût de revient. Le module STOCK FONDANT n'y touche jamais.

  

Valeur de pilotage : valeur du stock calculée par le module STOCK FONDANT par décote progressive. Sert la décision du dirigeant : commander, écouler, retourner, arrêter. Ne s'écrit ni dans les comptes, ni dans une déclaration fiscale, ni dans un document remis à un tiers financier.

  

Zemidjan : moto-taxi, en particulier au Bénin et au Togo. Acteur fréquent du dernier kilomètre africain.

  
  

FIN DU DOCUMENT MC-CORE-F05-UNITE-PROFESSIONNELLE-V1

  

Document inscrit à la carte du patrimoine via public.inscrire\_document\_moi avec impersonation du compte cabinet (auth\_uid 4fd4f60e-af7c-4f6d-9c01-b6177ad2269b).

Dérive explicite de la doctrine d'architecture de la plateforme MEDEGNAN.

Tient lieu de seed et de dossier d'unité en l'absence d'un seed MC-FONCTION-F05 préexistant.

Reprend intégralement MC-STOCK-FONDANT-V1 et le bloc Logistique de MC-PROTO-F05-F06-V1.0, qui restent en régime propre.

  

Fait foi dès adoption. Toute évolution ultérieure se fait en V2 par un dossier plus profond qui absorbe la V1.


---

**Édité par MEDEGNAN CONSULTING, Cotonou (Bénin).** Licence Apache 2.0. Dernière mise à jour : 22 novembre 2026.
