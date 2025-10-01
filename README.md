# 📚 Gestion des Dossiers de Professeurs - UQAC

## 📋 Description
Système de gestion de dossiers de professeurs développé en C++ utilisant des **listes chaînées** et des **pointeurs**. Projet académique réalisé dans le cadre du cours *Structure de données (8INF259)* à l'Université du Québec à Chicoutimi.

## 🎯 Fonctionnalités

### 🏗️ Structures de Données
- **Listes chaînées** customisées pour professeurs, cours et étudiants
- **Gestion mémoire** manuelle avec pointeurs
- **Architecture modulaire** avec séparation header/implementation

### ⚙️ Opérations
- ✅ **Suppression** de professeurs par nom
- ✅ **Recherche** du professeur avec le plus d'étudiants  
- ✅ **Identification** du cours le plus demandé
- ✅ **Comptage** des professeurs par cours
- ✅ **Sauvegarde** des données dans un fichier

## 🛠️ Stack Technique
- **Langage** : C++ 17
- **Compilateur** : MSVC (Visual Studio 2022)
- **Structures** : Listes chaînées, pointeurs, classes
- **Gestion fichiers** : ifstream/ofstream
- **Paradigmes** : POO, programmation procédurale

## 📁 Architecture
GestionDossiersProfesseurs/
├── DossierProfesseur.h # Déclarations des structures et classe
├── DossierProfesseur.cpp # Implémentation des méthodes
├── main.cpp # Programme principal et interface
├── PF.txt # Données professeurs (input)
├── FT.txt # Transactions (input)
└── FP_updated.txt # Résultats (output)

##🎓 Compétences Développées
🔧 Techniques C++ Avancées
Pointeurs : Gestion manuelle mémoire (new/delete)

Listes chaînées : Implémentation from scratch

Classes : Encapsulation, constructeurs/destructeurs

Fichiers : Lecture/écriture streams

Algorithmes : Recherche, parcours, comptage

🧠 Concepts Informatiques
Structures de données linéaires

Complexité algorithmique O(n)

Gestion des ressources

Manipulation de chaînes

Parsing de fichiers

📊 Performance
Temps : Opérations linéaires O(n)

Espace : Allocation dynamique optimisée

Robustesse : Gestion d'erreurs intégrée

👨‍💻 Auteur
Développé dans le cadre du cours 8INF259 - Structure de données - Université du Québec à Chicoutimi

📄 Licence
Projet académique - UQAC
