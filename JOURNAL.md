# Journal

## 2026-10-03 — Création de l'archive

- Création du dépôt public `zer0pixels0px-dev`.
- README initial avec les thèmes réellement échangés depuis la prise en main.
- Mise en place de la consignation automatique des sessions futures (une entrée datée par jour actif, sans doublon).

## 2026-10-03 — Culture Planner, wiki de culture et automatisations

- Construction de « Culture Planner » (webapp de planification de culture, version MVP en français) : tableau de bord, assistant de création d'environnement en 7 étapes, éditeur 2D, cultures, équipements, données avec graphiques, moteur de diagnostic avec recommandations, assistant conversationnel, paramètres avec mode débutant/expert.
- Quatre nouveautés ajoutées le soir même à la v1 : type de substrat par environnement, équipements enregistrés modifiables ou supprimables, sélection de plusieurs types d'éclairage à la création d'un environnement (fabricant, modèle, puissance, nombre, hauteur), suivi photo avec note et date en galerie chronologique.
- Construction de « Culture Planner 2 » (version persistante avec base de données serveur) : insights en haut du tableau de bord (progression du cycle, temps avant récolte, objectifs pH/EC, alertes pédagogiques non alarmistes), wiki en parcours éducatif à 5 niveaux, achievements/badges calculés depuis les vraies mesures. Point faible connu : l'insight « progression semaine/mois » affiche des volumes de suivi plutôt qu'une vraie évolution sur 7 et 30 jours (à corriger, en attente de la décision d'Alain).
- Ajouts à Culture Planner 2 : section Nutriments (programmes CANNA, General Hydroponics, House & Garden, Advanced Nutrients avec calculateur de recette 1–1000 L, ordre de mélange, historique d'arrosage) avec NPK corrigés depuis documents fabricants — attribution encore partielle pour certains liens sources ; gestionnaire de Tâches (arrosage, défeuillage, topping, transplantation, vérification nuisibles, etc.) avec alertes de retard ; calendrier cultural avec fenêtres favorables et notifications (transplantation J+14, topping J+21, défeuillage calé sur récolte) ; duplication et déplacement d'équipements entre environnements.
- Import/export dans Culture Planner 2 : produits et tables de dosage personnalisés (export CSV par table), sauvegarde/restauration JSON complète, import de mesures par CSV ou lien Google Sheets partagé, exports diagnostics / historique des tâches / historique complet. Correctifs : parseur CSV gérant les champs entre guillemets ; collecte de la date de récolte à la création des cultures (repère « renseigner la date » sur les fiches sans échéance) ; navigation mobile en grille fixe 6×2 ; logos des 4 marques et photos de bouteilles ajoutés aux Nutriments. Reste incertain : la date de récolte perdue de la culture « Test Flo » n'est peut-être pas restaurée — à vérifier avec Alain.
- Création de l'objectif « Veille cannabis au Québec » : briefing hebdomadaire chaque lundi matin vers 8h40 sur les nouvelles du secteur, les compagnies québécoises et la réglementation.
- Lancement de l'approfondissement du wiki de culture cannabis : chapitre 15 « Récolte » complété et intégré au wiki (sources vérifiées, résumé et quiz), suivi dans progress.md (1/30), approfondissement quotidien planifié chaque matin vers 9h pour les chapitres restants.
- Fichier Figma « Culture Planner » créé pour accueillir le design de l'application ; Alain a choisi de coller lui-même le code de capture dans sa console navigateur — en attente de sa confirmation, idéalement après publication de la nouvelle version (le lien public affiche encore l'ancienne).
- Courte liste d'offres d'emploi en culture au Québec livrée (FSB Canopeï, MTLC, Sumo Cannabis ; offre Origine Nature expirée exclue), actualisable sur simple demande d'Alain.
