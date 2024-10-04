## Exercice Pratique

#### **Objectif :** Intégrer OWASP ZAP dans votre pipeline CI de votre projet GitLab pour détecter les vulnérabilités de sécurité.

#### **Étapes :**

1. **Configurer OWASP ZAP pour Analyser l'Application :**
   - Utiliser l'image Docker `owasp/zap2docker-stable`.
   - Effectuer un scan rapide avec ZAP.

2. **Mettre à Jour le Job pour Échouer en Cas de Vulnérabilités :**
   - Utiliser `zap-cli` pour analyser le rapport et faire échouer le job si des vulnérabilités sont trouvées.

3. **Vérifier les Résultats :**
   - Push les modifications vers le dépôt GitLab.
   - Vérifier que le pipeline CI s'exécute correctement et qu'il échoue en cas de détection de vulnérabilités.

---

### **Ressources Supplémentaires :**
- [Documentation GitLab CI](https://docs.gitlab.com/ee/ci/yaml/)
- [Documentation OWASP ZAP](https://www.zaproxy.org/)

- [Petit tutoriel de mise en place](https://codific.com/integrate-owasp-zap-and-gitlab/#Overall_setup)

---

### Conclusion
L'intégration de tests de sécurité automatisés dans votre pipeline CI/CD permet de détecter rapidement les vulnérabilités et d'améliorer la sécurité de vos applications. 
Utiliser OWASP ZAP avec GitLab CI est une méthode efficace pour inclure des analyses de sécurité dynamiques dans votre flux de travail de développement.
