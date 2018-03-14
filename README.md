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
* Forker ce repo depuis l'interface GitHub.
* Cloner le fork résultant (attention, l'url du fork devrait être [https://github.com/votre\_username/Applied-Gitology]())
* En local, créer une nouvelle branche avec un nom explicite. (`git branch <nom_de_la_branche>`). Passer sur cette branche (`git checkout <nom_de_la_branche>`). 
* Editer le fichier `participants.txt` présent dans le repo, et uniquement celui la. Y ajouter votre username GitHub (celui présent dans l'URL ci dessus) en respectant la casse, sur une nouvelle ligne. Stage (`git add ...`) et commit (`git commit -m ...`) le fichier.
* Pousser les modifications faites sur votre fork (`git push -u <nom_de_la_branche>`).
* Ouvrir une PR pour merger votre branche dans la branche master de [https://github.com/SUStudentDevs/Applied-Gitology](https://github.com/SUStudentDevs/Applied-Gitology). Félicitation, c'est votre première PR, que je mergerai le plus vite possible !

# Liens et resources
* [Github Student Developer Pack](https://education.github.com/pack)
* [Ma page Campus Experts](https://githubcampus.expert/Vertmo/)
