# Portfolio — Owaïs Dhoiffir

Site personnel publié sur GitHub Pages : https://owais-dhoiffir-iut.github.io/
Dépôt : github.com/owais-dhoiffir-iut/owais-dhoiffir-iut.github.io (branche `main`, déploiement automatique à chaque push).

## Objectif
Portfolio de candidature pour une **alternance sept. 2026 → août 2027** (BUT R&T parcours Cybersécurité, IUT de La Réunion). Public : recruteurs et tuteurs en systèmes/réseaux, support et cybersécurité.

## Stack
- Un seul fichier `index.html` : HTML + CSS + JS inline, **aucun framework, aucun build, aucun traceur**.
- Polices Google Fonts : Plus Jakarta Sans (texte) et JetBrains Mono (code).
- Style **clair et animé** : fond blanc, dégradé bleu → violet → rose (`--grad`), taches floues qui dérivent, bulles irisées qui montent, cartes en verre dépoli (`.glass`) avec reflet au survol (`.shine`), carte de code qui s'écrit et s'incline à la souris.
- Expériences : frise verticale dont la ligne se remplit au défilement ; chaque étape arrive par la gauche ou la droite (`.xp-item.in`).
- Toutes les couleurs sont des variables CSS dans `:root`. Ne jamais mettre de couleur en dur dans un nouveau composant.

## Structure de la page
Hero (nom, rôle animé, carte de code + pastilles flottantes) → chiffres clés animés → 01 Profil → 02 Compétences → 03 Expériences (timeline) → 04 Projets (cartes, le projet R502 en vedette) → 05 Formation → 06 Contact → footer.

## Conventions
- Contenu en **français**, ton sobre et professionnel, phrases courtes.
- Accessibilité : contraste AA, `:focus-visible` visible, cibles tactiles ≥ 44 px, `prefers-reduced-motion` respecté, aucun défilement horizontal à 375 px.
- Ne rien affirmer qu'Owaïs n'a pas réellement fait ; pas de notes/moyennes ni d'âge sur le site.
- Tester en 375 px, 768 px et 1440 px avant de pousser ; toute animation doit être coupée sous `prefers-reduced-motion`.

## Publier une modification
Dans VS Code : Source Control → message → Commit → Sync. Le site est à jour ~1 minute après.

## Source de vérité
Le contenu suit `CV_Owais_Dhoiffir.pdf` (dans ce dossier, téléchargeable depuis le site). Si le CV change, remplacer le PDF et mettre le site à jour en conséquence.

## À compléter / vérifier
- Ajouter éventuellement une version anglaise.
- Le CV PDF contient le numéro de téléphone : il est public sur le site.
