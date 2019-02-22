# Applied-Gitology
Le Workshop Applied Gitology, edition 2018 (la première en fait)

# Présentation
La présentation est visible sur [GitPitch](https://gitpitch.com/SUStudentDevs/Applied-Gitology), et est réalisée en Markdown dans le fichier `PITCHME.md`.

# Exercices
### Exercice 0 : Préparation
* Si vous êtes sur votre machine personnelle, installer Git : [Plusieurs méthodes dépendamment de votre OS](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* Si vous êtes sur une machine de la PPTI, Git est déjà installé, mais le proxy de la FAC empêche de l'utiliser en réseau. Télécharger et executer le script `git-PPTI-proxy.sh` présent sur ce répo pour régler le proxy automatiquement.
* [Créer un compte Github](https://github.com/join) si ce n'est pas encore fait.

### Exercice 1 : Première contribution
Ce premier exercice a deux objectifs : vous faire pratiquer le processus de base de collaboration via GitHub, et me permettre de récupérer la liste de vos noms d'utilisateurs GitHub sans trop d'efforts.
* Forker ce repo depuis l'interface GitHub.
* Cloner le fork résultant (attention, l'url du fork devrait être [https://github.com/votre\_username/Applied-Gitology]())
* En local, créer une nouvelle branche avec un nom explicite. (`git branch <nom_de_la_branche>`). Passer sur cette branche (`git checkout <nom_de_la_branche>`). 
* Editer le fichier `participants.txt` présent dans le repo, et uniquement celui la. Y ajouter votre username GitHub (celui présent dans l'URL ci dessus) en respectant la casse, sur une nouvelle ligne. Stage (`git add ...`) et commit (`git commit -m ...`) le fichier.
* Pousser les modifications faites sur votre fork (`git push -u origin <nom_de_la_branche>`).
* Ouvrir une PR pour merger votre branche dans la branche `WS2019` de [https://github.com/SUStudentDevs/Applied-Gitology](https://github.com/SUStudentDevs/Applied-Gitology). Félicitation, c'est votre première PR, que je mergerai le plus vite possible !

### Exercice 2 : Des repos par milliers
Maintenant que j'ai vos noms, on va pouvoir s'amuser ! Je vais maintenant vous demander de créer le plus de repos possibles, mais pas des repos vides bien entendu. Votre objectif est de mettre en ligne les projets, TPs, etc réalisés jusqu'ici a la FAC durant les semestres précédants celui ci. Vous pouvez suivre à l'écran le nombre total de repo créés durant l'atelier, ainsi que votre classement (l'application utilisée au tableau est [repo-counter](https://github.com/Vertmo/repo-counter), je vous invite à y jeter un coup d'oeil et à y contribuer si cela vous intéresse).

Petit rappel des phases pour créer un repo:
* Créer le repo sur GitHub avec le bouton `New repository`. Lui donner un nom et une description explicites. De préférence ajouter un `README` que vous remplirez après, ainsi qu'un `.gitignore` (GitHub propose de nombreux `.gitignore` correspondants à a peu près tous les langages de programmations possibles). Je vous recommande aussi d'ajouter une licence, car c'est toujours mieux (même si pour un petit repo comme celui la cela peut paraitre superflu).
* Cloner le repo créé sur votre machine. Si vous utilisez `git log`, vous verrez que le repo ne contient qu'un seul commit, nommé `initial commit`.
* Ajouter des fichiers dans les repo (dans ce cas sans doute les copier-coller depuis un autre dossier), puis `git add .` et `git commit -m ...`. Le `.gitignore`, si il est bien choisi, devrait empêcher que les fichiers non-sources (binaires générés par un compilateur par exemple) soient ajoutés.
* `git push`, et voila vos changements sont en ligne !

# Liens et resources
* [Github Student Developer Pack](https://education.github.com/pack)
* [Ma page Campus Experts](https://githubcampus.expert/Vertmo/)
* [Le repo-counter](https://github.com/Vertmo/repo-counter)

Merci à Malik Ben Kirane pour les deux liens suivants (en anglais):
* [Comprendre l'index](https://alblue.bandlem.com/2011/10/git-tip-of-week-understanding-index.html)
* [Introduction pour les pythoniens](https://realpython.com/python-git-github-intro/)
