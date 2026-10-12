# Minha contribuição no CULTIVIS

## Sobre minha atuação

No desenvolvimento do **CULTIVIS — Sistema Inteligente para Gerenciamento e Monitoramento Agrícola**, minha atuação está concentrada principalmente no Back-End, na modelagem do banco de dados, no processamento de informações dos sensores e na experimentação com inteligência artificial.

Meu objetivo é contribuir para uma estrutura que permita integrar os diferentes componentes do sistema, organizar os dados agrícolas e implementar regras de negócio que apoiem o monitoramento e o gerenciamento das propriedades rurais.

## 1. Desenvolvimento Back-End

Participei do desenvolvimento da estrutura de Back-End, trabalhando na implementação da lógica responsável pelo processamento das informações e pela comunicação entre os componentes do sistema.

Minhas atividades incluem:

- Implementação de rotas, controllers e services.
- Desenvolvimento de regras de negócio.
- Implementação de mecanismos de autenticação e controle de acesso.
- Validação de dados de entrada.
- Processamento de informações relacionadas aos sensores e aos alertas.
- Integração dos componentes necessários ao funcionamento do sistema.

### Tecnologias utilizadas

- Node.js
- TypeScript
- APIs REST
- Supabase Auth
- Zod
- bcrypt

## 2. Modelagem e gerenciamento do banco de dados

Fui responsável por grande parte do trabalho de modelagem e implementação do banco de dados, incluindo o planejamento das tabelas, a definição dos relacionamentos e a organização das informações necessárias ao sistema.

A estrutura foi planejada para atender às diferentes áreas do gerenciamento agrícola, como propriedades, plantações, sensores, produção e alertas.

Também trabalhei na integração do Back-End com a camada de persistência de dados, utilizando Prisma ORM e Supabase com PostgreSQL.

### Principais atividades

- Planejamento da estrutura do banco de dados.
- Criação e organização das tabelas.
- Definição dos relacionamentos entre as entidades.
- Integração entre a aplicação e o banco de dados.
- Consideração da integridade e da organização dos dados.

## 3. Processamento de leituras e alertas

Também participei da implementação e adaptação da lógica responsável pelo processamento das leituras dos sensores e pelo tratamento dos alertas.

Essa parte do sistema busca transformar os dados coletados em informações úteis para o acompanhamento das condições monitoradas, contribuindo para que situações relevantes possam ser identificadas e apresentadas ao usuário.

O CULTIVIS contempla a integração com sensores de temperatura, umidade e pH, utilizados no contexto do monitoramento agrícola.

## 4. Protótipo experimental de inteligência artificial

Além do Back-End principal, desenvolvi um protótipo independente de inteligência artificial para explorar como modelos generativos podem auxiliar na configuração e no acompanhamento de parâmetros agrícolas.

O protótipo utiliza a API do Gemini e explora recursos que permitem ao modelo consultar informações estruturadas sobre culturas e produzir respostas em formato definido.

### Recursos explorados

- **Function Calling:** permite ao modelo solicitar a execução de uma função para consultar informações sobre uma cultura.
- **Structured Output:** utilização de uma estrutura de saída em JSON para organizar as respostas do modelo.
- **Interação com o usuário:** solicitação de confirmação antes de considerar uma configuração sugerida.
- **Consulta a informações agrícolas:** uso de uma base demonstrativa de conhecimento sobre culturas.

O desenvolvimento desse protótipo faz parte da investigação de possíveis aplicações de IA no contexto do CULTIVIS.

### Estado atual do protótipo

O protótipo funciona de maneira independente do Back-End principal. As informações utilizadas na demonstração são limitadas à implementação experimental, e as configurações não são persistidas no banco de dados.

Portanto, essa etapa representa uma exploração técnica de recursos de IA, e não uma integração concluída com todos os componentes do sistema.

## 5. Integração com o projeto

Minha atuação busca contribuir para a integração entre a lógica da aplicação, a estrutura de dados e os componentes de monitoramento agrícola.

O trabalho é desenvolvido em conjunto com a equipe, que também participa das demais frentes do projeto, incluindo o aplicativo móvel e o hardware de monitoramento.

A documentação e a evolução dessas integrações dependem do desenvolvimento conjunto dos componentes.

## 6. Aprendizados e competências desenvolvidas

O desenvolvimento do CULTIVIS tem contribuído para minha experiência prática em:

- Desenvolvimento de APIs e lógica de Back-End.
- Modelagem e organização de bancos de dados relacionais.
- Autenticação, controle de acesso e validação de dados.
- Integração entre tecnologias e componentes de software.
- Processamento de dados provenientes de sensores.
- Experimentação com APIs de inteligência artificial generativa.
- Organização de responsabilidades e desenvolvimento colaborativo.

## Considerações finais

O CULTIVIS representa uma oportunidade de aplicar conhecimentos de desenvolvimento de software em um problema relacionado ao gerenciamento e ao monitoramento agrícola.

Minha contribuição está especialmente relacionada à construção da estrutura de Back-End e de dados, além da exploração de recursos de inteligência artificial que poderão ser avaliados em futuras etapas do projeto.
