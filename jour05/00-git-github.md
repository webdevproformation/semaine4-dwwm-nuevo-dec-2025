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
git config --global user.name "Audrey B"
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
git remote add origin https://github.com/webdevproformation/nuevo-tech.git
git push -u origin main
```

# dans repository distant activer une option 

activer l'option "github pages"
