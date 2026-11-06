# Pizzamama

Site web d'une pizzeria, développé avec Python et Django. Le menu est affiché dynamiquement à partir d'une base de données, et les pizzas se gèrent depuis l'administration Django.

**Démo en ligne :** https://desirechristian.pythonanywhere.com

## Fonctionnalités
- Page d'accueil
- Page menu avec les pizzas affichées depuis la base de données
- Pour chaque pizza : nom, ingrédients, prix et indication végétarienne
- Ajout, modification et suppression des pizzas depuis l'administration Django

## Technologies
- Python
- Django (modèles, vues, templates, administration)
- SQLite
- HTML / CSS
- Déploiement sur PythonAnywhere

## Lancer le projet en local

1. Installer les dépendances :
   ```
   pip install -r requirements.txt
   ```
2. Créer la base de données :
   ```
   python manage.py migrate
   ```
3. Charger les pizzas d'exemple :
   ```
   python manage.py loaddata pizzas
   ```
4. Lancer le serveur :
   ```
   python manage.py runserver
   ```
5. Ouvrir http://127.0.0.1:8000/

## Ce que j'ai appris
- Créer un projet Django et organiser ses modèles, vues et templates
- Afficher des données dynamiquement depuis une base
- Utiliser l'administration Django pour gérer le contenu
- Mettre un site en ligne

## Auteur
Désiré Mahi Mezack
