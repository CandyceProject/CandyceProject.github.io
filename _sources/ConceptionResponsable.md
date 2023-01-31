(ConceptionResponsable)=

# Principes de conception responsable

(ProtectionDonneesUtilisateurs)=

## Protection des données utilisateurs

La politique de protection des données personnelles mise en oeuvre par la
plateforme devra être exemplaire dans son application des grands principes,
notamment de **_proportionnalité_**, de **_confidentialité_**, et de
**_finalité_** de toute collecte et traitement de données utilisateurs, et ce,
quel que soit le rôle de ces derniers : élèves, étudiants, enseignants,
chercheurs, etc.

L'accent sera mis sur la **_transparence_**. Au-delà des droits réglementaires
aux données collectées (accès, modification, suppression, ...), les utilisateurs
auront accès à plusieurs outils leur permettant d'explorer leur propre usage de
la plateforme _via_ un tableau de bord individualisé. Des exemples de notebooks
permettant aux utilisateurs d'analyser leurs propres données seront mis à
disposition sur la bibliothèque de contenus. Ces ressources ont pour but de
favoriser la **_littératie_** du public en termes d'usages de données.

Les développements effectués dans le contexte de Candyce devront garantir la
confidentialité de la plateforme dès la conception ("**_privacy by design_**")
et par défaut ("**_privacy by default_**"). Par exemple, les traces
d'apprentissage collectées sur l'usage d'une ressource pédagogique ne seront par
défaut accessibles qu'aux personnes concernées, et tout partage en dehors de ce
groupe sera explicite et géré par des jetons d'accès révocables (par
l'établissement, l'académie ou l'utilisateur selon le cas).

La politique de collecte et de protection des données sera garantie par un
_délégué à la protection des données_ (DPD, _data protection officer_, DPO) en
charge du projet.

## Ecoconception du projet

D'après l'ADEME, le numérique représente aujourd'hui environ 4% des émissions
mondiales de gaz à effets de serre, avec une croissance anticipée de 10% par an.
Loin d'être uniquement virtuels, les outils et services numériques ont des
impacts importants sur l'environnement à travers leur matérialité et le
quotidien des humains qui les font vivre. Il est donc indispensable qu'un projet
d'une telle ampleur implémente dès son lancement les grands principes
d'**écoconception de services numériques** afin de réduire au maximum ses
impacts.

Il ne s'agit pas uniquement d'une recherche d’optimisation, d’efficience ou de
performance visant à réduire la consommation énergétique en phase d'usage, mais
d'une réflexion plus globale à tendre vers la sobriété. Il est question d'agir
sur l'ensemble du cycle de vie du service numérique et de l'activité des humains
impliqués dans le projet, tout autant que sur l'usage des technologies. Cette
démarche vise notamment directement ou indirectement à allonger la durée des
vies des équipements numériques, à réduire la consommation de ressources
informatiques et énergétiques des terminaux, des réseaux, des centres de
données, et de l'activité humaine intrinsèquement liée.

Pour se faire, il existe plusieurs ressources de référence sur lesquelles une
telle démarche devra s'appuyer, dont on peut citer comme exemple :

- Le Référentiel Général d'Ecoconception de Services Numériques
  [RGESN](https://ecoresponsable.numerique.gouv.fr/publications/referentiel-general-ecoconception/)
  : il s'agit d'un référentiel constitué dans le cadre de la mission
  interministérielle «
  [Green Tech](https://ecoresponsable.numerique.gouv.fr/a-propos/) » piloté par
  la Direction interministérielle du numérique (DINUM) et le Ministère de la
  Transition Ecologique (MTE), avec la participation de tous les ministères. Il
  a pour ambition d'intégrer le cercle vertueux comprenant les référentiels et
  règlements existants : RGAA pour l’accessibilité, RGS pour la Sécurité, RGI
  pour l’interopérabilité et RGPD pour la protection des données personnelles ;

- Le Guide de Référence de Conception Responsable de Services Numériques
  [GR491](https://gr491.isit-europe.org/) mis en place par l'Institut du
  Numérique Responsable : ce guide contient 491 bonnes pratiques pour
  implémenter 57 recommandations déclinées en 8 grandes familles. Il ne se
  focalise pas que sur les impacts environnementaux, les bonnes pratiques sont
  catégorisées selon les trois piliers du développement durable : l'aspect
  social, l'aspect économique, et l'aspect environnemental.

Néanmoins l'écoconception d'un service numérique est une discipline balbutiante
avec encore beaucoup de zones d'ombre et très peu de retours d'expérience
concrets et chiffrés. Aucun ne porte sur un projet d'une envergure similaire à
la présente proposition. L'implémentation pionnière d'une telle démarche est
donc l'opportunité de produire un contenu permettant d'enrichir la connaissance
globale, la compréhension du sujet et la création de données pour la recherche
en numérique frugal.

Sa mise en œuvre va nécessairement devoir passer par plusieurs étapes
essentielles, dont voici une liste non-exhaustive :

- la sensibilisation de l'ensemble des acteurs du projet aux enjeux. Il ne
  s'agit pas ici d'une formation technique spécialisée réservée à une population
  ciblée, mais bien d'actions de sensibilisation. Il est indispensable qu'à tous
  les niveaux de contribution, de la définition stratégique à la mise en œuvre
  en passant par le pilotage, les acteurs prennent conscience de l'importance
  d'intégrer les impacts environnementaux dans les critères de décisions ;

- la formation d'acteurs spécialisés. Il est probable qu'à différents niveaux,
  notamment sur le design des interfaces hommes/machines ou le développement
  logiciel, il soit nécessaire d'organiser des sessions de formations techniques
  spécialisées sur le sujet de l'écoconception pour permettre la montée en
  compétence des équipes ;

- la mise en place d'outils de mesure. Avant de lancer une démarche de réduction
  des impacts, il est nécessaire de mettre en place les outils et les
  méthodologies permettant la mesure à tous les niveaux. Il peut s'agir par
  exemple d'établir la collecte des indicateurs permettant de réaliser le bilan
  carbone du projet, le recensement des infrastructures, tout autant que la mise
  en place de sondes logicielles ou matérielles permettant d'évaluer les
  consommations énergétiques en phase d'usage. L'impact sur les terminaux devra
  également être mesuré, afin d'éviter d'éventuels effets rebonds ou
  d'obésiciels ;

- ces indicateurs une fois collectés permettront d'alimenter un tableau de bord
  de suivi, permettant ainsi un pilotage du projet incluant l'axe
  environnemental ;

- l'application des bonnes pratiques d'écoconception va influer sur de nombreux
  choix structurants du projet, comme celui des centres de données hébergeant
  l'infrastructure, le design des interfaces ou la politique de déplacement des
  équipes. Le détail de la mise en œuvre de ces bonnes pratiques serait trop
  longue à détailler ici mais leur implémentation dans le projet fera l'objet
  d'un rapport spécifique qui fera office de retour d'expérience avec l'ambition
  de pouvoir éclairer la mise en place d'une démarche similaire dans de futurs
  projets ;

- l'information et la sensibilisation des utilisateurs aux impacts de leur usage
  est une étape importante du processus d'écoconception. Une fois des métriques
  produites sur les impacts, il sera alors possible de les rendre accessibles
  aux utilisateurs à travers la plateforme, à des fins de sensibilisation. Ces
  données pourront également être personnalisées en fonction de leur propre
  usage, et intégrées à leurs données de profile.

- il est fort probable que des développements spécifiques d'outils ou de
  méthodologies soient nécessaires pour mettre en œuvre une telle démarche. Ces
  créations seront rendues disponibles à la communauté, sous la forme d'outils
  logiciels libres ou de rapports détaillant les méthodologies déployées.

(ScienceOuverte)=

## Science Ouverte

La plupart des partenaires de Candyce sont des promoteurs de longue date de la
[Science Ouverte](https://www.ouvrirlascience.fr/) et Candyce s'inscrit
naturellement dans ce mouvement. Les motivations en sont tout autant d'ordre
éthiques (transparence, redonner le contrôle aux utilisateurs), pédagogiques
(permettre aux apprenants de réutiliser à volonté les outils mis à disposition,
d'«ouvrir la boîte», les former à la science ouverte, etc.) que pragmatiques
(reproductibilité, mutualisation, efficience des investissements consentis, coût
d'opération, simplicité de la gestion de la propriété intellectuelle dans un
contexte multi-acteurs, etc.).

Candyce n'aurait simplement pas pu voir le jour sans la Science Ouverte, et
réciproquement le projet a pour mission de la promouvoir, avec pragmatisme.

- Logiciel libre: tous les logiciels développés dans le cadre du projet Candyce
  le seront sous licence libre (comme la
  [Licence BSD](https://fr.wikipedia.org/wiki/Licence_BSD) utilisée par le
  projet Jupyter), en contribuant à chaque fois que possible à des logiciels
  existants.

- Publications ouvertes: toutes les publications produites dans le cadre du
  projet Candyce (publications scientifiques, matériel pédagogique, ...) seront
  diffusées sous licence libre (typiquement
  [Creative Commons Attribution](https://fr.wikipedia.org/wiki/Licence_Creative_Commons)).
  Cela inclue notamment les productions de matériel pédagogique commanditées par
  Candyce à des EdTechs.

- Données ouvertes: toutes les données produites par le projet seront diffusées
  selon le paradigme de «aussi ouvert que possible» (pour soutenir la recherche
  et la valorisation équitable sous toutes ses formes) et «aussi fermé que
  nécessaire» (pour garantir la
  [protection des données personnelles](ProtectionDonneesUtilisateurs)), sous
  l'égide du
  [comité de gouvernance des données personnelles](ComiteGouvernanceDonneesPersonnelles)>
- Gestion ouverte: le paradigme de «aussi ouvert que possible» et «aussi fermé
  que nécessaire» s'appliquera aussi à la mise en œuvre de Candyce (rapports
  d'étapes, ...).

Il est important de préciser que, si Candyce promeut la Science Ouverte et ses
pratiques vertueuses, et en impose les pratiques aux actions financées dans le
cadre du projet, elle n'a pas vocation -- en tant qu'infrastructure -- à en
imposer la pratique à ses utilisateurs; dans le respect des contraintes
techniques et légales, ceux-ci doivent rester libres de leurs choix pédagogiques
(enseignants) ou de leurs modèles économiques (auteurs, entreprises). Par
exemple, un.e enseignant.e ou une entreprise pourra diffuser via
l'infrastructure du matériel pédagogique qu'il ou elle a produit sous tout autre
licence. De même, un enseignant pourra proposer un projet pour ses étudiants
utilisant des outils non libres.
