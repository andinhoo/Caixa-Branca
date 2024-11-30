# User.java - Correções e Melhorias

## Erros Identificados
1. Driver incorreto no carregamento do MySQL.
2. Falta de tratamento de exceções adequado.
3. Objetos `Connection`, `Statement` e `ResultSet` não eram fechados.
4. Código vulnerável a SQL Injection.
5. Acesso direto a membros públicos sem encapsulamento.

## Melhorias Implementadas
- Utilização de `PreparedStatement` para evitar SQL Injection.
- Encapsulamento das variáveis `nome` e `result`.
- Gerenciamento correto de recursos usando `try-with-resources`.
- Adicionado tratamento de exceções com `e.printStackTrace()`.

## Como usar
1. Configure o banco de dados conforme o exemplo.
2. Execute a classe principal ou testes.
3. Insira credenciais válidas para verificar o funcionamento.
