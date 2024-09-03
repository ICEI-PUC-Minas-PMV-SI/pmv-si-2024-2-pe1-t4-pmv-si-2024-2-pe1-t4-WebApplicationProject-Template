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

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

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


> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

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
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

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
