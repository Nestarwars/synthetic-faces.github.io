---
title: "Interview de Cédric Thebault et Kelian Baert"
collection: interviews
type: "interviews"
permalink: /interviews/ThebaultBaert
---

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
