# DESIGN — Relâche

## Brand overview
Relâche vend une culotte gainante taille haute (S au 5XL) aux femmes françaises de 28 à 60 ans. Promesse : arrêter de rentrer son ventre. Ressenti visé : soulagement, douceur, franchise. Jamais de honte, jamais de promesse minceur.

## Design thesis
Une page qui respire comme la cliente quand elle enlève son jean : beaucoup d'air, une seule couleur vive, des phrases franches en grand.

## Colors
| Nom | Valeur | Réglage | Rôle |
| --- | --- | --- | --- |
| Blanc | #FFFFFF | background | Fond principal |
| Nude | #FBF5F1 | fond de section, footer_background | Sections alternées, pied de page |
| Nude rosé | #F6E9E4 | emplacements média | Fonds d'images |
| Encre | #1C1917 | text_color, header_text_color | Texte |
| Rouge Relâche | #B3261E | primary_button_background, accent des sections RL, barre d'annonce | Seule couleur vive : accent, pictos, boutons |

## Typography
- Titres : Montserrat 800 (`heading_font`), capitales, interlignage 1.04 à 1.15, `text-wrap: balance`. Repli : sans-serif.
- Texte : police de texte du thème (`text_font`), 15 à 18 px, interlignage 1.55.
- Sous-titres de cartes : police de texte, 18 px, graisse 700, bas de casse.

## Spacing and composition
- Sections : padding vertical `clamp(56px, 8vw, 96px)`, horizontal `clamp(20px, 5vw, 64px)`.
- Largeur de contenu max 1180 px ; texte long max 820 px.
- Rayons : cartes 16 px, médias 14 px, boutons en pilule.
- Pas d'ombres ; la séparation se fait par alternance blanc / nude.

## Components
- Sections `rl-*` : hero, presse, bénéfices, UGC, avis, mode d'emploi, FAQ, contact. Chacune expose ses textes, images et couleurs dans l'éditeur.
- Bouton principal : fond rouge Relâche, texte blanc, pilule.
- Barre d'annonce : fond rouge, texte blanc.
- Pied de page : fond nude, texte encre.

## Dos and Don'ts
- Faire : une seule couleur vive ; vendre le confort et l'effet visuel ; avis et logos presse réels uniquement.
- Ne pas faire : promesse d'amincissement, faux compteurs de stock, faux avis, prix barrés sans historique, blocs noirs.

## Motion philosophy
Sobre. Pas d'animation décorative ; lecture auto silencieuse des vidéos UGC uniquement.
