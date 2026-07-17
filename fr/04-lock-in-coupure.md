# 04 — Lock-in et coupure : marché ou fief

[← Sommaire](../README.fr.md) · [← 03 France ou Europe](03-france-europe.md)

Tout le débat sur la souveraineté tourne autour d'un mot mal posé : « l'innovation ». On se demande qui invente le meilleur modèle, qui a le plus gros datacenter. Mauvaise question. La bonne, c'est le coût de sortie. Parce qu'un marché et un fief ne se punissent pas de la même façon. Un marché te punit par un prix moins bon. Un fief te punit par la non-existence. La coupure n'est pas un signal de prix, c'est une excommunication.

---

## Deux coupures réelles, pas deux hypothèses

Le 12 juin 2026, Fable a été désactivé mondialement par décret américain. Mais le précédent le plus parlant est plus ancien et plus brutal. En 2025, le procureur de la Cour pénale internationale, Karim Khan, visé par des sanctions américaines, a vu son compte de messagerie Microsoft coupé. Une institution judiciaire internationale a découvert qu'elle ne possédait pas sa propre existence administrative : elle la loue à un seigneur de cloud soumis au droit extraterritorial américain. Et la leçon de sortie est limpide : la Cour n'a pas migré vers une fonderie européenne, elle a basculé vers OpenDesk, une suite open source. La parade à la coupure ne fut pas du matériel, ce fut du logiciel libre.

C'est la définition même d'un fief. L'outil fonctionne tant que le propriétaire étranger le veut bien.

## Le cadre juridique : le robinet est à Washington

Le CLOUD Act de 2018 autorise les autorités américaines à accéder à toute donnée détenue par un prestataire américain, quelle que soit la localisation physique du serveur. La section 702 du FISA va dans le même sens. Et les offres estampillées « cloud souverain » (l'AWS European Sovereign Cloud, la Microsoft EU Data Boundary) ne neutralisent pas cette portée tant que l'entité reste sous contrôle américain. Devant le Sénat français, un dirigeant de Microsoft France a admis ne pas pouvoir garantir que les données européennes échapperaient à une réquisition américaine.

La dépendance est massive : AWS, Azure et Google captent environ 70 % du marché cloud européen, quand les fournisseurs européens sont retombés autour de 15 %, contre 29 % en 2017. La souveraineté de données recule pendant qu'on en parle.

## Reconnaître un fief : un seul test

La grille la plus utile n'est pas technique, elle est politique. Pour savoir si une infrastructure est un outil ou un fief, une seule question : peuvent-ils te couper, et la coupure serait-elle catastrophique ? Si oui, ce n'est pas un outil, c'est un fief. Un outil, on le quitte. Un fief, il te quitte.

Le test s'applique partout. La messagerie d'une institution. Le cloud d'un hôpital. Le rail de paiement Visa ou Mastercard, qui est sans doute la coupure la plus pure de toutes : on ne contrôle pas le robinet. Le Starlink d'un État en guerre, que Musk a bridé puis coupé au-dessus de la Crimée en 2022, décidant seul quelles opérations militaires l'Ukraine avait le droit de mener. À chaque fois, la même structure : la non-coupabilité a été déléguée à un acteur étranger sans aucune redevabilité.

## L'abonnement subventionné : le fief à l'échelle de l'individu

Le test vaut aussi pour le particulier, et c'est là qu'on le voit le moins. Un abonnement à un modèle de pointe se paie aujourd'hui une vingtaine d'euros par mois, mais ce prix ne reflète pas le coût réel de l'inférence. Pour un usage soutenu, la valeur en calcul d'un tel forfait dépasse de loin son prix : des analyses du secteur estiment qu'un abonnement vendu une vingtaine de dollars équivaut, au tarif d'inférence facturé à la requête, à plusieurs centaines de dollars de calcul, et qu'un fournisseur n'atteint l'équilibre que si l'abonné consomme peu. Le service est vendu à perte sur les usages intensifs.

Ce n'est pas une générosité, c'est une tactique de verrou. Le prix bas est financé par le capital pour capter l'usager et installer la dépendance pendant que c'est bon marché. Une fois l'habitude prise, le coût de sortie est constitué : la rareté et la hausse viennent ensuite, et elles ont déjà commencé à se matérialiser dans le prix du matériel (voir [section 01](01-etat-des-lieux.md)). Le fief ne se reconnaît pas seulement à la coupure brutale d'une institution. Il se reconnaît aussi à la subvention douce qui rend un outil indispensable avant d'en révéler le prix.

## Le cas Mistral : la souveraineté conditionnelle, sans procès d'intention

Mistral est l'étude de cas, et il faut le traiter avec justesse, sans en faire un coupable.

La dépendance est réelle et se joue à quatre niveaux simultanés. Les capitaux : des fonds américains importants au tour de table, et ASML devenu premier actionnaire en septembre 2025. L'infrastructure : un partenariat de distribution avec Microsoft Azure, qui a d'ailleurs déclenché un examen de la Commission européenne. Le matériel : des GPU Nvidia, le logiciel CUDA, gravés à Taïwan. La juridiction : le CLOUD Act, qui s'applique aux briques américaines que Mistral utilise. La dépendance est même circulaire : Mistral s'endette de 830 millions d'euros pour acheter du Nvidia, et le monopoleur européen de la gravure finance le champion européen du modèle.

Mais la conclusion honnête n'est pas « Mistral est une imposture ». La façade est dans le discours politique qui survend l'autonomie, pas dans l'entreprise. Mistral fait la seule chose réellement possible : la souveraineté d'usage, via l'open-weight. Aucun acteur européen seul ne peut internaliser la chaîne, c'est structurel, on l'a démontré. Attaquer Mistral, c'est confondre le messager et le système. La souveraineté de Mistral est conditionnelle parce que celle de toute l'Europe l'est.

---

## La leçon : on ne répond pas au féodalisme par le mercantilisme

Si le problème est le coût de sortie, alors la réponse n'est pas de subventionner des fonderies qu'on perdra, ni de bâtir un fief européen où l'on arrivera trop tard. La réponse est d'abolir les coûts de bascule par la loi, et de bâtir de l'infrastructure publique non coupable.

L'argent dépensé à rendre la migration gratuite défait plus de féodalité que l'argent dépensé à construire un meilleur fief. Le féodalisme meurt quand le serf peut partir. C'est tout le sujet de la section suivante : non pas comment posséder la chaîne, mais comment cesser d'être captif.

[← Sommaire](../README.fr.md) · [Suite : 05 — Le pari →](05-pratique.md)
