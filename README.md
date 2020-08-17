
# Django_Pi-Temp

Pi-Temp (côté Django) pour les administrateurs
URL : http://164.90.234.183/home/

## Projet Django

### Objectif

Le site web a pour objectif d'afficher un tableau de bord à un utilisateur authentifier.
Ces informations (température dans un premier temps) sont récupérées à l'aide d'une API et proviennent d'une sonde de température connecté à un Raspberry Pi 3.

### Les bloques applicatifs

Le projet se composera de 3 parties applicatives :

website : partie dédiée au site web 
authenticate : réservé pour tout ceux qui concerne les méthodes d'authentification
api : api mise en place pour communiquer avec les Raspberry utilisateurs.

Nous utiliserons une base de données Postgresql ainsi qu'un serveur web Nginx et Gunicorn.
L'envoie d'informations sera automatiser à l'aide de taches Cron.