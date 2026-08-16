# tadhakkar-site

Pages publiques de l'application **Tadhakkar** (dhikr, adhkār, Noms d'Allah,
Coran, Qibla), servies par GitHub Pages. Elles valent pour les **deux
versions** de l'app : celle de l'App Store (iPhone, iPad) et celle de Google
Play (Android).

| Fichier | Rôle | Exigence de la boutique |
|---|---|---|
| `index.html` | Aide, questions fréquentes, contact | **Support URL** de la fiche App Store |
| `confidentialite.html` | Politique de confidentialité (FR + EN) | **Privacy Policy URL** — obligatoire chez Apple **et** chez Google Play |

Ce dépôt est public **uniquement** parce que les boutiques exigent des URL
publiquement accessibles. Il ne contient aucun code : le code source des deux
applications reste dans ses dépôts privés.

## Tenir les pages à jour

`confidentialite.html` est la copie de `docs/confidentialite.html` du dépôt
iOS. Les deux doivent rester identiques, et les écrans « Confidentialité » des
**deux** applications — `ConfidentialiteView.swift` côté iOS, les chaînes
`confidentialite_*` des dix `strings.xml` côté Android — doivent dire la même
chose qu'elles : ce sont quatre énoncés du même engagement, et l'un ne peut pas
contredire les autres. Après toute modification, corriger les quatre et mettre
à jour la date.

Ce que chaque système impose de dire à part : la sauvegarde (iCloud d'un côté,
sauvegarde d'Android de l'autre) et la finesse de la position demandée
(approximative seulement sur Android).
