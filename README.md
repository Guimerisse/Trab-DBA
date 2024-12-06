# Trab-DBA

Guilherme Merisse Santos

Carlos Filho Silva Oliveira 

Ana Luisa Matias Araujo

Atividade Em Grupo - Criação e Gestão de um Banco de Dados - implementar as estruturas e os dados de um banco de dados utilizando os comandos DDL e DML no Oracle, com base no Modelo Físico de Dados (MFD) fornecido.




**As tabelas e seus relacionamentos:**

1. Sistema de Gestão de Relacionamento com o Cliente:
- **CLIENTES**: Armazena informações sobre os clientes. 
- **CAMPANHAS**: Armazena informações sobre as campanhas de marketing.
- **INTERACOES**: Armazena informações sobre as interações dos clientes com as campanhas.

2. Gestão Acadêmica:
- **MATRICULAS**: Armazena informações sobre as matrículas dos estudantes nas disciplinas.
- **DISCIPLINAS**: Armazena informações sobre as disciplinas oferecidas nos cursos.
- **ESTUDANTES**: Armazena informações sobre os estudantes.
- **CURSOS**: Armazena informações sobre os cursos oferecidos.
- **PROFESSORES**: Armazena informações sobre os professores.

3. Gestão de Hotéis e Restaurantes:
- **CLIENTES**: Armazena informações sobre os clientes.
- **QUARTOS**: Armazena informações sobre os quartos disponíveis.
- **RESERVAS**: Armazena informações sobre as reservas dos clientes.
- **PEDIDOS**: Armazena informações sobre os pedidos feitos pelos clientes.
- **ITENS_PEDIDO**: Armazena informações sobre os itens dos pedidos.   

4. Gestão de Projetos:
- **TAREFAS**: Armazena informações sobre as tarefas dos projetos.
- **FUNCIONARIOS**: Armazena informações sobre os funcionários.
- **PROJETOS**: Armazena informações sobre os projetos.

5. Gestão de Recursos Humanos:
- **DEPARTAMENTOS**: Armazena informações sobre os departamentos.
- **FUNCIONARIOS**: Armazena informações sobre os funcionários.
- **AVALIACOES_DESEMPENHO**: Armazena informações sobre as avaliações de desempenho dos funcionários.
- **FOLHA_PAGAMENTO**: Armazena informações sobre a folha de pagamento dos funcionários.



**O objetivo do banco de dados:**

1. Sistema de Gestão de Relacionamento com o Cliente: Gerenciar informações de clientes, histórico de interações, preferências, e atividades relacionadas a vendas e suporte ao cliente.

2. Gestão Acadêmica: Armazenar e organizar informações sobre alunos, professores, cursos, disciplinas, matrículas e avaliações.

3. Gestão de Hotéis e Restaurantes: Gerenciar reservas, informações de hóspedes, cardápios, pedidos e faturamento.

4. Gestão de Projetos: Organizar projetos, tarefas, equipes, prazos, e custos para garantir o sucesso na execução.

5. Gestão de Recursos Humanos: Armazenar informações de funcionários, cargos, salários, benefícios, e acompanhar recrutamento e treinamento.

6. Gestão de Transporte e Logística: Controlar dados sobre frota, rotas, motoristas, entregas e otimizar operações logísticas.

7. Imobiliário e Gestão de Propriedades: Gerenciar propriedades, locações, inquilinos, contratos e transações imobiliárias.

8. Marketing Digital: Monitorar campanhas de marketing, engajamento, leads, conversões, e outras métricas relacionadas a estratégias digitais.

9. Saúde e Fitness: Gerenciar informações de clientes, treinos, dietas, progressos, e dados de academias ou clínicas.

10. Sistema de Gestão de Geração de Energia: Controlar dados de geração, distribuição e consumo de energia, monitorando eficiência e demandas.

**Conclusão**:

Em suma cada banco de dados é criado para facilitar/corrigir algum problema do nosso dia a dia.





**Como executar os scripts no Oracle (ex.: comandos SQL*Plus, SQL Developer):**

1. Abra o SQL*Plus ou SQL Developer.
2. Execute o script `estrutura.sql` para criar as tabelas e definir as restrições.
3. Execute o script `dados.sql` para inserir os dados nas tabelas.
