# starwars
Repositórios para o desafio da B2W-bit para desenvolvedor front end júnior

## Visão Geral do Projeto
O objetivo é desenvolver uma aplicação que descobrisse um planeta aleatório da fraquia Star Wars, fazendo perguntas sobre o mesmo.

### Tecnologias
- HTML5

- CSS
  - [SCSS](https://sass-lang.com/)
  - [CSS Reset](https://gist.github.com/hcatlin/1027867)
  - [SpinKit](http://tobiasahlin.com/spinkit/)
  - [Night sky with twinkling stars](https://codepen.io/WebSonick/pen/vjmgu) 
  - [Crawl text] (https://css-tricks.com/snippets/css/star-wars-crawl-text/)
  
- JavaScript
  - TypeScript
  - Angular 5
  - Angular CLI  
  
### Instalando as Dependências
Para instalar as dependências do projeto basta abrir o **Prompt de Comando do Node.js** (caso você esteja no linux, basta utilizar o terminal), acessar a pasta do repositório e inserir o seguinte comando:
``` node
npm install
```

## Servidor de Desenvolvimento
Basicamente você deverá escrever seu código e enquanto você efetua alterações no arquivo é necessário deixar o comando abaixo rodando:
``` node
ng serve
```
O código irá rodar o plugin **serve**, dessa forma gerando um servidor para o desenvolvimento (`http://localhost:4200/starwars`) sendo assim toda alteração de código nos arquivos de origem irá recarregar automaticamente a página.

## Novos Componentes
Para a criação de um novo componente execute o comando a seguir:
``` node
ng generate component component-name | ng g c component-name
```
Você também pode usar ng generate `directive | pipe | service | class | guard | interface | enum | module`
