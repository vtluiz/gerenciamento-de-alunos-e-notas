# gerenciamento-de-alunos-e-notas

Este projeto é um sistema de gerenciamento escolar simples que permite cadastrar alunos, cursos e registrar notas. O sistema também permite a realização de consultas para visualizar as notas dos alunos, calcular médias e atualizar dados. O banco de dados foi implementado utilizando SQL.

## Estrutura do Banco de Dados

O banco de dados contém as seguintes tabelas:

- **Alunos**: Armazena os dados dos alunos, incluindo nome, data de nascimento e endereço.
- **Cursos**: Armazena os cursos disponíveis, com uma breve descrição.
- **Notas**: Armazena as notas dos alunos nos diferentes cursos.

## Scripts SQL

Os seguintes arquivos SQL estão disponíveis na pasta `src/`:

- **database.sql**: Contém a criação das tabelas `Alunos`, `Cursos` e `Notas`, além da inserção de dados de exemplo.
- **consultas.sql**: Contém várias consultas úteis, como a visualização de notas por curso, cálculo de médias e obtenção da maior nota de cada aluno.
- **atualizacoes.sql**: Contém comandos para atualização de informações (como alterar notas ou dados dos alunos) e exclusão de registros.

## Passos para Utilização

1. Clone este repositório.
2. Importe o arquivo `database.sql` em seu banco de dados MySQL ou MariaDB.
3. Execute as consultas no arquivo `consultas.sql` para gerar relatórios.
4. Utilize o arquivo `atualizacoes.sql` para manter o banco de dados atualizado.

## Requisitos

- MySQL ou MariaDB
- Acesso a um terminal SQL

## Licença

Este projeto está sob a licença MIT.
