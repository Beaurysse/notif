Notyf README
@author : Boris K

# Instructions pour collborer sur le projet : 
# Environnement de developpement : 

#Structure du dossier :
---------------------
.vagrant ---- les fichiers et dossiers de configuration vagrant (fichier)
/hmtl ----- repertoire synchronisé avec les serveur apache2 sur la machine virtuelle (repertoire)
.gitignore ----- Contient les éléments devant être ignorés par git lors du commit (fichier)
Vagrantfile ----- LE FICHIER LE PLUS IMPORTANT, contenant toute la configuration de l'environnement de developpement.

#Etapes à suivre :
----------------
1/. cloner le depot
2/. taper dans un terminal, en étant sur d'être dans le repertoire du projet et d'avoir la connexion internet 
(du fait des téléchargements qui devront être fait) : vagrant up

#Test de vérification :
---------------------
Dans le repertoire /html il y a le fichier index.php contenant la ligne <?php phpinfo () ?> permettant d'avoir 
des informations sur la version de php installée.
- Dans un navigateur tapez 192.168.33.10 (l'adresse ip du serveur) suivi de /index.php et observez.
si rien ne s'affiche, c'est que quelque chose à mal fonctionné.