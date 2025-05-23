# 🎓 Projet de Gestion de Concours Universitaire

## 📝 Présentation du projet

Ce projet est une application web complète destinée à la gestion des concours au sein d’un établissement universitaire. Elle permet :

- aux **candidats** de s’inscrire, soumettre leur dossier et suivre l’état de leur candidature ;
- aux **administrateurs** de gérer les concours, vérifier les candidatures et publier les résultats.

Le système est composé de deux interfaces indépendantes : une interface **Candidat** et une interface **Administrateur**.

---

## 🎯 Objectifs du projet

- **Automatiser** la gestion des concours pour réduire les tâches manuelles.
- **Faciliter l’inscription** et le suivi des candidatures pour les étudiants.
- **Optimiser** le traitement et la validation des dossiers par l’administration.
- **Offrir une interface moderne** et intuitive grâce aux technologies web récentes.

---

## 📁 Clonage du projet

Cloner le dépôt principal avec ses sous-modules :

```bash
git clone https://github.com/Zitouni12/concours-app.git
cd concours-app
git submodule update --init --recursive
````

Cette commande télécharge le projet principal ainsi que les sous-modules `frontend-fst` et `fst-front-admin-Concours`.

---

## 🚀 Lancement des applications

Le projet est composé de deux interfaces principales :
➡️ **Espace candidat**
➡️ **Espace administrateur**

---

### 1. Espace Candidat (`frontend-fst`)

Cet espace contient à la fois le **frontend React.js** et le **backend Laravel** pour les candidats.

#### a. Lancer le backend Laravel

```bash
cd frontend-fst/backend
composer install
cp .env.example .env
php artisan key:generate
```

🛠️ **Configurer la base de données** dans le fichier `.env` selon vos paramètres locaux (MySQL, port, nom de base...).

Puis lancer le serveur :

```bash
php artisan serve
```

🔗 Le backend sera accessible à l'adresse : [http://localhost:8000](http://localhost:8000)

#### b. Lancer le frontend React

Dans un **nouveau terminal** :

```bash
cd frontend-fst
npm install
npm start
```

🔗 Le frontend sera accessible à l'adresse : [http://localhost:5173](http://localhost:5173)

---

### 2. Espace Administrateur (`fst-front-admin-Concours`)

Cette interface est dédiée aux administrateurs pour la **gestion complète des concours**.

```bash
cd fst-front-admin-Concours
npm install
npm run dev
```

🔗 L'interface admin sera accessible à l'adresse : [http://localhost:5174](http://localhost:5174)
(ou un autre port libre si 5174 est déjà utilisé)

---

## 🔄 Mise à jour des sous-modules

Pour récupérer les dernières modifications des sous-modules, exécutez la commande suivante depuis le répertoire racine du projet :

```bash
git submodule foreach git pull origin main
```

---

## 👥 Équipe de développement

Ce projet a été réalisé par un groupe de trois étudiantes dans le cadre de leur formation :

| Nom complet   | Rôle                    | GitHub                                          |
| ------------- | ----------------------- | ----------------------------------------------- |
| Hafsa Merzouk | Développeuse full stack | [MerzoukHafsa](https://github.com/MerzoukHafsa) |
| Zitouni Safia | Développeuse full stack | [Zitouni12](https://github.com/Zitouni12)       |
| Moulim Hsanae | Développeuse full stack | [hasnaemoulim](https://github.com/hasnaemoulim) |

---

## 📄 Licence

Ce projet est distribué sous licence **MIT**.


---

```
