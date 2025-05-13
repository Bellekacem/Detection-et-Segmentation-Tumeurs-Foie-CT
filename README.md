# Détection de Tumeurs Hépatiques à partir de Scans CT

## 📌 Présentation du projet

Ce dépôt présente le **principe général** d’un projet de deep learning développé dans le cadre d’une collaboration académique et industrielle. En raison de contraintes de confidentialité, l’ensemble du code ne peut pas être publié. Ce dépôt contient une description globale du projet, les définitions des architectures de modèles utilisées, ainsi que les **slides de la soutenance finale**.

## 🧠 Objectif

L’objectif de ce projet est d’assister au diagnostic de tumeurs du foie à partir d’images de **scanners (CT scans)** à l’aide de deux approches principales en deep learning :

1. **Classification**  
   Un modèle basé sur **VGG16** permet de classer les patients comme :
   - **Sains**
   - **Malades**

2. **Segmentation**  
   Un second modèle, utilisant l’architecture **UNet**, permet de segmenter les zones tumorales dans les images CT du foie.

Ces deux tâches visent à aider les radiologues en automatisant la détection et la localisation des tumeurs hépatiques.

## 🖼️ Données en entrée et sortie

- **Entrée** : images CT du foie
- **Sortie** :
  - Pour le modèle de classification : une étiquette indiquant l’état du patient (Sain / Malade)
  - Pour le modèle de segmentation : un masque binaire mettant en évidence les régions tumorales

> ⚠️ **Remarque** : Le jeu de données et le code complet ne sont **pas partagés** en raison de la propriété intellectuelle de l’entreprise partenaire.

## 🧱 Modèles inclus

- `VGG16_model.py` : définition de l’architecture utilisée pour la classification
- `UNet_model.py` : définition de l’architecture utilisée pour la segmentation

Ces fichiers contiennent **uniquement les définitions des modèles**. Aucun script d’entraînement ni données confidentielles ne sont fournis.

## 📂 Contenu du dépôt

- `VGG16_model.py`
- `UNet_model.py`
- `soutenance_finale.pdf` – Présentation synthétique du projet, des méthodes et des résultats

## 📄 Avertissement

En raison d’un **contrat CIFRE** et des règles de propriété intellectuelle de l’entreprise, **le code complet et les données ne peuvent pas être rendus publics**. Merci de respecter ces contraintes légales et éthiques.

## 📬 Contact

Pour plus d’informations ou une éventuelle collaboration, vous pouvez ouvrir une issue ou nous contacter directement.
