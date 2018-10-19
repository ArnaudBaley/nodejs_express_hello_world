# nodejs_express_hello_world

![screenshot](https://github.com/ArnaudBaley/nodejs_express_hello_world/blob/master/Capture.PNG)

## SOURCES

[Installation](https://expressjs.com/fr/starter/installing.html)

[Hello world](https://expressjs.com/fr/starter/hello-world.html)


## Installation 

```bash
npm install
```

## LANCEMENT

```bash
node app.js
```

http://localhost:3000/


## FROM SCRATCH

### Installation 

-Créer le dossier "myapp"

-Générer le fichier "package.json"
```bash
npm init
```

-mettre "app.js" comme nom de principal fichier 

-Installer express :
```bash
npm install express --save
```

-Créer fichier "app.js"


### Dev

Ajouter à app.js
```bash
const express = require('express')
const app = express()

app.get('/', function (req, res) {
  res.send('Hello World!')
})

app.listen(3000, function () {
  console.log('Example app listening on port 3000!')
})
```
