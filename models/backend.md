📋 **Público-Alvo**


🎯 **Objetivo Geral**


  

🚶‍♀️ **Jornada do Usuário**

**Cenário Inicial**

*   

**Objetivo do Backend**

* 

🔧 **Tarefas de Implementação**

1. **Criação de Endpoint**
    *   **GET /states**
        *   **Descrição:** 

  

1. **Validações e Regras de Negócio**

2. **Testes Automatizados**
    *   **Cenários de sucesso:** 
    *   **Cenários de falha:** 

3. **Documentação da API**
    *   Atualizar o Swagger com:
    *   Descrição do endpoint e parâmetros disponíveis.
    *   Exemplos de requisição e resposta para diferentes cenários (com e sem filtros, com paginação).

🔄 **Fluxo de Trabalho**

    1. O frontend envia uma requisiçã com os parâmetros opcionais de paginação ou filtro.
    2. O backend busca os dados no banco de dados, incluindo as contagens.
    3. O backend retorna a lista formatada para exibição na tabela.

🧰 **Tecnologias e Ferramentas**

*   Framework: NestJS
*   ORM: Prisma
*   Banco de Dados: PostgreSQL
*   Testes: Vitest + Supertest
*   Documentação: Swagger