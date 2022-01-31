<h1 align="center">
    Aluracord - Matrix
</h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

<br>

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [JavaScript](https://www.javascript.com/)
- [Next.js](https://nextjs.org/)
- [Supabase](https://supabase.com/)

## 💻 Projeto

O Projeto Aluracord - Matrix se trata de um canal de chat em que os usuários que acessaram com seus logins conseguirão encaminhar mensagens e stickers tendo sua própria identificação.

Esta aplicação faz integração com a API do GitHub para que sejam recuperados dados do usuário que irá utilizar desta aplicação. Ao realizar o login, o usuário será encaminhado ao canal do chat.

Tendo como base para a idéia o programa Discord, o Aluracord foi desenvolvido utilizando o conceito de _Back-end as a service_ e está aberto a novas idéias para implementações de novas funcionalidades.

## 🔖 Layout

Você pode visualizar o layout do projeto através [desse link](https://www.figma.com/file/NLG1O4IA2GX9LlJpnTy49z/Imers%C3%A3o-React---Aluracord---Matrix?node-id=0%3A1). É necessário ter conta no [Figma](https://figma.com) para acessá-lo.

## 🚀 Como executar

* 🧑‍💻 **Conectando-se ao servidor criado**
    * Para acessar ao projeto em execução no ambiente da Vercel, acesse um dos seguintes links:
        [Link 1](aluracord-matrix-sable.vercel.app) / [Link 2](aluracord-matrix-git-main-andrenavarro.vercel.app) / [Link 3](aluracord-matrix-andrenavarro.vercel.app)
    * A partir deste acesso, conecte-se com seu login do GitHub
    * Feito isso, a página de chat estará disponível para envio e recebimento de mensagens em tempo real.

<br>

* 🌐 **Criando e se conectando a um novo servidor**
    * No [Github](https://github.com/AndreNavarro/Aluracord-Matrix), faça um clone deste projeto em sua máquina com o seguinte comando:
        ```
        git clone https://github.com/AndreNavarro/Aluracord-Matrix.git
        ```
    * Crie uma conta no [Supabase](https://supabase.com/) e faça a criação de um novo Projeto
    * Feito isso, copie os valores dos campos ```ANON PUBLIC``` e ```URL``` para os campos indicados no arquivo ```chat.js``` dentro do diretório */pages*. Substitua os valores existentes
    * No Supabase, clique em **Table editor**
    * Clique em **Create new Table** - Name: **mensagens**
        * Adicione novas colunas:
        * Name: **de** / Type: **text**
        * Name: **texto** / Type: **text**
    * No menu lateral, clique em **Database** e em **Replication**
    * Seguindo a tabela de nomes das tabelas criadas, à direita é possível visualizar um botão de ativação. Ative-o para que haja a replicação em tempo real.
    
    > Caso também queira executar o projeto no ambiente da Vercel, seguir os seguintes passos:

    * Primeiramente, é necessário que o projeto esteja em seus repositórios do Github
    * Autentique-se no site da [Vercel](https://vercel.com/) e conecte sua conta do Githuib
    * Selecione o projeto e clique em **Import**
    * Fazendo isso, você irá receber os links de acesso à aplicação através do e-mail cadastrado. Basta acessar e utilizar

## 📝 Licença

O Projeto Aluracord - Matrix foi desenvolvido durante a semana de Imersão React da Alura.