# Aula-de-banco-de-dados-DDL-e-DML
**DDL (Data Definition Language)** e **DML (Data Manipulation Language)** são dois tipos de comandos SQL que têm propósitos diferentes no contexto de um banco de dados. Vou explicar a diferença e como cada um é utilizado:

### 1. **DDL (Data Definition Language)**

A **DDL** é responsável pela definição e estruturação do banco de dados. Ela permite criar, alterar e excluir objetos no banco de dados, como tabelas, índices, views e esquemas.

#### Principais comandos da DDL:
- **CREATE**: Cria objetos no banco de dados, como tabelas, índices, etc.
  - Exemplo: `CREATE TABLE clientes (id INT, nome VARCHAR(100));`
  
- **ALTER**: Modifica a estrutura de objetos já existentes.
  - Exemplo: `ALTER TABLE clientes ADD email VARCHAR(100);`
  
- **DROP**: Exclui objetos do banco de dados.
  - Exemplo: `DROP TABLE clientes;`
  
- **TRUNCATE**: Remove todos os dados de uma tabela, mas não a estrutura dela.
  - Exemplo: `TRUNCATE TABLE clientes;`
  
- **RENAME**: Altera o nome de um objeto.
  - Exemplo: `RENAME TABLE clientes TO clientes_antigos;`

Esses comandos são usados para definir a estrutura do banco de dados e seus objetos.

### 2. **DML (Data Manipulation Language)**

A **DML** é usada para manipular os dados dentro dos objetos definidos pelo banco de dados. Ela permite inserir, atualizar, excluir e consultar dados.

#### Principais comandos da DML:
- **SELECT**: Recupera dados de uma ou mais tabelas.
  - Exemplo: `SELECT * FROM clientes;`
  
- **INSERT**: Insere novos dados em uma tabela.
  - Exemplo: `INSERT INTO clientes (id, nome, email) VALUES (1, 'João', 'joao@example.com');`
  
- **UPDATE**: Atualiza dados existentes em uma tabela.
  - Exemplo: `UPDATE clientes SET nome = 'João Silva' WHERE id = 1;`
  
- **DELETE**: Exclui dados de uma tabela.
  - Exemplo: `DELETE FROM clientes WHERE id = 1;`

Os comandos da DML são usados para manipular e interagir com os dados dentro do banco de dados.

---

### Resumo da diferença:

- **DDL**: Define a estrutura do banco de dados (como tabelas, índices, esquemas).
- **DML**: Manipula os dados dentro das tabelas do banco de dados (como inserir, atualizar e excluir dados).

Esses dois conjuntos de comandos são essenciais para administrar e trabalhar com bancos de dados em SQL.


Um **banco de dados** é uma coleção organizada de dados, que são armazenados e acessados de forma eficiente. Ele é projetado para armazenar, gerenciar e facilitar a recuperação de grandes volumes de dados de forma estruturada. A ideia é que o banco de dados ofereça maneiras de armazenar dados de forma segura, acessível e consistente.

Existem diferentes tipos de bancos de dados, como:

1. **Banco de Dados Relacional (RDBMS)**: 
   - Usa tabelas para armazenar dados em linhas e colunas. 
   - Exemplos: MySQL, PostgreSQL, Oracle, SQL Server.
   - Utiliza SQL (Structured Query Language) para manipular dados.

2. **Banco de Dados Não Relacional (NoSQL)**: 
   - São mais flexíveis, permitindo armazenamento de dados em formatos não estruturados ou sem estrutura fixa.
   - Exemplos: MongoDB, Cassandra, CouchDB.
   - Frequentemente utilizado para grandes volumes de dados distribuídos ou dados sem formato predefinido.

3. **Banco de Dados em Nuvem**:
   - Banco de dados hospedado na nuvem, facilitando a escalabilidade e o gerenciamento.
   - Exemplos: Amazon RDS, Google Cloud SQL, Azure SQL Database.

4. **Banco de Dados Hierárquico**:
   - Organiza dados em uma estrutura de árvore, onde cada registro tem um único "pai".
   - Exemplos: IBM Information Management System (IMS).

5. **Banco de Dados Orientado a Objetos**:
   - Armazena dados como objetos, como em linguagens de programação orientadas a objetos.
   - Exemplos: ObjectDB, db4o.

O modelo mais utilizado atualmente é o **relacional**, mas o **NoSQL** ganhou popularidade devido ao aumento do uso de dados não estruturados e à necessidade de escalabilidade.



