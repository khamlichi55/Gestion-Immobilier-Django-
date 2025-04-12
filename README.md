
# Projet Django : Gestion Immobilière

## Description

Le projet **Gestion Immobilière** vise à simplifier la gestion des biens immobiliers en offrant une interface web conviviale pour les agents immobiliers et les locataires. Il permet l'inscription et la gestion des locataires, la création, modification et suppression des biens, ainsi qu'une fonctionnalité de recherche avancée pour trouver des propriétés selon des critères spécifiques.

## Fonctionnalités clés

- **Inscription et gestion des locataires** : Les locataires peuvent s'inscrire et gérer leurs informations personnelles.
- **Gestion des biens** : Création, suppression et modification des propriétés disponibles à la location.
- **Recherche et filtrage des biens** : Recherche de biens immobiliers par fourchette de prix, emplacement, type, etc.
- **Recherche avancée des biens** : Recherche de biens selon plusieurs critères personnalisés pour affiner les résultats.

## Avantages

- **Simplification de la gestion des biens immobiliers** grâce à un système CRUD (Créer, Lire, Mettre à jour, Supprimer) intuitif.
- **Amélioration de l'expérience utilisateur** avec une fonction de recherche avancée permettant de filtrer facilement les propriétés selon différents critères.
- **Automatisation des processus administratifs**, ce qui permet de gagner du temps et d'augmenter l'efficacité des agents immobiliers.

## Stack technique

- **Backend** : Django
- **Base de données** : MySQL
- **Frontend** : HTML, CSS, JavaScript
- **Framework CSS** : Bootstrap pour une interface moderne et réactive

## Installation

### Prérequis

- Python 3.x
- MySQL
- Django
- Pip (gestionnaire de paquets Python)

### Étapes d'installation

1. **Clonez le projet** sur votre machine locale :

```bash
git clone https://github.com/votrecompte/gestion-immobiliere.git
cd gestion-immobiliere
```

2. **Créez un environnement virtuel** (recommandé) :

```bash
python -m venv venv
source venv/bin/activate   # Sur Windows : venv\Scripts\activate
```

3. **Installez les dépendances du projet** :

```bash
pip install -r requirements.txt
```

4. **Configurez la base de données MySQL** :
   - Créez une base de données MySQL.
   - Configurez les informations de connexion à la base de données dans le fichier `settings.py` de Django (remplacez les valeurs par les vôtres).

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'nom_de_votre_base_de_donnees',
        'USER': 'votre_utilisateur_mysql',
        'PASSWORD': 'votre_mot_de_passe_mysql',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
```

5. **Appliquez les migrations de la base de données** :

```bash
python manage.py migrate
```

6. **Créez un superutilisateur** (facultatif, mais nécessaire pour l'accès à l'interface d'administration) :

```bash
python manage.py createsuperuser
```

7. **Lancez le serveur de développement** :

```bash
python manage.py runserver
```

8. **Accédez à l'application** en ouvrant votre navigateur à l'adresse [http://127.0.0.1:8000](http://127.0.0.1:8000).


## Auteurs




