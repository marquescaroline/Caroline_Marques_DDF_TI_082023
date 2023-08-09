# Caroline_Marques_DDF_TI_082023

Segue o repositório para solução do desafio proposto no processo seletivo da Dadosfera.

## Case 1
Uma possibilidade de implementar uma analise de dados para rastrear a satisfação do cliente, seria seguir alguns pontos que considero importantes como:
1.	Como o objetivo principal é rastrear a satisfação do cliente o primeiro ponto é definir as métricas que serão consideradas para avaliar a satisfação do cliente e melhorar o tempo de resposta do suporte.
2.	Integrar com as ferramentas de service desk como (HubSpot Service, Zendesk, ServiceNow, Drift, Intercom) para além conseguir fazer pesquisas de satisfação com o cliente, coletar os dados importantes que serão necessários para serem analisados.
3.	Após a coleta é necessário armazenar esses dados em um banco de dados adequado, para essa decisão iria consultar a equipe para saber as tecnologias que são mais adequadas ao conhecimento da equipe, e após essa pesquisa interna decidir o banco que seria mais eficiente unindo a proficiência da equipe com o tipo e quantidade de dados fazendo uma definição mais eficiente do banco.
4.	Um próximo passo seria utilizar ferramentas de análise de dados de maneira a garantir, além da qualidade dos dados, verificando os dados mais relevantes, se existem dados corrompidos ou duplicados, utilizando ferramentas como por exemplo o Power BI entre outras, para além de calcular métricas importantes, conseguir fazer separações de dados por tipos como (equipe, canal e outros).
5.	Como citado no passo anterior aproveitar o Power BI, para realizar a criação de dashboards e ferramentas visuais de maneira que consiga demonstrar graficamente pós filtragem das informações, como estão as métricas e o que podemos evoluir.
6.	Analisar algumas métricas como NPS, CSAT, tempo médio de resposta e procurar relações, tendencias, padrões e possíveis pontos de melhoria com base nos dados analisados.
7.	Ter contato com a equipe de suporte e obter um feedback deles, e onde eles acreditam que pode melhorar a experiencia deles com o usuário.
8.	Compartilhar essas informações após filtragem adequada aos gerentes e responsáveis, já com sugestões de melhorias e como iriamos implementar, buscando integrar toda a equipe em busca dos objetivos principais.
9.	Implementar as melhorias decididas com a equipe, identificar áreas de oportunidade para aumentar a satisfação do cliente e seguir acompanhando continuamente com a equipe os dados, e caso seja necessário ajustar as métricas de maneira que o negocio sempre esteja alinhado com a necessidade do cliente atual. 

## Case 2
Para realizar este upgrade utilizando uma nova plataforma de gerenciamento de diretório em nuvem com MDM (Mobile Device Management), SSO (Single Sign-On) e recursos de ciclo de vida, é necessário pensar com calma cada passo do projeto e tentar organizar em pontos para facilitar a divisão de tarefas e organização dos passos, uma maneira de fazer seria:
1.	Primeiro passo e talvez o mais importante deles entender os motivos e necessidades que fizeram a decisão de se fazer o update, identificando os recursos necessários, como por exemplo: como iremos gerenciar nossos arquivos e informações, pontos de integração com os outros sistemas da empresa, com os requisitos de controle e qualidade da dadosfera e políticas de segurança, o gerenciamento de usuários como será feito, e se o sistema possui escalabilidade para diminuir o impacto de upgrades futuros.
2.	Após alinhamento das decisões do passo anterior com os superiores, irei garantir a confiabilidade do sistema anterior, realizando o máximo de testes possíveis para verificar a qualidade do sistema atual, para não ter problemas com a migração causados pelo sistema atual.
3.	Em seguida devemos garantir que toda a infraestrutura necessária está pronta para a nova plataforma, e a criação de ambientes de desenvolvimento e de testes para conseguir validar todos os cenários possíveis antes da implementação por completa.
4.	Treinamento da equipe, dos administradores e dos usuários finais, coletando possíveis beta testers (usuários que aceitem acessar primeiramente o novo sistema sabendo que existe a possibilidade de ter alguns erros durante a migração),se a política da empresa permitir a utilização de beta testers externos, para que estes após alguns passos da migração, nos ajudem ao utilizar a plataforma a coletar primeiras informações sobre erros e funcionalidades que não estão funcionando antes do lançamento final.
5.	Configurar a nova plataforma com base nos requisitos de controle, segurança e qualidade da dadosfera, configurando todas as politicas e regras de negócio e configurando o SSO.
6.	Integrar o sistema com os outros sistemas da empresa e com sistemas externos, certificando que a integração está funcionando bem para garantir a compatibilidade do sistema atual com o anterior, e o funcionamento correto das integrações com outros sistemas.
7.	Realização dos testes completos de todos os passos, e aqui entra o começo da inclusão dos betas testers do passo 4, os quais vão ajudar a encontrar possíveis erros não encontrados pela equipe antes do lançamento final da aplicação, e realizar a correção de possíveis erros encontrados ou pela equipe ou pelos primeiros usuários (se possível).
8.	Migração dos usuários com opção de utilização do sistema antigo para mitigar erros, e garantir a satisfação além de facilitar a identificação de possíveis problemas que tenham passado despercebidos até então.
9.	Monitorar continuamente a plataforma, mantendo comunicação constante com o usuário, fornecendo ajuda se necessário, e recebendo feedbacks sobre a migração.
10.	Analisar posteriormente se todos os objetivos foram atingidos e continuar o monitoramento e correção de qualquer inconsistência encontrada tentando garantir que todos os objetivos foram concluídos.

## Case 3
Pensando em uma plataforma robusta como a da dadosfera algumas medidas de gestão de acesso são ainda mais cruciais, levando em conta o que o mercado utiliza e buscando inovar irei citar algumas práticas que considero interessantes de serem adotadas:
1.	Autenticação Multifator (MFA): Uma das práticas mais consolidadas no quesito de segurança pois ao requerer que o usuário forneça duas ou mais formas de verificação de identidade antes de permitir o acesso, adiciona uma forma de proteção antes do acesso aos dados.
2.	Como citado na questão 2 nas possibilidades de upgrade, utilizar ferramentas de SSO (Single Sign-On), permite possibilitar ao usuário a possibilidade de realizar um login único que acesse diversas aplicações aumentando a eficiência, segurança e a conveniência ao acesso.
3.	Controle de acesso e permissões do usuário, utilizar politicas como RBAC (Controle de Acesso Baseado em Função) e PoLP(Política de Menor Privilégio) para garantir que o usuário terá somente as permissões mínimas necessárias para realizar suas tarefas e não consiga acessar ambientes que deveria ser restrito a outros perfis.
4.	Controle de acesso dos funcionários, com politicas de troca de senhas periódicas (3 em 3 meses ou menos) para evitar que um funcionário utilize a mesma senha que usa em outros sites, ela seja comprometida e a aplicação seja comprometida junto, e controle de criação e exclusão de contas ligados a contratação e demissão de funcionários, fazendo com que um funcionário desligado não tenha permissões administrativas após o desligamento.
5.	Detecção de atividades e locais suspeitos, utilizar ferramentas de IA, e ferramentas de localização geográfica, tipo de acesso, para detectar acessos suspeitos, com base em comportamento do usuário, horário, localização entre outros detectando possíveis acessos suspeitos/maliciosos.
6.	Monitoramento e auditoria do acesso dos usuários mantendo registros de todas as ações dos usuários conseguindo auditar esses dados auxiliando na investigação de incidentes.
7.	Realização de testes periódicos sobre a segurança da aplicação procurando vulnerabilidades ajudando a mitigar os riscos.
8.	Atualizações periódicas com correções e updates buscando sempre se manter com as últimas correções de seguranças
9.	O último, mas não menos importante a conscientização do usuário através de informativos, vídeos e outras formas de comunicação buscando a minimização dos erros humanos.

## Case 4
Com o objetivo de melhorar a interação com os clientes pensei nos passos a seguir para implementar um chatbot AI:
1.	Analisar e estabelecer os pontos de melhoria que serão focados nessa integração com a ferramenta de chatbot, decidindo o que será melhorado como interação com o cliente, registro entre outras e com base nisso procurar qual a melhor ferramenta de chatbot com base nos pontos definidos.
2.	 Personalizar o chatbot com a marca da empresa, modificando a forma de escrita das respostas para algo personalizado, criando fluxos de respostas padrão com base nos possíveis principais questionários dos clientes e dando um nome tornando algo menos robótico e mais pessoal.
3.	Integrar gradualmente o chatbot ao sistema da empresa, colocando responsabilidades no chatbot aos poucos, tentando minimizar falhas, e saindo de responder perguntas simples até interações completas com o usuário como fazer o registro do usuário e ir coletando as informações.
4.	Posteriormente criar um suporte que funcione 24h 7 dias por semana, com possibilidade de migrar para atendimento humano em horário comercial mas ter um suporte em todos os horários do dia.
5.	Coletar os dados e ir melhorando gradativamente a ferramenta com base nos dados colhidos tornando cada vez mais independente do suporte humano, aumentando a satisfação dos clientes com a ferramenta.
6.	Suporte continuo e sempre procurando com base nos dados evoluir a ferramenta acompanhando as métricas de satisfação do cliente.

## Case 5
Fiz uma query que busca os dados da tabela users_emails e retorna os dados para serem exportados
```
SELECT *
FROM users_emails
WHERE data_registro >= DATE_SUB(CURRENT_DATE, INTERVAL 30 DAY);
```


Explicando a query, 
1.	Select * -> para selecionar todos os dados da tabela
2.	FROM users_email -> seleciona a tabela que vai ser retirado os dados
3.	(Where data_registro >=) -> considerando que existe uma informação na tabela com o data_registro para verificar quando foi feito o cadastro do usuário.
4.	DATE_SUB(current_date, interval 30 day) -> selecionar o dia atual e com base nisso conseguir definir os últimos 30 dias para selecionar só os usuários dos últimos 30 dias.
