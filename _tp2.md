DAMASCENO Thomas
BRUNO Loic

#Les commandes linux
les programmes des commandes linux se situent dans le répertoire /bin

#Les variables d'environnements

1. Le chemin du dossier home se trouve dans la bien nommée variable $HOME
2. La varibale $LANG contient la langue courante ainsi que l'encodage, par exemple fr_FR.UTF-8 
3. $PWD contient le répertoire courant
4. $OLDPWD contient le répertoire précédent
5. $SHELL contient le répertoire des commandes BASH shell
6. la variable $_ contient la dernière réponse du terminal

#Création de variables 

Pour créer une variable il suffit de lui assigner une valeur commme suivant:
$ VAR = coucou
ou de la définir sans la remplir
$ $VAR

Attention ! les variables sont sensibles à la casse

Pour créer une variable de type string qui contient un espace, pensez aux guillemets

8. variables peuvent ensuite être utilisée dans des echos comme suivant :
echo "bonjour $NOMS"

il ne semble y avoir aucune différence entre 'unset VAR' et 'VAR=' mais unset supprime la variable complètement contrairement à 'VAR='

pour échapper le nom d'une variable, mettez un \ devant
e.g: echo "\$HOME = $HOME"




