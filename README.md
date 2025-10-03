#### Como criar uma estrutura inicial de projeto NodeJS
##### Intuito é configurar o DotEnv ( Configurar Variaveis de Ambiente )

* Biblioteca
```
https://www.npmjs.com/package/dotenv
```

* Embasamento
```
https://www.youtube.com/watch?v=_gyspXv7B-0
```

#### Bora codar

* > 1 Criar projeto Node
```
npm init -y
```

* > 2 Instalar dotenv
```
npm i dotenv
```

#### Como usar
* instale a biblioteca citada a cima.

* Passo 3 crie um arquivo test.js
```
require('dotenv').config()

console.log(process.env.SENHA)
console.log(process.env.EMAIL)
```
* Passo 4 rode o comando
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

* Crie o git gitIgnore
```
.gitignore
```

* Conteudo do gitIgnore
```
node_modules
```