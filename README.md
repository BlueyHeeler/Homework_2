MyRottenPotatoes

Trabalho do Homework 2 da matéria Engenharia de Software, baseado no livro Construindo Software como Serviço: Uma Abordagem Ágil Usando Computação em Nuvem (Primeira Edição, 1.1.2) de Armando Fox e David Patterson
Este projeto está relacionado à tarefa do Capítulo 4 - Introdução ao Rails, criação do site myrottenPotatoes.


Como Iniciar

Siga os passos abaixo para configurar o projeto localmente:

    Crie uma nova pasta e entre nela

mkdir myrottenpotatoes
cd myrottenpotatoes

Crie um novo projeto Rails
No terminal, execute:

rails new myrottenpotatoes -T

Substitua os arquivos

    Delete todos os arquivos e pastas dentro do diretório myrottenpotatoes.
    Substitua pelos arquivos deste repositório (clonando ou baixando o ZIP).

Acesse a pasta do projeto

cd myrottenpotatoes

Execute as migrações do banco de dados

rails db:migrate

Inicie o servidor

rails server

Acesse a aplicação
Abra o navegador e vá para http://localhost:3000. Se tudo estiver correto, a página será carregada com sucesso.
