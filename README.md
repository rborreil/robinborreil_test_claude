# Écosystème commercial — Robin Borreil

Partenaire numérique indépendant des petites entreprises. Basé au Pays basque, intervention dans toute la France.

Ce dépôt réunit tout ce qui sert à vendre, livrer et faire connaître l'activité : stratégie, identité, site, supports commerciaux, formations, bibliothèque de solutions et outils d'exploitation.

## Par où commencer

| Besoin | Où regarder |
| --- | --- |
| Comprendre le positionnement et les choix validés | `00-strategy/positionnement.md` (et `revue-critique.md` pour le pourquoi) |
| Trouver des clients cette semaine | `00-strategy/acquisition.md` |
| Savoir à qui je vends quoi, secteur par secteur | `00-strategy/secteurs.md` |
| Chiffrer une prestation ponctuelle | `03-commercial/offers/catalogue-interne.md` |
| Expliquer ou contractualiser un abonnement | `03-commercial/offers/abonnements.md` |
| Rédiger ou modifier une page du site | `00-strategy/architecture-editoriale.md`, puis `02-website/` |
| Voir l'avancement et les décisions | `07-roadmap/suivi-projet.md` |

## Organisation

```
00-strategy/        Positionnement, secteurs, architecture éditoriale
01-branding/        Identité visuelle et design system
02-website/         Code du site (Astro, sortie statique)
03-commercial/      Plaquettes, offres, propositions, prospection, partenariats
04-training/        Catalogue, ateliers, guides participants
05-solutions/       Fiches solutions réutilisables (web, IA, automatisation, visibilité)
06-operations/      Audit, onboarding, maintenance, reporting
07-roadmap/         Suivi de projet, décisions, feuille de route
08-documentation/   Déploiement, conventions, guides techniques
exports/            Versions finales destinées aux clients (PDF, DOCX, HTML)
```

## Conventions

- **Markdown** pour tout ce qui est interne. Les documents destinés aux clients sont toujours exportés en PDF, DOCX ou HTML dans `exports/`.
- **Prix** : affichés HT, avec la mention « TVA non applicable, art. 293 B du CGI » tant que l'activité est en franchise en base. Tous les prix de ce dépôt sont des hypothèses de travail tant qu'ils ne sont pas marqués comme validés.
- **Honnêteté** : aucun faux témoignage, chiffre, client, certification ou résultat. Toute démonstration fictive est signalée comme telle.
- **Secrets** : aucune clé ni aucun identifiant dans le dépôt. Les variables d'environnement sont documentées dans `08-documentation/`.

## État

Phase 1 (stratégie) livrée en version 1. Prochaine étape : phase 2 (identité visuelle). Voir `07-roadmap/suivi-projet.md`.
