# Application AR pour la Formation Médicale (Projet MV50)

> Projet de fin d'études du Master Ingénieur Informatique (UTBM), spécialisation Mondes Virtuels (MV50). Cette application de Réalité Augmentée (AR) pour la formation médicale a été développée en collaboration avec l'Hôpital de Belfort et a obtenu la note maximale (A) lors du jury.

[![Moteur](https://img.shields.io/badge/Moteur-Unreal_Engine-black.svg)](https://www.unrealengine.com/)
[![Plateforme](https://img.shields.io/badge/Plateforme-Meta_Quest_3-blue.svg)](https://www.meta.com/quest/quest-3/)
[![Outils](https://img.shields.io/badge/Outils-Blender-orange.svg)](https://www.blender.org/)
[![Scripting](https://img.shields.io/badge/Scripting-Blueprints-blue.svg)](https://docs.unrealengine.com/en-US/Engine/Blueprints/index.html)

---

## 🎯 Contexte et Objectif

Ce projet a débuté comme une simulation en **Réalité Virtuelle (VR)** pour l'apprentissage de la prise de sang.

Après une rencontre décisive avec le **Dr Laurent Faivre**, Chef du service réanimation de l'Hôpital de Belfort, le projet a pivoté vers une application de **Réalité Augmentée (AR)** répondant à un besoin plus concret.

L'objectif final est de permettre au personnel médical de s'entraîner à la **reconnaissance visuelle de symptômes cliniques** (pathologies) directement sur un mannequin virtuel superposé au monde réel.

## 🎥 Démonstration Vidéo

Une vidéo complète présentant les fonctionnalités de l'application (sur Meta Quest 3) est disponible sur Google Drive.

**[➡️ Regarder la vidéo du projet ici](https://drive.google.com/file/d/178HY_PfaL4dJqKItYMrfNSf1Q0En1jRS/view?usp=sharing)**

---

## ✨ Fonctionnalités Principales

Le prototype fonctionnel (MVP) développé permet les actions suivantes en Réalité Augmentée via le casque Meta Quest 3 :

* **Affichage du Mannequin :** Fait apparaître un corps humain virtuel complet dans l'espace réel de l'utilisateur.
* **Positionnement Manuel :** L'utilisateur peut "attraper" (gâchette gauche) et "relâcher" (gâchette droite) le mannequin pour le positionner librement dans la pièce.
* **Changement de Symptômes :** L'utilisateur peut appliquer instantanément différentes textures pathologiques sur le corps à l'aide des manettes :
    * **Bouton X :** Applique la texture "Cyanose".
    * **Bouton Y :** Applique la texture "Marbrures".
    * **Bouton A :** Applique la texture "Prurit".
    * **Grip Droit :** Applique la texture "Choc allergique" (plaques rouges).
    * **Bouton B :** Réinitialise le mannequin à son état normal.

---

## 🛠️ Stack Technique

* **Moteur de Jeu :** **Unreal Engine** (choisi pour sa qualité graphique et sur conseil de l'encadrant).
* **Framework RA :** **Meta XR** (pour le "pass-through" et l'ancrage spatial sur Meta Quest 3).
* **Scripting :** **Blueprints** (pour gérer les interactions, les changements d'état et le système de "grab").
* **Modélisation 3D :** **Blender** (utilisé pour l'UV mapping du corps humain et la création des masques de texture en "Texture Paint").

---

## 🚀 Tester l'Application (APK Android)

Bien que le projet ait été principalement développé pour le Meta Quest 3, une version multi-support (smartphone) a également été implémentée.

Vous pouvez tester la version Android en installant l'APK suivant :

1.  **[Télécharger le fichier APK ici](https://drive.google.com/file/d/1Tn-LowIA2MuJt6Ao4O_JkbRrAu9NGLmW/view?usp=sharing)**
2.  Autorisez votre appareil à **"Installer des applications de sources inconnues"** dans vos paramètres de sécurité.
3.  Ouvrez le fichier `.apk` téléchargé pour installer l'application.
4.  Lancez l'application et accordez les autorisations de caméra.

---

## 👥 Auteurs et Encadrement

* **Étudiants :**
    * Victor PIANA
    * Cyprien JURY
    * Maxime KYRIAKIDES
* **Encadrant Universitaire (UTBM) :**
    * Fabrice Lauri
* **Encadrant Professionnel (Hôpital) :**
    * Dr Laurent FAIVRE (Chef du service réanimation, Hôpital de Belfort)
