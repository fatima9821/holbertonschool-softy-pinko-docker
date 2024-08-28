# Utiliser l'image Nginx la plus récente
FROM nginx:latest

# Copier les fichiers du front-end vers le répertoire Nginx
COPY softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copier le fichier de configuration Nginx dans le conteneur
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

