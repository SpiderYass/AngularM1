[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=16068212)
# Angular-start
## Michel Buffa, Leo Donati, Université Côte d'Azur 
Repository de démarrage pour vos TP de Angular

C'est dans ce repository que vous allez créer votre projet Angular qui va évoluer tout au long du semestre.

Vous devez donc modifier ce README en ajoutant votre nom et l'avancement de votre projet, ainsi que d'éventuelles difficultés que vous avez eues ou des bonus que vous avez ajoutés par rapport à ce qui vous est demandé.

* Si vous utilisez le github Codespace, alors dans votre machine virtuelle `npm`, `node` et `angular/CLI` sont déjà installés.
* Pour cloner en local ce repository, il faut :
   1. avoir installé `git` (ou `gitbash`) sur votre machine
   1. créer un répertoire de travail et s'y déplacer
   1. cloner le repository distant
```bash
git clone nom-du-repository
```



### Pour vérifier que l'installation est complète

```bash 
npm --version
node --version
ng version
```

### Chaque fois que vous modifiez votre code 

```bash
git pull            #pour synchroniser votre repo local avec le repo de github 
git add -A          #pour informer git de suivre tous les fichiers présents dans le répertoire
git commit -m "message descriptif"      #pour intégrer dans git les dernières modifications faites     
git push            #pour synchroniser le repo github avec le repo local
```

### Pour ajouter un tag (une étiquette) à l'état courant du repository sur github

Une étiquette TPXX doit être ajoutée à la fin de chaque séance de TP pour voir l'évolution progressif de votre travail.

```bash
git tag NomEtiquette
git push --tags
```








