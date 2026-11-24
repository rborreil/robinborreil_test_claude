# Architecture éditoriale du site

Version 1, du 24/11/2026. Ce document sert de cahier des charges pour la rédaction (phase 3). Les titles visent environ 60 caractères maximum et les meta descriptions environ 155. Aucune promesse de position dans Google.

## Règles globales

- **Menu** : Solutions · Formations · Réalisations · Ressources · À propos, plus un bouton « Faire le diagnostic ». Contact se trouve dans le pied de page et dans le bouton secondaire de l'en-tête sur ordinateur.
- **Un seul appel à l'action principal par page** : soit « Faire le diagnostic » (questionnaire, puis rendez-vous de 20 min), soit « Prendre rendez-vous ». Le contact libre reste toujours accessible.
- **Pied de page** : coordonnées, zone (« Basé au Pays basque · Intervention dans toute la France »), liens vers les pages « Pour qui », pages légales, mention TVA.
- **Données structurées** : `ProfessionalService` sur l'accueil et la page Contact. `areaServed` : Pays basque et France. Adresse affichée seulement si tu le décides. `Course` pour chaque formation. `FAQPage` uniquement si la FAQ est visible sur la page. Aucun avis ni note en données structurées.
- **Maillage** : chaque page Solution renvoie à 1 ou 2 pages « Pour qui », à une étude de cas et à une ressource. Chaque page « Pour qui » renvoie vers ses solutions et vers le diagnostic.
- **Preuves** : on n'affiche que des réalisations et des témoignages autorisés. Les exemples fictifs portent la mention « Exemple illustratif ».

## Pages

### Accueil — `/`

- **Title** : Robin Borreil · Partenaire numérique des petites entreprises
- **Meta** : Site, visibilité, IA et outils numériques pour les petites entreprises. Basé au Pays basque, j'interviens dans toute la France. Diagnostic à 290 €.
- **H1** : Le web, l'IA et les bons outils, au service de votre activité.
- **Sections** : (1) proposition de valeur et appel à l'action ; (2) « Vous vous reconnaissez ? », 6 situations dans les mots du client ; (3) trois domaines : Comprendre, Construire, Accompagner ; (4) exemples concrets de solutions (avant / après) ; (5) méthode en 4 étapes ; (6) aperçu des offres et prix d'entrée ; (7) réalisations réelles (3) ; (8) formations et ateliers ; (9) présentation personnelle, courte, avec photo ; (10) FAQ (6 questions) ; (11) appel à l'action final.
- **Liens** : diagnostic, les 3 pages Solutions, les 3 pages « Pour qui », Tarifs, Réalisations, Formations, À propos.

### Diagnostic numérique — `/diagnostic-numerique/`

- **Title** : Diagnostic numérique pour TPE · 290 € · Robin Borreil
- **Meta** : Un état des lieux de votre site, de votre visibilité et de vos outils, avec un plan d'action priorisé. Questionnaire gratuit en 5 minutes.
- **H1** : Savoir quoi faire, avant de dépenser.
- **Sections** : à quoi sert le diagnostic ; ce que vous recevez (exemple de plan d'action, anonymisé ou fictif et signalé comme tel) ; déroulé et durée ; prix et déduction sous 60 jours ; ce que le diagnostic n'est pas ; questionnaire d'orientation ; FAQ.
- **Appel à l'action** : remplir le questionnaire.

### Solutions — `/solutions/`

- **Title** : Solutions numériques pour petites entreprises · Robin Borreil
- **H1** : Comprendre, construire, accompagner.
- **Rôle** : page de tri. Trois blocs, chacun avec ses exemples et son lien. Un tableau « Votre situation → par où commencer ».

### Création web et visibilité — `/solutions/site-internet-visibilite/`

- **Title** : Création de site internet et visibilité locale · Pays basque
- **Meta** : Sites vitrines rapides, fiche Google optimisée, avis clients : être trouvé par les bons clients, près de chez vous. Prix à partir de 1 290 € HT.
- **H1** : Être trouvé, et donner envie de vous appeler.
- **Sections** : problèmes ; ce que je fais (site, refonte, fiche Google, avis, bilingue) ; ce qui est inclus et ce qui ne l'est pas ; méthode ; prix repères ; réalisations ; FAQ (délais, propriété du site, modifications).

### IA et automatisation — `/solutions/ia-automatisation/`

- **Title** : IA et automatisation pour TPE et indépendants · Robin Borreil
- **Meta** : Assistants IA configurés pour votre métier, automatisations simples et fiables, usage sécurisé de vos données. Concret, sans jargon.
- **H1** : Moins de tâches répétitives, sans perdre la main.
- **Sections** : tâches typiques concernées ; trois exemples illustratifs (devis, réponses aux avis, accueil d'un nouveau client) ; ce que l'IA fait mal ; confidentialité et charte ; prix repères ; FAQ (« faut-il un abonnement ? », « mes données ? »).
- **Ton** : prudence explicite. Pas de promesse de gain chiffré.

### Conseil et accompagnement — `/solutions/accompagnement/`

- **Title** : Maintenance et accompagnement numérique · Robin Borreil
- **H1** : Un interlocuteur qui connaît vos outils, dans la durée.
- **Sections** : les 4 formules (tableau) ; comment le temps est compté ; exclusions ; réversibilité ; FAQ.

### Tarifs — `/tarifs/`

- **Title** : Tarifs · Diagnostic, sites, IA, abonnements · Robin Borreil
- **H1** : Des prix clairs, des limites écrites.
- **Sections** : diagnostic ; prix repères des projets ; abonnements ; formations ; déplacements ; mention TVA ; « Pourquoi des prix à partir de ».

### Pour les artisans — `/pour/artisans/`

- **Title** : Site internet et outils numériques pour artisans · Pays basque
- **H1** : Moins de soirées sur les devis, plus de demandes qualifiées.
- **Sections** : situations ; solutions (fiche Google, demande qualifiée, relances, avis) ; étude de cas Couverture Puel (si autorisée) ; diagnostic.

### Pour la restauration et l'hébergement — `/pour/restaurants-hebergements/`

- **Title** : Restaurants, hébergements, conciergeries : numérique simplifié
- **H1** : Des infos justes partout, et moins de messages répétitifs.
- **Sections** : restaurateurs (fiche, carte, bilingue, avis) ; conciergeries (messages voyageurs, reporting propriétaires, acquisition) ; saisonnalité ; étude de cas ; diagnostic.

### Pour les indépendants et cabinets — `/pour/independants/`

- **Title** : Indépendants, cabinets, consultants : gagner du temps avec l'IA
- **H1** : Votre métier, pas l'administratif.
- **Sections** : libéraux (conformité, confidentialité) ; coachs et consultants (offre, prospects, contenus) ; organismes de formation (parcours administratif) ; diagnostic.

### Formations — `/formations/` et `/formations/[slug]/`

- **Title** : Formations et ateliers IA, visibilité, outils · Robin Borreil
- **H1** : Des ateliers pratiques, utiles même sans suite commerciale.
- **Fiche formation** : public, objectifs, prérequis, durée, programme, modalités, tarif, fiche PDF. Aucune mention de certification ni de financement tant que ce n'est pas vérifié.

### Réalisations — `/realisations/` et `/realisations/[slug]/`

- **H1** : Des projets réels, des clients réels.
- **Étude de cas** : contexte, problème, ce qui a été fait, résultat mesuré ou « à mesurer », citation autorisée.

### Ressources — `/ressources/`

- **Lancement** : 3 ou 4 guides pratiques, par exemple : « Compléter sa fiche Google en 30 minutes », « 10 usages de l'IA sans données sensibles », « Checklist avant de refaire son site ».

### À propos — `/a-propos/`

- **Title** : Robin Borreil · Parcours, méthode et engagements
- **H1** : Un parcours business, un métier technique.
- **Sections** : parcours (ESSEC, gestion de projet, reconversion, enseignement en économie-gestion) ; méthode ; engagements prouvés (prix publics, réversibilité, sobriété des outils) ; zone et déplacements.

### Contact — `/contact/`

- **Title** : Contact · Robin Borreil · Pays basque et France entière
- **Sections** : formulaire ; prise de rendez-vous de 20 min ; téléphone et email ; zone et déplacements ; délai de réponse.

### Pages légales

`/mentions-legales/`, `/confidentialite/`, `/cgv/` : à rédiger après réception de la forme juridique et du SIRET.
