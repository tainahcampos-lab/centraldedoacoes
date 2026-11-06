Escopo do Projeto — Central de Doações

1. Identificação

Nome do projeto: Central de Doações
Linguagem: Python
Banco de dados: PostgreSQL


2. Apresentação

O projeto consiste no desenvolvimento de um sistema de gerenciamento de doações, destinado ao cadastro de doadores, registro de itens recebidos, controle de estoque e gerenciamento da distribuição de produtos para projetos sociais.

3. Problema

Organizações que recebem doações precisam administrar informações sobre doadores, produtos recebidos, quantidades disponíveis e instituições beneficiadas.
A ausência de um controle centralizado pode ocasionar dificuldades na organização dos registros, divergências no estoque e falta de acompanhamento da destinação dos produtos.

4. Objetivo geral

Desenvolver uma aplicação em Python integrada ao PostgreSQL para gerenciar o recebimento, armazenamento e distribuição de doações.

5. Objetivos específicos

Cadastrar e consultar doadores.
Registrar doações recebidas.
Classificar produtos por categorias.
Controlar entradas e saídas de estoque.
Cadastrar projetos sociais beneficiados.
Registrar a distribuição dos produtos.
Consultar quantidades disponíveis.
Gerar relatórios de movimentações e doações.

6. Funcionalidades previstas

Gerenciamento de doadores.
Gerenciamento de categorias e itens.
Registro de doações.
Gerenciamento de projetos sociais.
Controle de estoque.
Registro de entradas e saídas.
Controle de distribuição.
Consulta e emissão de relatórios.
7. Escopo e limitações

A primeira versão contemplará doações de produtos físicos, como alimentos, roupas, calçados, materiais escolares, produtos de higiene e produtos de limpeza.

8. Organização do desenvolvimento

O projeto será dividido em três módulos:

Módulo A — Doações: cadastro de doadores, categorias, itens e registro de doações.
Módulo B — Estoque: cadastro de projetos sociais, controle de estoque e distribuição.
Módulo C — Base e integração: conexão com banco de dados, estrutura central, menu, integração e relatórios.

9. Requisitos técnicos

Utilização de banco de dados relacional PostgreSQL.
Integridade referencial por meio de chaves primárias e estrangeiras.
Validação dos dados informados.
Tratamento de exceções.
Implementação de testes de unidade.
Organização modular do código.
Controle de versão com Git e GitHub.

10. Resultado esperado

Espera-se desenvolver um sistema funcional que permita gerenciar o ciclo das doações, desde o cadastro do doador e recebimento dos produtos até o controle de estoque e distribuição para projetos sociais.

A aplicação terá interface pelo terminal e não contemplará processamento de pagamentos, integração bancária ou aplicativo móvel.
