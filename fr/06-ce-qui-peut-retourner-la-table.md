# 06 — Ce qui peut retourner la table

[← Sommaire](../README.fr.md) · [← 05 Le pari](05-pratique.md)

Un instantané ment, on l'a dit. Tout ce qui précède décrit le présent, et le présent peut basculer. Cette section regarde les forces qui pourraient retourner la table, en posant à chacune la même discipline, pour ne pas se raconter d'histoires : érode-t-elle le fossé du modèle, celui du compute, ou celui de la fonderie ? Et est-ce une opportunité spécifiquement européenne, ou un simple changement de maître étranger ?

La réponse d'ensemble, qu'on démontre vecteur par vecteur, est nette. Presque tout peut bouger sur la couche logicielle, où l'Europe peut suivre. Presque rien ne bouge sur le mur matériel, où elle est captive. Et la seule vraie issue n'est pas un vecteur technologique, c'est un changement de regard.

---

## Le mur qui ne bouge pas

Commençons par ce qui ne change pas, parce que c'est le sol. Aucun des vecteurs explorés n'érode le fossé fonderie, HBM et matériaux. Plusieurs le renforcent : multiplier les designs (modèles, accélérateurs sur mesure, RISC-V, robots) augmente la pression sur le même goulot, le silicium de pointe gravé chez TSMC avec les machines d'ASML. Le silicium ne se récupère pas du e-waste. La HBM reste un oligopole asiatique et américain sans aucune part européenne. Et les matériaux critiques restent une arme chinoise. Sur ce mur, le pessimisme est justifié et durable.

## Ce qui érode vraiment la couche modèle

C'est ici que le pessimisme est, lui, surévalué. La couche modèle se commoditise sous nos yeux, et c'est une bonne nouvelle pour l'Europe.

L'**effondrement des coûts** (l'économie à la DeepSeek : mélange d'experts, distillation, quantization, recettes d'entraînement publiques) fait tomber l'écart avec la frontière à environ dix points et trois à six mois, avec un coût par token divisé par dix chaque année. La preuve que ce fossé est mince est juridique : faute de barrière technique, les États-Unis le défendent désormais par le droit. Les **petits modèles sur edge** donnent une souveraineté d'usage tangible, sans datacenter, immunisée à la coupure. L'**open-weight comme commun**, porté notamment par Hugging Face (entreprise d'origine française qui banalise la couche modèle avec deux millions de modèles et des recettes ouvertes), est le seul étage où l'Europe peut bâtir un bien souverain sans permission. Et le **compute citoyen décentralisé**, s'il est public, ouvre un actif que personne ne peut exfiltrer.

Tous ces leviers partagent une limite : ils donnent la souveraineté d'usage, jamais la souveraineté matérielle. Le petit modèle tourne quand même sur une puce gravée à Taïwan. Mais l'usage, c'est déjà la non-captivité, et c'est l'essentiel du combat à court terme.

## Ce qui pourrait contourner le mur (où l'Europe a de vraies cartes)

Trois axes, et ce sont les seuls espoirs sérieux d'une souveraineté qui ne soit pas que d'usage.

Les **substrats non-EUV** (photonique, calcul en mémoire, neuromorphique) se fabriquent sur des nœuds matures, sans EUV. C'est le seul terrain compute où l'Europe possède déjà la chaîne, et il vise l'inférence, le gros du volume de demain.

Le **paradigme suivant**, les world models, déplace le terrain de jeu du texte (épuisé, verrouillé) vers les données physiques industrielles (que l'Europe détient). Et le pari le plus sérieux y est français, AMI Labs à Paris. Si le monde bascule de l'IA-texte vers l'IA-physique, l'avance américaine ne se transfère pas mécaniquement.

Le **quantique**, enfin, est le domaine où, contrairement à l'IA générative, l'Europe est réellement dans la course : 54 % des déploiements mondiaux de processeurs, une domination des goulots matériels (cryogénie, lasers), une diversité technologique unique. Mais deux nuances honnêtes. D'abord, le quantique ne change pas la donne de l'IA à cinq ou dix ans : il ne remplace pas le GPU, c'est même l'IA qui fait marcher le quantique. Ensuite, le vrai levier souverain quantique à court terme n'est pas l'ordinateur, c'est la **cryptographie post-quantique** : « récolter maintenant, déchiffrer plus tard », une migration datée, des produits déjà certifiés par l'ANSSI, un cœur algorithmique européen. C'est concret, urgent, et personne ne le finance parce que ce n'est pas spectaculaire.

## Les nouveaux fronts qui aggravent la dépendance

La robotique et le spatial sont les deux fronts émergents, et tous deux suivent la même loi : ils ajoutent de la dépendance, sauf là où une demande souveraine non négociable existe.

La **robotique** empile une couche matériaux pire que les puces : les aimants à terres rares sont à 94 % chinois, et cette arme est déjà tirée. Sur le cerveau (les modèles d'action) comme sur le corps (Unitree), l'Europe est marginale. Sauf sur un point : la **défense et les drones**, où elle a des champions de classe mondiale (Helsing valorisé 18 milliards de dollars), une demande captive (on n'achète pas ses drones de guerre à Pékin), un terrain réel (l'Ukraine) et de l'argent public verrouillé. La guerre crée la demande souveraine qu'aucune politique civile n'a su créer.

Le **spatial** rejoue exactement l'affaire Fable : le précédent Starlink, quand Musk a coupé une infrastructure critique de guerre sur sa propre décision, est l'interrupteur étranger dans l'orbite. Et le symptôme parfait, c'est que l'Europe paie SpaceX pour lancer ses propres satellites Galileo. Les datacenters orbitaux sont une chimère américaine. Le vrai actif européen, c'est la donnée ouverte de Copernicus. Et là encore, c'est la demande de défense qui finance enfin la souveraineté. La leçon est dure : la souveraineté ne se gagne pas en orbite, elle se perd au sol, faute de silicium.

## Les deux variables qui écrasent tout

Deux forces dépassent les vecteurs technologiques, et toutes deux résistent à l'optimisme facile.

Le **climat et la rareté** peuvent rebattre les cartes dans les deux sens. Soit la contrainte force la frugalité et avantage le camp bas-carbone et efficient, ce qui servirait l'Europe. Soit, et c'est le scénario que la thèse confortable sous-estime, elle ne fait que confirmer la domination du mieux capitalisé (les États-Unis) et du mieux doté en raffinage (la Chine), reléguant l'Europe au rôle de fournisseur vertueux d'électrons propres. Le Danemark a prouvé que la grille la plus propre sature quand même. Le paradoxe de Jevons rappelle que l'efficience démultiplie la demande au lieu de la réduire. La frugalité n'est un avantage que si on a aussi la vitesse et le capital.

La **bulle économique de l'IA** est orthogonale à la souveraineté, et c'est le piège. Un krach détruirait du capital financier américain sans transférer aucune souveraineté industrielle à l'Europe : le mur fonderie survit à tout krach. Pire, il appauvrirait le plus faible. Le débat « la bulle va-t-elle éclater » est moins important que la question « l'Europe a-t-elle les reins pour acheter quand tout sera soldé ».

---

## La grille, d'un coup d'œil

| Vecteur | Fossé modèle | Fossé compute | Fossé fonderie | Opportunité européenne |
|---------|:---:|:---:|:---:|---|
| Commoditisation / coûts | **érode** | contourne | intact | Fast-follow jouable, comme la Chine |
| Small models / edge | **érode** | renforce | intact | Souveraineté d'usage réelle |
| Open-weight / Hugging Face | **érode** | intact | intact | Commun souverain (origine FR) |
| Compute citoyen décentralisé | **érode** | contourne | intact | Commun public RGPD, peu saisi |
| Substrats non-EUV | intact | **érode** | **contourne** | Vrai avantage EU (nœuds matures) |
| World models | **contourne** | aggrave | intact | AMI Labs Paris, données physiques EU |
| Quantique (calcul) | marginal | ne remplace pas | échappe partiellement | EU forte sur le hardware |
| Quantique (crypto PQC) | hors sujet | hors sujet | hors sujet | **Le vrai levier court terme, daté** |
| TPU / accélérateurs non-Nvidia | partiel | **érode** | renforce | Surtout un autre maître US |
| Hardware ouvert / RISC-V | marginal | contourne par le bas | intact | Design oui, fabrication non |
| Matériel réparable | intact | marge | intact | Résilience, pas puissance |
| Robotique | aggrave | aggrave | **aggrave** | Ouverture = défense / drones |
| Spatial | intact | aggrave | aggrave | Galileo, Copernicus, défense |

---

## Les cygnes noirs

L'agent chargé de penser à contre-courant a produit des scénarios non évidents qui méritent d'être nommés, parce qu'ils peuvent tout changer.

Le **verrou de Taïwan** qui transforme ASML en arme d'embargo inversé : un choc sur l'île gèle la fonderie mondiale, et l'Europe se découvre, le temps d'une fenêtre étroite, arbitre de la reconstruction. La **frontière qui cesse de compter** : si les usages saturent et qu'un retournement de capital gèle l'investissement, les six mois d'avance américaine perdent toute valeur, et la sous-capitalisation européenne devient un non-événement. L'**Europe qui mandate l'interopérabilité** par la loi, transformant son marché de 450 millions d'habitants en levier sans posséder un transistor. Le **coup d'État industriel** : une golden share qui sauve les champions de design avant qu'ils ne partent aux États-Unis. Le **découplage forcé** : si Washington bloque l'accès au frontier, la contrainte produit l'autonomie que la volonté politique n'a pas faite, comme le découplage sino-américain a produit l'écosystème chinois en trois ans. Le **compute citoyen public** qui devient une infrastructure souveraine pour les langues et les données sensibles. Et l'**IA physique** qui déplace le terrain vers les données industrielles européennes, la meilleure fenêtre depuis les modèles de langage.

---

## Le plus gros angle mort

Au bout de toute cette analyse, l'erreur la plus profonde est dans la mesure elle-même. On mesure la souveraineté comme une chaîne d'approvisionnement, et on conclut « vassalité » parce que l'Europe ne fabrique aucun maillon amont. Mais la valeur capturable et défendable n'est pas dans la fabrication, elle est dans le contrôle de la demande, de l'intégration et de la donnée d'usage. Un acteur américain qui domine le modèle, le compute et la fonderie, mais doit passer par des intégrateurs, des données et une conformité européens pour toucher un marché réglementé de 450 millions de personnes, en dépend.

Et il y a une seconde dimension à cet angle mort : aucune analyse ne modélise sérieusement le scénario où la frontière cesse d'avoir une valeur marginale capturable. Si ce jour arrive, tout le « retard » européen devient un non-événement, et la doctrine indispensabilité plus fast-follow plus conformité passe de perdante à suffisante.

La table peut donc être retournée. Mais elle se retourne sur la couche logicielle, où l'Europe peut suivre, et sur l'axe du paradigme suivant et des substrats, où elle a de vraies cartes. Pas sur le mur matériel, qui tient. Et le levier le plus puissant n'est pas une technologie : c'est de cesser de mesurer la souveraineté comme une usine, et de la mesurer comme un robinet et une règle.

[← Sommaire](../README.fr.md) · [Suite : 07 — La couche oubliée →](07-donnees-consentement.md)
