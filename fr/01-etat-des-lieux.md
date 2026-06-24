# 01 — État des lieux : les quatre couches de dépendance

[← Retour au sommaire](../README.md)

La souveraineté en intelligence artificielle n'est pas un objet. Ce n'est pas « un modèle » qu'on posséderait ou pas. C'est une pile, une chaîne de couches empilées, et chacune a son propriétaire, sa géographie, sa vulnérabilité. Pour savoir où l'Europe est libre et où elle est captive, il faut décomposer cette chaîne et poser à chaque étage deux questions simples : qui fait la loi, et qui peut couper l'accès ?

On va les parcourir de la couche la plus réversible à la couche la plus verrouillée. Ce n'est pas un détail d'ordre : c'est le cœur de l'analyse. Là où le verrou est faible, l'Europe a des leviers. Là où il est physique, aucune volonté politique ne le desserre à court terme.

---

## Couche 4 (la plus réversible) — Les modèles et le logiciel

C'est ici qu'on regarde toujours, et c'est ici que la dépendance est la moins grave.

Au 14 juin 2026, aucun modèle européen n'est à la frontière mondiale. Le haut du tableau est tenu par Claude, GPT-5.5 et Gemini 3.1. Mistral, le champion européen, a levé de l'ordre de 4 milliards de dollars cumulés, à comparer aux quelque 186 milliards d'OpenAI et 125 milliards d'Anthropic. L'écart de capital est d'un facteur quarante à cinquante.

Mais ce retard est largement un faux problème, et il faut le dire précisément pour ne pas se tromper de combat. D'abord parce que la couche modèle se commoditise : distillation, mélange d'experts, quantization, recettes d'entraînement publiques font tomber l'écart avec la frontière à environ dix points et trois à six mois, pendant que le coût par token chute d'un facteur dix par an. La preuve a contrario est juridique : faute de barrière technique durable, les États-Unis défendent désormais leur avance par le droit. Ensuite parce que la mesure brute trompe : Mistral Large 3 affiche 43,9 % sur le benchmark de raisonnement GPQA Diamond, mais en mode standard, sans raisonnement activé ; ses variantes de raisonnement referment largement l'écart. Mistral ne se compare d'ailleurs pas aux modèles fermés américains mais à ses pairs ouverts, DeepSeek ou Kimi.

Le vrai levier de cette couche, c'est l'open-weight. Les modèles de Mistral sont sous licence libre Apache 2.0 : on peut les inspecter, les ajuster, les exécuter hors-ligne, en air-gap. C'est une souveraineté d'usage réelle, et c'est précisément ce qui rend immunisé contre une coupure d'API à distance, comme celle qui a frappé Fable le 12 juin. Les armées françaises ne s'y sont pas trompées : un accord-cadre signé le 8 janvier 2026 déploie Mistral en environnement isolé, données exclues de l'entraînement.

Deux réserves, cependant. La première : l'open-weight mondial est dominé par la Chine, pas par l'Europe (DeepSeek, Qwen trustent les classements ouverts). La seconde, plus profonde : cette souveraineté logicielle ne franchit jamais le mur matériel des couches du dessous. Un modèle libre tourne quand même sur des GPU Nvidia, via le logiciel propriétaire CUDA, gravés à Taïwan. Pire, la dépendance est circulaire : ASML, le monopoleur européen des machines de gravure, est devenu en septembre 2025 le premier actionnaire de Mistral, qui s'endette par ailleurs de 830 millions d'euros pour acheter des puces Nvidia. Le champion de la souveraineté européenne approfondit la dépendance américaine en même temps qu'il l'incarne.

---

## Couche 3 — Le compute et l'électricité

L'Europe pèse environ 5 % du compute IA mondial, contre 70 à 80 % pour les États-Unis et 11 % pour la Chine, et cette part baisse depuis le début 2025.

Mais le vrai goulot d'étranglement n'est plus le capital. L'argent privé existe (plus de 200 milliards d'euros d'intérêt exprimé). Ce qui bloque, c'est le **raccordement au réseau électrique** : sept à treize ans de file d'attente en moyenne sur les grandes places européennes, pour une électricité industrielle environ deux fois plus chère qu'aux États-Unis. Le Danemark l'a prouvé brutalement en mars 2026 : son gestionnaire de réseau a dû imposer un moratoire de trois mois sur les nouvelles connexions, avec 60 GW de demandes en attente pour un pic national de 7 GW. Même la grille la plus propre d'Europe sature.

C'est ici qu'on cite le nucléaire français comme atout souverain, et il faut être précis pour ne pas mentir. Oui, la grille française est parmi les moins carbonées au monde, autour de 20 à 27 gCO2 par kWh selon les années (21,7 g en 2024 selon RTE), juste derrière la seule Norvège en Europe. Mais « faible intensité carbone » ne veut pas dire « propre » ni « souverain » :

- ce n'est pas propre : déchets de haute activité dangereux sur des dizaines de milliers d'années, sans stockage géologique profond opérationnel ;
- ce n'est pas pleinement souverain : l'uranium est importé à près de 100 %, du Niger et du Kazakhstan notamment, avec une dimension néo-coloniale assumée ;
- ce n'est pas insensible au climat : les réacteurs se brident l'été quand les fleuves sont trop chauds, et leur chaleur perdue est elle-même une pollution thermique locale.

C'est un avantage réel d'intensité carbone, à ce titre seulement. Un avantage de fond, pas encore activé, et certainement pas un blanc-seing écologique.

Côté infrastructure, les gigafactories européennes (le plan EuroHPC, environ 20 milliards d'euros pour quatre à cinq sites) n'ont, à la mi-2026, aucune date de sélection confirmée et aucun site financé. Le seul supercalculateur exascale européen, JUPITER à Jülich, tourne à 100 % sur des GPU Nvidia.

---

## Couche 2 — La mémoire HBM et les matériaux critiques

C'est une couche dure, et l'Europe y est absente.

La mémoire à haute bande passante (HBM), indispensable aux puces IA, est un oligopole asiatique et américain : SK Hynix autour de 62 %, Micron 21 %, Samsung 17 %, et 0 % européen. Toute la production 2026 est déjà vendue, sous contrats non annulables, avec une pénurie qui s'étend jusqu'en 2027 et au-delà.

Les matériaux sont pires encore, parce qu'ils sont déjà transformés en arme. La Chine fournit environ 98 % des terres rares et 71 % du gallium importés, et contrôle 60 % de l'extraction mondiale et 90 % du raffinage. Sa règle extraterritoriale dite des 0,1 %, entrée en vigueur le 1er décembre 2025, étend ce contrôle à tout produit contenant ces matériaux ; Pékin l'a suspendue pour un an (novembre 2025 à novembre 2026) dans le cadre d'une trêve commerciale, ce qui ne désarme rien mais confirme que le robinet est politique et peut être rouvert à tout moment. Le prix du gallium a augmenté de 365 % sur la seule année 2025. Ce n'est pas une dépendance théorique : en avril 2025, des usines occidentales ont été mises à l'arrêt faute d'aimants.

### La pénurie déborde sur le grand public

Cette pénurie ne reste pas confinée aux datacenters. En réallouant leurs capacités vers la mémoire haute bande passante et les serveurs IA, les fondeurs ont raréfié la mémoire ordinaire, et le prix a suivi. Sur les contrats, la DRAM a bondi de l'ordre de 90 % sur le seul premier trimestre 2026 ; au détail, des modules DDR5 ont vu leur prix multiplié par trois à quatre entre l'automne 2025 et la fin de l'année. La mémoire haute bande passante dédiée à l'IA absorbe désormais près d'un quart de la production de galettes DRAM.

Il faut le formuler sans exagérer, car le chiffre est ici un argument, pas un slogan : on parle d'un facteur trois à quatre sur certains produits et sur une fenêtre précise, pas d'un facteur vingt. Mais la conséquence politique est claire. Quiconque achète un ordinateur en 2026 paie une prime de rareté indirectement causée par la demande des datacenters. C'est une taxe matérielle, invisible et non votée : la couche la plus industrielle de la pile, la mémoire, se répercute jusque dans le portefeuille de l'acheteur individuel, qui finance malgré lui la course au compute.

---

## Couche 1 (la plus verrouillée) — La fonderie de pointe et l'EUV

On arrive au mur, et au paradoxe central de toute cette histoire.

Le mur, c'est que l'Europe ne grave aucune puce de pointe. Son nœud le plus avancé est le 18nm FD-SOI de STMicroelectronics à Crolles, soit plusieurs générations derrière les 3 et 2 nanomètres où se jouent les puces IA. Le bilan industriel est cruel : le Chips Act de 2022 va manquer son objectif phare (la Cour des comptes européenne projette 11,7 % du marché mondial en 2030, contre une cible de 20 %), et le méga-projet d'Intel à Magdebourg, environ 30 milliards d'euros, a été annulé en 2025, les quelque 10 milliards de subventions promises jamais versées. Le Chips Act 2.0, présenté le 3 juin 2026 avec un besoin chiffré à environ 120 milliards d'euros d'ici 2035, ressuscite l'idée d'une fonderie souveraine de pointe, mais c'est une intention politique, pas une obligation juridique, et neuf ans de délai au minimum. Les seuls succès concrets sont hors pointe : Infineon ouvre sa Smart Power Fab à Dresde le 2 juillet 2026 (des puces de puissance, pas de la logique de pointe), et la fonderie ESMC de TSMC, toujours à Dresde, produira en 2027 sur des nœuds matures de 28 à 16 nanomètres.

Le paradoxe, maintenant. L'Europe détient le seul point d'étranglement mondial qui compte vraiment : **ASML**, monopole absolu à 100 % sur les machines de lithographie EUV, sans lesquelles personne au monde, ni TSMC, ni Samsung, ni Intel, ne grave une puce avancée. C'est l'unique maillon où le monde entier dépend de l'Europe, États-Unis compris. Son chiffre d'affaires 2026 est attendu entre 36 et 40 milliards d'euros, ses machines High-NA de nouvelle génération coûtent 350 à 400 millions d'euros l'unité.

Et pourtant l'Europe ne peut pas convertir ce monopole en souveraineté. Parce que les machines d'ASML partent chez TSMC, Samsung, Intel, jamais vers une fonderie européenne de pointe. L'Europe vend l'outil qui fabrique la puissance des autres, tout en restant dépendante de cette puissance. Elle tient le couteau le plus précieux de la chaîne, et ne sait pas forger.

---

## Ce qu'il faut retenir de l'état des lieux

Quatre couches, une logique unique. Plus on descend, plus le verrou se durcit, et plus l'Europe est captive :

| Couche | Verrou | Position européenne |
|--------|--------|---------------------|
| Modèles / logiciel | Faible (se commoditise) | Retard réel mais rattrapable ; l'open-weight est un vrai levier d'usage |
| Compute / électricité | Moyen (réseau, énergie) | ~5 % du compute mondial ; le nucléaire est un atout bridé, pas une victoire |
| HBM / matériaux | Dur (oligopole, arme chinoise) | 0 % européen, déjà sous pression |
| Fonderie / EUV | Physique (8 à 12 ans) | Aucune fab de pointe ; le paradoxe ASML |

Et il faut anticiper une mécanique qui reviendra tout au long de ce document : **chaque nouveau front technologique ajoute des couches de dépendance plutôt qu'il n'en retire.** La robotique empile une dépendance aux aimants et aux moteurs chinois par-dessus la dépendance aux puces. Le spatial empile une dépendance au lancement américain par-dessus la dépendance au silicium. On le verra en détail dans la [section 06](06-ce-qui-peut-retourner-la-table.md). Le verrou matériel n'est pas un point parmi d'autres : c'est le sol sur lequel tout le reste repose.

*Sources détaillées et datées dans [`SOURCES.md`](../SOURCES.md).*

[← Retour au sommaire](../README.md) · [Suite : 02 — Horizons →](02-horizons.md)
