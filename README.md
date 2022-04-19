# setup_php_mariadb_docker-compose

## Project installation and configuration

1. Open up command prompt
2. Create a new project folder and cd into it
3. Create etc/nginx folder and place default.conf inside it
4. Execute a "docker-compose up -d"
5. Open up the browser and navigate to "localhost:8000". You should see the nginx start page.

 - si ce n'est déja fait, installer docker et docker-compose: `sudo apt install docker-compose` (docker s'installera automatiquement s'il ne l'est pas encore).
 - cloner le repo
 - (optionnel) modifier les paramètres dans .env
 - dans votre terminal, `cd dossierDuRepo`
 - `sudo docker-compose up`
 - votre projet est à flot:
    - localhost:8000 => server web
    - localhost:8080 => phpMyAdmin (server: test_mysql , root, root)
    - localhost:8081 => mysql