# Maquettes — pâtisseries et traiteurs

Maquettes de sites vitrines à présenter aux prospects : https://jeancdf.github.io/maquettes-patisserie/

- `index.html` : les modèles, avec un aperçu et un lien vers chaque page.
- `comparer.html` : bascule rapide entre les formules (boutons, touches 1 à 5, flèches ←/→, ancres `#essentiel`, `#complet`, `#celeste`…).

| Page | Modèle |
| --- | --- |
| `essentiel.html` | Maison Lemoine — Formule Essentiel |
| `complet/` (5 pages : `index`, `prestations`, `realisations`, `a-propos`, `contact`, plus `mentions-legales`) | Maison Lemoine — Formule Complet |
| `celeste.html` | Atelier Céleste — wedding cakes, Bordeaux |
| `saison.html` | Saison — traiteur, Lyon |
| `nour.html` | Les Douceurs de Nour — pâtisseries orientales, Marseille |

Tous les boutons, menus et formulaires fonctionnent ; les formulaires affichent un récapitulatif mais n’envoient rien.

- `kit/std.css`, `kit/std.js` : socle des formules Essentiel et Complet (réservation ou demande rapide qui pré-remplit le formulaire de contact, galerie filtrable avec visionneuse, FAQ, menu mobile).
- `kit/bespoke.js` : rend fonctionnelles les maquettes sur mesure (champs saisissables, demandes avec confirmation, menu mobile, options).
- `complet.html` redirige vers `complet/index.html`.

Essentiel (690 € HT) et Complet (1 190 € HT) utilisent le même établissement fictif pour comparer les gammes. Sur mesure : 1 990 à 2 990 € HT.

Établissements fictifs : tarifs et cartes indicatifs, coordonnées entre crochets à personnaliser.
Photographies : [Unsplash](https://unsplash.com) (licence Unsplash), utilisées à titre d’illustration.
