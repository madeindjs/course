---
title: Gestion de projet
start: 2018-04-03
end: 2018-04-06
---

# Jour 1

## Notions de système d'information

Système d'information se définie en 4 verbes:

- collecter
- transformer
- conserver
- diffuser

Un système d'information est articulé en 4 ressources: des personnes, du matériel, du logiciel et des données.

### Catégorisation

Le projets informatiques aident à gérer les **fonctions de l'entreprise** et les **Processus métier**. Exemple:

- Opération
  - prise de commande
  - gestion Stocks
- Marketing
  - prévision des ventes
  - gestion des clients

Les système d'informations se classent en **4 niveaux d'utilisation**

- **individuel**. Tableau de bord d'un commercial
- **collectif**. Gestion des payes
- **organisationnel**. Messagerie d'entreprise
- **inter-organisationnel**. Déclaration URSAFF 

Les 3 catégories principales sont donc la **communication**, la **décision** et le **pilotage**.

### Exemple: Wall Mart

Les clients veulent tout trouver au même endroit. Le points critique est donc la **gestion des stocks** (85 milliards pour Wall Mart). Une bonne gestion aurait un impact direct sur le bilan de l'entreprise.

Exemple, les rondelle de caoutchouc d'étanchéité de bocal sont principalement utilisé au printemps pour les confitures. La météo à un impact sur les productions de fruits, donc de la production de la confiture et donc sur les ventes de rondelles.

## Gestion des projets

La réussite d'un projet se mesure avec le respect de la **deadline**, du **budget** et du **cahier des charges**.

Pour que le service technique et l'utilisateur se comprennent, il faut que client liste tous ses besoins.

Les activités des projets IT sont:

- mise en place de l'outils (infrastructure, migration des données, etc..)
- accompagnement des utilisateurs (formation, support, etc..
- assurer la maintenance

## Ébauche de gestion de projets IT

- **Avant**-Projet
- **Étude** d’opportunité
- **Caractéristiques** du projet (Périmètre, Demandes des utilisateurs, Exigences, Évolutions)
- **Analyse** de la valeur (nécessité du projet, bénéfices internes, bénéfices externes, risques)
- **Cahier des charges** (Présentation, Description de la future solution, Prestations attendues, rôles et responsabilités, Organisation, Calendrier)
- **Conception** (Analyse fonctionnelle, Détermination des données à gérer, Contraintes)
- **Réalisation** (Découpage du projet, Ordonnancement des taches, Réalisation du planning)
- **Validation** (Tests sur des plate-formes dédiées, Tests techniques, Tests fonctionnels, Tests en charge, Tests d’intégration)
- **Recette** et réception (Initialisation, définition des objectifs, des rôles et responsabilités)
- **Livraison** (Fournir l’application aux utilisateurs finaux, Suivi, écoute des retours des premiers utilisateurs, Adaptations)
- **Bilan** financier, qualité, technique, méthodologique (Enquête de satisfaction des utilisateurs)

## Les acteurs des projets IT

### Maîtrise d’Ouvrage (MOA)

Le maître d’ouvrage fixe les objectifs  sur ces axes. Il est responsable de l’aboutissement, mais aussi de la phase d’exploitation du résultat. Il est responsable:

- du besoin
- du budget
- des interfaces avec les utilisateurs
- des aspects fonctionnels

### Maîtrise d’Œuvre

Le maître d’œuvre est responsable de la conception (en respect du cahier des charges), l’étude, la réalisation, dans le respect des objectifs de coûts, délais et qualité. Il est responsable:

- choix techniques
- réalisation
- respect des besoins
- respect des indicateurs de performance


---


# Jour 2

Une entreprise n'est pas capable d'exprimer son besoin et donc le cahier des charges est **incomplet**. S'il est incomplet, il faut **poser des questions** afin de lever les ambiguïtés.

Certains entreprises utilisent des **Assistance à Maîtrise d'Ouvrage** afin de rédiger un cahier des charges complets.

## Analyse fonctionnelle

- cartographie des processus (lien entre les processus)
- description des processus
- représentation des processus
- diagramme général
- schéma général de navigation 

    +---------+     données    +---------+
    |processus  >  --------->  |processus  >
    +---------+                +---------+

### Description du processus

- **positionner** le processus avec ses liens vers les autres processus
- décrire les **objectifs**
- décrire le **résultat** que le processus doit atteindre
- décrire les **indicateurs** (taux de satisfaction, etc..)
- **découper** le processus en activités avec des entrées / sorties

### Représentation métier

On découpe par acteur:

    +-----------------+-----------------+
    | Acteur / Role 1 | Acteur / Role 2 |
    +-----------------+-----------------+
    |                 |                 |
    | +------------+  |                 |
    | | Activité 1 |  |                 |
    | +------------+  |                 |
    |       |         |                 |
    |       V         |                 |
    | +------------+  |  +------------+ |
    | | Activité 2 |---->| Activité 3 | |
    | +------------+  |  +------------+ |
    |                 |                 |
    +-----------------+-----------------+

### Description détaillée

- Identifier les objectifs de chaque cas d’utilisation
- Identifier les acteurs de chaque cas (cf étape précédente)
- Définir les préconditions et post-conditions de chaque cas
- Décrire le scénario sous forme de liste d’actions concrète, avec l’agencement (chronologique, …) des actions
- Décrire les scénarios alternatifs

## Méthodologies de gestion de projet

3 familles existent:

- séquentielles (spécifications > développement > test > mise en prod)
- itératives
- Agile (SCRUM, AS, etc..)

### séquentielles

#### En cascade

On découpe le projet en **phases** et le client teste à la fin. Adapté aux **projets cours** (inférieur à 1 an) mais Effet tunnel (si le résultat ne convient pas, on revient au début)

#### En V

C'est le cycle le plus utilisé. On livre quelque chose à chaque étapes. Exemple

* analyse du besoin -> livraison du CDC
* Spécification -> livraison UML
* conception architecture -> livraison test d'intégration
* conception détaillé -> livraison tests fonctionnels

On évite l'effet tunnel.

### itératives

Basé sur la réalisation de prototype. Destiné à des grands projets **complexes** et / ou **innovant**. Permet de valider la réalisation des itération et de valider des hypothèses. Cependant il faut fixer le nombre d'itération avec le client.

### Agiles

Remise en question périodiques pour mieux s'aligner sur les besoins du client. Les sprint sont fixés à **3 semaines**. une réunion quotidienne de **15 minutes** est réalisée pour définir les ponts d'actions. Cela permet de coller aux besoins du clients.


## Chiffrage

- Méthode du **marché**, en comparant avec a concurrence. Le problème est que ça ne compte pas de votre spécificité.
- en faisant appel à un expert
- par **Analogie**. on s'appuie sur l'étude du marché et on fait une conjecture
- **ascendante** (_Bottom-up_), on découpe en tâches et on estime le temps nécessaire. Statistiquement, elle arrive toujours à un chiffrage plus élevé.

> Un bon chiffrage est fait par plusieurs méthodes

## Planification

Utilisation d'un diagramme de Gant avec [Gantter](https://www.gantter.com/) ou [Ganttproject](http://www.ganttproject.biz).


---


# Jour 3

## L'organisation du travail

Lorsqu'on organise le travail, il faut considérer la **dimension humaine**. Il faut prendre en compte les **envies** des développeurs (travailler avec JAVA, faire du front, etc..). C'est pour cela qu'il faut nommer ses ressources et éviter de nommer ses ressources "développeur 1", "développeur 2", etc..

Le **découpage du travail** change en fonction de l'expérience du développeur (plus il est expérimenté, plus le découpage est long). 

Deux solutions sont possible pour le répartissement des tâches:

- **spécialisation**: chaque développeur est spécialisé. Plus rapides mais si un spécialiste est absent, c'est problématique
- **polyvalence**: chaque développeur touche à tout

La **Coordination** peut se faire sous deux formes:

- **personnelle** se base sur des **personnes**: échange informels entre développeur
- **impersonnel** se base sur des **standards**: les tâches sont fixées et précises

### Les parties prenantes

Se décompose en:

- ceux qui font le projet
- ceux qui sont concernés et/ou impacté par le projet

Deux hémisphères doivent communiquer:

- Maîtrise d'ouvrage MOA. Par exemple c'est le client qui possède des idées farfelues et qui connaît sont métier (idées, métier, valeur)
- Maîtrise d'œuvre. Par exemple c'est le développeur qui sait bien développer (architecture, technique, artisanat)

Pour **définir les besoins** il faut **canaliser** le nombre d'utilisateurs clé et les canaliser. Le client doit **coordonner** et **centraliser** les décideurs.

### Le changement

Le responsable actuel doit avoir un rôle clef dans la refonte d'un système car c'est lui qui a la connaissance de la logique métier. S'il ne joue pas un rôle clef, se serra un frein et la mise en place du projet sera compliqué.

## Le rôle du chef de projet

Le chef de projet est responsable du projet. Il doit avoir des compétences suffisantes dans la technologie utilisée. Il gère les décisions, la production et les changements. Il est responsable de:

- gérer le groupe et l'individu
- produire le livrables en temps et en heure
- anticiper le changement
- assurer que le processus de décision fonctionne

Il doit adapter sont style de management suivant un des suivant:

+----------------+------------------------------+------------+-------------------+
| Style          | explication                  | à utiliser | à ne pas utiliser |
+
| directif       | sans demander                | équipe pas expérimenté
| consultatif    | après avoir demandé          |
| participatif   | ils prennent la décision     |
| persuasif      | sans demander et on convainc |
| par délégation | laisse carte blanche         |

Pour gérer les conflits il faut choisir entre le retrait, l'apaisement, la force, le compromis ou la collaboration.


---

# Jour 4

## Management des risques

Faire une **Provision pour risque**. Exemple, une coupure internet arrive 1 fois par mois et dure 1/2 journée. Cela réduit l'efficacité de 50%. Un développeur coûte 300 € / jour donc ça va coûter 150 € / mois / développeur. 

Une provision pour risque va de 5 à 10 %.

## Suivi de l'entreprise - Sous-traitance

Au forfait : faire réaliser des travaux pour un montant forfaitaire. Engagement de résultats pour le prestataire,

En régie : demande de mise à disposition de personnel. Engagement de moyens,

Expertise : achat d’une compétence dans un domaine précis pour traiter un problème. Intervention ponctuelle du fournisseur.


## Pilotage projet

Les **instances de suivi**. Besoin de suivre le projet dans la durée, de communiquer, de rendre compte, de décider. Il a pour but de:

- Suivre la prestation pour respecter les critères de coûts, délais et qualité,
- Contrôler la prestation

Le **comité projet** est hebdomadaire ou par quinzaine avec les responsables MOE . Composé de 

- revue des actions
- réalisé, reste à faire
- détail sur les difficulté

Le **comité de pilotage** est fait par la **maîtrise d'ouvrage**. Composé de:

- Point sur les actions précédentes des comité de pilotage
- avancement global
- ratios / indicateurs

Le comité **ad-hoc** est fait avec les représentants du projets et les utilisateurs. Il est très utile pour les phases critiques comme les spécifications. Composé de:

- échange avec les utilisateurs
- décisions sur des points de spécifications
- lever les ambiguïtés


> Toutes les actions définies doivent contenir un **description**, un **responsable** et un **jalon**.

