# Real-Time-Object-Detection-and-Voice-Announcement-with-YOLOv8-
### Description du Programme

Ce projet Python implémente un système de détection d'objets en temps réel à l'aide du modèle **YOLOv8**, combiné à une synthèse vocale (TTS) pour annoncer les objets détectés via une webcam.

---

#### **Fonctionnalités**  
- Détection d'objets en temps réel avec **YOLOv8**, affichant des cadres de délimitation et des scores de confiance sur le flux vidéo.  
- Annonce vocale des objets détectés et de leur nombre toutes les 3 secondes, avec prise en charge des voix anglaises (Zira ou David) si disponibles.

---

#### **Pré-requis**  
- **Python 3.9** (recommandé).  

---

#### **Fonctionnement**  
1. Le moteur TTS est initialisé et sélectionne une voix anglaise si disponible.  
2. Le programme ouvre le flux vidéo de la webcam et charge le modèle **YOLOv8**.  
3. Les images capturées sont analysées pour détecter les objets, avec des cadres de délimitation affichés.  
4. Toutes les 3 secondes, une annonce vocale informe sur les objets détectés et leur nombre.  
5. Le flux vidéo est affiché dans une fenêtre qui peut être fermée avec la touche **Q**.

---

Ce programme combine vision par ordinateur et interaction vocale pour fournir une expérience d'analyse en temps réel intuitive et performante.
