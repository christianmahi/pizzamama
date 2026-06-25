# Pizzamama projet personnel

Projet web développé avec Python et Django pour présenter une pizzeria et afficher un menu de pizzas depuis une base de données SQLite.

## Fonctionnalités

- Page d'accueil
- Page menu
- Affichage dynamique des pizzas depuis la base de données
- Gestion des pizzas depuis l'administration Django
- Affichage du nom, des ingrédients, du prix et du statut végétarien
- Déploiement en ligne avec PythonAnywhere

## Technologies utilisées

- Python
- Django
- SQLite
- HTML
- CSS
- PythonAnywhere

## Lancer le projet en local

Installer les dépendances :

```bash
pip install -r requirements.txt
```

Appliquer les migrations :

```bash
python manage.py migrate
```

Charger les pizzas d'exemple :

```bash
python manage.py loaddata pizzas
```

Lancer le serveur :

```bash
python manage.py runserver
```

Puis ouvrir :

```text
http://127.0.0.1:8000/
```

## Démo en ligne

https://desirechristian.pythonanywhere.com

## Auteur

Mahi-Mezack Desire Christian
