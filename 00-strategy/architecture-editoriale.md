# Architecture éditoriale du site

Version 2 du 25/11/2026, simplifiée après la revue critique. Ce document sert de cahier des charges pour la rédaction (phase 3). Titles d'environ 60 caractères, meta descriptions d'environ 155. Aucune promesse de position dans Google.

## Ce qui change par rapport à la version 1

- L'appel à l'action principal devient la **visite découverte gratuite**. Le diagnostic payant passe au second plan.
- Les pages Solutions sont organisées autour des **4 produits**, et non plus de catégories abstraites.
- **2 pages « Pour qui »** au lieu de 3. Les indépendants sont servis par les ateliers et la page IA.
- L'accueil passe de **12 à 8 sections**.

## Règles globales

- **Menu** : Offres · Réalisations · Ateliers · À propos, plus le bouton « Demander une visite ». Ressources et Contact sont dans le pied de page.
- **Un seul appel à l'action principal** : « Demander une visite gratuite », qui ouvre le questionnaire de 2 minutes puis la prise de rendez-vous. Le téléphone est toujours visible sur mobile.
- **Pied de page** : coordonnées, zone, pages « Pour qui », pages légales, mention TVA.
- **Données structurées** : `ProfessionalService` (accueil, contact), `Course` (ateliers), `FAQPage` seulement si la FAQ est visible. Aucun avis en données structurées.
- **Preuves** : réalisations et témoignages autorisés uniquement ; « Exemple illustratif » ou « Client pilote » quand c'est le cas.

## Arborescence

| Page | URL | Rôle |
| --- | --- | --- |
| Accueil | / | Comprendre en 10 secondes, demander une visite |
| Visite et bilan | /visite-et-bilan/ | Déroulé de la visite gratuite et du bilan à 290 € ; complément aux diagnostics CCI et CMA |
| Offres | /offres/ | Les 4 produits, les abonnements, tous les prix, les exclusions |
| Être trouvé sur Google | /offres/visibilite-google/ | Produit à 390 € |
| Site vitrine | /offres/site-internet/ | Produit à partir de 1 290 € |
| Gagner du temps | /offres/gagner-du-temps/ | Produit à 590 €, ses 3 déclinaisons, programme pilote |
| Entretien et accompagnement | /offres/abonnements/ | 49 € et 149 € par mois, sur mesure |
| Pour les artisans | /artisans/ | Devis, chantiers, Google, cas Couverture Puel |
| Pour les restaurants et hébergements | /restaurants-hebergements/ | Saison, avis, bilingue, conciergeries |
| Réalisations | /realisations/ + études de cas | Preuves réelles |
| Ateliers | /ateliers/ + une page par atelier | Pour les réseaux et les entreprises |
| Ressources | /ressources/ | 3 guides au lancement |
| À propos | /a-propos/ | Parcours, méthode, zone |
| Contact | /contact/ | Formulaire, rendez-vous, téléphone |
| Pages légales | /mentions-legales/, /confidentialite/, /cgv/ | Après réception du statut juridique et du SIRET |

## Accueil en 8 sections

1. **Accroche** : « Plus de clients, moins de temps perdu. », sous-titre, bouton « Demander une visite gratuite », téléphone, photo réelle.
2. **Vous vous reconnaissez ?** : 4 situations dans les mots du client.
3. **Les offres** : les 4 produits avec leur prix, plus une ligne sur les abonnements. Elle remplace les anciennes sections « Trois façons de travailler », « Méthode » et « Tarifs ».
4. **Comment ça se passe** : 3 étapes (visite gratuite → proposition à prix fixe → mise en place et suivi).
5. **Réalisations** : 3 projets réels.
6. **Qui je suis** : court, avec photo, parcours et zone.
7. **Questions fréquentes** : 5 questions, dont « J'ai déjà eu un diagnostic CCI ».
8. **Appel final** : visite gratuite.

Les ateliers et les exemples illustratifs ont leurs propres pages. L'accueil y renvoie par un lien, sans section dédiée.

## Pages clés : titres et messages

| Page | Title | H1 |
| --- | --- | --- |
| Accueil | Robin Borreil · Site, Google et outils pour TPE · Pays basque | Plus de clients, moins de temps perdu. |
| Visite et bilan | Visite découverte gratuite · Pays basque · Robin Borreil | 45 minutes chez vous, et un avis honnête. |
| Offres | Offres et tarifs · Site, Google, IA · Robin Borreil | Quatre offres, des prix fixes, des limites écrites. |
| Être trouvé sur Google | Optimisation fiche Google · Pays basque · 390 € | Que l'on vous trouve, et qu'on vous choisisse. |
| Site vitrine | Création de site internet · Pays basque · dès 1 290 € | Un site qui vous amène des demandes. |
| Gagner du temps | IA et automatisation simples pour TPE · Robin Borreil | Moins de devis le soir, moins de réponses en double. |
| Artisans | Site internet et fiche Google pour artisans · Pays basque | Plus de chantiers choisis, moins de paperasse. |
| Restaurants et hébergements | Restaurants et hébergements : Google, site, avis | Des infos justes partout, avant la saison. |
| Ateliers | Ateliers IA et visibilité pour pros · Robin Borreil | Des ateliers pratiques, utiles même sans suite. |
| À propos | Robin Borreil · Parcours et méthode | Un parcours business, un métier technique. |
