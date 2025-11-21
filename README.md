# Banco-Digital-Guardian-Bank

## Descrição
Projeto exemplo para banco digital utilizando arquitetura hexagonal, com as principais funcionalidades bancárias: abrir conta, depósito, saque e consulta de saldo.

## Estrutura
- domain: entitades e regras de negócio.
- application.port: interfaces de portas (entrada e saída).
- adapters: implementações concretas para bancos de dados, APIs externas, REST API.
- bot: assistente digital para interação com cliente.

## Como Executar
1. Ter Java 17+ e Maven instalados.
2. Clonar o repositório.
3. Rodar `mvn clean install`.
4. Configurar adaptadores (banco de dados, SMS) conforme necessidade.
5. Executar via IntelliJ IDEA: Run `BancoDigitalApplication`.

## Testes
- Testes unitários estão localizados em `src/test/java`.
- Rodar com `mvn test`.

## IntelliJ IDEA
Importar como projeto Maven.
Configurar JDK.
Configurar Run Configurations para executar main class da aplicação.

---
