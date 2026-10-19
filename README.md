# Solution Automobile – site commercial

Site de présentation de l'offre unique « site vitrine + gestion de parc » pour garages indépendants, négociants et professionnels du véhicule d'occasion : 50 € HT/mois, sans frais d'installation, nom de domaine à la charge du client.

Site statique (HTML, CSS, JS sans dépendance) publié sur GitHub Pages depuis la branche `main`.

| Fichier | Rôle |
| --- | --- |
| `index.html` | Page unique : hero, fonctionnement, site vitrine, dashboard, cycle de vente, référence Livradois, diffusion (en préparation), tarif, démarrage, FAQ, contact |
| `styles.css` | Thème « bleu pétrole » (`--brand: #0f6b78`) repris de la première version de Livradois Automobiles |
| `script.js` | Menu mobile, galerie, onglets, agrandissement des captures, formulaire de contact (`mailto:`) |
| `assets/img/` | Captures du site et du dashboard Livradois (démo, données fictives) |

## À compléter avant diffusion

- **Adresse de contact** : constante `CONTACT_EMAIL` en tête de `script.js`.
- **Mentions légales** de l'éditeur du site.
- Nombre d'utilisateurs, de véhicules, niveau d'assistance et sauvegardes : à reprendre des conditions contractuelles définitives (la FAQ y renvoie sans inventer de limite).
