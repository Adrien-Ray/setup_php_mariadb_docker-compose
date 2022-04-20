# setup_php_mariadb_docker-compose

## Project installation and configuration

 - si ce n'est déja fait, installer docker et docker-compose: `sudo apt install docker-compose` (docker s'installera automatiquement s'il ne l'est pas encore).
 - cloner le repo
 - (optionnel) modifier les paramètres dans .env
 - dans votre terminal, `cd dossierDuRepo`
 - `sudo docker-compose up`
 - votre projet est à flot:
    - localhost:8000 => server web
    - localhost:8080 => phpMyAdmin (server: test_mysql , root, root)
    - localhost:8081 => mysql

source: https://github.com/jegali/docker-nginx-mysql-php-phpmyadmin
