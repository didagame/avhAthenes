# Une voix à Athènes

Aventure dont vous êtes le héros pour ouvrir le chapitre « La Méditerranée antique : les empreintes grecques et romaines » en histoire, classe de seconde générale et technologique.

Point de passage du programme : **Périclès et la démocratie athénienne**. Le jeu montre comment Athènes associe régime démocratique et empire maritime, et amène l'élève à s'interroger sur les forces et les limites de la démocratie athénienne.

## Le jeu en bref

- Athènes, 444-443 av. J.-C. L'élève joue **Kallias**, jeune citoyen rameur et tailleur de pierre, ou **Phanostratè**, sa fiancée, tisserande, sans droits politiques.
- Lykon, un riche rival, accuse Kallias de ne pas être citoyen. Il faut réunir des appuis pendant un mois : au Pirée, à la Pnyx, sur le chantier de l'Acropole et au théâtre de Dionysos.
- Un plan 3D d'Athènes et de l'Attique sert de carrefour : la ville (asty) dans ses murailles, les Longs Murs jusqu'au Pirée, et tout autour la campagne (khôra), où vit la majorité des citoyens. Il utilise Three.js (chargé depuis cdnjs) ; sans connexion, le plan 2D prend le relais.
- Puis viennent les noces, le vote du dème, le procès devant l'Héliée, l'ostracisme de 443 et une représentation d'*Antigone* en 441.
- Mini-jeux : population de l'Attique, chemin d'un décret, saison du chantier de Périclès (payer, embaucher, hisser à la grue, bâtir en dévoilant la vraie façade du Parthénon, l'Acropole et ses murailles en 3D), tirage au sort des juges, plaidoirie, ostrakon.
- Trois fins. Au bilan, l'élève range ses découvertes, des tessons, dans un vase « Force » ou « Limite », puis le jeu corrige.
- Durée : environ 35 à 40 minutes, élève seul, sans compte ni donnée personnelle.

## Utilisation

Tout le jeu tient dans un seul fichier : `index.html`.

- **Google Sites** : Insérer → Intégrer → Code d'intégration, puis coller le contenu de `index.html`. Prévoir un bloc d'au moins 480 px de haut. Le bouton « Plein écran » est conseillé.
- **Ouvrir directement** : `index.html` s'ouvre dans Chrome, Firefox ou Safari.
- **GitHub Pages** (facultatif) : dans les réglages du dépôt, rubrique Pages, choisir la branche `main`. Le jeu est alors en ligne à l'adresse du dépôt.

## Modifier les textes

Tous les textes sont en tête du fichier, dans le bloc `CONTENU MODIFIABLE` : scènes, dialogues, découvertes, documents, glossaire. On peut les corriger sans toucher au code.

- `[[mot]]` ou `[[clé|mot affiché]]` crée un mot expliqué en bulle ; la clé doit exister dans le glossaire.
- `lienDon` : adresse de la page de dons (HelloAsso). Vide = bouton caché.
- Le point « Le savais-tu ? » sur les marbres du Parthénon décrit la situation d'octobre 2026. Il faudra le mettre à jour (`docs.marbres`).

## Crédits

- Photos intégrées au fichier, toutes issues de Wikimedia Commons :
  - plaque des Ergastines (frise est du Parthénon, musée du Louvre) : Jastrow, 2006, domaine public ;
  - façade ouest du Parthénon et temple d'Héphaïstos : Guillaume Piolle, 2008, CC BY 3.0 ;
  - le Parthénon : Steve Swayne, 1978, CC BY 2.0 ;
  - temple de Poséidon au cap Sounion : Nikthestoned, 2012, CC BY-SA 3.0.
- Les photos ont été redimensionnées pour alléger le fichier ; aucune autre modification.
- Illustrations, carte, musique et vue 3D : dessinées et générées par le code du jeu.
- Polices : Alegreya, Alegreya Sans SC et Marcellus SC (Google Fonts, licence SIL Open Font License).
