```markdown
# Rendu : pseudo

- Dépôt :
- Site GitHub Pages :

## Ex2
git log --oneline :
bfc7f25 (HEAD -> main) ex2: corrige une faute
23316e6 ex2: ajoute trois lignes
569f401 ex2: crée les notes
0b10bcc ex1: initialise le dépôt

## Ex3
- config.local est-il encore dans l'historique ? Pourquoi ?
Parce que même si on ne le suit plus, la version qu'on a push sur GitHub reste dedans ; 
Bon par contre si il fallait pas le push (ce que je viens de voir dans l'exo 3) entre les deux étapes, je suppose qu'il sera présent uniquement dans le git ignore ! Puisqu'on ne push pas le commit, il n'apparaîtra pas :)

## Ex4
- git status après avoir retiré brouillon.txt du staging :

On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   RENDU.md
	modified:   brouillon.txt

- Différence entre annuler une modification et retirer du staging ?
Retirer du staging permet de ne plus suivre les changements du fichier ? Alors qu'annuler une modification c'est simplement effacer ce qu'on a fait avant. 

## Ex6
- À quoi servent <<<<<<<, ======= et >>>>>>> ?
Ils servent à baliser le conflit !


## Ex7
- git stash list (avant récupération) :
stash@{0}: WIP on main: d60d83c ex7: ajoute une ligne par erreur
stash@{1}: WIP on main: d60d83c ex7: ajoute une ligne par erreur

- Pourquoi annuler un commit plutôt que l'effacer de l'historique ?
Pour pas perdre de trace sans perdre la face devant nos contributeurs / notre public GitHub parce qu'on est tellement indécis que le commit est très brouillon :D


## Ex8
- git pull = git fetch + quoi ?git merge !## Ex9
https://nycia-pf.github.io/tp-git-no1/


## Ex10
git log --oneline --graph --all :
0c289da (HEAD -> main, tag: rendu) ex10: complète le rendu
- c06ef47 ex10: complète le rendu
- 56b0958 ex9: ajoute la page d'accueil
- 9d2f780 ex9: ajoute la page d'accueil
- 52507e1 ex8: modification depuis GitHub
- b1461ad Merge pull request #1 from Nycia-pf/feature-contact
  |\  
  | _ dd1d504 (feature-contact) ex8: ajoute la page contact
  |/  
  | _ 7ddf059 (refs/stash) WIP on main: d60d83c ex7: ajoute une ligne par erreur
  |/|
  | \* b38a932 index on main: d60d83c ex7: ajoute une ligne par erreur
  |/
- d60d83c ex7: ajoute une ligne par erreur
- 625b750 ex6: résout le conflit du titre
  |\  
  | \* ec5aaa1 ex6: titre en anglais
- | 93e3124 ex6: titre en français
  |/
- ca16c79 ex5: fusionne feature-menu
  |\  
  | _ 21d8027 ex5: ajoute un dessert
  | _ 95a382e ex5: crée le menu
  |/
- 659ed21 ex4: supprime a-supprimer.txt
- a366574 ex4: renomme ancien.txt
- 1814e6b ex4: ajoute trois fichiers
- ee09867 ex3: arrête de suivre config.local
- 6452f17 ex3: arrête de suivre config.local
- 1bc0077 ex3: ajoute config.local (erreur)
- d8eac94 ex3: ajoute .gitignore
- bfc7f25 ex2: corrige une faute
- 23316e6 ex2: ajoute trois lignes
- 569f401 ex2: crée les notes
- 0b10bcc ex1: initialise le dépôt
```