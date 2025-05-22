# Projet Application de Gestion de Concours

---

## Présentation du projet

Ce projet est une **application de gestion de concours universitaire** développée dans le cadre de notre formation à la Faculté des Sciences et Technologies.  
Elle permet de gérer les inscriptions, le suivi et l’organisation des concours d’admission via deux interfaces principales :

- **Espace Candidat** : Pour consulter les concours, s’inscrire et suivre son dossier.
- **Espace Administrateur** : Pour gérer les phases du concours, les candidats et les résultats.

---

## Notre équipe

Ce projet a été réalisé par un groupe de **trois étudiants** :

| Nom complet        | Rôle dans le projet         | GitHub                       |
|--------------------|----------------------------|------------------------------|
| Hafsa Merzouk      | Développeuse full stack       | [MerzoukHafsa](https://github.com/MerzoukHafsa)    |
| Zitouni Safia            | Développeuse full stack  | [Zitouni12](https://github.com/Zitouni12)          |
| Moulim Hsanae | Développeuse full stack     | [hasnaemoulim](https://github.com/hasnaemoulim)   
---

## Objectif du dépôt

Ce dépôt centralise l’ensemble du frontend de l’application via des sous-modules Git pointant vers les dépôts spécifiques à chaque interface :  

- `frontend-fst/` : l’espace candidat (React.js)  
- `fst-front-admin-Concours/` : l’espace administrateur (React.js + Material UI)  

Le backend Laravel est disponible dans un autre dépôt indépendant.

---

## Instructions pour lancer le projet

### Prérequis

- Installer [Node.js](https://nodejs.org/) (version 18 ou plus recommandée)  
- Installer [Git](https://git-scm.com/)  
- Utiliser `npm` (inclus avec Node.js) ou `yarn` pour la gestion des dépendances  

---

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

## Remarques

* Ce dépôt sert de base pour démontrer le fonctionnement des deux frontends en vue d’une présentation au doyen de la faculté.
* Le backend Laravel est à déployer séparément selon les instructions fournies dans son dépôt dédié.

---

## Remerciements

Nous remercions notre professeur pour son accompagnement tout au long de ce projet.

---

## Contact

* Hafsa Merzouk – [GitHub](https://github.com/MerzoukHafsa)
* Zitouni Safia – [GitHub](https://github.com/Zitouni12)
* Moulim Hasnae – [GitHub](https://github.com/hasnaemoulim)

---

## Licence

Ce projet est distribué sous licence MIT.

```

---

```
