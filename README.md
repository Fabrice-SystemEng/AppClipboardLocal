# 🌐 WEB NAVIGATION HUB

![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)

**WEB NAVIGATION HUB** est une plateforme de lancement personnalisée conçue pour centraliser vos liens Web et vos listes d'URLs. Développée en Python avec Streamlit, elle offre une interface fluide et moderne, optimisée pour un usage sur ordinateur et smartphone (testée sur Samsung S25+).

## 🚀 Caractéristiques
- **Double Navigation** : Basculez entre vos URLs directes et vos listes de raccourcis.
- **Totalement Personnalisable** : Gérez vos boutons (nom, lien, couleur) via de simples fichiers `.txt`.
- **Responsive Design** : Affichage en grille optimisé pour mobile.
- **Sécurisé** : Accès restreint via le déploiement privé Streamlit.

## 📁 Structure du Projet
- `streamlit_app.py` : Le cœur de l'application.
- `requirements.txt` : Liste des dépendances (Streamlit).
- `data/` : Dossier contenant les fichiers de configuration :
  - `Url_Liste_Modifiable.txt` : Liens pour l'onglet **LISTES TXT**.
  - `Url_Liste_Modifiable_2.txt` : Liens pour l'onglet **URLS DIRECTES**.

## ⚙️ Personnalisation des boutons
Pour ajouter ou modifier un bouton, éditez les fichiers dans le dossier `/data`. Utilisez le format suivant :
`Nom du bouton, URL ou fichier, Code Couleur Hexadécimal`

**Exemple :**
`Google, https://google.com, #4285F4`

## 📲 Installation sur Mobile (Android)
1. Ouvrez l'URL de votre application dans **Chrome**.
2. Appuyez sur les **trois points** en haut à droite.
3. Sélectionnez **"Ajouter à l'écran d'accueil"**.
4. L'application se lancera désormais en plein écran comme une application native.

## 🛠️ Technologies
- **Langage** : Python 3.13
- **Interface** : Streamlit
- **Hébergement** : Streamlit Community Cloud
