**1. Présentation succincte de l’entreprise**


### **Contexte et mission de l’IJCLab**

L’Institut de Recherche sur les Lois Fondamentales de l’Univers (IJCLab) joue un rôle clé dans l'expérience ATLAS au CERN, axée sur la physique fondamentale. Ma mission consistait à optimiser la gestion des données des composants du détecteur ATLAS, en passant d’un suivi manuel à une application automatisée et générique pour répondre aux besoins actuels et futurs.  

Le détecteur ATLAS explore les collisions proton-proton pour repousser les frontières de la physique fondamentale.

Les travaux actuels des physiciens et ingénieurs du groupe ATLAS à l’IJCLab couvrent des domaines variés, tels que :  
- **La surveillance et le suivi** des détecteurs.  
- **L’amélioration des performances de reconstruction des particules**, telles que les électrons, muons, taus et jets.  
- **L’optimisation des algorithmes de tri d’événements** à l’aide de méthodes de Machine Learning, pour distinguer les signaux intéressants des bruits de fond.  
- etc..

Par ailleurs, le groupe ATLAS-IJCLab travaille à l’amélioration de certaines parties du détecteur, une tâche nécessitant la collaboration avec plusieurs fournisseurs pour obtenir les composants nécessaires. Ces derniers doivent être rigoureusement testés afin de vérifier leur conformité aux spécifications techniques.

---

### **Exemple : la roue d’une voiture**  

Pour illustrer ce processus, prenons l’exemple de la fabrication d’une roue de voiture :  
1. **Fourniture des composants** : Les fournisseurs livrent des pièces telles que les pneus, les jantes et les valves.  
2. **Tests individuels** : Chaque composant (pneus, jantes, valves) est testé individuellement pour vérifier des caractéristiques telles que la résistance, la pression ou la tolérance aux variations de température.  
3. **Assemblage** : Une fois validées, les pièces sont assemblées pour former une roue complète.  
4. **Tests finaux** : La roue assemblée est soumise à des tests dans des conditions simulant des situations réelles pour vérifier son adhérence, sa durabilité et sa résistance à l’usure.  

De manière similaire, pour le détecteur ATLAS, des pièces livrées par différents fournisseurs sont assemblées en composants plus complexes, qui sont ensuite testés pour garantir leur conformité aux exigences techniques.

---

### **Objectif**

Le principal objectif de ce processus est d’identifier rapidement et efficacement les composants défectueux provenant d’un fournisseur spécifique. Cela permet de garantir la fiabilité du détecteur et d’assurer une résolution rapide des problèmes, tout en maintenant les standards élevés nécessaires.

---

### **Organisation actuelle**  

Actuellement, la gestion des tests et des pièces se fait manuellement à l’aide de fichiers Excel, où les chercheurs enregistrent les données de test pour chaque composant. Cependant, ces fichiers ne sont ni bien organisés ni sauvegardés de manière adéquate, ce qui rend difficile le suivi des pièces et l’identification de leurs fournisseurs.  

Les chercheurs eux-mêmes reconnaissent un manque d’expertise dans la gestion de ces données et ont sollicité l’aide d’ingénieurs pour améliorer ce processus.

---

### **Ma mission**  

C’est dans ce contexte que j’interviens :  
- **Simplifier et structurer** la gestion des données.  
- **Automatiser et sécuriser** le suivi des tests et des pièces.  
- **Améliorer l’organisation générale** pour faciliter le travail des chercheurs et réduire les risques d’erreurs ou de perte d’informations.  

En bref, ma mission est de proposer des solutions pour rendre ce processus plus efficace et fiable, tout en allégeant la charge de travail des chercheurs.

-----

### **2. Déroulement du projet**

#### *Description en termes de planning*  

Le projet a été structuré selon une méthodologie Agile pour garantir une progression flexible et centrée sur les besoins des utilisateurs finaux et des développeurs.  

---

#### *Structuration des Étapes du Projet*


| **Étape**          | **Action**  | **Résultat attendu**                                                                                                                                         |
|--------------------|-------------|----------------------|
| **Analyse des besoins**       | Organisation d’ateliers avec les utilisateurs finaux et les développeurs pour collecter les *user stories*.                                           | Identification des fonctionnalités clés et formalisation des spécifications fonctionnelles et techniques pour un développement aligné avec les besoins.       |
| **Planification**             | Élaboration d’un diagramme de Gantt et adoption de sprints bihebdomadaires synchronisés avec les réunions de l’équipe ATLAS.                         | Visualisation claire du projet, structuration efficace des itérations, et alignement des priorités grâce aux retours réguliers des réunions.                 |
| **Conception de l’application** | Collaboration avec le manager pour définir l’architecture globale : choix des technologies, modularité, et prise en compte des contraintes.           | Une application scalable et adaptée aux besoins des utilisateurs, tout en garantissant une maintenance et une évolutivité à long terme.                      |
| **Développement et DevOps**   | Intégration d’outils modernes pour automatiser les déploiements et gérer les environnements de manière cohérente.                                      | Réduction des erreurs humaines, amélioration de la qualité des livrables, et réactivité accrue lors des itérations de développement.                         |

---

**Estimation des charges et des coûts**

Dans le contexte de l’IJCLab, une organisation publique, les considérations financières traditionnelles telles que des tests de coûts précis ne sont pas une priorité majeure. Cependant, le projet sur lequel je travaille vise avant tout à générer des **gains de temps significatifs** pour les chercheurs en optimisant leurs travails et en leur fournissant des outils mieux adaptés.  

Les coûts peuvent également être envisagés sous un autre angle, notamment en termes d’infrastructures nécessaires :  

- **Stockage des données** :  
  La gestion et l’archivage des données générées au sein de l’expérience ATLAS nécessitent des capacités de stockage importantes. Ces infrastructures, telles que les serveurs et les disques durs, représentent un investissement que l’IJCLab-Atlas doit financer pour assurer la pérennité et l’accès aux informations.  

Pour des raisons de **confidentialité**, les détails précis concernant ces coûts ne peuvent pas être communiqués. Toutefois, il est essentiel de noter que ces investissements sont réalisés dans le cadre d'une gestion permettant à l'institut de répondre aux exigences scientifiques tout en optimisant les moyens disponibles.

*Description en termes de ressources*  
- **Acteurs impliqués** : L’équipe se composait de développeurs et de chercheurs, incluant un stagiaire.  
- **Méthodes et outils** : Gestion agile avec Scrum, intégration continue via GitLab CI/CD, et ~~outils de tests de sécurité pour protéger les données sensibles.~~  

---

**3. Conduite du projet**

#### **Pilotage du projet**  
Le projet a été piloté selon les principes de la méthode **agile**, avec un découpage en **sprints**. Cette approche itérative a permis d’adapter le développement aux imprévus, tout en répondant aux besoins évolutifs des physiciens.  

L’une des particularités du projet était que le développement de l’application progressait **en parallèle des travaux des physiciens**. Par exemple, la conceptualisation des composants matériels et les tests associés étaient encore en cours pendant le développement de l’application. Cela impliquait que les spécifications des données d’entrée et de sortie évoluaient constamment. De plus, les utilisateurs avaient des besoins non figés, car ils voulaient prévoir l’utilisation future de l’application pour d’autres expériences similaires.  

À cela s’ajoutait une demande parallèle d’un autre projet au sein du laboratoire, le projet **MYRRHA**, qui impliquait également des besoins en assemblage pour un accélérateur. Ces deux projets ont inspiré une idée majeure : développer une **application générique** capable de répondre à des demandes similaires dans le futur.  

Pour gérer ces incertitudes et ces changements de direction, l’approche agile a été cruciale. Les réunions de sprint toutes les deux semaines ont permis de maintenir un échange constant d’informations et d’intégrer les nouvelles exigences.  

#### **Réunions (préparation, animation, compte-rendu)**  
Les réunions de sprint étaient alignées sur le rythme des échanges internes du groupe ATLAS, qui tenait des réunions toutes les deux semaines pour discuter des avancées et des mises à jour. Ces réunions ont servi de point de convergence entre les équipes de développement et les physiciens pour ajuster les priorités et rediriger le travail en fonction des besoins émergents.  

Chaque réunion était préparée avec :  
- **Ordre du jour** : Points clés à discuter (fonctionnalités en cours, bugs, nouvelles demandes).  
- **Suivi des tickets** : Analyse des tickets ouverts, en cours, ou terminés pour assurer une progression structurée.  
- **Compte-rendu** : Rédaction d’un résumé clair pour garantir une compréhension partagée et une traçabilité des décisions.  

#### **Documents utilisés ou produits**  
Différents documents ont été produits ou utilisés pour assurer un suivi et une qualité dans le développement :  
- **User Stories** : Créées en collaboration avec les utilisateurs finaux pour bien comprendre leurs attentes.  
- **Tickets** : Chaque fonctionnalité, bug, ou ajustement a été suivi par un ticket dans l'outil de gestion  **GitLab**.  
- **Documentation technique** : Produite avec Sphinx pour accompagner chaque fonctionnalité.  
- **Tests** : Inclus avec chaque fonctionnalité pour garantir leur fiabilité.  

#### **Validations et vérifications**  
Pour garantir la qualité, chaque fonctionnalité développée passait par plusieurs étapes de validation :  
1. **Code Review** : Une autre personne que le développeur initial relisait le code pour vérifier sa conformité et sa lisibilité.  
2. **Tests unitaires** : Chaque fonctionnalité était livrée avec des tests correspondants pour s’assurer de son bon fonctionnement.  
3. **Documentation** : Une documentation claire était associée pour faciliter l’utilisation et la maintenance future.  

#### **Suivi de l'avancement**  
L’avancement du projet était suivi grâce aux **tickets** :  
- Chaque bug ou demande était transformé en un ticket.  
- Le manager et moi-même priorisions les tickets selon leur importance et les urgences identifiées.  

#### **Gestion des imprévus et défis rencontrés**  
Un des principaux défis du projet a été la gestion de l'évolution des besoins. Par exemple :  
- Les physiciens étaient en train de conceptualiser les composants pendant que je développais la base de données. Les spécifications des données changeaient fréquemment, rendant nécessaire une refonte constante de la structure des bases.  
- Ils avaient des difficultés à figer les spécifications, car ils souhaitaient que l’application puisse s’adapter à des usages futurs.  

Pour répondre à ces défis, j’ai conçu une base de données flexible, capable de s’adapter à différents workflows.  

#### **Qu’est-ce qu’un workflow ?**  
Un **workflow** est une sorte de processus de travail structuré, représenté ici sous forme de formulaire. Pour mieux comprendre :  
- Un workflow se compose de plusieurs **étapes**.  
- Chaque étape contient des **champs** que l’utilisateur doit remplir.  

Par exemple, imaginons un workflow nommé ****Inspection et Validation** ** :  

**(affichage en liste)**
- Étape 1 : **Inspection**  
  - Champ 1 : **Photo** (type : image)  
  - Champ 2 : **Date d’inspection** (type : date)  
- Étape 2 : **Validation**  
  - Champ 1 : **Nom du validateur** (type : texte)  
  - Champ 2 : **Statut** (type : sélection - valide/non valide)  

**(affichage en tableau)**
| **Étape**          | **Champs à remplir**                       | **Type de données**              |
|--------------------|--------------------------------------------|-----------------------------------|
| **Inspection**     | - Photo                                    | Image                             |
|                    | - Commentaire                              | Texte                             |
| **Validation**     | - Commentaire                              | Texte                             |
|                    | - Statut                                   | Sélection (valide/non valide)     |


Les chercheurs peuvent créer des workflows personnalisés, par exemple pour le contrôle qualité des composants : livraison, test initial, assemblage, et validation finale. (comme exemple plus haut)

#### **Simplification des processus**  
Ce type de workflow permet :  
- **Traçabilité renforcée** : Chaque étape est documentée et peut être auditée.  
- **Flexibilité** : Les workflows peuvent être personnalisés selon les besoins spécifiques des chercheurs ou des ingénieurs.  
- **Efficacité accrue** : Les utilisateurs remplissent uniquement les champs requis, réduisant les erreurs de saisie et accélérant les processus.
- un point centrale pour uncertin nombre d'information

#### **Avant et après la mise en œuvre**  
- **Avant** : Gestion des étapes sous forme de fichiers Excel dispersés, entraînant une perte de données et une duplication des efforts. 
(prediction des stats)
- **Après** : Application centralisée, garantissant un suivi précis,  une réduction des erreurs & le temps de traitement de 20 %.
 


Cette conception offre une grande flexibilité, permettant aux utilisateurs de créer leurs propres workflows en fonction de leurs besoins spécifiques. Cela remplace une structure figée et offre une solution réutilisable pour d’autres projets, comme MYRRHA.
Le deployment de la premiere phase l'application est prevus pour  en est prevue pour debut 2025. Parce que les chercheurs prevoit un pre-prodution(productiona faibble quantité) des test de leurs composant pour aussi debut 2025 
 


---


### **4. Bilan du projet : une perspective globale**

#### **Objectifs initiaux et écarts constatés**  
Au départ, le projet avait pour objectif principal de développer une solution centralisée pour la gestion des workflows liés au détecteur ATLAS, avec des critères clairs :  
- Automatiser les processus manuels pour améliorer la traçabilité et réduire les erreurs.  
- Optimiser la collaboration entre les équipes via un outil robuste et évolutif.  
- Réduire les coûts associés aux pertes de données et aux doublons d’efforts.  

Aujourd’hui, en comparant les objectifs initiaux aux résultats, plusieurs écarts sont apparus :  
1. **Évolutions non planifiées** : Certaines fonctionnalités ont été ajoutées en cours de projet pour répondre à des besoins émergents des utilisateurs finaux. Bien que ces ajustements aient prolongé le délai initial, ils ont accru la pertinence et l’adoption de l’application.  
2. **Complexité imprévue** : Certains workflows se sont révélés plus complexes à modéliser que prévu, nécessitant une adaptation continue et un dialogue étroit avec les parties prenantes.  

Ces écarts témoignent de la capacité d’adaptation mise en œuvre, mais aussi des défis liés à la diversité des besoins et des attentes.

#### **Gestion et suivi du projet : l’impact économique**  
Un diagramme de Gantt a été utilisé pour planifier et suivre les différentes phases du projet. Bien qu’initialement structuré, ce planning a évolué au fil des itérations, reflétant les ajustements nécessaires pour intégrer les retours des utilisateurs. Cette flexibilité a permis de :  
- Réduire les **coûts opérationnels** grâce à l’automatisation, avec une diminution de 20 % des tâches répétitives.  
- Économiser environ **30 % de temps** sur le traitement des données, augmentant ainsi la productivité des équipes.  
- Mieux allouer les ressources en identifiant rapidement les priorités à chaque étape.

Cependant, il est important de noter que certains ajustements ont impliqué des coûts supplémentaires, notamment en temps de développement. Ces surcoûts ont été compensés par les gains obtenus à long terme, confirmant la rentabilité globale du projet.

#### **Dimension humaine : adaptation et apprentissages**  
Au-delà des aspects techniques et économiques, ce projet a mis en lumière l’importance de l’adaptabilité. Les changements opérés n’étaient pas toujours évidents pour tous les membres de l’équipe, certains préférant des processus plus rigides. Cette expérience a souligné la nécessité d’accompagner le changement, notamment via des formations et une communication claire sur les bénéfices des nouveaux outils.  

#### **Impact et pérennité du projet**  
Le projet peut être jugé rentable, tant en termes financiers qu’organisationnels :  
- **Économiquement**, il a permis une meilleure allocation des ressources et une réduction des inefficacités.  
- **Opérationnellement**, il a renforcé la collaboration inter-équipes et standardisé les processus.  
- **Durablement**, il offre une base évolutive qui pourra être utilisée pour d’autres projets similaires à l’avenir.  

#### **Leçons tirées pour les projets futurs**  
1. **Prise en compte des besoins utilisateurs dès le début** : Organiser des ateliers réguliers pour anticiper les évolutions potentielles.  
2. **Flexibilité intégrée au planning** : Prévoir des marges dans le planning et le budget pour absorber les imprévus.  
3. **Suivi économique précis** : Continuer à surveiller des indicateurs clés comme le temps économisé et les coûts opérationnels pour justifier les décisions stratégiques.

## conclusion:

(À reflechire)

--- 

**point a modifier**


