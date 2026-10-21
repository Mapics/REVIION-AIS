# Fiche de révision — soutenance FreeMotions

Page de révision personnelle pour la soutenance du titre professionnel
**Administrateur d'infrastructures sécurisées** (RNCP 37680 · TP-01352).

Projet soutenu : refonte et sécurisation du système d'information de FreeMotions,
loueur de véhicules électriques, 50 salariés sur deux sites (Paris et Lyon).
Périmètre personnel : réseau, interconnexion chiffrée, accès distant, zone exposée,
filtrage, détection d'intrusion, journalisation, supervision et audit.

## 👉 La page

**https://<ton-pseudo>.github.io/<nom-du-depot>/**

> Remplace cette ligne par l'URL réelle une fois GitHub Pages activé
> (*Settings → Pages → Source : `main`, dossier `/root`*).

Un seul fichier, `index.html`. Aucune dépendance, aucun script externe, 116 Ko.
Elle fonctionne hors ligne : télécharge le fichier et ouvre-le, ça marche pareil.

## Ce qu'il y a dedans

| Section | Contenu |
|---|---|
| **00 · Plan sur deux jours** | 12 étapes cochables, réparties matin et après-midi. L'ordre est voulu : les chiffres d'abord, l'oral en dernier. |
| **01 · Ce qui doit sortir sans réfléchir** | 16 chiffres clés (adressages, ports, RPO/RTO, montants du devis, scores d'audit), la phrase d'ouverture mot pour mot, les trois attentes du client. |
| **02 · Le fil de la soutenance** | Partie par partie : ce que je raconte et la phrase qui doit rester. Les diapos sont citées par leur titre, pas par leur numéro. |
| **03 · Sigles et concepts** | **96 entrées** : tous les sigles présents dans le dossier, le diaporama et le devis, chacun avec son développé, sa définition et son usage réel dans le projet. Plus 17 produits et outils, 12 termes, et **26 encadrés « à comprendre »** qui répondent aux *pourquoi* et aux *comment*. |
| **04 · Questions du jury** | **34 questions** sur le projet, réponse repliée, étiquetées `BASE`, `PIÈGE` ou `CHIFFRES`. |
| **05 · Questions générales** | **19 questions** hors projet, remontées par des camarades passés avant : OSI, LACP, VLAN et routage inter-VLAN, niveau 2 contre niveau 3, proxy et reverse proxy, filtrage web, 3-2-1, SLA, ITIL, RGPD et CNIL, PRA et PCA, agile contre cycle en V. |
| **06 · QCM** | 20 questions à correction immédiate, avec l'explication et un score. |
| **07 · Pièges et réflexes** | Les règles de comportement à l'oral, dont quoi dire quand on ne sait pas, et le tableau des trois pannes avec leur cause. |
| **08 · Les dix compétences** | C1 à C10, et où chacune se prouve dans le dossier. |

## Comment s'en servir

**Le mode flash** — le bouton vert en bas de l'écran. Il tire une question au hasard
parmi celles qui ne sont pas encore marquées comme sues : tu réfléchis, tu affiches la
réponse, puis « je savais » ou « à revoir ». C'est du rappel actif, bien plus efficace
que relire. Une variante **pièges seulement** est disponible dans la barre d'outils de
la section Questions.

**Le suivi** — chaque question a un bouton ✓. La barre dans l'en-tête montre la
progression (`0 / 53`) et les questions acquises s'estompent. L'état est conservé sur
l'appareil, donc on reprend où on s'est arrêté.

**Le filtre** — le champ en haut masque tout ce qui ne contient pas le mot cherché.
Tape `RADIUS`, `VLAN` ou `RPO` pour retrouver instantanément toutes les entrées
concernées, définitions et questions confondues.

**Au téléphone** — navigation en pastilles défilables, tableaux à défilement
horizontal, boutons dimensionnés pour le doigt. Conçue pour réviser debout dans le
métro autant que sur un écran large.

**À l'impression** — toutes les réponses se déplient automatiquement et la navigation
disparaît : `Ctrl+P` donne une fiche papier complète.

## Publier

```bash
cd REVISION
git init
git add index.html README.md .gitignore
git commit -m "Fiche de revision soutenance"
git branch -M main
git remote add origin https://github.com/<ton-pseudo>/<nom-du-depot>.git
git push -u origin main
```

Puis **Settings → Pages → Source : `main` / `/root`**. L'URL est active en deux
minutes. Comme le fichier s'appelle `index.html`, il s'affiche directement à la racine.

## Note

Les chiffres cités correspondent au dossier de projet remis au jury. En cas d'écart
entre cette page et le dossier papier, **c'est le dossier qui fait foi** — c'est lui
que le jury a sous les yeux.
