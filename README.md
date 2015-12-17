# Bastien Stephan 
### Mon readme 
### Installation de Jekyll, git & Github Pages.

---

Il faut tous d'abord installer Ruby :
```
 sudo apt-get install ruby-full
```
Le mettre a jours:
```
 sudo gem update –system
```
**Installer Jekyll :**

Il faut ensuite NodeJS pour que Jekyll marche.

Il faut installer Curl pour installer NodeJS :

```
sudo apt-get install curl
```

Commande pour NodeJS :

```
curl --silent --location https://deb.nodesource.com/setup_0.12 | sudo bash -
```

Puis (pour terminer l’installation) : 

```
sudo apt-get install --yes nodejs
```

Puis, il faut se placer dans le dossier à la racine du site et ecrire :
```
jekyll new nomdusite
```
```
cd nomdusite
```
```
jekyll serve
```
L'URL seras alors :
```
http://localhost:4000/
```

**Installation de GIT :**

Crée un compte GitHUB

Ouvrir un nouveau terminal :

```
sudo apt-get install libcurl4-gnutls-dev libexpat1-dev gettext \libz-dev libssl-dev
```
```
sudo apt-get install git 
```


**Configuration du compte et du repository :**

Se placer dans le dossier du site à cloner et remplacer les username (Pour moi "Bastoza") :
```
git clone https://github.com/username/username.github.io
```
Entrer dans le projet et crée le fichier index.html :
```
cd username.github.io
```
```
echo "Hello World" > index.html
```

L'ajouter au repository :
```
git add --all
```
```
git commit -m "Initial commit"
```
```
git push -u origin master
```

### Problème rencontrer :
```
git config --global user.email "you@example.com"
```
```
git config --global user.name "Your Name"
```
enlever le “--global” →
```
git config user.email "you@example.com"
```
```
git config user.name "Your Name"
```
