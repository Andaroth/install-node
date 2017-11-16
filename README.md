# How to NodeJS

## Installer NodeJS
`sudo apt install -y nodejs`

Okay, maintenant tu as une version obsolète ! 

## Mettre à jour NodeJS
Tu n'as pas ce qu'il faut, regarde pour voir : 

`node -v`

Si tu as genre une version inférieure à 6 (par défaut tu risque d'avoir la 4), il te faut `nvm` pour mettre à jour nodeJS :

`curl https://raw.githubusercontent.com/creationix/nvm/v0.30.2/install.sh | bash`

C'est bon ? Relance ton terminal. 

Ensuite tu mets NodeJS à jour comsa : `nvm install 9.2` 

Okay, quand c'est fait, normalement tu as une version de NodeJS un peu plus appropriée ! :) 

Le terminal devrait dire un truc comme ça : `Now using node v9.2.0 (npm v5.5.1)`

## Fini !
Tu peux maintenant utiliser `npm install [nom-du-module]` pour installer des modules trop cool tels que express et vuejs ou des frameworks comme react, electron et cordova ! 
