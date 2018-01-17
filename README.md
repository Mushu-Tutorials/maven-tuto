# MavenTuto

## Télécharger Maven

- Télécharger le fichier **bin.zip** : https://maven.apache.org/download.cgi
- Décompresser le fichier bin dans le dossier voulu


## Ajouter Maven aux variables d'environnement

- `Sytème` > `Paramètres système avancés` > `Variable d'environnement...` > `Nouvelle (Variable utilisateur)`
- Ajouter le nom de la variable : MVN_HOME
- Ajouter le chemin du dossier bin : `C:\...\...\apache-maven-[version]`
- Valider


## Ajouter Maven au PATH

- `Sytème` > `Paramètres système avancés` > `Variable d'environnement...` > `Nouvelle (Variable utilisateur)` > `Path` > `Modifier...` > `Nouveau`
- Ajouter à la suite le chemin allant jusqu'au dossier bin : `C:\...\...\apache-maven-[version]\bin`
- Valider


## Test d'installation

- Ouvrir le menu `Démarrer` > Taper `cmd` ou `Invite de commande`
- Taper ensuite `mvn --version`

Si vous avez un texte comme ci-dessous, vous avez installé correctement Maven. Sinon, veuillez le réinstaller depuis le début.
```
Apache Maven 3.5.2 (...)
Maven home: C:\...\...\apache-maven-[version]\bin\..
Java version: 1.8.0_151, vendor: Oracle Corporation
Java home: C:\Program Files (x86)\Java\jre1.8.0_151
Default locale: fr_FR, platform encoding: Cp1252
OS name: "windows 10", version: "10.0", arch: "x86", family: "windows"
```


###### *Edited by [MushuLeDragon](https://github.com/MushuLeDragon)*
