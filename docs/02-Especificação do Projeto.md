# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

Persona 01

Nome: Marcos Souza
Idade: 38
Ocupação: Proprietário de Quadras de Areia
Localização: Rio de Janeiro, RJ

Histórico:
Marcos começou no mundo dos esportes como jogador amador de futebol de areia. Vendo a crescente demanda por espaços de qualidade em esportes como vôlei de praia, futevôlei e futebol de areia, ele decidiu investir criando sua própria quadra. Com um espírito empreendedor que transformou uma paixão de longa data em lucro — alugando quadras para diferentes jogos e organizando eventos esportivos.

Objetivos:

Trazer mais pessoas para a quadra por meio de parcerias e eventos locais.

Manutenção da quadra para ter altos padrões, segurança e satisfação dos usuários.

Abrir o negócio com mais quadras ou até mesmo ter uma academia anexa.

Persona 2

Dona de Quadra: Mariana Costa tem 42 anos, é proprietária e gerente de uma quadra esportiva em São Paulo. Ex-atleta, Mariana transformou sua paixão pelos esportes em um negócio próspero, oferecendo um espaço seguro e de qualidade para práticas esportivas como futebol, basquete e vôlei. Casada e com formação superior em Administração de Empresas, ela busca constantemente inovações para melhorar seu empreendimento e aumentar sua visibilidade através de marketing digital e parcerias locais. Mariana enfrenta desafios como a forte concorrência e a manutenção da qualidade de sua quadra com um orçamento limitado. Ela valoriza a saúde e o bem-estar através do esporte e está comprometida em oferecer um atendimento excelente, tornando-se uma referência na comunidade local. 

desafios:

Competir com outras quadras da área e se destacar no mercado.

Gerenciar os horários das quadras criando eficiência sem overbooking ou espaços ociosos.

Persona 3 

Enzo Henrique, 25 anos, é técnico em administração e, desde que seu pai precisou dedicar mais atenção à própria saúde devido à idade avançada, assumiu a gestão da quadra de futebol e da quadra de areia de propriedade de seu pai, localizada em Contagem/MG. Enzo sempre colaborou com o negócio, porém, agora que conduz a atividade integralmente, pretende implementar melhorias nos sistemas de gestão das quadras. Enzo se deparou com uma metodologia de gestão antiga e obsoleta de modo que concluiu ser necessário ampliar a divulgação do espaço bem como gerir o atendimento de forma mais automatizada e eficiente.  

Persona 4 
Nome: João Pereira
Idade: 27
Ocupação: Analista de Sistemas
Localização: São Paulo, SP
Histórico:
João sempre gostou de esportes, principalmente se forem esportes ao ar livre. Jogou futebol na escola, mas nos últimos anos se apaixonou pelo vôlei de praia e futevôlei. Embora tenha um emprego de escritório durante a semana, ele encontra tempo para praticar esportes em equipe com os amigos. Ultimamente, ele tem procurado lugares mais regulares por perto para praticar e competir a pé.

Objetivos:

Encontrar uma quadra de areia de boa qualidade para jogar regularmente.

Fazer amigos e ser social praticando esportes.

Desafios:

Conseguir uma quadra de areia de qualidade com horários flexíveis porque a agenda do homem é pesada de trabalho.

Conciliar esportes e encontrar tempo para obrigações profissionais

Encontrar quadras com boa relação custo-benefício e convenientemente localizadas

Persona 5 

Nome: Camila Ribeiro
Idade: 34 anos
Ocupação: Professora de Educação Infantil
Localização: Belo Horizonte, MG
História: Camila descobriu o vôlei de areia durante a pandemia e quer continuar praticando de forma recreativa. Agora, procura uma quadra próxima para jogar aos fins de semana e, ocasionalmente, durante a semana. 

Objetivos:

Ela busca um espaço com boa infraestrutura, horários flexíveis e um ambiente acolhedor. 
Seus desafios incluem conciliar a prática com sua rotina de trabalho e encontrar uma quadra disponível em horários convenientes.

Desafios:

Quadras lotadas nos horários desejados.
Clima imprevisível interrompendo os treinos.



 

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO             | QUERO/PRECISO                      |PARA              
|--------------------|------------------------------------|----------------------------------------|
| Marcos Souza       |                                    |                                        |
|--------------------|------------------------------------|----------------------------------------|
| Mariana Costa      |                                    |                                        |
|--------------------|------------------------------------|----------------------------------------|
| Enzo Henrique      |                                    |                                        |
|--------------------|------------------------------------|----------------------------------------|
| João Pereira       |                                    |                                        |
|--------------------|------------------------------------|----------------------------------------|
| Camila Ribeiro     |                                    |                                        |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O aplicativo deve ser compatível com as principais plataformas e dispositivos | ALTA | 
|RNF-002| O aplicativo deve ter uma interface amigável e intuitiva |  BAIXA | 
|RNF-003| O sistema deve ser capaz de processar até 1000 requisições simultâneas sem comprometer a perfomance |  ALTA |
|RNF-004| O sistema deve ter uma disponibilidade mínima de 99,9% ao longo do ano |  ALTA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
