# Medical AR: Immersive Clinical Symptom Training (MV50 Project)

> This repository contains the final-year project for my Computer Science Engineering Master's Degree at UTBM (specialization in Virtual Worlds, MV50). This Augmented Reality (AR) application for medical training was developed in collaboration with the Belfort Hospital and was awarded the **highest possible mark (A)** by the jury.

[![Engine](https://img.shields.io/badge/Engine-Unreal_Engine-black.svg)](https://www.unrealengine.com/)
[![Platform](https://img.shields.io/badge/Platform-Meta_Quest_3-blue.svg)](https://www.meta.com/quest/quest-3/)
[![Framework](https://img.shields.io/badge/Framework-Meta_XR-blueviolet.svg)](https://developer.oculus.com/)
[![Tools](https://img.shields.io/badge/Tools-Blender-orange.svg)](https://www.blender.org/)
[![Scripting](https://img.shields.io/badge/Scripting-Blueprints-blue.svg)](https://docs.unrealengine.com/en-US/Engine/Blueprints/index.html)

---

## 🎯 Project Overview & Context

This project initially began as a **Virtual Reality (VR)** simulation for practicing blood draw procedures.

Following a decisive meeting with **Dr. Laurent Faivre**, head of the intensive care unit at Belfort Hospital, the project was strategically pivoted to **Augmented Reality (AR)** to address a more pressing and practical need.

The final application is an AR training tool that allows medical students and staff to practice the **visual recognition of clinical symptoms**. It works by superimposing a realistic, interactive virtual mannequin onto the user's real-world environment, which can then display various pathologies.

## 🎥 Video Demonstration

A full video demonstrating the application's features running on a Meta Quest 3 (using pass-through) is available on Google Drive.

**[➡️ Watch the Project Video Here](https://drive.google.com/file/d/178HY_PfaL4dJqKItYMrfNSf1Q0En1jRS/view?usp=sharing)**

---

## ✨ Core Features (MVP)

The functional prototype allows the following actions within the AR environment:

* **Virtual Mannequin:** Spawns a full-size virtual human body in the user's real space.
* **Manual Positioning:** The user can grab (Left Trigger) and release (Right Trigger) the mannequin to freely position it in the room, making it adaptable to any training space.
* **Dynamic Symptom Switching:** The user can instantly apply different pathological textures to the mannequin using the controller buttons:
    * **'X' Button:** Applies **Cyanosis** texture.
    * **'Y' Button:** Applies **Mottling (Marbrures)** texture.
    * **'A' Button:** Applies **Pruritus (Prurit)** texture.
    * **Right Grip:** Applies **Allergic Shock** (red patches) texture.
    * **'B' Button:** Resets the mannequin to its normal, healthy state.

---

## 🛠️ Tech Stack

* **Game Engine:** **Unreal Engine** (Chosen for high-fidelity graphics and on advisor's recommendation).
* **AR Framework:** **Meta XR SDK** (To leverage the pass-through and spatial tracking capabilities of the Meta Quest 3).
* **Scripting:** **Blueprints** (Used to manage all interactions, state changes, and the custom grabbable system).
* **3D Assets:** **Blender** (Used for UV mapping the human model and creating the texture masks via "Texture Paint" to define where symptoms appear).

---

## 🚀 How to Test (Android APK)

While the primary development target was the Meta Quest 3, a multi-platform version for Android smartphones was also implemented.

You can test this version by sideloading the provided APK:

1.  **[Download the .apk file here](https://drive.google.com/file/d/1Tn-LowIA2MuJt6Ao4O_JkbRrAu9NGLmW/view?usp=sharing)**
2.  Enable **"Install from unknown sources"** in your phone's security settings.
3.  Open the downloaded `.apk` file to install the application.
4.  Launch the app and grant camera permissions to enable the AR experience.

---

## 👥 Authors & Acknowledgements

* **Student Developers:**
    * Victor PIANA
    * Cyprien JURY
    * Maxime KYRIAKIDES
* **University Advisor (UTBM):**
    * Fabrice Lauri
* **Professional Advisor (Hospital):**
    * Dr. Laurent FAIVRE (Head of Intensive Care, Belfort Hospital)
