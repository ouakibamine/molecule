# 🧪 Molecule Public – Réalité Augmentée pour la Visualisation de Molécules

## 🎯 Objectif

**Molecule Public** est une application mobile interactive développée en **C# avec Unity**, qui permet aux utilisateurs de **scanner une formule chimique ou un nom de molécule via la caméra**, puis d’afficher automatiquement sa **structure 3D en réalité augmentée (AR)** dans leur environnement réel.

---

## 🔑 Fonctionnalités principales

### 1. 📷 Scan de texte via la caméra (OCR)
- Utilise la caméra du téléphone pour scanner des documents, livres ou écrans.
- Détection automatique de **formules chimiques** (ex: `C6H12O6`) ou **noms de molécules** (ex: `glucose`) via un module OCR intégré.
  
### 2. 🔍 Identification de la molécule
- L'application interroge des **bases de données chimiques publiques** (PubChem, ChEMBL, ChemSpider).
- Si la molécule est trouvée, sa structure 3D est automatiquement téléchargée ou générée.

### 3. 🧬 Génération et affichage en réalité augmentée (AR)
- Visualisation 3D de la molécule dans l’environnement réel avec **AR Foundation**.
- Fonctionnalités interactives :
  - Zoom, rotation, déplacement
  - Affichage d'informations chimiques : atomes, types de liaisons, nom IUPAC, charge partielle, etc.

### 4. 🧾 Interface intuitive
- Historique des molécules scannées
- Capture d’écran ou sauvegarde de modèle
- Explications pédagogiques intégrées (structure, polarité, fonctions chimiques…)

---

## 🛠️ Technologies utilisées

| Technologie | Usage |
|-------------|-------|
| **C#** | Développement de la logique applicative |
| **Unity** | Moteur de jeu 3D et interface AR |
| **Unity AR Foundation** | Gestion AR pour Android/iOS |
| **Tesseract OCR** ou **Google ML Kit** | Reconnaissance de texte via caméra |
| **PubChem REST API**, **ChEMBL**, **ChemSpider** | Recherche et récupération de données moléculaires |
| **Formats .mol, .sdf, .mol2** | Conversion en modèles 3D dans Unity |

---

## 🎓 Cas d’usage

- 👨‍🎓 **Étudiants** : Scanner une formule dans un manuel et voir la molécule en 3D devant soi.
- 👩‍🏫 **Enseignants** : Projeter des molécules en classe pour illustrer des concepts.
- 🏛️ **Grand public** : Visualisation interactive dans les musées, expositions scientifiques, ou à domicile.

---

## 🚀 Prochaines étapes

- Reconnaissance vocale : dire le nom de la molécule au lieu de le scanner.
- Mode quiz éducatif : “À quelle molécule appartient cette structure ?”
- Affichage de **réactions chimiques complètes** avec animation.
- Support des **macromolécules** (protéines, ADN).

---

## 📷 Captures d’écran (à venir)

*(Ajoutez ici des captures d'écran de l'application en cours d'exécution, interface, résultats AR)*

---

## 📄 Licence

Ce projet est open-source. Licence à déterminer (MIT, GPL, etc.).

---

## 🙋‍♂️ Contact

**Amine Ouakib**  
📧 amineouakib3@gmail.com  

---

