# DxO PhotoLab — Vision d'une interface repensée

> Un exercice de design personnel, réalisé par amour du développement photo et en hommage aux équipes de DxO.

Lien : https://phikuhn.github.io/dxo-photolab-ui-redesign/

---

## Contexte

Après huit ans sur Lightroom, un an sur Capture One, c'est DxO PhotoLab qui m'a réconcilié avec le développement photo ! La qualité du dématriçage RAW est unique, la réduction du bruit numérique et d'autres fonctionnalités sont sans équivalent sur le marché, et la philosophie du logiciel est portée par de véritables passionnés. Tout cela fait de PhotoLab un outil (vraiment) à part.

Pourtant, certains aspects de l'interface méritaient, selon moi, d'être repensés. Ce projet est une **vision personnelle**, réalisée par pur plaisir et gratitude envers les équipes DxO. Il ne s'agit pas d'un travail de UX/UI au sens professionnel du terme, mais d'une réflexion sur comment cette interface pourrait être encore plus fluide, intuitive et moderne, sans en trahir l'ADN.

---

## Ce qui a été modifié

### Navigation principale
- **"Personnaliser" → "Développer"** : on développe une photo, on ne la personnalise pas. Un détail sémantique, mais qui a du sens selon moi.
- **Bouton "Exporter"** ajouté directement dans la barre de navigation, aux côtés de Photothèque et Développer, là où il devrait naturellement se trouver.

### Barre d'outils
- **Nom affiché sous chaque icône** : même après plusieurs années d'utilisation, certains boutons restent ambigus. Le label lève toute ambiguïté.
- **Séparation en groupes fonctionnels** via des séparateurs verticaux : Comparer | Zoom | Outils. Plus lisible, plus intuitif.

### Histogramme
- **Déplacé dans le panneau latéral droit**, toujours visible, au-dessus des corrections. Quand on règle l'exposition ou les tons, l'histogramme doit être à portée de regard, pas à l'opposé de l'écran.
- **Indicateurs visuels de part et d'autre** de l'histogramme pour signaler les zones écrêtées (hautes lumières) ou bouchées (ombres), sous forme d'icônes d'alerte activables.

### Aperçu photo
- **Overlay EXIF** incrusté dans le coin supérieur gauche de la photo (ISO, ouverture, vitesse, focale, résolution, format de fichier), activable et désactivable en un clic. Ces informations sont essentielles lors du contrôle d'une image et ne devraient pas nécessiter de regarder dans le panneau gauche.

### Pellicule de vignettes
- **Troisième statut ajouté** : en plus de "acceptée" (vert) et "rejetée" (rouge), une **pastille orange** pour les photos encore indécises. Entre conserver et rejeter, il manquait cet état intermédiaire.
- La pellicule est légèrement raccourcie horizontalement pour laisser le panneau droit s'étendre sur toute la hauteur de l'interface.

### Pellicule de vignettes
- **Infobulles redessinées** : dans la version actuelle, l'infobulle qui s'affiche au survol d'une vignette est volumineuse et empiète sur la photo en cours de contrôle — ce qui perturbe directement la revue des images. Dans cette vision, l'infobulle est réduite à l'essentiel et dimensionnée pour ne jamais déborder sur la zone d'aperçu.

### Esthétique générale
- Plus de **rondeur** dans les éléments visuels (sliders, modules, boutons).
- **Curseurs agrandis** pour une manipulation plus précise.
- Interface globalement **modernisée** tout en conservant le thème sombre et la logique de PhotoLab.

---

## Ce que ce projet n'est pas

- Ce n'est pas une critique.
- Ce n'est pas une refonte fonctionnelle complète.
- Ce n'est pas un prototype livrable ou un cahier des charges.

C'est une conversation visuelle, une façon de dire : *voilà comment je vis cet outil au quotidien, et voilà ce qui rendrait mon expérience encore meilleure.*

---

## Stack technique

- HTML / CSS / JavaScript
- Conçu et généré avec Claude Design, pour intensifier ma pratique LLM

---

## Crédits

Toute la gratitude de ce projet va aux équipes de **[DxO](https://www.dxo.com/fr/)** — un logiciel construit par des passionnés, pour des passionnés.

---

*Philippe Kuhn — 2026*
