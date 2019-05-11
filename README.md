# Exemple d'application web en python et API flask/connexion

la structure du projet :

    tree
    .
    ├── READLME.md
    ├── __init__.py
    ├── people.py
    ├── server.py
    ├── static
    │   ├── css
    │   │   └── home.css
    │   └── js
    │       └── home.js
    ├── swagger.yml
    └── templates
        └── home.html


server.py : contient le programme principal.  
swagger.yml : contient le descriptif des api  
people.py : contient les codes des services qui sont derriere chaque endpoint

les repertoires static et templates contiennent le code du front.

Les pre-requis pour faire fonctionner le projet :
1. Python 3
2. pip install flask
3. pip install connexion[swagger-UI]