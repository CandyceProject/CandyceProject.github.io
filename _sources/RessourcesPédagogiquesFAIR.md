# Ressources pédagogiques FAIR

## Introduction

L'un des objectifs du programme Candyce est d'accompagner l'émergence d'un
écosystème de ressources pédagogiques, en favorisant la production par la
communauté (enseignants, institutions, associations, éditeurs, ...), le partage,
la montée en qualité et la réutilisation (_sharing, curation, publication_).

Dans Capytale, cet objectif est traité au moyen d'un _Gestionnaire de Contenu_
permettant dépôt, indexation, recherche, recommandation (par les pairs, les
institutions), import. Techniquement, ce gestionnaire ce contenu est basé sur un
CMS (Content Management System) WordPress. Il accueille ... produites par xxx
personnes.

Il convient maintenant de réfléchir aux moyens à mettre en œuvre en vue de cet
objectif dans le programme Candyce. Par exemple, faut-il prévoir un Gestionnaire
de Contenu dédié, basé ou non sur les mêmes technos que dans Capytale?

L'enjeu est de concilier:

- la simplicité d'utilisation: les cas d'usages triviaux doivent être triviaux
- l'efficacité (TODO: à mieux définir)
- la soutenabilité
- la flexibilité
- éviter l'effet silo

=>

- modularité
- réutilisation de bonnes pratiques, de standards, de protocoles, de logiciels
  et de services existants.

Par chance, nous pouvons nous appuyer sur un état de l'art considérable dans le
domaine de la Science Ouverte et de l'accompagnement d'écosystèmes de communs
numériques (logiciels, données, publications, ...), avec notamment le cadre
FAIR: Findable (Découvrable), Accessible (), Interoperable (Interopérable),
Reusable (Réutilisable).

Avec Erlangen : quelles métadonnées, quel usage des métadonnées, moteur de
recommandation interopérable

## Les pièces du puzzle

Pour bien analyser le problème, il faut clarifier quels sont les différentes
pièces du puzzle.

### Actions (TODO: meilleur nom)

- Métadonnées
- Production, éventuellement collaborative (authoring; TODO: traduction en
  français?)
- Publication (au fil de l'eau)
- Previsualisation, Consultation
- Archivage
- Gestion de version?
- Référencement
- Recherche
- Exécution / Utilisation
- Recommandation: évaluation et validation par les pairs et les institutions des
  ressources pédagogiques, en vue de valoriser les ressources de qualité et
  favoriser leur visibilité
- Apprentissage Adaptatif / Visite guidée
- Identification (DOI, ...)

- Réseau social

### Services

- [ ] Forges logicielles: github/gitlab/..., ==> Production (collaboration
      asynchrone), publication (projets publics, github/gitlab pages,
      readthedocs), gestion de version, recommandation
- [ ] Documents / espaces collaboratifs (collaboration temps-réel): codimd,
      sharelatex, overleaf, nextcloud, mybox, ... ==> Production, publication
      (?)
- [ ] (Provisionneur d')Environnements virtuels (collaboratifs): machine perso,
      mésocentres, binder, cocalc, colab, ... et Candyce! ==> exécution,
      production (? collaboration temps réel), publication(? à faire pour
      Candyce!)
- [ ] Archives ouvertes: zenodo (publis, données, ...), arxiv (publis), hal
      (publis), Software Heritage (logiciel) ==> Archivage, Référencement,
      Recherche, Identification, recommandation????
- [ ] Bibliothèques de ressources pédagogiques: Unisciel, ...
- [ ] Moteurs de recherche: ==> indexation, référencement, recherche,
      intégration à des moteurs existants
- [ ] Apprentissage adaptatif: système proposant des ressources pédagogiques à
      un apprenant en fonction de son avancement et de ses objectifs
- [ ] Prévisualisation: nbviewer, github/... (service), nbconvert, jupyterbook
      (logiciel)

### Tâches de préfiguration

- [ ] Produire un visuel brossant le paysage de cette note

  - Concepts
  - Rôles: apprenants/ utilisateurs, enseignants/auteurs, auteurs, validateurs

- [ ] Identifier les experts
- [ ] État de l'art
  - bonnes pratiques, acteurs et services existants pour les ressources
    pédagogiques
- [ ] Identifier ce qui rend spécifique, ou non, des ressources pédagogiques
      interactives, par rapport à:
  - des ressources pédagogiques
  - du logiciel
  - des publications
  - ...

### Tâches pour le projet

- [ ] Standardization
  - Des métadonnées:
    - À différentes granularité : élément, ressource, collection de ressources
      - Environnement: logiciels et artefacts requis
  - De l'encodage des métadonnées dans un document / une collection de
    documents, ou une publication de ceux-ci Exemple:
    - De la représenation d'un environnement
- [ ] Interopérabilité
  - Import «un clic» d'une ressource pédagogique publiée dans un environnement
    virtuel Exemple: zenodo -> Candyce
  - Production d'une url "telle ressource sur tel environnement virtuel"
  - Publication «un clic» d'une ressource
- [ ] Surcouches à des services existants (exemple: gitlab, zenodo) pour
      permettre une intégration poussée à Candyce, avec une interface simple et
      homogène, pour les cas d'usage simples.

      Question: authentification croisée?

- [ ] Aide à la saisie de métadonnées

### Experts

- Rnbm
- CoSo: Comité pour la Science Ouverte
- HAL
- IMS https://www.imsglobal.org/
