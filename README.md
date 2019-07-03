"# deploy-react-app-github-pages" 

## Add homepage

Abra seu arquivo package.json e adicione a propriedade da página inicial.

### "homepage":"https://yourusername.github.io/repository-name"

Substitua o URL acima pelo seu nome de usuário e repositório do github.

## Install gh-pages
Em seguida, precisamos instalar um pacote chamado gh-pages

## npm

### npm install --save gh-pages

## yarn 

### yarn add gh-pages

## Deploy script
É hora de adicionar um comando de script de implantação em nosso arquivo package.json.


Agora, no seu terminal, execute 

### npm run deploy
 ou
### yarn run deploy 

Se tudo ocorrer normalmente, irá aparecer no terminal o caminho onde a aplicação foi publicada.


Mais informações: https://reactgo.com/deploy-react-app-github-pages/
