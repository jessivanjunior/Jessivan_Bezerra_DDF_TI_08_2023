# Jessivan_Bezerra_DDF_TI_08_2023

## Case 1:
Primeiramente, é necessário definir os objetivos. Precisamos compreender exatamente o que iremos medir em relação à satisfação do cliente. Além disso, devemos identificar as métricas relevantes, como feedbacks e avaliações, por exemplo. Após essa etapa, procederemos com a coleta dos dados, seu gerenciamento e análise por meio de ferramentas como o Tableau ou o Power BI. Com isso, poderemos avançar para a visualização dos dados, permitindo que sejam debatidos pelas partes interessadas. Dessa forma, a equipe poderá implementar melhorias que resultem no aumento da satisfação dos clientes e na eficiência da equipe de suporte. Vale destacar que um monitoramento contínuo se torna fundamental para assegurar que o cliente jamais fique insatisfeito.


## Case 2:
Após a análise dos requisitos do MDM e SSO, é necessário desenvolver um plano estratégico que inclua metas, datas e orçamento. Com a nova plataforma já escolhida, é importante preparar a infraestrutura e realizar testes piloto. Enquanto isso, a equipe deve passar por treinamento para se familiarizar com a nova plataforma. Em seguida, a migração dos dados será conduzida em fases, com monitoramento e suporte contínuo aos usuários. Após a conclusão de todas as etapas, é crucial coletar feedback tanto dos usuários quanto da equipe envolvida.

## Case 3:
O aprendizado de máquina e a inteligência artificial estão em alta no momento. Utilizar esses recursos para identificar padrões de acesso e detectar anomalias pode resultar em uma significativa melhoria, permitindo uma detecção rápida de atividades irregulares. Esses recursos podem ser empregados até mesmo para análise comportamental.
Por essa mesma razão, a autenticação multifator é uma abordagem bem-vinda. Ela aumenta a segurança ao exigir que o usuário forneça um segundo fator além da senha. A implementação de um sistema com provisionamento e desativação automáticos também intensifica a segurança, diminuindo as chances de erros humanos durante os processos de concessão e revogação de acesso aos usuários que entram e saem do sistema.

## Case 4:
Devemos começar definindo quais serão as interações que o chatbot terá, a fim de identificar os casos de uso. Em seguida, desenvolveremos os diálogos, criando um roteiro para a interação com os clientes. Após isso, integraremos o chatbot ao sistema, o treinaremos e então faremos o monitoramento após o lançamento, sempre buscando melhorias a partir do feedback dos clientes. É importante garantir que os clientes tenham a opção de conversar com um humano caso o chatbot não seja capaz de lidar com a situação.

## Case 5:
```SQL
SELECT * //Selecione Tudo
FROM users_emails //Da tabéla users_emails
WHERE data_cadastro >= DATE_SUB(CURRENT_DATE, INTERVAL 30 DAY); //Onde a coluna data_cadastro possuir a data atual até 30 dias atrás
```
