# Modèle de projet Talend DI Open Studio (Version 7.3.1)

## Introduction

Ce projet git est le modèle de projet à utiliser sur tous les nouveaux projets Talend.

Contenu :
- Contextes
  - Des groupes de contexte prêt à être utilisés
    - job
    - salesforce
    - current_file
- Exemples de job
  - Des exemples de job pour les opérations les plus courantes
- Modèle de job
- Librairies de code Java
  - ContextUtil
  - FileUtil
  - JobUtil
  - ReflexionUtil
  - SalesforceUtil

Avantages de ce modèle de projet Git :

- Meilleure maitrise
  - Le modèle est sur Git donc Git sera utilisé
  - Votre projet Talend doit être obligatoirement présent sur infrastructure Git de Niji (GitLab) ou celle du client
- Qualité
  - Le modèle de job permet d’avoir une base minimum avec les fondamentaux : variables de contexte et logs
  - Il est préférable de dupliquer des exemples qui marchent

- Industrialisation
  - S’appuyer sur des exemples permet d’uniformiser les implémentations
  - Les noms des variables de contexte sont les mêmes d’un projet à l’autre

- Productivité
  - De nombreux exemples sont présents, il suffit de les copier-coller
  - Inutile de réinventer la roue

## Créer un nouveau projet depuis le modèle

[Documentation : Créer un nouveau projet](./docs/creer-un-nouveau-projet.md)

[Documentation : Cloner et utiliser le projet localement](./docs/cloner-le-projet-localement.md)

[Documentation : Importer un ancien projet](./docs/importer-un-ancien-projet.md)


## Exemple de documentation développeur

[Documentation : Préparer son poste de travail](./docs/preparer-son-poste-de-travail.md)

[Documentation : Utiliser et lancer ce projet Talend](./docs/creer-un-nouveau-projet.md)