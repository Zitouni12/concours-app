# Projet Application de Gestion de Concours

---

## Présentation du projet

Ce projet est une **application de gestion de concours universitaire** développée dans le cadre de notre formation à la Faculté des Sciences et Technologies.  
Elle permet de gérer les inscriptions, le suivi et l’organisation des concours d’admission via deux interfaces principales :

- **Espace Candidat** : Pour consulter les concours, s’inscrire et suivre son dossier.
- **Espace Administrateur** : Pour gérer la création et la publication de concours, la creation de formulaire asocié a chaque concours, gérer les phases du concours (candidature , epreuve ecrit , epreuve oral), les candidats et les résultats.

---


---

## Objectif du dépôt

Ce dépôt centralise l’ensemble de l’application via des sous-modules Git pointant vers les dépôts spécifiques à chaque interface :  

- `frontend-fst/` : il contient le frontend et backend de l espace candidat et aussi le backend de l espace administrateur (dans meme dossier backend) (React.js + Material UI + laravel)  
- `fst-front-admin-Concours/` : l’espace administrateur au niveau frontend (React.js + Material UI)  

Le backend Laravel est disponible dans un autre dépôt indépendant.

---

## Instructions pour lancer le projet
 ## rediger moi ces prerequis  d une manier plus claire 
### Prérequis

- Installer [Node.js](https://nodejs.org/) (version 18 ou plus recommandée)  
- Installer [Git](https://git-scm.com/)  
- Utiliser `npm` (inclus avec Node.js) ou `yarn` pour la gestion des dépendances  

---
#### pour ces etapes d installation il y a un probleme pour  `fst-front-admin-Concours/ " se run sur  `http://localhost:5173` avec npm run dev 
  et pou`frontend-fst/ il contient deux dossiers backend pour backend : php artisan serve  et frontend npm start 
### Étapes d’installation

1. **Cloner ce dépôt et ses sous-modules**  
```bash
git clone https://github.com/Zitouni12/concours-app.git
cd concours-app
git submodule update --init --recursive
````

2. **Installer les dépendances et lancer les applications**

* Espace Candidat :

```bash
cd frontend-fst
npm install
npm run dev
```

L’application sera accessible à l’adresse : `http://localhost:5173`

* Espace Administrateur :
  Dans un autre terminal :

```bash
cd fst-front-admin-Concours
npm install
npm run dev
```

L’application sera accessible à l’adresse : `http://localhost:5174` (ou autre port libre)

---

## Mise à jour des sous-modules

Pour récupérer les dernières modifications des sous-modules :

```bash
git submodule foreach git pull origin main
```

---


---

## Remerciements

Nous remercions notre professeur pour son accompagnement tout au long de ce projet.

---

## Notre équipe

Ce projet a été réalisé par un groupe de **trois étudiants** :

| Nom complet        | Rôle dans le projet         | GitHub                       |
|--------------------|----------------------------|------------------------------|
| Hafsa Merzouk      | Développeuse full stack       | [MerzoukHafsa](https://github.com/MerzoukHafsa)    |
| Zitouni Safia            | Développeuse full stack  | [Zitouni12](https://github.com/Zitouni12)          |
| Moulim Hsanae | Développeuse full stack     | [hasnaemoulim](https://github.com/hasnaemoulim)   

---

## Licence

Ce projet est distribué sous licence MIT.

```

---

```
##Rerediger moi ce readme pour expliquer en detail comment runner mon projet a partir de cette repo etape apr etape comme tu explique pour un debuatnat tous les commandes les installations necessaires 
