# Cubase-French-Azerty-Shortcuts
## Raccourcis clavier de [Cubase](https://fr.wikipedia.org/wiki/Cubase) pour clavier [AZERTY](https://fr.wikipedia.org/wiki/AZERTY) français sous macOS

Ce dépôt propose les raccourcis clavier de Cubase que je recommande à mes étudiants pour produire de la musique électronique (house, techno, garage, bass, etc.). Ils sont disponibles via un document Google Sheets et via un fichier XML à importer dans le logiciel.

Cubase a beaucoup de qualités : très complet, une gestion de la latence et une gestion du MIDI bien supérieures à la concurrence. Mais depuis son reboot des années 2000, ce séquenceur audionumérique est devenu « [wonky](https://www.linkedin.com/posts/pavel-samsonov-44ba2833_trying-to-improve-the-wrong-dimension-of-activity-7178479192555077633-4NVo) ». Son interface mélange constamment musique horizontale et son vertical. 

Dit autrement : son interface mélange constamment ce qui relève de l’art de la production musicale (écriture, programmation, enregistrement, automation, arrangement, gestion du temps) et ce qui relève de la technique du mixage (configuration, trajet du signal, état initial, réglages statiques, équilibre des fréquences). 

Il en résulte un outil informatique lourd, capricieux, incohérent, qui demande une attention de tous les instants, à l’opposé de l’idéal de l’instrument de musique, qui se fait oublier.

Les raccourcis clavier sont un excellent moyen de contourner son interface-champ de mines et de se rapprocher de l’instrument de musique. Malheureusement, les presets proposés par Steinberg font le service minimum. Prendre le temps d’en choisir, programmer et apprendre par cœur de mieux adaptés change véritablement la vie. Ce dépôt vise à vous mâcher le travail.

---

Le document Google Sheets présente les raccourcis clavier sur deux tableaux, qui regroupent les mêmes mais présentés différemment, accessibles via les onglets en bas à gauche :

https://docs.google.com/spreadsheets/d/1gC02NLNjDQHW8Q47bPoo8kpMkJnirxTmAqoKUOCGSd4/edit?usp=sharing

- Le premier tableau, _Mapping Clavier Azerty_, est optimisé pour la mémorisation. Il liste tous les raccourcis dans l’ordre du clavier et groupés par touche de modification. Le code couleur est expliqué en légende, dans le cadre en bas à droite.

- Le deuxième tableau, _Fenêtre Key Commands_, est optimisé pour la saisie dans Cubase. Il reproduit la fenêtre _Key Commands_, son ordre et la façon dont les raccourcis y sont notés. La deuxième ligne sert de légende.

---

Il est aussi possible d’importer dans Cubase tous ces raccourcis en une fois, sans devoir les saisir un par un. Il faut pour cela :

- [Télécharger le fichier Cubase-French-Azerty-Shortcuts.xml](https://github.com/TheMicronauts/Cubase-French-Azerty-Shortcuts/releases/download/v1.0.0/Cubase-French-Azerty-Shortcuts.xml)

- Glisser-déposer ce fichier dans le sous-dossier  ~/Library/Preferences/Cubase xx/Presets/KeyCommands/                
  (où ~ indique l’arborescence jusqu’à votre dossier _Home_ et où xx correspond à votre version de Cubase)

- Sélectionner le Preset _Cubase-French-Azerty-Shortcuts_ dans la fenêtre _Key Commands_ de Cubase

Chaque nouvelle version de Cubase ajoute de nouveaux raccourcis clavier. Le fichier XML a été créé avec Cubase 10.5 tandis que les tableaux se référent à Cubase 13. Par conséquent, un ou deux raccourcis indiqués dans le document Google Sheets sont absents du fichier. Ils devront être ajoutés manuellement le cas échéant.

Le fichier XML peut aussi être importé dans les versions antérieures. Les raccourcis non pris en charge sont simplement ignorés (testé avec Cubase 6.5 et 10).

---

Exemple de dispositions de touches considérées :

![2025-03-20 11 07 31Autos](https://github.com/user-attachments/assets/1dee9a29-8ed2-4112-9f4e-ba61e4adce83)

![2025-03-20 10 56 20](https://github.com/user-attachments/assets/6061b62f-f09e-4df9-8978-c6eb22e843cf)

![2025-03-20 10 54 28](https://github.com/user-attachments/assets/43bf3ab7-0cbd-492a-819e-b44edfb27c13)
