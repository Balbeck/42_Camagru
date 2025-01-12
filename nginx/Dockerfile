FROM nginx:latest

# Définir l'utilisateur à utiliser dans le conteneur (non-root si nécessaire)
USER root

# Créer le répertoire php-fpm si nécessaire
RUN mkdir -p /var/www/html/php-fpm

# Modifier les permissions du dossier où se trouve le fichier index.php
RUN chown -R www-data:www-data /var/www/html/php-fpm && \
    chmod -R 755 /var/www/html/php-fpm

# Copier le fichier de configuration Nginx
COPY ./default.conf /etc/nginx/conf.d/default.conf