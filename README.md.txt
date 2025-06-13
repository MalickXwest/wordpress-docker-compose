# Déploiement WordPress avec Docker Compose

Ce projet permet de lancer un site WordPress avec une base de données MySQL, le tout isolé dans des conteneurs Docker via Docker Compose.

## 🧱 Technologies utilisées

- Docker
- Docker Compose
- MySQL (v5.7)
- WordPress (latest)

## ▶️ Lancement rapide

### 1. Cloner le dépôt
```bash
git clone https://github.com/MalickXwest/wordpress-docker-compose.git
cd wordpress-docker-compose

2. Démarrez les services :
docker-compose up -d

3. Accédez à WordPress :
- URL : http://localhost:8080

## Conteneurs utilisés

- **MySQL** : stocke les données WordPress
- **WordPress** : CMS pour créer votre blog

## Variables configurées

- MYSQL_ROOT_PASSWORD, MYSQL_DATABASE, MYSQL_USER, MYSQL_PASSWORD
- WORDPRESS_DB_HOST, WORDPRESS_DB_USER, WORDPRESS_DB_PASSWORD, WORDPRESS_DB_NAME
