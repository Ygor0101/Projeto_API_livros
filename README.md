## Visão Geral do Projeto
O objetivo deste projeto é desenvolver uma API RESTful simples utilizando Python e Flask para gerenciar um cadastro de livros. O sistema permite realizar operações de CRUD (Criar, Ler, Atualizar e Excluir), funcionando como um backend básico para controle de acervo.

## Estrutura de dados (O que guardamos)
Cada livro cadastrado no sistema contém obrigatoriamente as seguintes informações:

id: Identificador único numérico do livro.

titulo: Título da obra.

autor: Nome do autor do livro.

## Requisitos Funcionais (O que a API FAZ)
São os endpoints e ações disponíveis na API:

RF01 - Listar todos: Consultar a lista completa de livros cadastrados (GET /livros).

RF02 - Buscar por ID: Consultar os detalhes de um livro específico a partir do seu ID (GET /livros/<id>).

RF03 - Cadastrar: Adicionar um novo livro informando id, título e autor (POST /livros).

RF04 - Editar: Atualizar os dados de um livro já existente com base no seu ID (PUT /livros/<id>).

RF05 - Excluir: Remover um livro do sistema utilizando seu ID (DELETE /livros/<id>).

## Requisitos Não Funcionais (Como o sistema É)
RNF01 - Interface: A aplicação roda como um servidor web local (API HTTP), consumida via requisições JSON.

RNF02 - Armazenamento: Os dados são salvos temporariamente apenas na memória RAM (utilizando listas e dicionários em Python), sem persistência em banco de dados nesta versão.
