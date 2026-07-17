# 05 — Le pari : indispensabilité, autre axe, demande

[← Sommaire](../README.fr.md) · [← 04 Lock-in et coupure](04-lock-in-coupure.md)

Avant la stratégie, une correction de cadrage, parce que c'est elle qui change tout. Toute l'analyse qui précède mesure la souveraineté comme une chaîne d'approvisionnement : qui fabrique la puce, qui possède le modèle, qui détient le compute. Et mesurée ainsi, la conclusion est « vassalité », puisque l'Europe ne contrôle aucun maillon amont décisif.

Mais l'histoire économique dit l'inverse. La rente ne se loge pas dans la fabrication la plus capitalistique, elle migre vers le contrôle de la relation client et de la donnée d'usage. Le pétrole raffiné capte plus de valeur que le brut. Le système d'exploitation plus que le matériel. Android plus que les fabricants de téléphones. Un acteur américain qui domine le modèle, le compute et la fonderie, mais qui doit passer par des intégrateurs européens, des données européennes et une conformité européenne pour toucher 450 millions de clients réglementés, n'a pas la souveraineté sur ce marché : il en dépend.

Confondre « ne pas fabriquer la puce » avec « ne pas avoir de pouvoir » est l'erreur centrale du débat. La souveraineté ne se gagne pas seulement à l'usine. Elle se gagne aussi au robinet et à la règle.

Le pari réaliste n'est donc ni de rattraper la pile américaine (perdu d'avance), ni un pari purement frugal et décentralisé (nécessaire mais insuffisant, puisque tout tourne encore sur Nvidia et TSMC). C'est un pari hybride, à trois étages.

---

## Étage 1 — Indispensabilité : jouer le verrou qu'on détient

L'Europe ne possède qu'une carte de coercition mondiale : ASML. Le bon usage n'est pas le chantage, qui serait l'escalade, mais l'indispensabilité, qui est le levier. La doctrine s'énonce simplement : indispensabilité, pas autosuffisance. Le mécanisme est transactionnel, pas martial : garantir l'accès aux machines de lithographie européennes contre un accès prioritaire aux puces étrangères et des contreparties industrielles. L'objectif n'est pas de couper, c'est de rendre toute tentative de nous couper trop coûteuse pour être tentée.

Concrètement, cela veut dire reprendre un contrôle souverain européen sur ASML, par une golden share européenne et pas seulement néerlandaise, établie avant toute crise de Taïwan, et réduire le contenu d'origine américaine dans sa chaîne pour échapper à la portée des contrôles d'export américains. Trois limites doivent être regardées en face : l'Europe ne tient pas seule la gâchette aujourd'hui (ASML est sous licence d'export néerlandaise, déjà alignée sur la pression américaine) ; l'asymétrie de temps rend l'arme inutile en représailles directes (un embargo EUV mord en années, une coupure d'IA en heures) mais puissante en dissuasion de long terme ; et c'est une option nucléaire, catastrophique si on l'utilise. La carte se joue discrètement, comme un rappel que l'EUV ne peut être tenu pour acquis, pas comme une menace publique. Mal manié, on perd notre seule carte.

## Étage 2 — L'autre axe : là où l'avantage européen est réel

Plutôt que de courir, perdant, derrière la frontière américaine, l'Europe a intérêt à ouvrir un autre axe, là où son avantage est structurel et pas subi.

Les **substrats non-EUV** d'abord : la photonique, le calcul en mémoire, le neuromorphique, qui se fabriquent sur des nœuds matures sans EUV, là où l'Europe possède déjà la chaîne (GlobalFoundries Dresde, imec, le projet PIXEurope, Axelera, le CEA-Leti). C'est le seul terrain compute où l'Europe a un avantage spécifique, et il vise précisément le marché de l'inférence, qui devient le gros du volume quand l'entraînement plafonne.

Le **paradigme suivant** ensuite : les world models, où l'avance américaine sur le texte ne se transfère pas. Et là, le fait est frappant : le pari le plus sérieux est français. AMI Labs, fondé par Yann LeCun, est à Paris, avec un capital largement français. Wayve, au Royaume-Uni, a déjà un world model à l'échelle commerciale. La matière première de ce paradigme, ce ne sont plus les corpus de texte épuisés, mais les données physiques industrielles, que l'Europe possède (automobile allemande, manufacturing) et qu'aucun labo américain ne peut exfiltrer.

L'**open-weight comme commun** enfin : Mistral, SmolLM de Hugging Face (entreprise d'origine française), OpenEuroLLM, les datasets ouverts comme FineWeb. C'est la couche où l'Europe peut bâtir un bien commun sans la permission de personne. Et avec elle, les **petits modèles sur edge** (qui tournent sur un téléphone ou un Raspberry Pi, sans datacenter, immunisés à la coupure) et le **compute citoyen décentralisé**, à condition qu'il soit public et non spéculatif.

## Étage 3 — Demande garantie et judo réglementaire : le levier sans transistor

C'est la conséquence directe de la correction de cadrage. Si la souveraineté se gagne à la couche demande et donnée, alors les trois leviers les plus puissants ne nécessitent pas un seul transistor.

D'abord, l'**achat souverain** pluriannuel et garanti (défense, santé, administration, EuroHPC), pour que les champions européens cessent d'être des proies rachetées par les Américains. Les signaux d'alarme sont déjà là : Codasip, pilier européen du RISC-V, est en vente ; Ventana est parti chez Qualcomm. Sans demande-ancre, tous les champions de design européens finissent siphonnés.

Ensuite, le **mandat d'interopérabilité** des modèles et des données d'usage, sur la recette qui a déjà marché (RGPD, DMA). Forcer la portabilité des fine-tunes et des données transforme les modèles fermés américains en commodités interchangeables sur le marché des 450 millions, et casse le verrou du cloud. L'argent dépensé à rendre la migration gratuite défait plus de dépendance que l'argent dépensé à bâtir un fief.

Enfin, le **compute citoyen public**, non tokenisé (sur la brique de federated learning Flower, d'origine européenne, native au RGPD), pour la souveraineté d'usage sur les verticales que ni les États-Unis ni la Chine ne peuvent exfiltrer : santé, langues européennes, archives. Pas du Bitcoin, du commun public.

Et au ras du sol, là où chacun agit sans attendre l'État : inscrire des clauses anti-lock-in dans tout contrat critique. Escrow ou distillation des modèles, embeddings reproductibles, journaux exportables, tests de bascule réguliers. La réversibilité ne se décrète pas le jour de la coupure, elle se contractualise à froid.

La thèse, en une image : l'Europe ne peut pas posséder le brut, mais elle peut posséder le raffinage, le robinet et la règle.

---

## Ce qu'il faut enseigner

La souveraineté n'est pas qu'une affaire d'État. C'est aussi une hygiène, individuelle et collective, qui s'apprend. Voici ce qui mérite d'être transmis, sans jargon.

**Distinguer trois mots qu'on confond.** Autonomie, c'est ne pas dépendre d'autrui. Souveraineté, c'est faire la loi de son propre développement. Technodiversité, c'est qu'existent plusieurs trajectoires techniques, inscrites dans plusieurs visions du monde. On peut être autonome et prisonnier d'une monoculture. Le but n'est pas l'autonomie dans le même monde, c'est la pluralité des mondes.

**Lire une pile technique couche par couche.** Lithographie, fonderie, puce, modèle, cloud, application. À chaque étage, deux questions : qui en fait la loi, et qui peut couper l'accès ? La souveraineté se gagne ou se perd couche par couche, jamais en bloc.

**Reconnaître la souveraineté de marketing.** Un service estampillé « souverain » peut rester sous contrôle juridique ou matériel étranger. Le cas d'école est Gaia-X : une fois les hyperscalers américains à l'intérieur, l'initiative a perdu son objet. Le seul critère qui compte : qui détient le pouvoir d'exclusion ?

**Se méfier du don.** La dépendance n'arrive pas comme une contrainte, elle arrive comme un cadeau : un investissement, un accès gratuit à un modèle, un partenariat gagnant-gagnant. Évaluer un cadeau technologique à l'aune de ce qu'il rend ensuite impossible.

**Reconnaître un fief au test de la coupure.** Peuvent-ils te couper, et serait-ce catastrophique ? Si oui, ce n'est pas un outil, c'est un fief. Un outil, on le quitte. Un fief, il te quitte.

**Posséder la relation avec son public.** Son propre domaine, sa propre liste de contacts. La plateforme ne possède que l'audience qu'elle te laisse atteindre. Une liste qu'on exporte est l'actif le plus difficile à confisquer.

**Préférer ce qu'on peut quitter.** Formats ouverts, données exportables, outils auto-hébergeables, jamais un seul fournisseur pour quelque chose de critique. Le coût de bascule se conçoit à froid, à l'avance, pas le jour de la coupure.

**Traiter la coupure comme le vrai risque, pas le prix.** Une copie téléchargée, un second rail, un hébergeur de repli, avant d'en avoir besoin. La leçon du procureur de la CPI vaut pour chacun.

**La sortie collective bat la sortie individuelle.** Un fief survit parce que les captifs ne peuvent pas se coordonner pour partir. Coopératives, infrastructure mutualisée, régulation qui impose la portabilité : c'est là que le rapport de force bascule.

Et le fil rouge, qui vaut pour l'État comme pour l'individu : viser la non-captivité, pas la pureté. La dépendance zéro n'existe pas, ASML et TSMC sont sous tout. L'objectif n'est pas d'être pur, c'est de ne jamais pouvoir être coupé sur quelque chose qui compte.

---

## Le garde-fou : pourquoi ce pari peut échouer

Il faut le dire, sinon le document serait un tract. La voie frugale et souveraine n'est un avantage que si trois conditions sont réunies : un capital patient, un achat souverain réel, et une vitesse de raccordement au réseau débloquée. Sans elles, elle reste une vertu subordonnée, un fournisseur vertueux d'électrons propres et d'efficience que d'autres encaissent.

Pire : un krach de la bulle IA américaine n'égaliserait pas le terrain. Il détruirait du capital financier américain sans transférer un gramme de souveraineté industrielle à l'Europe (le mur fonderie survit à n'importe quel krach), et il appauvrirait le plus faible. L'Europe est déjà au bord de la récession, et elle serait la première à couper son capital patient et son achat souverain en cas d'austérité, pendant que les géants américains, riches en cash, rachèteraient les actifs bradés. La vraie question n'est pas « la bulle va-t-elle éclater », c'est « l'Europe a-t-elle un bilan assez solide pour acheter quand tout sera soldé ».

La doctrine à trois étages doit donc tenir que la bulle éclate ou non. C'est sa condition de crédibilité.

[← Sommaire](../README.fr.md) · [Suite : 06 — Ce qui peut retourner la table →](06-ce-qui-peut-retourner-la-table.md)
