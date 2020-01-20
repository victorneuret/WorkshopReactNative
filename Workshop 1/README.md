Dans ce permier workshop nous allons apprendre à utiliser React Native en réalisant un application basique utilisant l'api de SpaceX.

- [Mise en place](#mise-en-place)
    - [Installer NodeJS et npm](#installer-nodejs-et-npm)
    - [Installer expo](#installer-expo)
    - [Création du projet](#cr%c3%a9ation-du-projet)
- [Fondamentaux de React Native](#fondamentaux-de-react-native)
- [Librairie Kitten UI](#librairie-kitten-ui)
- [React Native Networking](#react-native-networking)

---

## Mise en place

#### Installer NodeJS et npm
Pour vérifier si vous avez déjà nodejs et npm sur votre ordinateur, tapez les commandes suivantes dans votre terminal.
```shell
node -v
npm -v
```
Si l'une des deux commandes ne fonctionne pas, [suivez ces instructions](https://nodejs.org/en/download/package-manager/).

#### Installer expo
Expo est un outils construit autour de React Native et des plateformes natives qui aide au developement, build et deploiement des applications.  
Expo a donc une interface cli et une interface mobile permettant un rendu de l'application en temps réeal avec un hot reload.

Tapez cette commande dans votre termial pour installer expo-cli
```bash
npm install -g expo-cli
```

Installer l'application Expo sur votre smartphone [Android](https://play.google.com/store/apps/details?id=host.exp.exponent) ou [iOS](https://itunes.com/apps/exponent)

#### Création du projet
Pour créer le projet tapez cette commande dans votre terninal dans le dossier ou vous voulez que votre projet soit créer. Cette commande va créer un dossier `SpaceXApp` avec la configuration de base du projet.
```bash
expo init SpaceXApp
```

Choisisez la template `minimal`
```bash
❯ expo init SpaceXApp
? Choose a template:
  ----- Managed workflow -----
  blank                 a minimal app as clean as an empty canvas
  blank (TypeScript)    same as blank but with TypeScript configuration
  tabs                  several example screens and tabs using react-navigation
  ----- Bare workflow -----
❯ minimal               bare and minimal, just the essentials to get you started

  minimal (TypeScript)  same as minimal but with TypeScript configuration
```

Remplisez les informations dans le json
```bash
? Please enter names for your project. › 100% completed
 {
   "name": "SpaceXApp",
   "displayName": "SpaceXApp"
 }
```

L'installation du projet devrait commencer.  
Une fois fini, déplacez vous dans le dossier du projet et lancez le.
```bash
cd SpaceXApp
expo start
```

Ouvrez l'application mobile Expo et utilisez la fonction `Scan QR Code` pour scanner le QR code affiché dans votre terminal.  
L'application devrait se lancer sur votre l'écran de votre smartphone avec un `Welcome to React Native`.

---

## Fondamentaux de React Native

## Librairie Kitten UI

## React Native Networking

