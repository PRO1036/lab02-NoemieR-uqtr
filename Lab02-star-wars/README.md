# Star Wars

Pour compléter l'exercice, vous devez commencer par récupérer le fichier Rmd dans lequel vous allez enregistrer vos réponses. Pour cela, deux possibilités, selon que git soit installé sur votre machine ou non

#### Git est correctement installé
Dans RStudio:

  - Fichier > Nouveau Projet
  - Version Control > Git
  - Dans _Repository URL_ : indiquez l'adresse: <https://github.com/PRO1036/star-wars.git>
  - Choisissez un nom pour le dossier qui sera créé, par exemple "Lab01"
  - Choisissez où vous voulez créer le projet dans votre ordinateur.

Cela va copier les fichiers présents sur GitHub, et les copier dans le dossier spécifié. Vous pouvez passer à [l'étape suivante](#suite)


#### Git n'est pas installé
Dans Rstudio:

  - Fichier > Nouveau Projet
  - New Directory > New Project
  - Choisissez un nom pour le dossier qui sera créé, par exemple "Lab01"
  - Choisissez où vous voulez créer le projet dans votre ordinateur.

Nous avons créer un projet vide. Il faut maintenant aller chercher les fichiers su GitHub.
Sur GitHub:

  - Visitez l'adresse: <https://github.com/PRO1036/star-wars>
  - Cliquez sur le bouton vert: `<> Code`
  - Cliquez ensuite sur *Download ZIP*
  - Ouvrez le fichier ZIP et copiez le contenu du dossier ZIP (fichier .Rmd) dans le dossier de votre projet R

⚠️ Dans le fichier zip, vous devriez avoir un dossier (nommé `star-wars-master`). Ne copiez pas ce dossier dans votre projet RStudio mais plutôt son contenu.

#### Dans les deux cas {#suite}
Dans RStudio, vous devriez voir le fichier .Rmd listé en bas à droite dans la liste de fichier.

Si vous cliquez maintenant sur le fichier .rmd, il va apparaitre dans la zone en haut à gauche. Vous pourrez l'éditer et le "Render/Knit" pour voir le résultat final.

Veuillez noter que ce que vous écriver dans le fichier Rmd et ce que vous écrivez dans la console ne communiquent pas (il s'agit de deux environnements différents). Si vous voulez utiliser la console (zone en bas à gauche), il faut retaper les commandes.