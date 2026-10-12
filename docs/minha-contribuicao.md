# Minha contribuição no CULTIVIS

## Sobre minha atuação

No desenvolvimento do **CULTIVIS — Sistema Inteligente para Gerenciamento e Monitoramento Agrícola**, minha atuação está concentrada principalmente no Back-End, na modelagem do banco de dados, no processamento de informações dos sensores e na experimentação com inteligência artificial.

Meu objetivo é contribuir para uma estrutura que permita integrar os diferentes componentes do sistema, organizar os dados agrícolas e implementar regras de negócio que apoiem o monitoramento e o gerenciamento das propriedades rurais.

## 1. Desenvolvimento Back-End e autenticação

Fui responsável pelo desenvolvimento das funcionalidades de autenticação do CULTIVIS, além de atuar na implementação da estrutura de Back-End e das regras de negócio da aplicação.

Minha atuação incluiu a implementação dos mecanismos necessários à autenticação dos usuários, à validação de dados e ao controle de acesso, contribuindo para a segurança e a organização do funcionamento do sistema.

Também fui responsável pela elaboração da parte escrita do TCC referente à autenticação, documentando essa funcionalidade no contexto do projeto.

### Principais responsabilidades

- Implementação das funcionalidades de autenticação.
- Desenvolvimento e integração da lógica de controle de acesso.
- Validação dos dados de entrada.
- Implementação de rotas, controllers e services do Back-End.
- Desenvolvimento de regras de negócio.
- Processamento dos dados relacionados ao monitoramento agrícola e aos alertas.

### Tecnologias utilizadas

- Node.js e TypeScript.
- APIs REST.
- Supabase Auth.
- Zod para validação de dados.
- bcrypt para operações de segurança relacionadas a dados sensíveis.

## 2. Modelagem, implementação e testes do banco de dados

Fui responsável por todo o trabalho relacionado ao banco de dados do CULTIVIS, desde o planejamento e a modelagem até a implementação e os testes.

Essa atuação envolveu a definição da estrutura de dados necessária ao sistema, a criação das tabelas, o estabelecimento dos relacionamentos entre as entidades e a verificação do funcionamento da estrutura implementada.

O banco de dados foi projetado para organizar as informações relacionadas às propriedades rurais, plantações, sensores, produção e alertas, permitindo que os diferentes componentes do sistema utilizem os dados de forma estruturada.

### Principais responsabilidades

- Planejamento e modelagem do banco de dados.
- Definição das entidades e de seus relacionamentos.
- Criação e implementação das tabelas.
- Organização e integridade dos dados.
- Integração do banco de dados com o Back-End.
- Realização de testes para verificar consultas, inserções e relacionamentos.
- Estruturação dos dados necessários ao processamento das leituras dos sensores e à geração de alertas.

### Tecnologias utilizadas

- PostgreSQL.
- Supabase.
- Prisma ORM.

## 3. Processamento de dados dos sensores e sistema de alertas

No desenvolvimento do monitoramento agrícola, minha responsabilidade está relacionada ao tratamento dos dados após sua coleta pelos dispositivos IoT.

Enquanto outro integrante da equipe ficou responsável pela programação do ESP32 e dos sensores em C/C++, incluindo a coleta das informações e a conexão dos dispositivos ao Supabase, trabalhei no restante do fluxo de processamento dessas informações dentro do sistema.

Minha atuação envolve a lógica responsável por lidar com os dados coletados, processá-los e disponibilizá-los para as funcionalidades do CULTIVIS.

### Principais responsabilidades

- Implementação e adaptação da lógica de processamento das leituras dos sensores.
- Tratamento dos dados recebidos dos dispositivos IoT.
- Desenvolvimento da lógica relacionada à geração de alertas automáticos.
- Integração do processamento dos dados com as funcionalidades do sistema.
- Preparação do fluxo de informações que serão apresentadas ao usuário no aplicativo.

O sistema contempla leituras relacionadas à temperatura, à umidade e ao pH, utilizadas no contexto do monitoramento agrícola.

### Evolução do monitoramento em tempo real

Uma das próximas etapas é concluir o dashboard de monitoramento do aplicativo. Para isso, pretendo utilizar o **Supabase Realtime**, permitindo que as atualizações relevantes sejam refletidas na interface em tempo real.

Essa funcionalidade ainda está em desenvolvimento e, por isso, não é apresentada como uma implementação concluída.

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
