# git 

- logiciel qui permet de versionner ton code 
- garder plusieurs versions de ton code => plusieurs photos de ton code au fur et à mesure du temps 

- installer git sur ton ordinateur
    - <https://git-scm.com/install/windows>
    - restart visual
    - lancer un terminal
    - git --version
- paramétré git : donner ton nom et ton email 
    
```sh
git config --global user.name "Tahma I"
git config --global user.email "ton@email.fr"

git config --list
```

# créer un repository local 

```sh
# permet de créer un repository local (dossier qui contient le versionning)
git init 
# permet de valider une liste de fichiers avant enregistrement dans le repository
git add .
# action d'enregistrer les fichiers validés
git commit -m "mise en ligne"
```

# mettre en ligne notre travail : sur github

- se créer un profil sur github.com
    - <https://github.com/>
- créer un repository sur github (repository distant)
    - 

```sh
# liaison entre le dépôt local et le dépôt distant
git remote add origin https://github.com/webdevproformation/nuevo-tech.git
# donner le nom main à la branch principale du projet
git branch -M main
# push prendre le repository local => dépôt distant
git push -u origin main
# validation par Navigateur 
```

# dans repository distant activer une option 

activer l'option "github pages"

Attention pour trouver la bonne adresse 

<https://webdevproformation.github.io/semaine4-dwwm-nuevo-dec-2025>/jour02 autonomie/01-

# je veux modifier un fichier  et le mettre en ligne 

1. modifier ton fichier dans Visual Studio Code 
2. enregistrer le fichier avec Ctrl + S
3. réaliser les commandes suivantes 

```sh
# prendre le fichier modifié et le push sur github
git add .
git commit -m "modification du titre"
git push
``` 

4. rafraichir la page html dans ton navigateur 
5. Attention il faut vider le cache navigateur pour que la mise à jour soit visible  