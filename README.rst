==========================================
Créer une image docker pour son projet PHP
==========================================

Tutorial rapide pour utiliser docker et docker-compose pour faire tourner l'équivalent d'un LAMP avec Docker.

Ce tutorial s'inspire de
   * https://github.com/nanoninja/docker-nginx-php-mysql
   * https://docs.docker.com/compose/gettingstarted/

1 - Nginx

Créer un répertoire *web* et *etc/nginx* à la racine du projet::

   mkdir -p web etc/nginx

Mettre le fichier du dépôt *index.html* dans *web et defautl.conf* dans etc/nginx

Créer un fichier *docker-compose.yml* à la racine. Pour voir son contenu::

   git checkout 1-nginx
