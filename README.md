# Desafio Tech Lead: Evolução Temporal de taxa de conversão

## Objetivo
O objetivo deste desafio é criar uma rota que exibe a **evolução temporal da taxa de conversão** por canal (Email, WhatsApp, Push Notifications, etc.) a partir de um banco de dados com milhões de registros. O maior desafio é otimizar a consulta de dados para garantir que o tempo de resposta da aplicação seja o mais rápido possível.

### Tecnologias permitidas

- **Backend**: Node.js, Python ou Golang.
- **Frontend**: React.
- **Banco de Dados**: PostgreSQL.
- **Contêinerização**: Docker.

## Requisitos Obrigatórios

- **Documentação Completa**: Detalhamento do processo de desenvolvimento, incluindo as escolhas feitas em termos de arquitetura, otimização de performance e trade-offs (ex: por que se escolheu uma determinada linguagem, estrutura ou técnica de otimização).
  
- **API**: Rota que retorna a evolução no tempo da taxa de conversão.
  
- **Contêinerização**: A aplicação deve estar dockerizada.


## Requisitos Adicionais

- **Front-end**: Implementar dashboard dos dados retornados.
  
- **Testes Automatizados**: Criar testes automatizados para garantir a qualidade e confiabilidade do código.
  
- **Filtros Adicionais**: Permitir que o usuário aplique filtros adicionais no dashboard.


### Considerações Importantes

#### 1. Detalhamento de Status.
Segue lista de status para identificação nos dados disponibilizados.

- 1 - Válido
- 2 - Inválido
- 3 - Incompleto
- 4 - Pendente
- 5 - Aberto
- 6 - Visualizou
