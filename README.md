# Banco-de-dados-I---
programe códigos SQL para criar um banco de dados chamado ESCOLA e deixe-o pronto para o uso. Depois, pesquise qual é o comando utilizado para inserir uma tabela no banco de dados e siga as instruções:

crie uma tabela chamada ALUNO;
defina os atributos da tabela;
adicione a chave primária de nome ID (identificador);
adicione um atributo nome do tipo varchar;
adicione um atributo e-mail do tipo varchar;
adicione um atributo endereço do tipo varchar.


-- Criar o banco de dados ESCOLA
CREATE DATABASE ESCOLA;

-- Usar o banco de dados ESCOLA
USE ESCOLA;

-- Criar a tabela ALUNO
CREATE TABLE ALUNO (
  ID INT PRIMARY KEY,
  nome VARCHAR(50),
  email VARCHAR(100),
  endereco VARCHAR(200)
);

-- Inserir registro na tabela ALUNO
INSERT INTO ALUNO (ID, nome, email, endereco)
VALUES (1, 'João', 'joao@example.com', 'Rua A'),
       (2, 'Maria', 'maria@example.com', 'Rua B'),
       (3, 'Pedro', 'pedro@example.com', 'Rua C');
