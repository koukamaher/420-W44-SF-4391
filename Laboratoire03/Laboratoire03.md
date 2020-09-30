# Laboratoire 03

Le but de se laboratoire est de monter un site Wordpress avec MySQL. Wordpress doit avoir 3 replica.

Le laboratoire s'effectue en groupe de 4 maximum. Vous devez créer vos objets dans un espace de nom qui contient la liste de vos matricules séparés par un tiret. Exemple "1234567-2134567-3214567-2234567".

Le temps alloué est de 2 séances. La remise est pour le 12 octobre 2020 minuit.

Vous devez fournir :

- Tous les fichiers YAML
- Un dessin qui illustre les noeuds, les services et les pods ainsi que leurs relations
- Une vidéo :
  - Explication de tous vos fichiers
  - Démonstration que le site fonctionne
  - Démonstration que vous êtes capable de faire une mise à l'échelle

À se rappeler :

- Vous aurez besoin d'un volume persistant pour la base de données
- Il faut passer les informations de la base de données à Wordpress et à MySQL par des variables d'environnement
- Si vous exposez votre MySQL avec un service, vous pouvez le contacter avec son adresse DNS

Références à lire :

- https://kubernetes.io/docs/tasks/inject-data-application/define-environment-variable-container/
- https://hub.docker.com/_/wordpress
- https://hub.docker.com/_/mysql
- Outils d'enregistrement : OBS, Screencast-o-matic, etc.