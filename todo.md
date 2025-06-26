# TODO - Sistema CROSS API .NET 8.0

## Fase 1: Análise e estruturação inicial do projeto
- [x] Criar documento de análise técnica detalhada
- [x] Definir arquitetura e padrões a serem utilizados
- [x] Mapear todos os endpoints e suas dependências
- [x] Identificar componentes críticos e ordem de implementação

## Fase 2: Criação da estrutura base do projeto .NET 8.0
- [x] Criar estrutura de pastas seguindo Clean Architecture
- [x] Configurar arquivos .csproj para cada camada
- [x] Configurar solution (.sln)
- [x] Instalar pacotes NuGet necessários

## Fase 3: Implementação das entidades de domínio e DTOs
- [x] Implementar entidades do domínio (UserSession, Tax, City, etc.)
- [x] Implementar DTOs de resposta (TaxClass, ComboItem, etc.)
- [x] Implementar Value Objects necessários

## Fase 4: Configuração do Entity Framework e DbContext
- [x] Configurar CrossDbContext com todas as entidades
- [x] Configurar mapeamentos e relacionamentos
- [x] Configurar índices e constraints

## Fase 5: Implementação dos serviços de validação de sessão
- [x] Implementar ISessionValidationService
- [x] Implementar SessionValidationService
- [x] Implementar ValidateSessionAttribute

## Fase 6: Implementação dos serviços de negócio para Tax e City
- [x] Implementar ITaxService e TaxService
- [x] Implementar ICityService e CityService
- [x] Implementar lógicas de negócio específicas

## Fase 7: Implementação dos controllers TaxController e CityController
- [x] Implementar TaxController com todos os 9 endpoints
- [x] Implementar CityController com todos os 7 endpoints
- [x] Configurar validação de sessão nos endpoints

## Fase 8: Configuração de injeção de dependência, middleware e Program.cs
- [x] Configurar Program.cs com todas as dependências
- [x] Configurar middleware pipeline
- [x] Configurar autenticação JWT
- [x] Configurar Serilog e logging
- [x] Configurar CORS e Health Checks

## Fase 9: Implementação de validadores FluentValidation e AutoMapper
- [x] Implementar validadores para DTOs
- [x] Configurar perfis do AutoMapper
- [x] Integrar FluentValidation no pipeline
- [ ] Implementar mapeamentos entre entidades e DTOs

## Fase 10: Configuração de logging, Swagger e políticas de resiliência
- [x] Configurar Serilog
- [x] Configurar Swagger com JWT
- [x] Implementar políticas de resiliência com Polly
- [ ] Configurar Swagger/OpenAPI
- [ ] Implementar políticas Polly

## Fase 11: Criação de scripts SQL para estrutura do banco de dados
- [ ] Criar scripts de criação de tabelas
- [ ] Criar scripts de índices e constraints
- [ ] Criar scripts de dados iniciais

## Fase 12: Implementação de testes unitários básicos
- [ ] Configurar projeto de testes
- [ ] Implementar testes para serviços principais
- [ ] Implementar testes para controllers

## Fase 13: Documentação final e entrega dos arquivos
- [ ] Criar documentação de instalação e configuração
- [ ] Criar documentação da API
- [ ] Organizar arquivos finais para entrega

