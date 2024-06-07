# devoirgit
#configuration du git config
git config --global user.name "ibrahimaoumardiallo"
git config --global user.email "ibrahimaoumardiallo9@gmail.com"
# b- creation de la branch facture oui
#git checkout -b "feature"
#git checkout feature 
# apres avoir faire creation du fichier index.html et faire
git add index.html
git commit -m "ajout du fichier index.html"
bon retour sur la branche feature et on va envoyer sur le depot
<<<<<<< HEAD
git checkout main //bascluer sur la branch main  pour completer le fichier html
=======
// git checkout main // pour me placer dans la branch main et completer le fichier html
git merge feature //fusionner la branch feature a la branch main
>>>>>>> c4f6f868f20c06cc50920ed084c1f4925f7e8340
