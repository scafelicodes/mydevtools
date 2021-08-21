# My Dev Tools
 Just some little pieces of code to improve our productivity


# Passo a passo para usar o gulpfile.js

Para utilização do arquivo gulpfile.js num novo projeto, siga os passos abaixo antes do comando "gulp" no terminal.

- Com o NodeJs instalado, instale o gulp de forma global
```sh
npm install --global gulp-cli
```

- Se você ainda não tem o arquivo package.json no seu projeto, vamos criá-lo agora com:
```sh
npm init
```
- Instale a dependência local do gulp
```sh
npm install --save-dev gulp
```

- O node vai criar a pasta "nodemodules" no seu projeto, então vamos fazer com que o seu serviço git ignore essas dependências criando o arquivo .gitignore na raiz do seu projeto com o conteúdo:
```sh
# NodeJs
node_modules
```

- Instale o gulp-sass e o gulp-rename para compilarmos o nosso arquivo de estilização, minificá-lo e adcioná-lo na pasta /css:
```sh
npm install --save-dev gulp-sass gulp-rename
```

Rode o comando gulp e veja a mágica acontecer:
```sh
gulp
```
