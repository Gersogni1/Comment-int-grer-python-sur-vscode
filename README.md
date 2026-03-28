# ⚙️ 1. Installer l’extension Python (indispensable)

## 📌 Dans VS Code :

Va dans Extensions (Ctrl + Shift + X)
Recherche :
👉 Python Extension for Visual Studio Code
Clique sur Install

👉 C’est cette extension qui active :

-  l’autocomplétion
-  l’exécution du code
-  le debugging

------------------------------------------------------------------------

## 🐍 2. Vérifier que Python est détecté

``` bash
python3 --version
```
------------------------------------------------------------------------

## 🛠️ Technologies utilisées

-   Python 3.14.3
-   Flask
-   Flask-Login
-   Werkzeug
-   MysQl

------------------------------------------------------------------------


## Si ça marche → OK
## Sinon, installe Python

------------------------------------------------------------------------

## 🎯 3. Sélectionner l’interpréteur Python

## Très important 🔥

Dans VS Code :

👉 Ctrl + Shift + P → tape :

``` bash
Python: Select Interpreter
```
👉 Choisis :

ton Python global OU
ton environnement venv


``` bash
./venv/bin/python
```

### 🧪 4. Créer et utiliser un environnement virtuel

-   Dans ton projet :

``` bash
python3 -m venv venv
```

-   Activer :

``` bash
source venv/bin/activate
```

-   Puis dans VS Code :
👉 re-sélectionne l’interpréteur (très important)
------------------------------------------------------------------------

### ▶️ 5. Exécuter ton premier code Python

-   Crée un fichier :

``` bash
# app.py
print("Hello Python 🚀")
```
-   👉 Pour exécuter :
-   bouton ▶️ en haut OU
-   terminal :

``` bash
python3 app.py
```
------------------------------------------------------------------------

## 👤 Auteur

Gersogni BASHIYA
gersogniyampanya@gmail.com
