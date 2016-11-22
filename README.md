# learn-sass
Intégration avec Tuto.com - ( Exercice : "Apprentissage de SASS" )

Pour savoir si l'installation de ruby à bien été faite, il faut taper dans l'invite de commande : <br />
**ruby -v** <br />
<img src="http://puu.sh/sqa5R/9844bca41f.png" alt="le résultat de l'invite de commande pour tester si ruby est installer" />

Pour générer un fichier css via sass on n'a la possibilité de le faire via cette command : <br />
**sass votre-fichier.scss votre-fichier.css** <br />
<img src="http://puu.sh/sqxIR/70536ae494.png" alt="ce qu'il faut taper dans l'invite de command"> <br />
Dans mon dossier tous les fichiers présent, sont générer via sass hormis le **readme.md**<br />
<img src="http://puu.sh/sqxKL/938a5fb60a.png" alt="Le contenu générer">

Pour générer automatiquement des changements sans intervenir une command existe : <br />
**sass --watch .** Le point signifie que le fichier css se trouve à la racine. <br />
<img src="http://puu.sh/sqxQG/3ab06ad9d5.png" alt="la command pour automatiser les changements"> <br />
Lorsqu'une modification est effectué dans notre fichier SCSS, automatiquement sass détecte un changement et donc il ré-écrit pratiquement instantanément le code dans notre fichier css.
<img src="http://puu.sh/sqxSg/ef676e2eb3.png" alt="Lors d'un changement, sass travail dans l'ombre">
