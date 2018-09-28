 
## VisaTM : Installation de la plateforme  OpenMinTeD

### Objectif

Cette opération concerne l'installation complète d'une instance OMTD.
L'instance déployée sera pleinement opérationnelle pour test dans un environnement minimal de type VMware, avec ouverte à l'extérieur (afin de lever d'éventuels problèmes liés à d'accès).

### Point de vigilance

L'installation permettra de mesurer les difficultés rencontrées dans le déroulé d'une installation tel que préconisée par le fournisseur.
Aucun test de couverture fonctionnelle ne sera réalisé à ce stade.
Néanmoins la participation à l'installation permettra d'avoir une vision claire de l'architecture logicielle, des flux de données et de contrôle.
Nous pourrons ainsi nous projeter dans une configuration plus complète.

Un certain nombre de points de vigilance seront mis en avant notamment pour ce qui concerne : 

#### Installation

 -  Complexité de la tâche : niveau d'automatisation et de packaging, dépendances
 -  Niveau de connaissance/compétence requis
 -  Dépendance vis a vis de couches logicielles bas-niveau (OS, stockage, gestion de ressources, load-balancing, etc.)
 -  La sécurité, en particulier lorsque le système est ouvert à l'extérieur
 -  Documentation : vue d'ensemble, disponibilité, clarté,  précision, exhaustivité, praticabilité, à jour
 - ...
 
#### Exploitation

##### Administration de la plateforme

 - Accès à l'espace de stockage de données et aspects sauvegardes
 - Capacité à monitorer  des traitements : traçabilité des erreurs, fichiers de log
 - Stabilité du service
 - ...

##### Evolution/adaptation 

 - Facilité d'évolution du code :  accessibilité au code source, conception modulaire, intégration IDE, code lisible et commenté, mécanisme de build, dépendances à des framework de conception (Spring, Hibernate, etc.)
 - Capacité à tester avant le déploiement
 - Dispersion technologique
 - ...
