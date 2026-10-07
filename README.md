<div align="center">

# Danilo Mendes

### Desenvolvedor Back-End | Java 17 · AWS Lambda · PostgreSQL · Integrações

[LinkedIn](https://www.linkedin.com/in/danilomendesaraujo/) · [E-mail](mailto:danilodev.br@gmail.com) · [Repositórios](https://github.com/Danilo-tec-2003?tab=repositories)

</div>

---

## Perfil profissional

Desenvolvedor back-end com atuação em sistemas corporativos para logística, transporte e operações comerciais. Trabalho principalmente com **Java 17**, **Spring Boot**, **AWS Lambda**, **PostgreSQL**, aplicações web e integrações entre sistemas.

Minha rotina envolve compreender regras de negócio, refinar soluções, orientar implementações, evoluir funcionalidades, investigar problemas entre aplicação e banco de dados e acompanhar correções até a validação. Também atuo com interfaces em Vue, relatórios operacionais, processamento de arquivos e integrações HTTP ou baseadas em troca de dados.

Valorizo código que torne a regra explícita, decisões técnicas proporcionais ao problema e documentação que ajude outras pessoas a manter o sistema com segurança.

## O que entrego na prática

- Desenvolvimento e evolução de funcionalidades com Java 17, Spring Boot, AWS Lambda, Vue e PostgreSQL.
- Construção e consumo de APIs e integrações com JSON, XML, CSV, XLSX, SFTP e HTTP.
- Modelagem, consultas SQL, manutenção de views e investigação de inconsistências de dados.
- Diagnóstico de bugs em homologação e produção atravessando interface, backend, banco, relatórios e serviços externos.
- Criação e manutenção de relatórios com JasperReports, parâmetros, sub-relatórios e consultas SQL.
- Acompanhamento da mudança desde o entendimento da demanda até sua validação.

## Refinamento técnico

Transformo demandas em orientação técnica para o time, detalhando:

- regras de negócio e comportamento esperado;
- requisitos funcionais e não funcionais;
- validações, critérios de aceite e cenários de erro;
- impactos entre frontend, backend, banco, relatórios e integrações;
- riscos de desempenho, segurança, compatibilidade e regressão;
- arquivos, camadas e sequência recomendada para implementação.

## Qualidade e colaboração

- Code review orientado a regra de negócio, contratos, dados, segurança e aderência ao padrão do sistema.
- Participação em refinamentos, Sprint Reviews e retrospectivas.
- Acompanhamento das demandas no IceScrum com organização Kanban.
- Apoio técnico aos demais desenvolvedores e compartilhamento de conhecimento no time.
- Uso de Git/GitLab, fluxo de branches e commits semânticos no desenvolvimento diário.

## Engenharia assistida por IA

Utilizo IA como apoio à investigação, ao refinamento, à análise de impacto, à revisão de código e à criação de testes. As sugestões são confrontadas com o código real, schema, contratos, padrões locais e validações executáveis; a decisão e a responsabilidade técnica permanecem humanas.

## Competências centrais

| Área | Tecnologias e práticas |
| --- | --- |
| Backend | Java 8/17, Spring Boot, Spring Data JPA, AWS Lambda, JSP, Servlets, APIs REST |
| Dados | PostgreSQL, MySQL, SQL, modelagem, análise e consistência de dados |
| Frontend | Vue, Angular, TypeScript, JavaScript, HTML, CSS e jQuery |
| Integrações | HTTP, JSON, XML, CSV, XLSX, SFTP, OpenAPI e Swagger |
| Relatórios | JasperReports, iReports e consultas orientadas a relatórios |
| Engenharia | Refinamento técnico, revisão de código, documentação, investigação de falhas e Git |
| Colaboração | Scrum, Sprint Review, retrospectiva, IceScrum e Kanban |
| Ecossistema | Docker, Docker Compose, Maven, Gradle, RabbitMQ, Go e Python |

## Projetos públicos selecionados

### [Travel Agency](https://github.com/Danilo-tec-2003/travel-agency)

Sistema de reservas construído com três microserviços em Spring Boot, comunicação assíncrona por RabbitMQ, persistência em PostgreSQL e execução integrada com Docker Compose.

O fluxo percorre todo o ciclo de uma reserva: criação, processamento, confirmação ou cancelamento e notificação por e-mail. Cada serviço possui uma responsabilidade definida, e os estados são propagados por eventos entre `booking-service`, `reservation-service` e `notification-service`.

**Evidências de engenharia:**

- consumo idempotente de eventos, com registro dos identificadores já processados;
- validação de entrada e tratamento global de respostas de erro;
- notificação por e-mail com Spring Mail e ambiente local isolado pelo Mailpit;
- testes unitários das regras principais e do processamento de eventos;
- workflow de integração contínua para executar os testes dos serviços;
- logs orientados ao acompanhamento do fluxo distribuído;
- infraestrutura local reproduzível com PostgreSQL, RabbitMQ e os três serviços em containers.

**Próximo passo:** realizar o deploy na AWS e evoluir configuração de ambientes, automação de entrega, observabilidade e operação dos serviços.

### [FiscalMove FMS](https://github.com/Danilo-tec-2003/fiscalmove-fms)

Sistema web para gestão operacional de fretes, com cadastros, ocorrências, relatórios em PDF e integração fiscal por API HTTP.

**Foco de engenharia:** Java 8, JSP e Servlets, PostgreSQL, JasperReports, integração entre sistemas e organização de um fluxo corporativo de ponta a ponta.

### [Motor Fiscal Go](https://github.com/Danilo-tec-2003/motor-fiscal-go)

API para simulação e cálculo tributário auditável em operações de frete, considerando regras, vigência e prioridade.

**Foco de engenharia:** Go, PostgreSQL, API Key, correlation ID, rastreabilidade das decisões e memória de cálculo.

### [Importador de Tabelas de Frete](https://github.com/Danilo-tec-2003/importador-frete)

Aplicação para importar e validar tabelas de frete em CSV, com processamento concorrente e acompanhamento do progresso.

**Foco de engenharia:** Go, goroutines, worker pool, Vue 3, TypeScript, métricas e separação entre processamento e apresentação.

### [Análise de Pull Requests Públicos](https://github.com/Danilo-tec-2003/public-prs-analysis)

Ferramenta em Python para analisar Pull Requests públicos, classificar mudanças e produzir um painel técnico anonimizado.

**Foco de engenharia:** qualidade de código, leitura de histórico, classificação de mudanças e comunicação de indicadores técnicos.

## Formação contínua

Mantenho aprendizado direcionado aos problemas que encontro na prática: arquitetura modular, testes, mensageria, observabilidade, segurança, serviços em Go e infraestrutura em nuvem.

Também registro reflexões sobre engenharia e produto no repositório [O engenheiro de software com mentalidade de produto](https://github.com/Danilo-tec-2003/O-engenheiro-de-Software-com-mentalidade-de-produtos), conectando leitura, experiência profissional e aplicação prática.

## Direção técnica

Busco evoluir sistemas com atenção simultânea à regra de negócio, integridade dos dados, capacidade de diagnóstico e experiência de quem mantém e opera o software. Meu foco não é apenas concluir funcionalidades, mas compreender o problema, reduzir risco e entregar uma solução que continue clara depois da primeira versão.
