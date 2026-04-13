# Skill: Projet HTML/CSS simple

## Objectif
Creer un petit projet web propre avec HTML5 et CSS basique, sans JavaScript.

## Etapes a suivre

1. Definir le besoin
- ectraire le besoin d'apres le chat et les consignes du TP.

2. Preparer la structure des dossiers
- Utiliser une arborescence claire:
  - `index.html`
  - `css/style.css`
  - `assets/images/`
 

3. Ecrire la base HTML5
- Ajouter `<!doctype html>`, `lang`, `meta charset`, `meta viewport`, `title`.
- Lier le CSS externe avec `<link rel="stylesheet" href="css/style.css">`.

4. Construire une structure semantique
- Utiliser: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`.
- Organiser les titres correctement (`h1` puis `h2`, `h3`...).

5. Ajouter le contenu essentiel
- Paragraphes, listes (`ul`, `ol`), liens (`href`, `target`, `rel`, `download`).
- Images avec `src` et `alt`.
- Tableau si necessaire (`thead`, `tbody`, `tfoot`).
- Formulaire simple (`label`, `input`, `select`, `textarea`) avec validation native (`required`, `pattern`, `min`, `max`).

6. Appliquer un CSS simple et lisible
- Couleurs unies, marges, paddings, bordures, largeur max.
- Typographie classique (ex: Arial, sans-serif).
- Mise en page basique (block, inline-block, flex simple si besoin).

7. Ajouter l'accessibilite de base
- `alt` sur toutes les images.
- Labels relies aux champs de formulaire (`for` / `id`).
- Skip link pour clavier.
- Attributs ARIA seulement si necessaire (`aria-label`, `aria-labelledby`, `aria-describedby`).

8. Verifier et corriger
- Verifier les liens et les ancres.
- Corriger l'indentation et nettoyer le code.
- Valider le HTML sur W3C Validator.

## Ce qu'il faut faire

- Garder HTML et CSS separes.
- Respecter la semantique HTML5.
- Utiliser des noms de classes simples et coherents.
- Ecrire du code propre, bien indente.
- Tester sur mobile (au moins largeur reduite).
- Utiliser `loading="lazy"` pour les images non critiques.

## Ce qu'il ne faut pas faire

- Ne pas utiliser JavaScript si le TP demande HTML/CSS seulement.
- Ne pas utiliser des effets compliques (gradients, animations avancees, frameworks lourds) si le prof demande du basique.
- Ne pas mettre tout le style en inline dans le HTML.
- Ne pas sauter la hierarchie des titres (ex: `h1` vers `h4` direct sans raison).
- Ne pas oublier `alt` sur les images.
- Ne pas laisser des liens vides (`href=""`) dans la version finale.
- Ne pas copier un template complexe qui depasse le niveau demande.

## Mini checklist finale

- HTML5 valide
- CSS separe et simple
- Structure semantique complete
- Navigation interne fonctionnelle
- Images avec `alt`
- Formulaire valide (required/pattern/min/max)
- Liens externes avec `target="_blank"` + `rel="noopener noreferrer"`
- Code propre et lisible
