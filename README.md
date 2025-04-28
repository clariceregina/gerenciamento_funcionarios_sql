# Gerenciamento de Funcionários e Projetos

Este projeto demonstra a criação, manipulação e exclusão de tabelas em SQL, aplicando comandos essenciais como `CREATE`, `INSERT`, `SELECT`, `UPDATE`, `DELETE` e `DROP`. O objetivo é praticar a gestão de informações de funcionários e projetos em um banco de dados relacional.

As consultas foram realizadas no SQLite Online.

## 📋 Descrição

As seguintes ações foram realizadas:

- Criação da tabela `tabela_funcionarios` para armazenar informações sobre funcionários.
- Inserção de 10 registros de funcionários com dados como nome, departamento e salário.
- Consulta de dados utilizando filtros (`WHERE`), seleção distinta (`DISTINCT`) e seleção condicional (`AND`).
- Atualização de salários para funcionários do departamento de TI.
- Exclusão de funcionários com salário inferior a R$ 4000.
- Criação da tabela `tabela_projetos`, associando projetos a gerentes (chave estrangeira).
- Inserção de registros na tabela de projetos e consultas específicas baseadas no gerente responsável.
- Remoção da tabela `tabela_funcionarios` do banco de dados.

## ⚡ Comandos Principais Executados

- **Criação de tabelas** com chave primária e chave estrangeira.
- **Inserção** de dados (`INSERT INTO`).
- **Consultas** simples e condicionais (`SELECT`, `WHERE`, `DISTINCT`).
- **Atualização** de registros (`UPDATE`).
- **Exclusão** de registros e tabelas (`DELETE`, `DROP`).

## 📈 Exemplos de Consultas Realizadas

- Listar todos os funcionários.
- Selecionar funcionários de um departamento específico.
- Atualizar salários dos funcionários de TI para R$ 7500.
- Deletar funcionários com salário inferior a R$ 4000.
- Listar projetos gerenciados por um gerente específico.
