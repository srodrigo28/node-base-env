
* Instalar dotenv
```
npm i dotenv
```

* Biblioteca
```
https://www.npmjs.com/package/dotenv
```

* Embasamento
```
https://www.youtube.com/watch?v=_gyspXv7B-0
```

#### Como usar
* 1 instale a biblioteca sitada a cima.
* 2 crie um arquivo test.js
```
require('dotenv').config()

console.log(process.env.SENHA)
console.log(process.env.EMAIL)
```
* 3 rode o comando
```
node test.js
```

#### Opcional
* Configurar o package.json
```
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "env": "node index.js",
    "env2": "node --env-file=.env index.js"
},
```