# Etapa 4: Documentação

## Descrição
Nessa etapa, foi adicionada a documentação ao código-fonte, utilizando os padrões do Javadoc para descrever as classes, métodos e variáveis.

### Alterações Realizadas:
- **Adição de Javadoc:** Foram incluídos comentários no formato Javadoc para explicar o propósito das classes e métodos.
- **Comentários no código:** Comentários explicativos também foram adicionados onde necessário.

### Instruções:
1. O código foi documentado com Javadoc, facilitando a compreensão do funcionamento de cada parte do código.
2. A documentação gerada pode ser acessada na pasta `docs` após rodar o comando `javadoc`.
3. O arquivo `README.md` contém as instruções e explicações sobre a documentação.

## Como usar:
Para visualizar a documentação gerada, basta abrir o arquivo `index.html` dentro da pasta `docs` após gerar o Javadoc.

## Exemplo de Uso:
```java
User user = new User();
boolean exists = user.verificarUsuario("login", "senha");
