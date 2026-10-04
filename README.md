# FocalizeIA — site public

Site statique (GitHub Pages) de FocalizeIA, agent IA de création de sites vitrines.

## Déploiement
- Branche `main`, dossier racine ; GitHub Pages activé dans Settings > Pages.
- Domaine : `focalizeia.fr` (fichier CNAME). DNS chez GoDaddy :
  - 4 enregistrements A pour `@` : 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
  - 4 enregistrements AAAA pour `@` : 2606:50c0:8000::153, 2606:50c0:8001::153, 2606:50c0:8002::153, 2606:50c0:8003::153
  - CNAME `www` -> `<compte>.github.io`
  - Puis cocher « Enforce HTTPS » dans Settings > Pages une fois le certificat émis.

## Avant mise en ligne
Les champs entre crochets ([ÉDITEUR], [SIRET], [MENTION TVA], etc.) dans `mentions-legales.html` et `cgv.html` doivent être complétés : ne pas publier le dépôt tant qu'il en reste.
