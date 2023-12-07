---
title: "Interview de Cédric Thebault et Kelian Baert"
collection: interviews
type: "interviews"
permalink: /interviews/ThebaultBaert
---
*Interview conduite en visio le 5 décembre 2023, au siège de Technicolor Creative Studios à Paris, par Nestor Laborier. Il est ingénieur photonicien, et ancien stagiaire chez Technicolor, avec Kelian Baert et Cédric Thébault, sur les sujets de génération de visages synthétiques.*


***Cédric Thébault*** :
Je suis Cédric Thebault, chercheur chez Technicolor depuis 3 ans. Mon travail consiste à développer des outils pour les effets spéciaux utilisés au cinéma. Nous utilisons des méthodes de machine learning et de computer vision.

***Kelian Baert***:
Je suis Kelian Baert, et je travaille dans la même équipe que Cédric depuis un an et demi. Nous travaillons sur les mêmes problématiques liées aux effets spéciaux pour le cinéma. Pour ma part, j'ai entamé une thèse et je suis actuellement étudiant au sein de cette équipe. Ma recherche se concentre sur les problématiques liées à l'édition de visages dans le contexte du cinéma et des effets visuels. Cela inclut des aspects tels que le remplacement spécifique de visages, que ce soit pour le vieillissement ou le rajeunissement d'acteurs, ou encore la substitution du visage d'une doublure sur celui d'un acteur, et d'autres problèmes similaires.

***Nestor Laborier***:
Dans votre domaine respectif, quel est votre rapport aux bases de données en tant qu'objet, et comment interagissez-vous généralement avec ces bases de données?

***K.B*** :
Pour moi, le rapport aux bases de données est souvent crucial pour résoudre efficacement les problèmes. Si nous n'avons pas accès à des données, nous sommes non seulement limités dans nos actions, mais aussi dans nos possibilités d'imaginer des solutions. Les données sont la base de la plupart des méthodes que nous utilisons, surtout dans le domaine de l'apprentissage automatique et de la vision par ordinateur.

Souvent, la collecte de données massives est difficile, et nous ne pouvons pas simplement créer une base de données nous-mêmes en raison du volume important d'informations nécessaires. Donc, l'absence de données peut être un obstacle majeur, mais si nous avons des données, cela ouvre la porte à de nombreuses possibilités.

***N.L***:
Donc on peut considérer les bases de données comme une ressource naturelle dans ce domaine ? Si elles sont disponibles, elles offrent des opportunités considérables. En revanche, si elles font défaut, cela crée des problèmes significatifs ?

***C.T***:
Oui, c'est tout à fait juste. Les bases de données sont effectivement un élément crucial qui peut soit limiter, soit ouvrir des possibilités dans le développement de nos méthodes. Leur disponibilité et leur variété sont essentielles pour garantir que nos méthodes soient suffisamment générales et capables de fonctionner correctement sur l'ensemble des données que nous souhaitons traiter. En résumé, l'importance des bases de données réside dans leur capacité à définir la portée et l'efficacité de nos méthodes.

***N.L***:
Dans votre domaine, est-ce plus crucial d'identifier les bonnes données ou de concevoir des algorithmes efficaces ? Comment gérez-vous l'équilibre entre votre expertise algorithmique et votre compétence dans la recherche, la compréhension et la sélection des données nécessaires ?

***K.B***:
Les deux aspects sont étroitement liés. En réalité, nous ne pouvons pas tout traiter ni tout faire. Il est impératif de savoir quels types de données sont accessibles, quelles bases de données nous pouvons construire ou utiliser pour nos travaux. Certaines tâches sont tout simplement impossibles sans les données nécessaires. Ainsi, si nous ne disposons pas des données adéquates, nous ne pouvons pas développer de méthodes efficaces.

C'est pourquoi, pour nous, il est crucial, dès le départ, d'avoir accès à des données de qualité pour orienter nos méthodes. En ce qui concerne la recherche de données, dans notre contexte, nous ne sommes généralement pas confrontés à la recherche d'une base de données miraculeuse, cachée ou publiée gratuitement. Dans le contexte industriel, notamment pour mon travail de thèse, nous devons travailler avec des données adaptées à un cadre commercial.

De plus, dans le domaine du cinéma et des effets visuels, nous sommes souvent confrontés à des données pour lesquelles nous n'avons pas le droit de publier librement. En général, les bases de données capables de résoudre nos problèmes sont connues, et nous n'allons pas souvent à la recherche de la base de données parfaite, car il y en a relativement peu. En travaillant longtemps dans un domaine, nous finissons par connaître celles qui sont disponibles, variées et utilisables.

***N.L***:
Avez-vous déjà été confronté à la nécessité de construire une base de données parce que celle-ci faisait défaut pour répondre à votre cas d'usage ? Peut-être parce que vous aviez déjà une base de données qui ne correspondait pas tout à fait à vos attentes ?

***K.B***:
Personnellement, je n'ai jamais eu à construire une base de données moi-même. J'ai eu des collègues qui l'ont fait, mais ce n'est pas quelque chose que j'ai expérimenté directement avec des données réelles. Il y a deux approches distinctes à considérer.

D'une part, il y a l'idée de créer entièrement sa propre base de données, en partant de zéro. Par exemple, si l'on cherche une base de données d'images, on peut sortir l'appareil photo, se rendre à l'extérieur et prendre des photos. Dans le contexte des visages, cela pourrait impliquer de se rendre en studio, d'inviter des personnes avec du matériel professionnel, et de scanner les visages, entre autres. Personnellement, je n'ai pas eu à entreprendre ce type d'initiative jusqu'à présent, mais j'ai observé des collègues et d'autres étudiants tenter des choses similaires.

D'autre part, il y a l'approche consistant à récupérer ou agréger des données existantes. Cette méthode peut être plus ou moins complexe en fonction du cas. Souvent, lorsque nous agrégeons des bases de données, elles ne présentent pas exactement les mêmes données, et nous devons soit interpoler certaines informations, soit nous contenter d'un sous-ensemble des données que nous souhaiterions avoir. Dans le domaine des visages en 3D, par exemple, nous pouvons être amenés à utiliser plusieurs bases de données pour obtenir une variété plus importante. Cependant, la qualité des données peut varier en termes de résolution d'image ou de résolution des maillages en 3D.

Dans mes études, il m'est arrivé de devoir récupérer des données en faisant du scraping, mais cela n'était pas destiné à un usage commercial. Dans ces cas-là, nous avons plus de liberté pour collecter ces données. Cependant, obtenir quelque chose de cohérent peut être compliqué. En général, la solution la plus simple est de trouver une source de données existante qui permet déjà de travailler, avant d'envisager de créer une base de données plus complexe en agrégeant d'autres sources.

***N.L***:
C'est donc peut-être dans ce cas là qu'on en vient à réfléchir à générer des bases de données synthétiques ? Quels en sont les avantages ?

***C.T***:
Le principal avantage pour nous d'avoir une base de données synthétique réside dans notre capacité à exercer un contrôle total. Nous pouvons gérer simultanément la diversité des données, en nous assurant d'inclure une grande variété de caractéristiques. Plus spécifiquement, notre objectif était d'obtenir une base de données de visages représentant une diversité en termes de morphologie, d'ethnicité (couleur de peau), de forme de visage, et même de genre. Nous avons pu tirer profit de la diversité présente dans la base de données de Microsoft, incluant une grande variété de coiffures, de styles, et représentant une diversité sociale.

Notre base de données synthétique nous a également offert une flexibilité par rapport aux bases de données classiques de photos disponibles sur Internet. En effet, ces bases de données présentent souvent des biais importants, tant au niveau des représentations des populations que des contraintes inhérentes aux poses et expressions. Les photos disponibles sur Internet sont souvent biaisées avec des gens souriants, faisant face à la caméra, ce qui ne correspondait pas à nos besoins spécifiques. La base de données synthétique nous a permis de contourner ces problèmes, en nous offrant naturellement une plus grande diversité en termes d'expressions et de poses. Construire une base de données réelle avec des photos aurait été coûteux et aurait entraîné des difficultés liées à la diversité naturelle des expressions et poses que nous recherchions.

***K.B***:
Cela nous offre également un accès complet à toutes les informations dont nous pourrions avoir besoin pour l'entraînement. Par exemple, si nous voulons apprendre à segmenter un visage, c'est-à-dire à reconnaître, sur des images d'entrée, toute la zone correspondant au visage et à éliminer l'arrière-plan, même avec des milliers ou des centaines de milliers de données réelles, il serait nécessaire que quelqu'un les annote. Annoter les données signifie que quelqu'un indique précisément les pixels correspondant à la zone du visage pour chaque image. Cela est essentiel pour les apprentissages supervisés.

En revanche, avec une base de données synthétique, notamment en 3D, on peut créer des rendus 3D de visages avec la zone correspondant au visage explicitement définie. Cela nous permet d'obtenir cette information directement, sans avoir besoin de passer du temps sur des données réelles à récupérer des annotations. Cette approche n'est pas limitée à la segmentation du visage ; elle peut être appliquée à de nombreuses autres caractéristiques. Ainsi, les bases de données synthétiques nous évitent non seulement de devoir collecter des annotations sur des données réelles, mais elles nous permettent aussi de contourner les biais potentiels liés à ces annotations.

Dans tous les domaines, l'utilisation de bases de données synthétiques offre un contrôle total sur les informations présentes dans ces données, tout en permettant de récupérer davantage d'informations. De plus, cela évite les biais introduits par les annotations humaines, car la machine donne les informations telles qu'elles ont été construites.

***N.L***:
Y aurait-il par hasard des risques associés aux bases de données synthétiques, risques qui pourraient différer de ceux présents dans les bases de données traditionnelles collectées à partir de données réelles ?

***K.B***:
Le risque principal c'est d'avoir une base de données qui s'éloigne trop de la réalité. En fin de compte, un algorithme peut être parfaitement capable de fournir des prédictions précises pour des données appartenant à la distribution de la base de données synthétique, atteignant même une précision de 100 %. Cependant, lorsqu'on lui présente des données réelles auxquelles il n'a jamais été exposé, l'algorithme peut avoir du mal à généraliser.

En travaillant avec des données synthétiques, l'objectif est généralement de pouvoir généraliser à des données réelles, en supposant que les données synthétiques soient suffisamment proches de la réalité. Cette notion de risque peut être étendue à d'autres domaines où des données sont collectées dans des conditions contrôlées, que ce soit en studio dans le contexte du cinéma, ou même dans des domaines comme l'aéronautique, où des données peuvent être recueillies dans un tunnel aérodynamique, par exemple. Il est crucial de s'assurer que les conditions réelles reflètent suffisamment les informations présentées à l'algorithme, afin d'éviter des surprises lorsque l'algorithme est confronté à des données totalement nouvelles. C'est là le principal défi auquel nous pourrions être confrontés.

***C.B***:
En ce qui concerne la construction des bases de données synthétiques, il existe des problématiques liées à la diversité. En théorie, on pourrait viser une très grande diversité, mais cela dépend des outils utilisés pour générer ces données. Par exemple, si l'on utilise un modèle morphable qui construit lui-même une base de visages à partir de données existantes, les biais présents dans la construction initiale de cette base de visages seront également présents dans le modèle morphable résultant. Ainsi, bien que l'on puisse viser des morphologies diverses, on peut finalement être limité par les biais présents dans la construction initiale, et ne pas pouvoir exprimer toute la diversité réelle souhaitée

***N.L*** :
Il existerait donc un risque de transmission de biais depuis l'étape de production ? Comme cette transmission de biais se produit dans une étape plus éloignée, au cours de la génération de données, il est possible que l'on en prenne moins conscience par rapport à une base de données réelle ?

***C.B***:
Dans une base de données réelle, les biais sont souvent plus facilement identifiables, peut-être plus visibles, alors que dans une base de données synthétique, en particulier en ce qui concerne les morphologies, il peut être très difficile de déterminer si la diversité est suffisante ou non.

***N.L***: Au delà des questions de performances et de généralisation de ces bases de données, y aurait-il des spécificités éthiques à utiliser des données synthétiques plutôt que des données réelles ?

***K.B***:
Cela dépend vraiment des cas. Si une base de données est entièrement générée de manière synthétique, ce qui est rarement le cas en réalité, alors, du point de vue éthique, on ne rencontre généralement pas de problèmes liés aux droits sur les données, tels que les droits à l'image ou les licences. Bien sûr, cela suppose que l'on utilise des logiciels pour lesquels on dispose des licences nécessaires et des droits d'utilisation.

Cependant, il est rare d'être en mesure de créer une base de données synthétique à partir de zéro. Souvent, cela repose sur des modèles génératifs qui sont une simplification de la réalité. Dans le contexte du visage, cela peut être basé sur des modèles morphables de visage de qualité inférieure à ce que l'on souhaite obtenir à la fin. Malgré cela, on a besoin de cette source d'information au début.

Dans ces cas, on déplace en fait le problème, car si le modèle génératif de base avait été créé à partir de données sous une licence non permissive, on ne fait que propager ces problèmes de licence en amont. Aujourd'hui, la législation sur ce sujet n'est pas forcément très claire, mais en général, il n'est pas permis d'utiliser des données ou un modèle qui a été créé à partir de données dont on ne détient pas les droits pour effectuer quelque chose par la suite. Ainsi, ces problèmes peuvent se propager tout au long du traitement des données.

Je pense que la question est vraiment complexifiée par le fait que nous travaillons sur des humains. Il y a des aspects liés au droit à l'image, à la propriété privée et intellectuelle, ainsi qu'à la sécurité des données. Pour constituer une base de données importante de visages, il est souvent nécessaire de récupérer des données à partir de sites web, de réseaux sociaux ou d'autres plateformes où les gens partagent des photos, mais pas nécessairement dans le but spécifique pour lequel nous les utilisons.

Si l'on examine les bases de données les plus exploitées pour l'apprentissage sur les visages, ce ne sont pas des personnes qui ont été informées au préalable que leurs photos seraient utilisées à des fins de traitement. Ces données sont collectées après coup, car il en faut des dizaines, voire des centaines de milliers, et il serait impossible de les obtenir du jour au lendemain avec un simple appareil photo tout en garantissant la diversité nécessaire.

***C.T***:
Un autre aspect éthique, distinct de celui mentionné précédemment, concerne la génération des données et des annotations. Dans notre cas, nous utilisons une base de données entièrement statistique, où la génération des annotations représente une vérité de terrain directe, car nous savons comment les données ont été générées. En revanche, si l'on parle de données réelles que l'on souhaite annoter, cela nécessite l'intervention d'un être humain pour effectuer les annotations. Cela soulève des questions sur qui effectue ces annotations, dans quel contexte cela se produit, et comment on peut exploiter une base de données lorsque l'on n'a pas d'informations détaillées sur la manière dont les annotations ont été réalisées.

J'ai déjà vu des publications où les services d'Amazon, tels que Mechanical Turk, étaient utilisés pour sous-traiter ces annotations. Cela permet de 'louer' des personnes qui consacrent un certain temps à ces annotations et qui sont rémunérées en échange. Cependant, cela pose des questions sur la qualité des données, car la motivation de la personne annotant peut être influencée par la rémunération. Par exemple, si quelqu'un est payé 10 € pour chaque 100 images annotées, sa priorité pourrait être d'aller rapidement plutôt que de produire des annotations parfaites. Dans ce contexte, des mesures sont souvent mises en place sur Mechanical Turk pour éviter que les annotateurs produisent des résultats de faible qualité. Ces mesures peuvent inclure la vérification des annotations par rapport à une référence attendue, et en cas de différences significatives, l'annotateur peut être rejeté et ne peut plus participer à l'annotation.
Il y a un gros marché du travail qui est lié à ça, notamment avec Mechanical Turk.

***N.L***:
Est-ce que vous avez l'impression, dans le milieu de la vision par ordinateur, plus spécifiquement dans le domaine du cinéma, qu'il y a une attirance croissante pour ces bases de données générées, précisément en raison de leur caractère maîtrisé et peut-être plus éthique, du moins affiché ? Est-ce qu'il y a un intérêt plus marqué pour ces bases de données récemment, une tendance en cours ?

***K.B***:
Je pense qu'on en voit plus en ce moment, en tout cas dans le milieu académique. On observe des publications qui se basent sur des données synthétiques. C'est souvent utilisé pour évaluer les méthodes, même si la méthode n'est pas forcément entraînée sur ces données. On peut s'en servir pour évaluer un algorithme, car on a toutes les informations. Par exemple, si on développe un algorithme visant à estimer la direction du regard d'une personne, on peut essayer de prédire cela sur des données synthétiques pour lesquelles on a exactement la bonne réponse. Cela permet de visualiser rapidement à quel point l'algorithme se trompe ou non, et cela peut aussi permettre de quantifier si notre algorithme est correct sur des données bien spécifiques. Par exemple, si nous ne savons pas si notre algorithme de prédiction du suivi du regard fonctionnera bien sur des données floues, nous pouvons prendre des données synthétiques ou même des données réelles que nous allons transformer avec un flou, puis essayer de relancer l'algorithme de cette manière. Ainsi, on peut utiliser des données entièrement synthétiques comme un benchmark.

***C.T***:
C'est ce qu'on voit le plus en tout cas, surtout dans le milieu académique. Pour ma part, du côté industriel, c'est difficile d'identifier des tendances, car tout évolue tous les 6 mois, voire moins. J'aurais tendance à dire que cela se répand, notamment en observant le nombre de sociétés qui se créent pour développer des bases de données artificielles, notamment pour les visages, comme le fameux DataGen, entre autres. Je pense qu'il y a un vrai marché derrière tout ça, et ce marché émerge parce que les données produites deviennent meilleures, notamment avec l'avènement de méthodes génératives permettant d'obtenir des résultats de plus en plus réalistes. Je pense que ce type de base de données sera de plus en plus courant, surtout dans le domaine des visages. Si l'on voulait construire nous-mêmes une base de données de visages dans le contexte actuel, en particulier avec le RGPD, cela serait assez compliqué. Normalement, pour inclure des personnes dans une base de données, il faut obtenir leur accord, et il faut pouvoir maintenir cette base de données. Si une personne demande à ne plus être présente dans cette base de données, elle a le droit de demander son retrait. Il faudrait mettre à jour la base de données, la suivre, traquer où elle a été utilisée, et tout cela devient très complexe dans le cadre du RGPD.

***N.L***: Il n'y aurait pas non plus une question de droits d'auteur là dedans ?

***K.B***: Je pense qu'il faudrait faire un micro-trottoir là-dessus, demander aux gens. Globalement, je pense que tout le monde est d'accord pour dire que le droit d'auteur est primordial, et c'est quelque chose de super important pour tous. Je me trompe peut-être, mais j'ai l'impression que c'est quelque chose qui est assez accepté, pas par tout le monde, mais par la plupart. Je pense que les gens voient l'intérêt du droit d'auteur quand même, au moins un minimum. Par contre, je pense aussi que, en fait, on aime bien avoir ces outils. Globalement, si tu faisais un référendum global sur 'est-ce que les droits d'auteur et l'application correcte des droits d'auteur sont plus importants que d'avoir à disposition ChatGPT, Stable Diffusion, et tous ces outils', enfin, je crois connaître la réponse. Il y a vraiment un sujet là dessus !