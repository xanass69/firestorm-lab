\# 🔥 FireStorm Lab - Reverse Engineering \& Firebase Exploitation



\## 📌 Objectif



L'application Android \*\*FireStorm\*\* contient une fonction de génération de mot de passe pour Firebase, mais celle-ci n'est jamais appelée dans le flux normal de l'application. L'objectif est de :



1\. Forcer l'exécution de la fonction avec \*\*Frida\*\*

2\. Récupérer le mot de passe généré dynamiquement

3\. S'authentifier sur \*\*Firebase\*\*

4\. Extraire le \*\*flag\*\* depuis la base de données



\*\*Niveau :\*\* Medium  

\*\*Techniques :\*\* Reverse Android (Jadx), Hooking Java (Frida), Authentification Firebase  

\*\*Date :\*\* 20/04/2026



\---



\## 🛠️ Prérequis



| Outil | Version |

|-------|---------|

| Python | 3.8+ |

| ADB | Platform-tools |

| Frida | 16.0+ |

| Jadx | 1.5.5+ |

| Émulateur Android | API 33+ (rooté) |



\### Installation rapide



```bash

\# Frida

pip install frida-tools



\# Pyrebase pour Firebase

pip install pyrebase4



\# Jadx (manuel)

\# Télécharger jadx-gui-1.5.5-with-jre-win.zip depuis:

\# https://github.com/skylot/jadx/releases

