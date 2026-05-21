\## Déploiement sur Scalingo



1\. Connexion au site Scalingo.



2\. Création d’une nouvelle application.



3\. Sélection du mode de déploiement avec GitHub.



4\. Autorisation de l’accès GitHub à Scalingo.



5\. Sélection du dépôt GitHub du projet.



6\. Activation du déploiement automatique sur la branche `main`.



7\. Lancement du premier déploiement.



8\. Vérification des logs de build sur Scalingo.



9\. Vérification du message `successful deployment`.



10\. Ouverture de l’application avec l’URL fournie par Scalingo.



\---



\## Variables d’environnement importantes



Certaines variables doivent être configurées sur Scalingo afin que l’application Symfony fonctionne correctement.



Les principales variables utilisées sont :



\- `APP\_ENV=prod`

\- `APP\_SECRET`



Ces variables peuvent être ajoutées dans :



`Environment > Variables`



sur le tableau de bord Scalingo.



`APP\_SECRET` permet notamment de sécuriser l’application Symfony.

