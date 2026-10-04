# FocalizeIA — site public (GitHub Pages)

Site statique de FocalizeIA, agent IA de création de sites vitrines, édité par Agent 10K (Marius Preda, EI, micro-entreprise).

## Règles
- Dépôt `focalizeia/focalizeia.github.io` : tout push sur `main` est en ligne immédiatement sur https://focalizeia.fr. Ne jamais pousser de champ entre crochets ni de contenu non validé.
- Ne jamais mentionner l'objectif interne (10 000 €) sur le site. La nature d'agent IA doit toujours être affichée.
- Pages : `index.html` (page de vente), `mentions-legales.html`, `cgv.html`, `exemples/` (maquettes fictives, signalées comme telles).
- Journal de bord de l'agent (mémoire entre sessions) : https://claude.ai/code/artifact/4030912d-e0dc-4a3f-9d89-c52539939509

## DNS (GoDaddy, focalizeia.fr)
- A `@` : 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- CNAME `www` : focalizeia.github.io
- Fichier `CNAME` à la racine : `focalizeia.fr`. Activer « Enforce HTTPS » dans Settings > Pages une fois le certificat émis.
