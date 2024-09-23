# Programme

Cette semaine un peu spéciale comporte des objectifs que l'on peut atteindre en théorie sans peine : il suffit de savoir utiliser les mécanismes natifs de protection des frameworks. 
Mais à quoi bon savoir les utiliser si on ne comprend pas à quoi ils servent, et comment ils fonctionnent ? 
La sécurité web est un domaine qui progresse parallèlement à la programmation, dans un espace discret. Si on ne regarde pas, il est presque difficile d'imaginer l'ampleur des événements qui ont lieu sous nos yeux. C'est une course constante et perdue d'avance sur laquelle nous avons une vision retardée, celle des défenseurs : Blue Team.
Cette semaine sera l'occasion de passer aussi de l'autre côté. Du côté obscur. En devenant une Red Team.

Nous verrons un petit bout d'histoire ( très subjectif ) de la sécurité à travers des profils et des événements qui m'ont personnellement marqué.
Nous allons découvrir comment exploiter des failles de sécurité, puis comment s'en défendre. 
Ce sera l'opportunité d'apprendre à travers des défis. Certains que nous réussiront, d'autres que nous ne franchirons pas. Mais toujours dans l'objectif de comprendre ce que l'on fait et pourquoi on le fait.

## Lundi
### Matin
  - Introduction
    - Pourquoi la sécurité est cruciale : Discussion sur l'importance de la sécurité dans le développement des applications.

      Protéger les données sensibles
      Prévenir les atteintes à la vie privée
      Éviter les pertes financières
      Maintenir la confiance des utilisateurs
      Respecter les réglementations
      
    - Concepts de base et terminologies : Vulnérabilité, menace, attaque, risque et sécurité.

      Vulnérabilité : Faiblesse dans un système qui peut être exploitée.
      Menace : Potentiel de source de danger pour une vulnérabilité.
      Attaque : Action d'exploitation d'une vulnérabilité par une menace.
      Risque : Potentiel de perte ou de dommage lorsqu'une menace exploite une vulnérabilité.
      Sécurité : Ensemble des mesures prises pour protéger contre les menaces.
      
    - Exemples d'attaques réelles
      
      Stuxnet (2010) : Ver informatique (malware) créé par la NSA et l'unité 8200 visant les central nucléaire irannien
      Yahoo (2013-2014) : 3 milliards de comptes compromis.
      Équifax (2017) : Vol de données personnelles de 147 millions de personnes.
      WannaCry (2017) : Rançongiciel ayant affecté 200 000 machines dans 150 pays.

  - Un peu d'histoire
    - Groupe 1 
        1. La sécurité informatique avant internet
        2. La cyber sécurité
        3. Personnages célèbres
    - Groupe 2  White Hat, Black Hat et Grey Hat
        1. Black hat / White hat / Grey hat
        2. Blue Team / Red Team
        3. Virus / Malware / Trojan / Ransomware
        4. Zero Days
    - Groupe 3
        1. Encodage vs Chiffrement vs Hachage
        2. Algorithmes de chiffrement
        3. Histoire du hachage MD5 et alternatives modernes
     - Groupe 4
        1. Quelques hacks notoires
### Après midi
  **Les Injections SQL**
  
  Présentation
  [Présentation injection sql]()
  
  Exercices Red Team : 
  - [RootMe Injection authentification](https://www.root-me.org/fr/Challenges/Web-Serveur/SQL-injection-Authentification?q=%2Ffr%2FChallenges%2FWeb-Serveur%2FSQL-injection-authentification)
  - [RootMe Injection String](https://www.root-me.org/fr/Challenges/Web-Serveur/SQL-injection-String)
  - *Ajout d'un exercices custom*
    
  Exercices Blue team (débat ouvert) : 
  - Comment prévenir d'une faille sql ?
  - Comment nos frameworks font pour se protèger de ces failles ?
  - Comment réagir suite à une attaque par injections SQL ?


## Mardi
## Mercredi
## Jeudi
## Vendredi
