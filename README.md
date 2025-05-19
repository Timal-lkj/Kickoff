# ⚽ Kickoff – Application WPF + API ASP.NET

> Projet réalisé dans le cadre de l’évaluation .NET du Master MSDD  
> 🧠 Thème : Gestion de joueurs et d'équipes de football

---

## 🛠 Technologies utilisées

- **Front-End** : WPF (.NET 6) avec pattern MVVM
- **Back-End** : ASP.NET Core API REST (Clean Architecture)
- **Base de données** : SQL Server (via Entity Framework Core)
- **Langage** : C#

---

## 🚀 Fonctionnalités

### 🖥 Côté WPF (interface utilisateur)

- Affichage des joueurs dans une `ListView`
- Boutons :
  - ➕ Ajouter un joueur
  - ✏️ Modifier un joueur (fenêtre modale)
  - ❌ Supprimer un joueur
- Liaison des données (`DataBinding`) avec `ObservableCollection`
- Pattern **MVVM** respecté
- Design réactif avec placeholders simulés

### 🌐 Côté API REST

- Endpoints pour **CRUD Joueurs** et **Équipes** :
  - `GET /api/joueur` / `GET /api/equipe`
  - `POST`, `PUT`, `DELETE`
- Connexion à la base via **DbContext**
- Architecture claire : `Domain`, `Application`, `Infrastructure`, `Presentation`

---

## 🖼 Captures d'écran

| Interface WPF                       |
|-------------------------------------|
| ![Screenshot](./screenshot.png)     |

---

## ⚙️ Lancer le projet localement

### 1. Cloner le dépôt

```bash
git clone https://github.com/Timal-lkj/Kickoff.git
