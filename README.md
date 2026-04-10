Requisitos do Projeto: Sistema de Gestão Financeira para Hotéis

Este documento detalha os requisitos funcionais e não funcionais para o desenvolvimento de uma aplicação web destinada à organização financeira de hotéis de pequeno e médio porte. O objetivo principal é auxiliar na gestão de receitas e despesas, otimizando o fluxo de caixa e fortalecendo a sustentabilidade financeira.

1. Requisitos Funcionais

Os requisitos funcionais descrevem as funcionalidades que o sistema deve oferecer aos usuários para atender aos objetivos de negócio.

1.1. Gestão de Receitas

RF001: O sistema deve permitir o registro de diferentes tipos de receitas, como reservas, eventos e serviços adicionais.

RF002: O sistema deve possibilitar a categorização das receitas registradas para facilitar a análise financeira.

1.2. Gestão de Despesas

RF003: O sistema deve permitir o registro de diferentes tipos de despesas, como manutenção, insumos, folha de pagamento e encargos.

•
RF004: O sistema deve possibilitar a categorização das despesas registradas para facilitar a análise financeira.

1.3. Visualização e Análise Financeira

RF005: O sistema deve proporcionar uma visão clara e atualizada do fluxo de caixa do hotel.

RF006: O sistema deve apresentar relatórios e visualizações dos resultados financeiros, permitindo uma tomada de decisão estratégica.

1.4. Otimização e Controle

RF007: O sistema deve auxiliar na otimização do fluxo de caixa, identificando oportunidades de melhoria.

RF008: O sistema deve contribuir para a redução de desperdícios através de um controle mais eficiente de despesas.

RF009: O sistema deve melhorar o controle administrativo geral das receitas e despesas do hotel.

2. Requisitos Não Funcionais

Os requisitos não funcionais descrevem as qualidades e restrições do sistema, abrangendo aspectos técnicos, de segurança e de desempenho.

2.1. Requisitos Tecnológicos

RNF001: O backend da aplicação deve ser desenvolvido utilizando Java 17, Spring Boot e Spring Data JPA.

RNF002: O frontend da aplicação deve ser desenvolvido utilizando JavaScript, HTML5, CSS3 e Bootstrap para interatividade e estilização.

RNF003: O banco de dados relacional utilizado deve ser o PostgreSQL, devido à sua robustez e segurança para dados financeiros.

RNF004: O controle de versão do código-fonte deve ser realizado com Git, utilizando GitHub para armazenamento e gerenciamento.

RNF005: O gerenciamento de dependências do projeto Java deve ser feito com Maven.

RNF006: As tecnologias utilizadas devem possuir licenças open source (GPL, Apache 2.0, MIT, Eclipse Public License, PostgreSQL License).

2.2. Requisitos de Segurança

RNF007: O sistema deve implementar validação de entrada de dados no frontend e backend para prevenir vulnerabilidades como Injeção de SQL e XSS.

RNF008: O sistema deve utilizar Spring Data JPA para mitigar riscos de Injeção de SQL.

RNF009: O sistema deve implementar mecanismos robustos de autenticação e controle de acesso para proteger os dados dos usuários.

RNF010: A comunicação entre o cliente e o servidor deve ser segura, utilizando HTTPS.

RNF011: O desenvolvimento do sistema deve seguir as boas práticas de segurança estabelecidas pelo OWASP Top 10.

RNF012: O sistema deve estar em conformidade com as normas de segurança da informação ISO/IEC 27001.

RNF013: O sistema deve garantir a conformidade com a Lei Geral de Proteção de Dados (LGPD) no tratamento de informações sensíveis.

2.3. Requisitos Éticos e de Privacidade

RNF014: O sistema deve tratar os dados financeiros dos usuários com responsabilidade, garantindo a privacidade e segurança das informações.

RNF015: Os dados coletados pelo sistema devem ser utilizados exclusivamente para a finalidade da aplicação, conforme estabelecido.

