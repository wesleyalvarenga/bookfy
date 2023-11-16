# bookfy
Esse projeto foi construido seguindo as boas praticas da Arquitetura limpa pragmática, abaixo descrevo os tópcos abordados na aplicacao bem como a responsabilidade de cada camada.

# Tópicos
- Arquitetura Limpa
- Design orientado por domínio
- CQRS com MediatR
- Autenticação com Keycloak
- Testes com xUnit

## Camada de domínio
- Entidades
- Objetos de Valor
- Eventos de domínio
- Serviços de domínio
- Interfaces
- Exceções
- Enums

## Camada de aplicação
- Casos de uso - CQRS + MediatR
- Cross-cutting concerns
  - Logs
  - Validações
- Exceções
- Injeção de Dependencia

## Camada de Infraestrutura
- EF Core
  - Db Context
  - Configurações do EF
  - Repositórios
- Concorrência otimista
- Publicações de eventos de domínio

## Camada de apresentação
- Web Api, .NET 7
- Minimals API
- Setup injeção de dependências
- Docker compose

## Testes
- Testes de unidade com xUnit
- Testes de arquitetura para validar nomenclaturas e dependencias entre os projetos

:rocket: Documento em andamento! Em breve adicionarei comentários e explicações do funcionamento das partes do projeto como classes, tecnicas utilizadas, fluxos e etc.
