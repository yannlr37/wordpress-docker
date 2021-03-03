# Wordpress / Docker installation

## Contenu

* **data/** : données et base de données
* **src/** : code du site WordPress
* **docker-compose.yml** : lancement de la configuration DOcker

## Installation

```
git clone <archive> <project_name>
cd <project_name>
docker-compose up
```

Puis procéder à l'installation.
Une fois celle-ci terminée, modifier les droits sur les fichiers pour pouvoir les éditer.

```
sudo chown -R yann:yann src/
```
