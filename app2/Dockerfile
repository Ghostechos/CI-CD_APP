FROM wordpress:latest

# Installer mysqli (utile avec MariaDB)
RUN docker-php-ext-install mysqli

# Ajouter un plugin de démo (crée un plugin fictif si non présent)
RUN mkdir -p /var/www/html/wp-content/plugins/myplugin
COPY plugins/myplugin /var/www/html/wp-content/plugins/myplugin
