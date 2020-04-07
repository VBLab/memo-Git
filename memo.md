Git sert à faire du versionning = donner différentes versions de l'ensemble d'un projet.
Versionning = travail collaboratif.

Git est un logiciel libre.

Github est le service qui s'est construit au dessus de Git.

Mots clés :

- Commit = modifications apportées à son code. Chaque commit crée une sorte de version du code.
  Ex : commit" texte reformulé", ou commit "PHP ajouté"
  Travailler de manière collaborative est ainsi plus pratique.
  Outils devenu indispensable pour tous les dév.
- repo :ou repository = espace de stockage que l'on crée sur Github pour y déposer notre projet.
- fork : une copie d'un repo sur GitHUb
- Pull requiest : faire des changements sur un travail commun et les proposer.
- clone : lorsque l'on copie pour la 1° fois un projet sur notre PC
- remote : "lien entre local et distant"
- merge : fusion automatique, à gérer qaund il y a conflit (= modif identiques sur mes codes...)
- fetch :sur desktop, pull, push et merge en m^me temps. A ses limites car on ne garde pas la main sur ce qui se passe.
- issues :problèmes soulevés

Pour tout cela, il faut utiliser la console Git Bash.

Configuration :
$ git config --global user.name [VBLab
$ git --config --global user.email [vbourgeon]
$ git init = création d'un nouveau projet, on dit : "ça c'est un dossier git"
$ git commit -m “votrecommentaire”
Pour mettre à jour en ajoutant un comm sur ces modifs...
$ git push
Pour mettre à jour sur le GitHub, "on pousse" son code sur GitHub...
$ git pull
Pour aller chercher, récupérer un code.On télécharge sur son PC, en local.
"On tire du code"
$ git add -u ou git add . ou git add “nomdufichier”
Le -u permet de add tous les fichiers “trackés” par git et le add . , ajoute tous les fichiers modifiés connus ou non de git.
$ git status
Pour savoir quels fichiers sont traqués (changements faits mais pas encore commités) = savoir ce qu'il se passe..; Ne pas hésiter à en abuser.
