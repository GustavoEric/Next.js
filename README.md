# Next.js

## O que é Next.js?
* Next.js é um framework de react ou seja não é nada mais do que uma ferramenta para nos auxiliar no desenvolvimento de aplicações 

## Instalação

Use o comando `npx create-next-app <nome>` para criar um projeto

Para iniciarmos o projeto usaremos o `npm run dev`
## Estrutura de pastas 

* `node_modules` É a pasta aonde ficam todas as dependencias do nosso projeto

* `next.cofig.js` é aonde adicionamos algumas configurações para o nosso projeto Next

* `.next` é a pasta que é basicamente o nosso projeto gerado é aonde acontece o server side render

* `styles` pasta que fica os estilos do nosso projeto por padrão é criado um arquivo `global.css` aonde fica os estilos gerais do nosso projeto

* `public` pasta aonde estão localizados os assets do nosso projeto que são imagens,icones e etc

* `pages` aqui ficam todas as nossas paginas do nosso projeto
OBS: todos os componentes de pagina são chamados pelo arquivo `_app.js`

* `api` para projetos em que o intuito é criar uma API com Next

## Páginas e Roteamento

* Em Next temos uma particulariedade interessante, os arquivos vão passar o roteamento.
* Ou seja, `com base no nome do arquivo`, faremos a geração de URLs do nosso projeto;
* Além disso, o arquivo `index.js` sinaliza a criação da rota base;
* Exemplo: https://www.meuprojeto.com.br/= index.js