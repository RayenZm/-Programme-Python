# -Programme-Python
Voici un résumé des principales fonctionnalités et sections du code :

1.Gestion des comptes utilisateurs :

L'utilisateur peut saisir un email et un mot de passe. L'email est validé à l'aide d'une expression régulière.
Le mot de passe est validé pour s'assurer qu'il comporte au moins 1 majuscule, 1 minuscule, 1 chiffre, 1 caractère spécial, et a une longueur de 8 caractères.
Les informations de compte sont stockées dans un fichier "enregist.txt".

2.Authentification :

L'utilisateur peut se connecter en saisissant un email et un mot de passe.
Le programme vérifie si les informations correspondent à celles stockées dans "enregist.txt".

3.Chiffrement (RSA) :

L'utilisateur peut générer des paires de clés RSA et les sauvegarder dans un fichier "keys.txt".
Il peut également chiffrer et déchiffrer des messages en utilisant ces clés.

4.Certificat (RSA) :

L'utilisateur peut générer des paires de clés RSA pour un certificat et les sauvegarder dans un fichier "certificat.txt".
Il peut créer un certificat autosigné avec ces clés et chiffrer des messages avec le certificat.

5.Attaque par dictionnaire :

L'option d'attaque par dictionnaire tente de décrypter un message chiffré en utilisant un dictionnaire de mots prédéfinis.
Interface utilisateur :

Le programme offre un menu interactif avec des options pour chaque fonctionnalité.
L'utilisateur peut naviguer dans les options en saisissant les lettres correspondantes.
Les mots de passe et les messages sont saisis de manière sécurisée à l'aide de la bibliothèque getpass.
Ce code est destiné à des fins d'apprentissage et de démonstration des concepts de sécurité. Assurez-vous de le personnaliser et de l'adapter à vos besoins avant de l'utiliser dans un environnement de production.
