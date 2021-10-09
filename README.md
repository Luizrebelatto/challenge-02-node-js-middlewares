<h1 align="center">Middlewares</h1>

<p align="center">
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-bibliotecas">Bibliotecas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-funcionalidades">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-rotas">Rotas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como Executar</a>&nbsp;&nbsp;&nbsp;
</p>

<br>

## 💻 Projeto

Objetivo deste projeto foi aplicar os conceitos aprendidos sobre middlewares no projeto todo

## ✨ Tecnologias
- Node
- JavaScript
- Insomnia
- express
- nodemon

## 📚 Bibliotecas
- uuid
- supertest
- cors
- jest

## 💻 Funcionalidades
- Criar Usuário
- Cadastrar Tarefas
- Mostrar Tarefas
- Atualizar titulo e prazo da tarefa
- Alterar estado da tarefa
- Deletar tarefa

## ✔️ Requisitos

- [x] checksExistsUserAccount
- [x] checksCreateTodosUserAvailability
- [x] checksTodoExists
- [x] findUserById

## 💻 Testes
- [x] Should be able to find user by username in header and pass it to request.user
- [x] Should not be able to find a non existing user by username in header
- [x] Should be able to let user create a new todo when is in free plan and have less than ten todos
- [x] Should not be able to let user create a new todo when is not Pro and already have ten todosShould not be able to let user create a new todo when is not Pro and already have ten todos
- [x] Should not be able to let user create a new todo when is not Pro and already have ten todos
- [x] Should be able to put user and todo in request when both exits
- [x] Should not be able to put user and todo in request when user does not exists
- [x] Should not be able to put user and todo in request when todo id is not uuid
- [x] Should not be able to put user and todo in request when todo does not exists
- [x] Should be able to find user by id route param and pass it to request.user
- [x] Should not be able to pass user to request.user when it does not exists


## 🚀 Como executar

1) Clonar o projeto do github:
    `git clone https://github.com/Luizrebelatto/challenge-02-node-js-middlewares.git`

2) Abrir terminal(CMD/TERMINAL ou VSCode/CMD) e acessar a pasta raiz do projeto (pelo terminal).
    
3) Instalar Dependências:
  execute `yarn`

4) Rodar Aplicação no http://localhost:3333:
    `yarn dev`
    
5) Rodar Testes:
    `yarn test`      

---

Desenvolvido por👋🏻:
- [Luiz Gabriel Rebelatto](https://www.linkedin.com/in/luiz-gabriel-rebelatto-bianchi-67097413b/)


