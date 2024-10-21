# **CANDYCE**

_CArnets Numériques DYnamiques, Interactifs et Collaboratifs pour
l’Enseignement_

**Vers une infrastructure souveraine pour l’éducation aux et par les sciences du
numérique et pour les activités de recherche, s'appuyant sur des logiciels
libres**

<!-- Ce document en <a href="Candyce.pdf">PDF</a>, en <a
href="Candyce.docx">DOCX</a>, en <a href="Candyce.md">Markdown</a>
(fichier concaténé). !-->

:::{attention} 2024/10: Candyce II, le retour?

À l'origine, Candyce devait être un programme financé à hauteur de 12M€ pour
2023-2027 dans le cadre du plan de relance et plus spécifiquement du PEPR
«Enseignement et Numérique». Déposé en juin 2021 puis février 2022, avec chaque
fois des retours très positifs par le SGPI et les ministères concernés et des
annonces par les gouvernements successifs
[1](https://www.info.gouv.fr/actualite/numerique-educatif-le-premier-ministre-dresse-le-bilan-des-enseignants-de-la-crise-et-presente-des),
[2](https://www.info.gouv.fr/actualite/l-innovation-au-service-de-l-enseignement-scolaire-annonces-des-premiers-laureats-edtech-de-france),
le PEPR n'a finalement pas été financé.

Le moment politique n'est pas favorable aux programmes ambitieux. Pour autant
les besoins du terrain sont toujours plus pressants, avec un environnement
national particulièrement favorable pour être à la pointe. D'autre part, le
travail de construction du programme a permis d'identifier et de modulariser les
actions à mener.

Aussi, avec le soutien d'Inria et de France Université, nous explorons les
opportunités pour lancer -- et financer! -- certaines de ces actions, façon
fusée à étages, en fonction de leur urgence, leur coût et leur impact, avec un
accent mis sur les besoins de l'enseignement supérieur et de la recherche.

Dès à présent, nous nous appuyons sur des financements existants (CMA
SaclAI-School, ...) pour mener des travaux préparatoires en faisant monter en
gamme des actions locales comme à Paris-Saclay (dont CentraleSupélec):
infrastructure [myDocker](https://mydocker.universite-paris-saclay.fr/),
développement d'outils métiers, production de ressources pédagogiques,
accompagnement, ...

Nous avons identifié plusieurs actions nationales qui permettraient de répondre
à court terme (~1 an après lancement) aux besoins les plus urgents (low hanging
fruits), avec un besoin de financement par action de l'ordre de 100k€.

Sur la base de ces deux premiers étages de fusée, nous pourrions alors aller
chercher des financements à l'échelle de quelques M€ pour la massification et la
pérennisation sur le long terme, à l'échelon Français ou Européen.

Pour en savoir plus, pour toute suggestion, ou si vous ou votre institution
souhaiteriez vous impliquer dans Candyce, merci de contacter le coordinateur
Nicolas.Thiery at universite-paris-saclay.fr. Vous pouvez aussi [consulter les
témoignages](https://codimd.math.cnrs.fr/kWae25O-Tqyg5_PdeH_VWw#) et y
contribuer.

:::

:::{warning} À propos de ce wiki
:class: dropdown

À ce stade, ce wiki regroupe les documents de la dernière proposition du
programme Candyce d'origine: description scientifique et <!--implémentation,!-->
annexes. La description de l'implémentation du programme devait être rendue
publique au moment de l'appel d'offre public pour le prestataire en charge du
cœur du développement logiciel. **Certains éléments étaient immatures ou
obsolètes; d'autres simplement absents; tous étaient susceptibles
d'évolutions.**

**Confidentialité:**

Ce document est public et peut être relayé sur les réseaux sociaux.

:::

<!--

:::{admonition} Description Scientifique du programme, telle que soumise au 02/2022 (~35 pages)

<a href="Programme-Candyce.docx">Programme-Candyce.docx</a>

[version collaborative sur MyBox](https://mybox.inria.fr/smart-link/23abf69f-a3e3-439c-950b-44b33f233441/)
(accès restreint)

:::

!-->

:::{admonition} Résumé en deux paragraphes

_Candyce – CArnets Numériques DYnamiques, interactifs et Collaboratifs pour
l’Enseignement – est un projet d’infrastructure numérique souveraine, basée sur
le logiciel libre et notamment l’environnement interactif
[Jupyter](https://jupyter.org), pour l’enseignement des et par les sciences du
numérique, à tous les niveaux du primaire au supérieur, dans les disciplines
scientifiques et au delà. Candyce a en sus pour ambition de devenir un
observatoire des usages pour alimenter la recherche en Sciences du Numérique et
en Sciences de l’éducation._

_Candyce s’appuiera sur l’expérience réussie du déploiement actuel de la
plate-forme
[Capytale](https://www.ac-paris.fr/portail/jcms/p1_1971804/capytale-un-service-web-pour-creer-et-partager-des-activites-pedagogiques-de-codage)
par l’académie de Paris et de multiples déploiements dans le supérieur et
l’industrie._

:::

:::{admonition} Résumé en une page
:class: dropdown

L’interaction avec l’outil informatique est une composante fondamentale de
l’expérience d’apprentissage, des mathématiques à la géographie, de la
programmation à la biologie.

Visualiser des données, les manipuler, afficher une figure, inclure un texte
explicatif et quelques lignes de code, se tromper, corriger ses erreurs,
recommencer, partager son travail en temps réel, le tout dans un simple
navigateur, accessible depuis n’importe où et avec n’importe quel type de
terminal, en prenant en compte les enjeux d’accessibilité aussi bien pour
l’enseignement scolaire que l’enseignement supérieur: c’est l’expérience
proposée par Candyce, **qui a pour ambition d’amener en milieu scolaire tout le
potentiel d’une plateforme numérique pour la construction des apprentissages à
partir d’un simple navigateur, en renforçant la créativité pédagogique des
enseignants.**

L’utilisateur va parcourir un ensemble de documents, les notebooks, se
présentant sous forme de livres numériques interactifs dont il est tour à tour
le héros, l’auteur et le lecteur, tout en étant capable de partager et de
collaborer à l’échelle d’une classe ou d’une équipe. **Cette plateforme ne se
substitue pas aux ENT ou LMS existants et déjà déployés dans les établissements,
elle en est un complément indispensable, qui vient s’y intégrer en apportant de
nouvelles expériences d’apprentissage. Elle est également un outil au service du
rapprochement d’une communauté scientifique pour lui permettre de partager son
expérience pédagogique en associant l’enseignement scolaire, l’enseignement
supérieur et la recherche.**

**Elle propose également un environnement permettant un enseignement plus
interdisciplinaire à l’aide du levier que procure une plateforme numérique pour
les équipes enseignantes.** Cette proposition s’intègre pleinement dans le
cinquième axe proposé dans la synthèse des États Généraux du Numérique Éducatif
: « _Favoriser le développement d’un numérique responsable et souverain_ » et
s’inscrit plus spécifiquement dans la proposition n°38 : « _Encourager
l’utilisation de logiciels et de ressources éducatives libres_ ».

**Cette infrastructure souveraine jouera un rôle majeur pour faciliter
l’enseignement et générer des données permettant l'individualisation des
apprentissages** car à l’instar d’un observatoire, Candyce sera en capacité
d’observer et mesurer les usages des notebooks pour alimenter la recherche sur
la conception didactique des sciences, notamment des sciences informatiques, sur
la reproductibilité d’expériences, sur la création de nouvelles formes de
coopération et de visualisation et d’interaction Homme-Machine qui ouvrent de
nouveaux pans de recherche avec la conception de nouvelles générations de
notebooks intelligents **construits sur le retour effectif d’usage des
apprenants et enseignants.**

**Elle est indispensable pour conserver la maîtrise de notre capacité formative
au moment où les hyperscalaires du numérique tels les GAFAM tentent de
s'accaparer le secteur en proposant des services similaires dans leurs
environnements. Une dynamique européenne sur la base d’un tel projet, socle
d’une standardisation possible, est à envisager dès le lancement, notamment dans
le cadre du Data Space «éducation et compétences» du projet GAIA-X.**

:::

**Table des matières**

```{tableofcontents}

```
