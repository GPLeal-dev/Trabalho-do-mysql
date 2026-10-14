# Sistema de Gerenciamento de Ordens de Serviço

Projeto desenvolvido em **MySQL** para praticar conceitos de banco de dados relacional, simulando o funcionamento de uma assistência técnica.

O sistema permite armazenar e relacionar informações sobre **clientes, técnicos, serviços, ordens de serviço e finalizações**.

## 📌 Funcionalidades

- Cadastro de clientes;
- Cadastro de técnicos e suas especialidades;
- Cadastro de serviços e valores;
- Criação de ordens de serviço;
- Definição de prioridade da ordem;
- Controle do status do atendimento;
- Associação de vários serviços a uma ordem;
- Registro de pagamento e garantia;
- Cálculo do valor total das ordens;
- Consulta de ordens abertas.

## 🗂️ Estrutura do Banco de Dados

O projeto possui as seguintes tabelas:

- `Cliente`
- `Tecnico`
- `Servico`
- `OrdemServico`
- `OrdemServico_Servico`
- `Finalizacao`

As tabelas utilizam **chaves primárias e estrangeiras** para manter o relacionamento e a integridade dos dados.

## 🔎 Consultas utilizadas

Durante o projeto foram aplicados conceitos como:

```sql
SELECT
WHERE
ORDER BY
INNER JOIN
GROUP BY
COUNT()
SUM()
```

Também foram criadas consultas para:

- Listar ordens abertas;
- Exibir serviços associados às ordens;
- Calcular subtotal dos serviços;
- Calcular o valor total de cada ordem.

## 🛠️ Tecnologias

- MySQL
- SQL
- MySQL Workbench

## 🎯 Objetivo

O objetivo deste projeto foi colocar em prática conhecimentos de **Banco de Dados Relacional**, principalmente criação de tabelas, relacionamentos, inserção de dados e elaboração de consultas SQL.

## 👨‍💻 Autor

Desenvolvido por **Gabriel Leal** como projeto de estudo na área de Banco de Dados e Ciência da Computação.
