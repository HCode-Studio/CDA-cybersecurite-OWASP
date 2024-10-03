# Découverte de OWASP ZAP 

[Présentation](https://docs.google.com/presentation/d/1pL_FPW42Jq6Z79e339zWLHOFovhXuGXfaZw7fuUvEvc/edit#slide=id.g307c3df7560_0_125)

## **Objectifs**

- **Comprendre les Concepts de Sécurité Web** : Apprenez les bases de la sécurité web et les types de vulnérabilités que ZAP peut détecter.
- **Installation et Configuration ZAP** : Installez OWASP ZAP sur vos systèmes et configurez-le pour des analyses de sécurité.
- **Utilisation de ZAP pour le Pentesting** : Utilisez les différentes fonctionnalités de ZAP pour explorer, scanner et tester des applications web.
- **Automatisation des Scans** : Découvrez comment automatiser vos scans de sécurité avec l’API REST de ZAP.
- **Adopter les Bonnes Pratiques** : Apprenez à maintenir ZAP à jour et à collaborer efficacement avec les développeurs pour améliorer la sécurité de vos applications.


## **Ressources tutoriel pour OWASP ZAP**
  - [Tutoriel OWASP ZAP : Guide Complet pour Débutants](https://www.youtube.com/watch?v=7ABK_nI5Lrs)

## **Exercice Pratique avec bWAPP**

Apprendre à utiliser OWASP ZAP en pratiquant sur des applications web vulnérables.

**bWAPP (buggy Web Application)** est une application web délibérément vulnérable conçue pour aider les développeurs, les experts en sécurité et les étudiants à apprendre les concepts de la sécurité web. L'application comprend plus de 100 vulnérabilités, couvrant divers aspects tels que les injections SQL, XSS, CSRF, et bien d'autres. bWAPP est idéale pour pratiquer les tests de pénétration et acquérir des compétences pratiques en sécurité informatique dans un environnement sécurisé et contrôlé.

- **Installation de bWAPP avec Docker** :
  
  - Téléchargez et installez [Docker](https://www.docker.com/products/docker-desktop).

  - Exécutez la commande suivante pour télécharger l'image bWAPP :
    ```bash
    docker pull hackersploit/bwapp-docker
    ```
  - Lancez le conteneur bWAPP :
    ```bash
    docker run -d -p 80:80 hackersploit/bwapp-docker
    ```
  - Accédez à l'application bWAPP en ouvrant `http://127.0.0.1/install.php` dans votre navigateur pour finir l'installation.
    
- **Utilisation de ZAP pour Scanner bWAPP** :
  - Configurez votre navigateur pour utiliser ZAP comme proxy.
  - Utilisez le Spider de ZAP pour explorer bWAPP.
  - Ajouter les différents plugins pour orienter vos scans
  - Lancez des scans actifs pour identifier les vulnérabilités.
  - Documentez les failles découvertes et proposez des correctifs.
 

Pensez à jeter un oeil à la [documentation de ZAP](https://www.zaproxy.org/docs/)
