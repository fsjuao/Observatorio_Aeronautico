# Observatório de Inovação de São José dos Campos — Seven Solutions

Projeto da **Aprendizagem por Projetos Integrados (API)** do 1º semestre do curso de Tecnologia em Logística da **Fatec São José dos Campos "Professor Jessen Vidal"**, em parceria com o **CADI e a Secretaria de Inovação e Desenvolvimento Econômico de São José dos Campos**.

Projeto baseado na metodologia ágil SCRUM, procurando desenvolver a Proatividade, Autonomia, Colaboração e Entrega de Resultados dos estudantes envolvidos.

# Índice
* [Projeto (API)](#projeto-api)
* [Equipe](#equipe)
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Tecnologias Utilizadas](#tecnologias-utilizadas)
* [Personas](#personas)
* [Product Backlog](#product-backlog)
* [Critérios de Aceitação](#critérios-de-aceitação)
* [Competências desenvolvidas](#competências-desenvolvidas)
* [Registro das Sprints](#registro-das-sprints)


# Projeto (API)
Projeto pedagógico alicerçado na Metodologia API para ensino-aprendizado focado no desenvolvimento de competências e fundamentada nos pilares de aprendizado com problemas reais (RPBL), validação externa e mentalidade ágil.
Uso de estratégias para entender o problema, conceber uma solução viável ao desenvolver e implementar o MVP seguido de sua operação (CDIO).
Os resultados dos projetos devem obedecer ao Aviso Legal disponível no site da Fatec SJC com definição das datas do kickoff e das sprints.

**Tema do semestre:** Mapeamento do Ecossistema Industrial e de Serviços da Região de São José dos Campos.

# Equipe
|    Função     | Nome                                   | LinkedIn & GitHub |
| :-----------: | :------------------------------------- | :---------------: |
| Product Owner | João Carlos Florencio de Sousa         | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/) |
| Scrum Master  | Gessika                                | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/) |
|  Team Member  | Integrante 3                           | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/) |
|  Team Member  | Integrante 4                           | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/) |
|  Team Member  | Integrante 5                           | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/) |
|  Team Member  | Integrante 6                           | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/) |
|  Team Member  | Integrante 7                           | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/) |


# Objetivo do Projeto
Desenvolver o **Observatório de Inovação de São José dos Campos**, uma plataforma de visualização de dados em Power BI que apresenta indicadores econômicos e produtivos do município a partir da base da **RAIS** (Relação Anual de Informações Sociais), do Ministério do Trabalho e Emprego, visando:
* Identificar e organizar informações sobre os principais setores industriais e de serviços da região;
* Representar a distribuição geográfica das empresas e setores produtivos;
* Apresentar indicadores de emprego (admissões, desligamentos e saldo) por setor;
* Apoiar a tomada de decisão de gestores públicos, empresas parceiras, potenciais investidores e cidadãos;
* Fomentar o diálogo entre governo, empresas e academia, segundo o modelo da **hélice tríplice**.


## Tecnologias Utilizadas

| Tecnologia | Uso no projeto | Requisito |
|------------|----------------|-----------|
| Google Colab | Acesso e organização dos dados públicos e institucionais | RN.P.1 |
| Python 3+ | Extração, filtragem (município de SJC) e tratamento dos dados da RAIS | RN.P.2 |
| Power BI | Visualização dos dados no Observatório | RN.P.3 |
| GitHub | Versionamento do código e documentação técnica | RN.P.4 |


# Personas

| Tipo de Usuário | Descrição / Interesse Principal | Necessidade Representativa |
|-----------------|---------------------------------|----------------------------|
| Gestor Público | Servidores da Secretaria de Desenvolvimento Econômico/CADI responsáveis por planejar políticas de fomento industrial e de inovação | Identificar setores estratégicos e monitorar o desenvolvimento econômico da cidade |
| Empresa Parceira | Empresas já estabelecidas na região, integrantes do ecossistema de inovação de SJC | Mapear sinergias, fornecedores e possíveis parcerias no mesmo setor ou com soluções agregadoras de valor |
| Parceiro em Potencial | Empresas ou investidores externos avaliando a instalação de operações na região | Comparar indicadores entre setores para embasar decisões de investimento |
| Cidadão (pesquisadores, estudantes e jornalistas) | Acesso ao painel para fins acadêmicos, jornalísticos ou de acesso à informação | Consultar dados abertos, confiáveis e com metodologia transparente |


# Product Backlog

| Rank | Prioridade | User Story | Estimativa | Sprint | Requisito do Parceiro |
|------|------------|------------|------------|--------|-----------------------|
| 1  | Alta  | Como sociedade civil, quero acessar o Observatório publicamente e sem necessidade de login, para exercer meu direito de acesso à informação sobre a economia do município (Lei de Acesso à Informação) | 3  | 1 | RN.P.3, RN.P.5 |
| 2  | Alta  | Como usuário do Observatório, quero navegar por uma página inicial com um resumo executivo dos principais indicadores econômicos de São José dos Campos, para ter uma visão geral rápida antes de aprofundar a análise | 5  | 1 | RN.P.3, RN.P.5 |
| 3  | Alta  | Como equipe de desenvolvimento, quero automatizar a extração dos dados da base RAIS nacional e filtrar apenas os registros do município de São José dos Campos, para garantir uma base de dados confiável e atualizável | 13 | 1 | RN.P.1, RN.P.2 |
| 4  | Alta  | Como equipe de desenvolvimento, quero versionar os scripts de tratamento de dados e a documentação do projeto no GitHub, para garantir rastreabilidade, colaboração e transparência do processo | 2  | 1 | RN.P.4, RN.P.6 |
| 5  | Alta  | Como gestor público, quero visualizar um mapa dos setores industriais e de serviços predominantes na região, para identificar oportunidades de fomento e atração de investimentos | 8  | 1 | RN.P.3, RN.P.5 |
| 6  | Alta  | Como membro do ecossistema de inovação, quero utilizar filtros por setor econômico, período e porte da empresa, para localizar rapidamente a informação relevante para minha análise | 5  | 1 | RN.P.3, RN.P.5 |
| 7  | Alta  | Como gestor público, quero visualizar indicadores de admissões e desligamentos por setor, para compreender a dinâmica do mercado de trabalho local e orientar políticas públicas | 5  | 2 | RN.P.3 |
| 8  | Alta  | Como gestor público, quero acompanhar a evolução do saldo de empregos (admissões menos desligamentos) por setor ao longo do tempo, para monitorar a saúde econômica regional | 5  | 2 | RN.P.3 |
| 9  | Alta  | Como gestor público, quero visualizar, no mesmo painel, indicadores relacionados aos três eixos da hélice tríplice (governo, empresas e academia), para embasar políticas de fomento ao diálogo entre esses atores | 8  | 2 | RN.P.3, RN.P.5 |
| 10 | Alta  | Como empresa parceira, quero identificar outras empresas do mesmo setor produtivo presentes na região, para mapear possíveis sinergias, fornecedores ou parcerias estratégicas | 8  | 2 | RN.P.3 |
| 11 | Alta  | Como empresa parceira, quero visualizar a distribuição geográfica das empresas por setor no município, para identificar clusters produtivos próximos ao meu negócio | 8  | 2 | RN.P.3, RN.P.5 |
| 12 | Média | Como parceiro em potencial, quero comparar indicadores econômicos entre diferentes setores da região, para apoiar minha decisão sobre onde investir ou instalar uma nova operação | 5  | 3 | RN.P.3 |
| 13 | Alta  | Como gestor público, quero identificar setores com altas taxas de desligamento, para direcionar políticas de requalificação profissional e apoio ao emprego | 3  | 3 | RN.P.3 |
| 14 | Média | Como estudante ou pesquisador, quero visualizar gráficos comparativos da evolução do emprego por setor ao longo dos anos, para compreender tendências econômicas da região | 3  | 3 | RN.P.3, RN.P.5 |
| 15 | Média | Como pesquisador, quero visualizar a classificação das atividades econômicas segundo a CNAE, para relacionar os dados da RAIS a categorias produtivas reconhecidas academicamente | 5  | 3 | RN.P.2, RN.P.3 |
| 16 | Média | Como empresa parceira, quero visualizar quais setores concentram a maior geração de empregos formais, para identificar players relevantes para possíveis parcerias | 3  | 3 | RN.P.3 |

> Estimativas em *story points* (escala de Fibonacci). O backlog é passível de revisão e refinamento ao longo das Sprints, em conjunto com o cliente.


# Critérios de Aceitação

**"Como empresa parceira ou em potencial, quero visualizar os principais motores econômicos da região, conseguir estimar os melhores espaços de inserção de oportunidade e parcerias comerciais e de desenvolvimento no município de São José dos Campos."**
* O painel deve apresentar a distribuição geográfica das empresas;
* As empresas abertas a parcerias devem ser distinguidas através de selo de cooperação em inovação;
* O resultado do processamento de empresas do ecossistema de inovação deve ser exposto em painel único, possibilitando filtragem por cadeia produtiva ou setor econômico;
* Os dados macroeconômicos da região devem ser expostos em primeiro plano.

**"Como gestor público, quero visualizar, no mesmo painel, as principais empresas e seus respectivos setores produtivos, para embasar políticas de fomento ao diálogo entre esses atores e o desenvolvimento econômico da região."**
* O painel deve apresentar uma seção específica que relacione indicadores das empresas com planta no município e sua relevância econômica na cidade;
* Deve ser possível filtrar a visualização por setor produtivo;
* A navegação deve ser fluida e intuitiva;
* Deve haver indicação clara da fonte de cada indicador exibido.


# Competências desenvolvidas
* Introdução aos fundamentos de cadeia de suprimentos;
* Leitura, organização e interpretação de dados econômicos e industriais;
* Pensamento computacional aplicado a problemas reais;
* Comunicação técnica e elaboração de relatórios;
* Trabalho em equipe e organização de projetos;
* Visão sistêmica de processos produtivos e de serviços;
* Uso de ferramentas digitais para análise e visualização de dados;
* Metodologia ágil para planejamento e execução do projeto.


# Registro das Sprints

| Sprint            | Previsão   | Status   | Histórico |
|-------------------|------------|----------|-----------|
| 01                | 28/09/2026 | a fazer  | [MVP](MVP/sp1.md)  |
| 02                | dd/mm/aaaa | a fazer  | [MVP](MVP/sp2.md)  |
| 03                | dd/mm/aaaa | a fazer  | [MVP](MVP/sp3.md)  |
| Feira de Soluções | dd/mm/aaaa | a fazer  | [MVP](#)  |
