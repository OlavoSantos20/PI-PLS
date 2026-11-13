# Requisitos FURPS+ — Sprint A

## 1. Introdução

O modelo FURPS+ é utilizado para organizar os requisitos de um sistema informático, permitindo identificar tanto as funcionalidades que o sistema deve disponibilizar como as características relacionadas com a sua qualidade e as respetivas restrições.

Neste projeto, este modelo será aplicado à Plataforma de Literacia em Saúde para Jovens, com o objetivo de organizar os requisitos identificados durante a fase de análise.

## 2. Requisitos funcionais (Functionality)

Os requisitos funcionais descrevem as funcionalidades que a plataforma deve disponibilizar aos seus utilizadores.

- **RF01 — Registo de utilizadores:** O sistema deve permitir que os utilizadores criem uma conta na plataforma.
- **RF02 — Autenticação:** O sistema deve permitir que os utilizadores iniciem e terminem sessão.
- **RF03 — Gestão de perfil:** O sistema deve permitir que os utilizadores consultem e atualizem os seus dados de perfil.
- **RF04 — Consulta de conteúdos:** O sistema deve permitir consultar conteúdos educativos relacionados com a saúde.
- **RF05 — Pesquisa e filtragem:** O sistema deve permitir pesquisar e filtrar conteúdos por tema ou palavra-chave.
- **RF06 — Gestão de conteúdos:** O sistema deve permitir aos administradores criar, editar e remover conteúdos educativos.
- **RF07 — Consulta de atividades:** O sistema deve permitir consultar webinars e workshops disponíveis.
- **RF08 — Inscrição em atividades:** O sistema deve permitir que os utilizadores se inscrevam em webinars e workshops.
- **RF09 — Questionários:** O sistema deve permitir realizar questionários antes e depois das atividades de formação.
- **RF10 — Histórico de participação:** O sistema deve permitir consultar o histórico de participação nas atividades.
- **RF11 — Badges e certificados:** O sistema deve permitir atribuir badges e certificados aos participantes, de acordo com os critérios definidos.
- **RF12 — Recomendações:** O sistema deve apresentar sugestões de conteúdos educativos relacionados com os interesses e atividades anteriores dos utilizadores.
- **RF13 — Estatísticas:** O sistema deve permitir consultar estatísticas relacionadas com a utilização da plataforma e a participação nas atividades.
- **RF14 — Gestão administrativa:** O sistema deve disponibilizar funcionalidades de administração para gerir utilizadores, conteúdos e atividades.

## 3. Usabilidade (Usability)

Os requisitos de usabilidade estão relacionados com a facilidade de utilização e compreensão da plataforma.

- **RU01:** A interface deve ser simples e intuitiva, permitindo que os utilizadores encontrem facilmente as funcionalidades disponíveis.
- **RU02:** A plataforma deve apresentar uma organização clara dos conteúdos e das diferentes áreas.
- **RU03:** A interface deve adaptar-se a diferentes tamanhos de ecrã, incluindo computadores, tablets e smartphones.
- **RU04:** As mensagens de erro e confirmação devem ser claras e compreensíveis.
- **RU05:** A informação deve ser apresentada numa linguagem acessível ao público jovem.

## 4. Fiabilidade (Reliability)

Os requisitos de fiabilidade definem as condições necessárias para garantir o funcionamento correto da plataforma.

- **RR01:** O sistema deve validar os dados introduzidos pelos utilizadores antes de os guardar.
- **RR02:** A plataforma deve impedir o acesso a funcionalidades reservadas a utilizadores sem as permissões necessárias.
- **RR03:** O sistema deve evitar a perda de informação durante operações de registo e atualização de dados.
- **RR04:** A plataforma deve apresentar mensagens adequadas quando ocorrerem erros durante a utilização.
- **RR05:** O sistema deve garantir a integridade dos dados armazenados na base de dados.

## 5. Desempenho (Performance)

Os requisitos de desempenho definem as condições relacionadas com a rapidez e eficiência da plataforma.

- **RP01:** As páginas da plataforma devem ser carregadas num período de tempo adequado à utilização normal.
- **RP02:** As pesquisas de conteúdos devem apresentar os resultados sem atrasos significativos.
- **RP03:** O sistema deve suportar vários utilizadores a aceder à plataforma em simultâneo.
- **RP04:** As operações de consulta, registo e atualização devem ser executadas de forma eficiente.

## 6. Suportabilidade (Supportability)

Os requisitos de suportabilidade estão relacionados com a manutenção, evolução e compatibilidade do sistema.

- **RS01:** O código da aplicação deve estar organizado de forma a facilitar futuras alterações e correções.
- **RS02:** A plataforma deve permitir a adição de novas funcionalidades sem exigir alterações profundas em toda a aplicação.
- **RS03:** O sistema deve permitir a realização de cópias de segurança da informação armazenada.
- **RS04:** A aplicação deve ser compatível com os navegadores modernos mais utilizados.
- **RS05:** A documentação do projeto deve acompanhar as alterações realizadas ao longo do desenvolvimento.

## 7. Restrições e requisitos adicionais (+)

Esta categoria identifica as restrições técnicas e condições adicionais consideradas para o desenvolvimento da plataforma.

- **R+01 — Tecnologias:** O frontend será desenvolvido com React.
- **R+02 — Backend:** O backend será desenvolvido em Python, utilizando Flask.
- **R+03 — Base de dados:** A plataforma deverá utilizar uma base de dados para armazenar utilizadores, conteúdos, atividades, inscrições e restantes informações necessárias.
- **R+04 — Arquitetura:** A aplicação deverá separar o frontend, o backend e a camada de armazenamento de dados.
- **R+05 — Segurança:** Os dados dos utilizadores devem ser protegidos e o acesso às funcionalidades deve respeitar as permissões atribuídas.
- **R+06 — Repositório:** O código-fonte e a documentação do projeto devem ser mantidos no repositório GitHub do grupo.
- **R+07 — Responsividade:** A plataforma deverá poder ser utilizada em diferentes dispositivos.

## 8. Considerações finais

A aplicação do modelo FURPS+ permite organizar os requisitos da Plataforma de Literacia em Saúde para Jovens, facilitando a identificação das funcionalidades e das características de qualidade pretendidas.

Estes requisitos servirão de base às fases seguintes do projeto, podendo ser detalhados ou ajustados durante o desenvolvimento, de acordo com as necessidades identificadas.