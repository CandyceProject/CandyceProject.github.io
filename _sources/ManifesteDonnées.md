# Manifeste sur la gestion des données

Le Premier Ministre
[a annoncé](https://www.enseignementsup-recherche.gouv.fr/fr/numerique-educatif-le-premier-ministre-dresse-le-bilan-des-enseignements-de-la-crise-et-presente-des-50939),
le 8 octobre 2021, les résultats des dispositifs de soutien à l’innovation.
Parmi ceux-ci, un programme d'équipements prioritaires et de recherche (PEPR) «
_Enseignement et numérique_ » visant à soutenir l'émergence de nouveaux concepts
et solutions numériques, les expérimenter à différentes échelles et mesurer leur
impact et celui de solutions d'ores et déjà existantes.

C’est dans ce cadre que le projet CANDYCE est mis en œuvre, en vue de «
\*développer une **infrastructure numérique souveraine**, pour le déploiement de
plateformes et de services adaptés aux besoins du scolaire et du supérieur et
permettant de **respecter la confidentialité des données\***».

Le présent manifeste entend répondre à cet appel, affirmer l’exigence des
acteurs impliqués dans sa structuration et son déploiement, et initier une
transparence exemplaire dans la mise en œuvre du projet ainsi que des
traitements de données à caractère personnel.

Le Règlement général sur la protection des données (RGPD), applicable depuis mai
2018, s’impose aux opérateurs européens, et le projet CANDYCE permet d’en
assurer la conformité dès la conception, et par défaut.

Parallèlement s’expriment des besoins et opportunités de valorisation des
données, en particulier des traces d’apprentissage, pour des usages légitimes en
termes de recherche scientifiques (_open science_), ou d’exploitation en vue de
développement de nouveaux services (_open data_).

L’objectif des porteurs du projet est non seulement de respecter le RGPD, mais
en plus de mettre en place les mesures techniques et organisationnelles
permettant d’aller au-delà des exigences communautaires, avec une gouvernance
adaptée, éthique et pédagogue, pour considérer les enjeux de protection de la
vie privée et d’acculturation des utilisateurs, ainsi que les enjeux de
valorisation de la donnée :

## 1. Structuration et gouvernance

Le projet s’appuie sur deux grands principes du RGPD **privacy by design et
privacy by default** (protection de la vie privée dès la conception et par
défaut).

Cette logique s’appuie sur des acteurs experts dans le domaine, issus de la
sphère publique (INRIA, Paris Saclay, FUN), du secteur privé <!--(QuantStack,
Hestia)!--> et entend bénéficier des retours de la société civile et des personnes
concernées. Y participent différents profils complémentaires, tels que des enseignants-chercheurs,
enseignants, chercheurs, développeurs, entrepreneurs, responsables des données, data
engineer, délégués à la protection des données,…

Ces experts de terrain mettent en œuvre la **commande politique et
stratégique**, en veillant à son application éthique, tant dans le choix des
technologies utilisées (logiciels, normes, protocoles,…) que des sous-traitants
éventuels, et des mesures techniques et organisationnelles.

Ces experts encadrent notamment, au sein d’un Comité idoine, les conditions de
traitements de données à caractère personnel réalisés dans le cadre du projet
(pour son déploiement, son fonctionnement, l’analyse de sa performance et son
optimisation), mais également les conditions d’exploitation des données, leur
interconnexion ou transfert pour des finalités connexes (recherche
universitaire, _opendata, data mining_,…).

## 2. Conformité RGPD

Les traitements de données sont réalisés de telle manière qu’ils respecteront, à
chaque étape, les exigences du Règlement, tel que sommairement rappelés à
travers des grands principes qui s'ajoutent aux 2 principes évoqués plus haut) :

### La finalité du traitement

Les données à caractère personnelles ne seront traitées que pour les seules
finalités permettant de fournir le service aux utilisateurs (élèves, étudiants,
enseignants) et, à travers des données agrégées, monitorer et optimiser ledit
service.

Toute autre utilisation, sous réserve d’une information claire et d’un accord de
l’utilisateur, ne pourra que :

- nécessiter des conditions de pseudonymisation et des mesures techniques et
  organisationnelles adaptées, dans le cas de recherches universitaires, tel que
  prévu par le Règlement et encadré par la législation nationale ;
- porter que sur des données strictement anonymisées en vue de l’alimentation
  d’entrepôts de données.

### La proportionnalité des données traitées

Seules les données strictement nécessaires à l’usage considéré ne devront
pouvoir être traitées. Les données qui ne remplissent pas cette condition ne
pourront qu’être sollicitées avec une information spécifique sur l’usage
envisagé, et le rappel du caractère facultatif de la collecte.

Incidemment, les données effectivement nécessaires à l’usage du service
s’appuieront sur les mécanismes existants et éprouvés (_single sign-on_, GAR,
fédération d’identité, OAuth, CAS, _learning tools interoperability_,…)
permettant de simplifier l’expérience utilisateur et, par leur paramétrage, de
minimiser les données collectées.

### La durée de conservation

La plateforme devra prévoir un mécanisme de suppression des données selon
différentes situations :

- à la demande de l’utilisateur, dans la limite des autorisations dont il
  dispose au regard de son profil et de la base légale qui a fondé le traitement
  (un étudiant, par exemple, ne pourra pas supprimer son compte si celui-ci lui
  est nécessaire aux activités scolaires durant l’année) ;
- après un certain temps d’inactivité.

### La sécurité des données

Les données, y compris les données à caractère personnel, seront sécurisées par
des mesures techniques à l’état de l’art et adaptées au niveau de sensibilité
des données, en utilisant par exemple le chiffrement dès que celui-ci est
possible techniquement et fonctionnellement -sur les protocoles, données
stockées et en transit-, des conditions d’authentification robustes, la
normalisation des traces générées,…

Elles seront également sécurisées par des mesures organisationnelles adaptées
(réalisation d’une analyse d’impact sur la protection des données (AIPD),
homologation au Référentiel Général de Sécurité (RGS), revue des habilitations,
contrats de sous-traitance éventuels, bridage des exports comportant des données
à caractère personnel, paramétrage strict des API,…).

### La transparence et les droits des personnes

Le projet intègre une forte **logique de transparence**, au vu de sa démarche
d’ouverture (_open source, open data, open science_) et de la possibilité donnée
de contribuer à l’acculturation des utilisateurs aux enjeux de protection des
données.

Dans ce cadre, les différentes étapes de structuration et fonctionnement du
projet ont vocation à être documentées et publiées : cela concerne l’ouverture
du code, la transparence des algorithmes, mais également les documentations
juridiques et techniques dès lors qu’elles ne portent pas atteinte à la sécurité
des systèmes d’information ou aux droits des tiers.

A titre d’exemple, l’analyse d’impact sur la protection des données a vocation à
être diffusée, mais certains éléments de sécurité pourraient être l’objet d’une
diffusion restreinte. De la même manière, les éventuels contrats de
sous-traitance n’auront pas vocation à être diffusés.

Cet objectif de transparence recouvre également un objectif de littératie
numérique, qui doit donc être recherché à travers une documentation complète
mais également adaptée pour être appréhendable aux différents profils
d’utilisateurs.

Dans le cadre de l’utilisation du service, la transparence permettra aux
étudiants et enseignants de comprendre les flux de données, leur devenir, et la
façon d’**exercer simplement leurs droits**.

## 3. Au-delà du RGPD

En complément de la conformité RGPD au sens juridique et technique, le projet
vise à **contribuer au débat public** et **promouvoir une approche éthique**.

La démarche éthique s’exprime en particulier par l’axe de la transparence, via
l’ouverture du code informatique et de la documentation, mais également avec un
souci de pédagogie et d’explicabilité des traitements de données.

Elle s’exprime également par la ré-affirmation des principes de _privacy by
design et privacy by default_, dans ce projet qui est l’occasion de montrer
qu’ils sont conciliables avec les objectifs d’ouverture et de valorisation des
données.

Ainsi, si le principe cardinal du projet pourrait être celui de la science
ouverte, « _aussi ouverte que possible, aussi fermé que nécessaire_ », la
prévalence de la protection sera garantie dans les cas où les deux objectifs se
révèlent inconciliables, ainsi que dans les cas où l’éthique le justifie.

Dans ce contexte, la mise en œuvre du projet **s’appuiera également sur les
publications et recherches universitaires** en cours, pour limiter l’impact de
l’usage des données d’apprentissage, par exemple en renonçant à leur
exploitation même lorsque celle-ci est techniquement et juridiquement possible
(cf. la notion de «
_[bienveillance algorithmique](https://journals.openedition.org/dms/4086)_ »
énoncée par le Loria).

De la même manière, les API visant à permettre l’interconnexion de la plateforme
avec d’autres systèmes d’information ou des entrepôts de données seront
**volontairement paramétrées afin d’interdire tous transferts** qui pourraient,
par recoupement, présenter des
[risques de réidentification](https://www.nature.com/articles/s41467-019-10933-3).
