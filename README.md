# Banco-Digital-Guardian-Bank

## Descrição
Projeto -  banco digital utilizando arquitetura hexagonal e o Angular, com as principais funcionalidades bancárias: abrir conta, depósito, saque e consulta de saldo, é um banco extremante seguro para os dias de hoje.

## Setup

1. Instale PostgreSQL e configure banco.
2. Ajuste `src/main/resources/application.properties` para conexão.
3. Compile backend:
4. mvn clean install
mvn spring-boot:run
5. Configure credenciais API SMS e IA (OpenAI token).
6. No frontend:
cd frontend
npm install
ng serve
7. Acesse o frontend via http://localhost:4200
8.  Ou com Docker Compose:

## Funcionalidades

- Cadastro cliente completo.
- Login seguro JWT.
- Conta corrente com saldo, limite e extrato.
- Cartão de crédito digital.
- Pagamentos Pix e débitos automáticos.
- Bot IA para atendimento em tempo real.

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
