
```markdown
# Application de Gestion de Concours - Projet Central

Ce dépôt centralise les deux interfaces frontend de l'application de gestion de concours universitaire, permettant de gérer à la fois l’espace candidat et l’espace administrateur.

---

## Structure du projet

```

concours-app/
├── frontend-fst/                # Interface Espace Candidat (React.js)
├── fst-front-admin-Concours/   # Interface Espace Admin (React.js + Material UI)
└── README.md                   # Ce fichier

````

Chaque dossier correspond à un sous-module Git, pointant vers un dépôt distinct.

---

## Prérequis

Avant de lancer les projets, assurez-vous d'avoir installé :

- [Node.js](https://nodejs.org/) (version 18 ou plus recommandée)
- [Git](https://git-scm.com/)
- Un gestionnaire de paquets : `npm` (inclus avec Node.js) ou `yarn`

---

## Installation et lancement

### 1. Cloner le projet central avec les sous-modules

Ouvrez un terminal et exécutez :

```bash
git clone https://github.com/Zitouni12/concours-app.git
cd concours-app
git submodule update --init --recursive
````

Cette commande va récupérer les deux sous-modules et les placer dans les dossiers `frontend-fst` et `fst-front-admin-Concours`.

---

### 2. Installation des dépendances et lancement des interfaces

#### Espace Candidat

```bash
cd frontend-fst
npm install
npm run dev
```

L’interface sera accessible à l’adresse :
`http://localhost:5173` (par défaut)

---

#### Espace Administrateur

Ouvrez un nouveau terminal ou onglet, puis :

```bash
cd fst-front-admin-Concours
npm install
npm run dev
```

L’interface sera accessible à l’adresse :
`http://localhost:5174` (ou un autre port libre)

---

## Mise à jour des sous-modules

Pour mettre à jour les sous-modules si leurs dépôts ont évolué :

```bash
git submodule foreach git pull origin main
```

---

## A propos

Ce projet est développé par les étudiants de la Faculté des Sciences et Technologies.
Il permet de gérer de manière centralisée le déroulement des concours d’admission, avec une interface dédiée aux candidats et une autre pour les administrateurs.

---

## Contact

* Hafsa Merzouk – [GitHub](https://github.com/MerzoukHafsa)
* Zitouni – [GitHub](https://github.com/Zitouni12)

---

## Licence

Ce projet est distribué sous licence MIT.

```

---

Tu peux copier-coller ce contenu dans un fichier `README.md` à la racine de ton repo `concours-app`.

Veux-tu aussi que je t’aide à faire un README spécifique pour le backend Laravel ou autre chose ?
```
