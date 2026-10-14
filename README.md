# EDM – site vitrine

Site vitrine de SARL EDM, entreprise de plomberie, chauffage, sanitaire et rénovation à Chennevières-sur-Marne (Val-de-Marne), créée en 1997.
HTML, CSS et JS natifs : aucune étape de build, aucune dépendance.

Production : https://edm-plomberie.vercel.app

## Arborescence

```
index.html                     page unique, sprite d'icônes inline, JSON-LD Plumber
assets/css/styles.css          styles, variables de couleur, mode sombre
assets/js/main.js              menu mobile, apparition au défilement, année, formulaire mailto
assets/img/logo.svg            logo couleur (edm + goutte bleue et flamme orange)
assets/img/logo-mono-blanc.svg logo blanc (footer, en-tête en mode sombre)
assets/img/favicon.svg         goutte et flamme sur fond ardoise
robots.txt                     autorise tout, pointe vers le sitemap
sitemap.xml                    une seule URL
```

## Lancer en local

```sh
python3 -m http.server 8000
```

Puis ouvrir http://localhost:8000.

## TODO

- Assurance décennale et qualifications (RGE, QualiPAC…) : à préciser (bandeau de réassurance).
- Email : remplacer `edm2009@hotmail.fr` par une adresse professionnelle (contact, formulaire, JSON-LD).
- Secteur : faire confirmer la liste des communes.
- Mentions légales : capital social et numéro RCS.

## Versions

| Version | Date | Direction visuelle |
|---|---|---|
| v1 | 2026-10-14 | Ardoise du camion, bande orange, goutte bleue et flamme ; hero sombre aligné à gauche, métiers en tuiles 2×2 |
