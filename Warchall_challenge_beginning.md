
# Training: Warchall - The Beginning (Realistic, Linux, Shell, Warchall)

**Voici le guide des niveaux que j'ai pu terminer sur le chapitre 1 : Warchall the beginning**

### ***Tout d'abord***,
Il faut se connecter au serveur par la commande suivante à ecrir sur le terminal :
```sh
$ ssh harena20@warchall.net -p 19198
```

### Niveau 0 : 
- **Aller dans le dossier level** : 
```sh
cd /home/level
```
- **Entrer dans le dossier 00_Welcome** : 
```sh
cd 00_Welcome
```
- **Ouvrir le fichier README.md qui contient la solution**
```sh
cat README.md
```

### Niveau 1 : 
- **Dans le dossier level , entrer dans le dossier 01_choice_tree** : 
```sh
cd 01_choice_tree
```
- **Pour chercher la solution , on utilise cette commande speciale :**
(Elle recherche de manière récursive des solutions dans tous les noms de fichiers ou contenus du répertoire actuel.)
```sh
grep -rn "solution"*
```

### Niveau 2 :
- **Dans le dossier level , entrer dans le dossier 02 :** 
```sh
cd 02
```
- **Pour chercher la solution , il faut chercher les fichiers cachés comme ceci :**
```sh
ls -a
```
- **Entrer dans le dossier caché porb puis ouvrir le fichier caché solution**
```sh
cd .porb
cat .solution
```

### Niveau 3 : 
- **Dans le dossier level , entrer dans le dossier 03 :** 
```sh
cd 03
```
- **Pour chercher la solution , il faut chercher les fichiers cachés comme ceci :**
```sh
ls -a
```
- **Entrer dans  le fichier caché .bash_history pour trouver la solution** 
```sh
cat .bash_history
```

### Niveau 4
- **Il faut se rediriger vers le dossier ~/level$ comme suit :** 
```sh
cd 
cd ~/level 
```

- **Pour chercher la solution , il faut entrer dans le dossier 04_kwisatz comme ceci :**
```sh
cd 04_kwisatz
```
- **Ouvrir le fichier README2.md pour trouver la solution**
```sh
cat README2.md
```

### Niveau 5
- **Dans le dossier level , entrer dans le dossier 05_privacy :** 
```sh
cd 05_privacy
```
- **Pour la solution , ouvrir README.md comme ceci :**
```sh
cat README.md
```













