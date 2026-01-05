# Squeaking - SPIP Syntax Highlighting

Extension VSCode pour la coloration syntaxique des templates SPIP.

## Fonctionnalités

Cette extension fournit la coloration syntaxique complète pour le langage de templates SPIP :

### ✨ Syntaxes supportées

- **Commentaires** : `[(#REM) votre commentaire ]`
- **Balises SPIP** : `#TITRE`, `#DATE`, `#TEXTE`, `#ENV{variable}`, etc.
- **Boucles** :
  ```spip
  <B_articles>
  <BOUCLE_articles(ARTICLES){id_rubrique}>
      #TITRE
  </BOUCLE_articles>
  </B_articles>
  <//B_articles>
  ```
- **Critères** : `{id_article}`, `{par date}`, `{inverse}`, etc.
- **Filtres** : `|majuscules`, `|date_relative`, `|trim`, etc.
- **Conditions** : `[(#ENV{test}|oui) Texte ]`
- **Inclusions** :
  - Syntaxe XML : `<INCLURE{fond=nav, param}>`
  - Syntaxe balise : `[(#INCLURE{fond=nav}|filtre)]`

## Installation

### Depuis un fichier .vsix

1. Téléchargez le fichier `.vsix`
2. Dans VSCode : `Extensions` → `...` (menu) → `Install from VSIX...`
3. Sélectionnez le fichier `squeaking-0.0.1.vsix`
4. Rechargez VSCode

### Depuis le Marketplace (à venir)

Recherchez "Squeaking" dans l'onglet Extensions de VSCode

## Utilisation

L'extension s'active automatiquement pour :
- Les fichiers `.html` contenant du code SPIP
- Les fichiers `.spip`

## À propos de SPIP

[SPIP](https://www.spip.net) est un système de publication pour l'Internet qui s'attache particulièrement au fonctionnement collectif, au multilinguisme et à la facilité d'emploi.

## Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
- Signaler des bugs
- Proposer des améliorations
- Soumettre des pull requests

## Licence

MIT

## Auteur

Joachim Séné
jsene.net

## Changelog

Voir [CHANGELOG.md](CHANGELOG.md)