[English](README.md) · **Français**

# Souveraineté IA : Europe et France

**Où on en est vraiment, et ce qu'on peut faire pour ne pas se faire piloter.**

*Document de recherche. État vérifié au 15 juin 2026. Version anglaise : [`README.md`](README.md). Sources : [`SOURCES.md`](SOURCES.md).*

> État des lieux compagnon : [Souveraineté numérique européenne et intelligence artificielle, état des lieux 2024-2026](europe/README.fr.md) — auparavant un dépôt autonome, désormais intégré à celui-ci.

---

## Pourquoi ce document

Je travaille avec l'intelligence artificielle comme matériau. Je dépends donc, concrètement, d'une chaîne d'outils que je ne contrôle pas. Le 12 juin 2026, un modèle déployé auprès de centaines de millions de personnes a été désactivé en quelques heures par le décret d'un État étranger. Ce jour-là, une inquiétude diffuse est devenue une question précise : qu'est-ce que l'Europe maîtrise vraiment, et qu'est-ce qu'on peut nous couper ?

J'ai voulu une réponse vérifiée, datée, sans slogan. Ni drapeau, ni camp. Ce document est cette réponse. Il ne promet pas une souveraineté qui n'existe pas, et il ne se résigne pas à la dépendance. Il vise la non-captivité, pas la pureté. Et il finit par ce qui me semble le plus utile : ce qu'on peut faire, et ce qu'il faut comprendre, pour ne pas se faire piloter.

Tout est sourcé et daté. Là où les sources sérieuses se contredisent, je le dis au lieu de trancher. Là où je me suis trompé en chemin, je l'ai corrigé dans le texte.

*Ismaël Joffroy Chandoutis*

---

## Le verdict en bref

> **L'Europe ne peut pas posséder le brut : la fonderie de pointe, la mémoire HBM, le compute d'entraînement. Mais elle peut posséder le raffinage, le robinet et la règle.** Souveraineté par indispensabilité et par contrôle de la demande, jamais par autarcie.

**Ce qui est vrai et dur.** Le fossé matériel est un mur. L'Europe ne grave aucune puce de pointe (son nœud le plus avancé est le 18nm de ST Crolles), ne produit aucune mémoire HBM, et pèse environ 5 % du compute IA mondial, en baisse. Multiplier les designs (modèles, ASIC, robots) ne fait qu'augmenter la pression sur le même goulot. La seule carte mondiale que l'Europe tient vraiment, c'est ASML, monopole absolu sur les machines de gravure EUV, dont le monde entier dépend, États-Unis compris. Mais elle ne peut pas la convertir seule en souveraineté.

**Ce qui est surévalué.** Le fossé modèle et capital. Il se commoditise : distillation, mélange d'experts, quantization, recettes d'entraînement publiques font tomber l'écart avec la frontière à environ dix points et trois à six mois, et le coût par token chute d'un facteur dix par an. La preuve a contrario est juridique : faute de barrière technique, les États-Unis défendent désormais leur avance par le droit. Le « retard modèle » européen est un faux handicap permanent. Mistral peut suivre à six mois de la frontière, et un acteur européen peut même être en tête sur le paradigme suivant (les world models : le pari le plus sérieux, AMI Labs, est à Paris).

**L'erreur de cadrage.** Mesurer la souveraineté comme une chaîne d'approvisionnement (qui fabrique la puce) conduit mécaniquement à conclure « vassalité ». Mais l'histoire économique dit l'inverse : la rente migre vers le contrôle de la relation client et de la donnée d'usage, pas vers la fabrication la plus capitalistique. Pétrole raffiné contre brut, système d'exploitation contre matériel, Android contre fabricants. Un acteur américain qui domine le modèle, le compute et la fonderie mais doit passer par des intégrateurs, des données et une conformité européennes pour toucher 450 millions de clients réglementés n'a pas la souveraineté sur ce marché : il en dépend.

**Le pari, à trois étages.**
1. **Indispensabilité.** Jouer le verrou qu'on détient (ASML) comme levier de négociation, via un contrôle souverain européen établi *avant* toute crise, pas la fonderie qu'on n'aura pas.
2. **L'autre axe, là où l'avantage européen est réel.** Les substrats non-EUV (photonique, neuromorphique) sur nœuds matures, où l'Europe possède déjà la chaîne, pour capter l'inférence ; le paradigme suivant (world models, où l'avance texte américaine ne se transfère pas) ; l'open-weight comme commun (Mistral, OpenEuroLLM).
3. **Demande garantie et judo réglementaire.** L'achat souverain pluriannuel pour que les champions européens cessent d'être rachetés par les États-Unis ; le mandat d'interopérabilité des modèles et des données à la RGPD ; le compute citoyen public, non spéculatif, pour les verticales que personne ne peut exfiltrer.

**Le garde-fou anti-naïf.** La voie frugale n'est un avantage que si trois conditions sont réunies : capital patient, achat souverain réel, et vitesse de raccordement au réseau électrique débloquée. Sans elles, elle reste une vertu subordonnée. Pire : un krach de la bulle IA américaine n'égaliserait pas le terrain, il appauvrirait le plus faible, l'Europe étant déjà au bord de la récession et la première à couper son capital patient en cas d'austérité. Et l'« atout » du nucléaire français mérite trois astérisques : faible intensité carbone, oui, mais ni propre (déchets éternels), ni pleinement souverain (uranium importé), ni insensible au climat (eau, sécheresse).

**En une phrase :** ni vassalité fatale, ni souveraineté triomphante. Une non-captivité possible mais conditionnelle, qui se joue dans les vingt-quatre à trente-six prochains mois, pas en 2036.

---

## Comment lire ce document

1. [État des lieux : les quatre couches de dépendance](fr/01-etat-des-lieux.md)
2. [Horizons : de six mois à dix ans](fr/02-horizons.md)
3. [France ou Europe : l'illusion du souverainisme national](fr/03-france-europe.md)
4. [Lock-in et coupure : marché ou fief](fr/04-lock-in-coupure.md)
5. [Le pari : indispensabilité, autre axe, demande](fr/05-pratique.md)
6. [Ce qui peut retourner la table : les inconnues](fr/06-ce-qui-peut-retourner-la-table.md)
7. [La couche oubliée : données et consentement](fr/07-donnees-consentement.md)

Annexe : [`SOURCES.md`](SOURCES.md) (bibliographie vérifiée, datée).

---

## Voir aussi

Deux dépôts compagnons, gardés séparés à dessein plutôt que fusionnés dans celui-ci :

- [`souverainete-ia-europe`](https://github.com/ismael-joffroy-chandoutis/souverainete-ia-europe) : un état des lieux antérieur et plus étroit, sur les puces, le cloud, les modèles et le quantique. Ce dépôt-ci en est la version canonique et à jour.
- [`souverainete-numerique-critique`](https://github.com/ismael-joffroy-chandoutis/souverainete-numerique-critique) : une critique du concept même de « souveraineté numérique », et des vocabulaires alternatifs (autonomie, convivialité, communs, vernaculaire). Lecture complémentaire, pas un doublon : ce dépôt questionne le cadre, celui-ci travaille dedans.

---

*Licence : CC BY-NC-ND 4.0 pour le texte (voir [LICENSE.md](LICENSE.md)). Travail de recherche personnel, pas un avis institutionnel.*

Par [Ismaël Joffroy Chandoutis](https://ismaeljoffroychandoutis.com).
