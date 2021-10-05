# Especificações do Projeto

O presente trabalho visa apresentar uma solução ao problema de acesso à educação pelas pessoas portadoras de deficiência auditiva, na medida em que cuida-se de um grupo marginalizado pela população, devido à falta de investimento para melhor suprir suas necessidades no âmbito educacional, sendo uma delas: a presença de um intérprete de libras para fazer a ponte entre o aluno PCD e o professor não-PCD.

## Personas

Luiza Magalhães Cortez tem 28 anos, é formada em Design de Produtos e no momento está a procura de uma oportunidade de recolocação no mercado. Surda desde que nasceu, Luiza gosta de estudar e aprender coisas novas e desde cedo teve incentivo para estudar, de tal forma que sua família a ajudou muito. Ela mora com seus pais e um irmão.

Luiza perdeu seu emprego durante a pandemia de COVID-19, fato esse que a levou a trancar a pós-graduação que estava cursando. Antes ela tinha o costume de ir trabalhar em uma agência no centro de Belo Horizonte, e ir para a pós, na região do bairro Funcionários. Gosta de ler livros, assistir filmes e séries no tempo livre. Gosta também de sair para passear, visitar exposições de arte e ir em um bom restaurante.

Luiza enumera algumas de suas dores relatando que teve oportunidade de estudar, porém o processo foi bem difícil. Sempre perdeu muita informação durante as aulas, por não ter intérprete, e, quando havia um, ela se sentia mais isolada dos ouvintes. Era necessário prestar muita atenção para fazer leitura labial, o que é muito cansativo. Segundo ela, existem aplicativos que transcrevem o que as pessoas estão falando, mas não funcionam tão bem. Além disso, as tecnologias que facilitam a comunicação costumam ser caras. 

Para ela, a maneira mais eficiente para aprendizado é através de intérpretes, apesar de gostar também de legenda e boas transcrições. Infelizmente, porém, há muitos surdos que possuem certa dificuldade no português, então preferem intérprete nas plataformas e ler em libras escrita.

## Histórias de Usuários

Com base na análise das personas foram identificadas as seguintes histórias de usuários:

| EU COMO... `PERSONA` | QUERO/PRECISO ... `FUNCIONALIDADE`                           | PARA ... `MOTIVO/VALOR`                                     |
| -------------------- | ------------------------------------------------------------ | ----------------------------------------------------------- |
| Luiza                | buscar intérpretes libras                                    | me ajudar nos meus estudos                                  |
| Luiza                | realizar a buscas com auxílio de filtros: de tempo de experiências, especialidade, gênero e reputação (NPS) | encontrar um profissional com maior aderência ao meu perfil |
| Luiza                | realizar buscas com auxílio de filtro de disponibilidade de data | evitar conflitos de agenda e evitar desencontros            |
| Luiza                | receber indicações de profissionais de acordo com o meu perfil | tornar a busca mais ágil                                    |
| Luiza                | favoritar os profissionais que já tive contato               | poder contratá-los novamente                                |
| Luiza                | efetuar o pagamento do profissional por meio do site         | tornar mais segura transação de crédito                     |
| Luiza                | poder reportar um profissional por desrespeito e outra falha ética | evitar contato futuro com o mesmo                           |
| Luiza                | buscar por nome o profissional que eu já conheça ou receba indicação | ser mais assertiva na busca                                 |
| Luiza                | poder indicar o profissional que tenha me atendido bem       | auxiliar colegas                                            |

## Requisitos do Projeto

O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir.

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos funcionais do projeto, identificando a prioridade em que os mesmos devem ser entregues.

| ID    | Descrição do Requisito                                       | Prioridade |
| ----- | ------------------------------------------------------------ | ---------- |
| RF-01 | O site deve apresentar, na página principal, uma caixa de busca para aulas e profissionais desejados | ALTA       |
| RF-02 | O site deve oferecer um menu adicional que permita ao usuário filtrar as informações de pesquisa | ALTA       |
| RF-03 | O site deve permitir ao usuário visualizar o texto completo das informações de todos os profissionais listados | ALTA       |
| RF-04 | O site deve oferecer um menu adicional que permita ao usuário filtrar as informações de pesquisa | ALTA       |
| RF-05 | O site deve oferecer a funcionalidade de comentar sobre os professores no qual ele teve aula ou contato e favoritar aqueles que mais se destacaram | MÉDIA      |
| RF-06 | O site deve permitir visualizar as informações de contatos do mantenedor do site | MÉDIA      |
| RF-07 | O site deve permitir a visualização dos feedbacks, tanto BC quanto CB | MÉDIA      |
| RF-08 | O site deve permitir que usuários possam comentar conteúdos  | BAIXA      |
| RF-09 | O site deve ter um fórum de dúvidas conforme a aula estudada | BAIXA      |

### Requisitos não Funcionais

A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender.

| ID     | Descrição do Requisito                                       | Prioridade |
| ------ | ------------------------------------------------------------ | ---------- |
| RNF-01 | O site deve ser publicado em um ambiente acessível publicamente na Internet (Repl.it, GitHub Pages, Heroku) | ALTA       |
| RNF-02 | O site deverá ser responsivo permitindo a visualização em um celular de forma adequada | ALTA       |
| RNF-03 | O site deve ter bom nível de contraste entre os elementos da tela em conformidade | MÉDIA      |
| RNF-04 | O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge) | ALTA       |
| RNF-05 | O site deve ter um banco de dado referente aos professores   | ALTA       |
| RNF-06 | O site deve oferecer pagamentos via plataforma (Paypal, Boleto, Cartão de crédito, PIX) | ALTA       |

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

| ID    | Restrição                                                    |
| ----- | ------------------------------------------------------------ |
| RE-01 | O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 06/12/2021 |
| RE-02 | O aplicativo deve se restringir às tecnologias básicas da Web no Frontend |
| RE-03 | A equipe não pode subcontratar o desenvolvimento do trabalho |
| RE-04 | Não pode ser desenvolvido um módulo de backend               |
