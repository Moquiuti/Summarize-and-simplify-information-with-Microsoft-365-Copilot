# Resumo da reunião - Integração B2B

## 1. Objetivo da reunião

Alinhar os principais pontos técnicos e responsabilidades para uma integração B2B entre sistemas corporativos, utilizando API Gateway e documentação Swagger/OpenAPI como base para o consumo dos serviços.

## 2. Principais decisões

- A integração será conduzida por meio de APIs expostas via gateway.
- A documentação técnica deverá ser disponibilizada em formato Swagger/OpenAPI.
- O sistema consumidor ficará responsável por implementar o consumo dos endpoints conforme contrato definido.
- O sistema fornecedor ficará responsável por disponibilizar os endpoints, regras de autenticação e exemplos de payload.
- Os testes deverão ocorrer inicialmente em ambiente de homologação.
- Os cenários de sucesso e erro deverão ser validados antes da entrada em produção.

## 3. Itens de ação

| Ação | Responsável | Status |
|---|---|---|
| Disponibilizar documentação Swagger/OpenAPI | Time fornecedor | Pendente |
| Validar endpoints necessários para o fluxo inicial | Time consumidor | Pendente |
| Confirmar estratégia de autenticação | Arquitetura técnica | Pendente |
| Preparar ambiente de homologação | Time de infraestrutura | Pendente |
| Mapear cenários de erro e respostas esperadas | Times técnicos | Pendente |

## 4. Dúvidas em aberto

- Qual será o padrão definitivo de autenticação utilizado?
- Todos os endpoints necessários já estão disponíveis no ambiente de homologação?
- Haverá limite de requisições ou regras específicas de timeout?
- Como serão tratados erros de negócio e erros técnicos?
- Qual será o fluxo de suporte em caso de falha na integração?

## 5. Próximos passos

- Receber e revisar a documentação Swagger/OpenAPI.
- Validar os contratos dos endpoints.
- Criar uma primeira prova de consumo da API.
- Testar os principais cenários em homologação.
- Registrar eventuais ajustes necessários antes da entrada em produção.

## Observação sobre privacidade

Este documento foi produzido com dados anonimizados. Nenhum nome real, empresa, e-mail, URL interna, credencial, dado pessoal ou informação sensível foi incluído.
