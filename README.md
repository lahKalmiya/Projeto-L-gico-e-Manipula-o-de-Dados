📚 Livraria Saber – Banco de Dados

Sistema de gerenciamento para uma livraria com integrações de livros, autores, clientes, vendas, papelaria e fornecedores.

📌 Sobre o Projeto

Este projeto contém a estrutura completa de um banco de dados MySQL para uma livraria, incluindo tabelas, relacionamentos, chaves estrangeiras e dados de exemplo.
O objetivo é oferecer um modelo funcional para estudos, testes e implementação de sistemas comerciais.

🗂️ Estrutura do Banco de Dados

O banco livraria_saber é composto pelos seguintes módulos:

📘 Módulo de Livros

livro: armazena informações dos livros vendidos.

autor: cadastro de autores.

editora: editoras responsáveis pelas publicações.

livro_autor: relacionamento N:N entre livros e autores.

🛍️ Vendas

venda: registro das vendas realizadas.

item_venda: itens vendidos (livros ou produtos de papelaria).

vendedor: funcionários responsáveis pelas vendas.

👥 Clientes

cliente: cadastro de clientes, incluindo CPF e endereço.

✏️ Papelaria

papelaria: produtos como cadernos, canetas, post-its etc.

fornecedor: fornecedores desses itens.

🔗 Principais Relacionamentos

Um livro pertence a uma editora.

Um livro pode ter vários autores.

Uma venda pertence a um cliente e um vendedor.

Um item_venda pode ser livro OU papelaria (restrição via CHECK).

Um produto de papelaria pertence a um fornecedor.

✔️ Recursos do Script

O arquivo inclui:

Criação de todas as tabelas com:

Primary keys

Foreign keys

Constraints

Restrições de unicidade

População com dados reais de exemplo

Configurações de ambiente:

Collations

Time zones

Revisão de verificações de chave estrangeira

Scripts de restauração no padrão MySQL Dump.
