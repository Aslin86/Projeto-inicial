# Sistema Casa de Leilões

## Sobre o Projeto

Sistema informatizado desenvolvido para automatizar e organizar
as rotinas operacionais de uma casa de leilões. O sistema permite
o cadastro de itens, lances, leiloeiros e compradores, além de
gerar relatórios das transações realizadas.

## Funcionalidades

- Cadastro e gerenciamento de itens para leilão
- Registro de lances em tempo real
- Controle de leiloeiros e compradores
- Histórico completo de leilões realizados
- Geração de relatórios gerenciais

## Tecnologias Utilizadas

- **Java** (JDK 11+) — linguagem principal de desenvolvimento
- **MySQL** (8.x) — banco de dados relacional
- **JDBC** — conexão entre Java e MySQL
- **Git / GitHub** — controle de versão

## Como Executar

1. Clone o repositório:
   git clone https://github.com/seu-usuario/casa-leiloes.git
2. Importe o banco de dados: execute o script `banco.sql`
3. Configure a conexão em `src/config/Conexao.java`
4. Execute a classe `Main.java`
