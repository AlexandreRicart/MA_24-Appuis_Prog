# MA_24-Appuis_Prog
Allons apprendre à utiliser GitHub  !  :^    )

Quelques commandes :

Créer Alias :
$ git config --global alias.co checkout
$ git config --global alias.br branch
$ git config --global alias.ci commit
$ git config --global alias.st status

Configuer GitHub :
$ git config --global user.name "[AlexandreR]"
$ git config --global user.email "[alex.ric@cp.ch]"

Modification GitHub :
D'abord se placer dans le bon réprtoire (du fichier)
$ cd nom_du_fichier
$git status

Ajouter :
$git add [nom_fichier]

Commiter :
$git commit -m "[une description]"

Pusher :
$git Push

Initialiser un rép:
$git init /**ATTENTION AU REPERTOIRE**/

git pull : download depuis le serveur

git push : upload sur le serveur

$ cd MA_24-Appuis_Prog/

$ git branch Branch1

$ git branch Branch2

$ git checkout Branch1 ou $ git checkout Branch2 ou $ git checkout master (changer de Branch1 à Branch2 ou à Master ...)

/**Ajouter physiquement un fichier sur Branch2**/
/**Etre sur d'être sur la Branch2**/

$ git status

$ git add *

$ git commit -m "[Blablabla]"

$ git push --set-upstream origin  Branch2

/**Se placer maintenant sur master **/
$ git checkout master

$ git merge Theo

$ git push
