# Cubase-French-Azerty-Shortcuts
## Raccourcis clavier de [Cubase](https://fr.wikipedia.org/wiki/Cubase) pour produire de la musique électronique, avec un clavier [AZERTY](https://fr.wikipedia.org/wiki/AZERTY) sous macOS

*Abstract in English:      
This GitHub repo shares the Cubase “Key Commands” I recommend to my students, tailored for AZERTY keyboards on macOS. They are available both as reference tables (online or downloadable) and as an XML preset importable directly into the software.       
I use Cubase primarily because of its MIDI implementation, which is superior to competing solutions. Yet, since its 2000s reboot, Cubase has grown wonky. Its interface reflects a confusion between two distinct concerns of music creation: composition and mixing. In practice, this tangles “horizontal music” (positioning of MIDI, native events, and recordings on a timeline) with “vertical sound” (balancing sounds with a mixing console).          
The result is a tool that often obstructs the workflow. This sharply contrasts with the ideal of a musical instrument, which disappears in the player’s hands. Genuine instrument makers (“luthiers”) actively combat inefficiencies, since they drain cognitive and physical resources that are consequently lost to the art.       
By working around problematic interfaces, keyboard shortcuts effectively bring software closer to the experience of an instrument.*

### Introduction

Ce dépôt GitHub propose les raccourcis clavier que je recommande à mes élèves pour la production de musique électronique avec Cubase (« _Key Commands_ »). Vous les trouverez réunis sur des tableaux à consulter en ligne ou à télécharger, et en preset XML à ouvrir depuis le logiciel.

La principale raison pour laquelle je produis avec ce séquenceur audionumérique est sa gestion du MIDI, supérieure en tout à celle de la concurrence.

Mais lors de son reboot des années 2000, Cubase est devenu « [wonky](https://www.linkedin.com/posts/pavel-samsonov-44ba2833_trying-to-improve-the-wrong-dimension-of-activity-7178479192555077633-4NVo) ». Une confusion entre ce qui relève de la composition et ce qui relève du mixage se traduit par une interface qui enchevêtre et emmêle « musique horizontale » et « son vertical » — c’est-à-dire la gestion du temps, via les évènements MIDI ou natifs et les enregistrements positionnés horizontalement sur une timeline, et la gestion de la balance sonore, via des réglages gérés et visualisés verticalement sur une console de mixage.

Il en résulte un outil informatique qui se dresse souvent en travers du chemin et exige une attention de tous les instants, à l’opposé de l’idéal de l’instrument de musique, qui se fait oublier (les luthiers éliminent les inefficacités car elles détournent des neurones et font consommer des calories, qui sont alors perdus pour l’art).

En contournant certains obstacles, les raccourcis clavier sont un excellent moyen de rapprocher l’outil de l’instrument.

Malheureusement, les presets proposés par Steinberg font le service minimum. Prendre le temps de choisir, programmer et apprendre par cœur des raccourcis mieux adaptés change véritablement la vie. Ce dépôt vise à vous mâcher le travail.

![Metastasis_2022-05-31_gris_AtAc_GaussianNoise2%composite](https://github.com/user-attachments/assets/b9024ce7-652e-47f2-aa44-8f6089ccf883)
*La partition de [Metastasis](https://fr.wikipedia.org/wiki/Metastasis_(Iannis_Xenakis)) de Iannis Xenakis anticipe dès 1954 le concept de ligne d’automation*

---

### Tableaux

Les raccourcis clavier sont notés sur deux tableaux, chacun offrant une présentation différente, accessibles en ligne et téléchargeables via ce document Google Sheets (les onglets pour changer de tableau se trouvent en bas à gauche) :

https://docs.google.com/spreadsheets/d/1gC02NLNjDQHW8Q47bPoo8kpMkJnirxTmAqoKUOCGSd4

- Le tableau _[Fenêtre Key Commands](https://docs.google.com/spreadsheets/d/1gC02NLNjDQHW8Q47bPoo8kpMkJnirxTmAqoKUOCGSd4/edit?gid=0)_ est optimisé pour la saisie dans Cubase. Il reprend l’ordre de la fenêtre _Key Commands_ et la façon dont les raccourcis y sont notés.

- Le tableau _[Mapping Clavier Azerty](https://docs.google.com/spreadsheets/d/1gC02NLNjDQHW8Q47bPoo8kpMkJnirxTmAqoKUOCGSd4/edit?gid=753362515)_ est optimisé pour la mémorisation. Il reprend l’ordre du clavier et regroupe les raccourcis par touche de modification. Le code couleur est expliqué en légende, dans le cadre en bas à droite.

---

### Preset

Il est possible d’importer dans Cubase tous ces raccourcis en une fois, sans devoir les saisir un par un, via un preset de _Key Commands_. Il suffit pour cela de :

- Télécharger le fichier [Cubase-French-Azerty-Shortcuts.xml](https://github.com/TheMicronauts/Cubase-French-Azerty-Shortcuts/releases/download/v1.0.1/Cubase-French-Azerty-Shortcuts.xml)

- Glisser-déposer ce fichier dans le sous-dossier `~/Library/Preferences/Cubase xx/Presets/KeyCommands/`                
  (où `~` indique le chemin jusqu’à votre dossier _Home_ et où `xx` correspond à votre version de Cubase)

- Sélectionner le preset _Cubase-French-Azerty-Shortcuts_ depuis la fenêtre _Key Commands_ de Cubase

Chaque nouvelle version de Cubase ajoute de nouvelles _Key Commands_, mais reste compatible avec les mêmes fichiers XML.

Ce preset a été créé avec Cubase 10.5 tandis que les tableaux se référent à Cubase 13. Par conséquent, un ou deux raccourcis indiqués dans le document Google Sheets sont absents du fichier et devront être ajoutés manuellement le cas échéant.

Le fichier XML peut aussi être importé dans les versions antérieures. Les raccourcis non pris en charge sont simplement ignorés (testé avec Cubase 6.5 et 10).

---

### Références

Exemples de dispositions de touches considérées :

![2025-03-20 11 07 31Autos](https://github.com/user-attachments/assets/1dee9a29-8ed2-4112-9f4e-ba61e4adce83)

![2025-03-20 10 56 20](https://github.com/user-attachments/assets/6061b62f-f09e-4df9-8978-c6eb22e843cf)

![2025-03-20 10 54 28](https://github.com/user-attachments/assets/43bf3ab7-0cbd-492a-819e-b44edfb27c13)
