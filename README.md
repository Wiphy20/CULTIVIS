# 🌱 CULTIVIS — Sistema Inteligente para Gerenciamento e Monitoramento Agrícola

O **CULTIVIS** é um projeto acadêmico que busca integrar tecnologia e agricultura por meio de uma solução para gerenciamento de propriedades agrícolas e monitoramento de condições ambientais.

A proposta reúne uma aplicação mobile, um Back-End, um banco de dados e dispositivos IoT para centralizar informações, acompanhar leituras de sensores e gerar alertas relacionados às condições monitoradas. O projeto também explora o uso de inteligência artificial para auxiliar na configuração do monitoramento agrícola.

> Projeto desenvolvido em equipe como Trabalho de Conclusão de Curso do programa Desenvolvimento de Sistemas AMS.

## 🎯 Objetivo

Desenvolver uma solução integrada para apoiar o gerenciamento agrícola, reunindo informações sobre propriedades, plantações e produção, além de permitir o acompanhamento de variáveis ambientais por meio de sensores.

O sistema busca facilitar a organização das informações e contribuir para a identificação de condições que mereçam atenção durante o monitoramento.

## ✨ Funcionalidades e recursos

- **Gerenciamento agrícola:** organização de informações sobre propriedades, plantações e produção.
- **Monitoramento ambiental:** coleta e processamento de leituras de sensores, incluindo temperatura, umidade e pH.
- **Sistema de alertas:** identificação de condições que ultrapassam os parâmetros configurados.
- **Autenticação e validação:** controle de autenticação e validação dos dados processados pela aplicação.
- **Integração com IoT:** comunicação entre dispositivos de monitoramento e os componentes de software.
- **CULTIVIS IA:** protótipo de assistência inteligente para consultar informações sobre culturas agrícolas e gerar sugestões estruturadas de configuração do monitoramento.
- **CULTIVISbox:** proposta de hardware para integrar os componentes de monitoramento, atualmente em fase de prototipagem.

O projeto continua em desenvolvimento, e algumas funcionalidades ainda dependem de integração e aprimoramento.

## 🏗️ Arquitetura da solução

O CULTIVIS está organizado em componentes que trabalham em conjunto para viabilizar o gerenciamento e o monitoramento agrícola.

| Componente | Tecnologias | Responsabilidade |
|---|---|---|
| Aplicativo mobile | React Native, Expo e JavaScript | Interface de interação com o sistema |
| Back-End | Node.js, Express e TypeScript | APIs, regras de negócio, validação e processamento |
| Banco de dados | PostgreSQL, Prisma ORM e Supabase | Persistência e organização das informações |
| IoT | ESP32 e sensores | Coleta de variáveis ambientais |
| Inteligência artificial | Google Gemini API e SDK `@google/genai` | Protótipo de assistência à configuração do monitoramento |

A integração completa entre todos os componentes está em evolução.

## 📚 Documentação

Para conhecer melhor a estrutura técnica do CULTIVIS, consulte:

- [Arquitetura do sistema](docs/arquitetura.md) — visão geral dos componentes, tecnologias e organização da solução.
- **Testes e validação:** documentação em preparação.
- **Hardware e IoT:** materiais visuais e registros de testes serão adicionados.
- **Aplicativo mobile:** documentação a atualizar após confirmação do estado atual com a equipe.

## 🧰 Tecnologias utilizadas

**Back-End**
- Node.js
- Express
- TypeScript
- Zod

**Banco de dados**
- PostgreSQL
- Prisma ORM
- Supabase

**Autenticação e proteção de informações**
- Supabase Auth
- bcrypt

**Inteligência artificial**
- Google Gemini API
- SDK `@google/genai`
- Function Calling
- Structured Output em JSON

**Aplicativo e IoT**
- React Native
- Expo
- JavaScript
- ESP32
- Sensores de temperatura, umidade e pH

## 🗄️ Banco de dados

O banco de dados foi estruturado para organizar as principais entidades do sistema e seus relacionamentos, incluindo informações relacionadas a usuários, propriedades, dispositivos IoT, sensores, leituras, plantações, produção e alertas.

A modelagem foi desenvolvida considerando a necessidade de centralizar os dados agrícolas e permitir a integração com os demais componentes da solução.

Atualmente, o banco conta com nove tabelas, e sua estrutura poderá evoluir conforme novas funcionalidades forem implementadas, incluindo a persistência de configurações de monitoramento sugeridas pela CULTIVIS IA.

## 🤖 CULTIVIS IA

O CULTIVIS IA é um protótipo independente que explora o uso de inteligência artificial para auxiliar na configuração do monitoramento de culturas agrícolas.

Utilizando a API do Google Gemini, o protótipo consulta uma base demonstrativa de conhecimento agrícola e produz sugestões estruturadas contendo informações sobre a cultura, os sensores e os parâmetros de monitoramento.

Entre os recursos implementados no protótipo estão:

- **Function Calling:** consulta de informações por meio de uma função definida pela aplicação.
- **Structured Output:** geração de respostas em formato JSON estruturado.
- **Confirmação do usuário:** solicitação de confirmação antes da aplicação demonstrativa de uma configuração.

Atualmente, o protótipo funciona separadamente do Back-End principal. A persistência das configurações no banco de dados e a integração com o monitoramento do sistema estão previstas para etapas futuras.

## 📡 Hardware e CULTIVISbox

A CULTIVISbox é uma proposta de hardware para integrar os componentes de monitoramento ambiental do projeto.

A equipe está desenvolvendo um protótipo com fabricação por impressão 3D, explorando uma estrutura física para acomodar componentes eletrônicos e sensores.

O projeto também envolve testes práticos com sensores e plantas reais, buscando observar seu funcionamento em condições de cultivo.

A evolução da CULTIVISbox considera a possibilidade de transformá-la futuramente em parte de uma solução de monitoramento agrícola destinada a produtores. Essa possibilidade ainda depende de desenvolvimento, integração e validação adicionais.

## 🧪 Testes e experimentação

Durante o desenvolvimento, foram realizados testes para verificar diferentes partes da solução, incluindo:

- **API:** testes de requisições HTTP e respostas dos endpoints utilizando Thunder Client.
- **Banco de dados:** verificações de operações de persistência, consultas e relacionamentos.
- **Monitoramento:** testes envolvendo leituras de sensores e processamento de alertas.
- **Hardware:** experimentação com sensores em testes práticos com plantas reais.

As evidências e os resultados documentados serão organizados para apresentar os cenários verificados e o estágio atual do sistema.

## 🔎 Pesquisa exploratória

Como parte do desenvolvimento, a equipe realizou um questionário com estudantes da área de Agronegócio para conhecer percepções, necessidades e sugestões relacionadas à proposta do CULTIVIS.

A iniciativa buscou aproximar o desenvolvimento tecnológico das perspectivas de pessoas ligadas ao setor. Os aprendizados e resultados que puderem ser divulgados serão apresentados nesta documentação, respeitando a privacidade dos participantes.

## 👨‍💻 Minha contribuição

Minha atuação no CULTIVIS está concentrada principalmente no Back-End, na estruturação do banco de dados e no desenvolvimento de um protótipo de inteligência artificial.

**Back-End e segurança**
- Desenvolvimento de funcionalidades e APIs com Node.js, Express e TypeScript.
- Implementação da autenticação com Supabase Auth.
- Implementação da validação de dados com Zod.
- Utilização de bcrypt na proteção de informações sensíveis associadas aos dispositivos IoT.
- Desenvolvimento e organização de regras de negócio e processamento de alertas.

**Banco de dados**
- Planejamento e modelagem da estrutura de dados.
- Criação das tabelas e definição dos relacionamentos.
- Organização das entidades e integração do banco com o Back-End.
- Planejamento da evolução do modelo de dados para persistir configurações de monitoramento sugeridas pela IA.

**CULTIVIS IA**
- Desenvolvimento de um protótipo independente com a API do Google Gemini.
- Implementação de consulta a uma base demonstrativa por meio de Function Calling.
- Definição de uma estrutura JSON para as sugestões geradas.
- Implementação do fluxo de confirmação e aplicação demonstrativa das configurações.

O projeto é desenvolvido em equipe, e os demais componentes possuem contribuições específicas de seus respectivos integrantes.

## 🚧 Estado atual e próximos passos

O CULTIVIS continua em desenvolvimento. Entre as próximas etapas estão:

- Evoluir a base de conhecimento agrícola utilizada pelo protótipo de IA.
- Integrar o CULTIVIS IA ao Back-End principal.
- Criar a estrutura de persistência para as configurações sugeridas pela IA.
- Integrar as configurações aprovadas ao processamento de leituras e alertas.
- Evoluir o protótipo físico da CULTIVISbox.
- Ampliar os testes e a documentação dos componentes.
- Consolidar os resultados da pesquisa exploratória e os aprendizados obtidos.

## 👥 Equipe

O CULTIVIS é um projeto colaborativo desenvolvido por:

- **Filipi Samuel Mariano de Souza**
- **Gabriel dos Reis Gomes**
- **João Victor Baptista Faria**

Os perfis profissionais e as contribuições individuais dos integrantes serão adicionados a esta seção.

## 📚 Contexto acadêmico

Projeto desenvolvido como Trabalho de Conclusão de Curso do programa Desenvolvimento de Sistemas AMS, com foco na aplicação prática de desenvolvimento de software, banco de dados, Internet das Coisas e inteligência artificial.

---

**CULTIVIS — Tecnologia para apoiar o monitoramento e o gerenciamento agrícola.**
