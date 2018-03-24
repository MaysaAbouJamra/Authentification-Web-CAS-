# Authentification-Web-CAS-
Ce projet consiste en l´installation d 'un système qui utilise 3 services : 
Un premier serveur https/nginx qui reçoit les requêtes et transmet au serveur tomcat. 
Un serveur http/tomcat 8 qui s'occupe du CAS.
Un serveur openldap existant à l'adresse .

Le serveur nginx a le rôle d'un reverse proxy, il doit gérer le protocole https et pour cela utiliser un certificat signé par l'autorité .

Ce projet est déployé avec docker . 
