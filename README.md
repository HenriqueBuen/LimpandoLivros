# O Faxineiro Implacável (Concluído)

Neste projeto, concluímos a atividade "O Faxineiro Implacável" com sucesso. A tarefa consistia em criar e organizar um banco de dados chamado "Biblioteca", normalizar os dados, ajustar um script de criação de livros e garantir que tudo esteja devidamente estruturado para adicionar novos livros à biblioteca.
Objetivos da Atividade

O objetivo dessa atividade era aprender a lidar com erros, revisar e refatorar um código e aplicar os princípios de normalização de dados em um banco de dados SQL. As etapas envolviam:

    Criar um banco de dados chamado "Biblioteca".
    Normalizar os dados, separando as informações de livros, autores e editoras.
    Corrigir um script de inserção de livros para refletir a nova estrutura do banco de dados.

Conclusão
Passo 1: Criando o Banco de Dados

Primeiro, criamos com sucesso um banco de dados chamado "Biblioteca" para armazenar nossos registros de livros, autores e editoras.
Passo 2: Normalização dos Dados

Normalizamos os dados para garantir que as informações estejam bem organizadas e eficientes. Isso envolveu:

    Adicionar a regra AUTO_INCREMENT para a chave primária livros_id na tabela "Livros".
    Criar tabelas separadas para "Autores" e "Editoras" com chaves primárias para gerar relacionamentos.
    Utilizar o comando ALTER TABLE para eliminar as colunas 'autor' e 'editora' da tabela "Livros" e adicionar as colunas 'autor_id' e 'editora_id' como chaves estrangeiras das respectivas tabelas "Autores" e "Editoras".
    Transferir os valores dos autores e editoras do script inicial para as novas tabelas "Autores" e "Editoras".

Passo 3: Corrigindo o Script de Inserção

Modificamos o script de inserção para adicionar novos livros à biblioteca, fazendo referência aos IDs dos autores e editoras adequados nas tabelas "Autores" e "Editoras. Isso garantiu que os novos registros estejam de acordo com a estrutura normalizada do banco de dados.
Como Foi Feito

Este projeto foi concluído seguindo as etapas detalhadas no README original da atividade. Utilizamos comandos SQL para criar tabelas, adicionar chaves primárias, criar tabelas separadas para autores e editoras, adicionar chaves estrangeiras e refatorar o script de inserção. Os comandos ALTER TABLE, DROP, IF EXISTS e IF NOT EXISTS foram utilizados conforme necessário.

A normalização dos dados garantiu que nossa biblioteca estivesse organizada e otimizada para futuras adições de livros, autores e editoras.




![untitled](https://github.com/HenriqueBuen/LimpandoLivros/assets/142261748/ad0f38c5-6979-49f9-b706-55bbbf7772be)
