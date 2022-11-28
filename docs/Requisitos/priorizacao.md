# Priorização de Requisitos

## Histórico de Versão
|Data|Versão|Descrição|Autor|Revisão|
| :----------: | :------: | :-----------: | :---------: |:---------: |
|27/11/2022|1.0|Criação do documento| [Ana](https://github.com/AnHoff) | - |
|28/11/2022|1.1|Adiciona outras técnicas e conclusão| [Ana](https://github.com/AnHoff) | - |

## Introdução
Para gerar valor agregado ao produto desde as primeiras entregas, é necessário saber quais requisitos elicitados serão desenvolvidos no início do processo para que haja um ponto de partida otimista para os clientes e/ou usuários. Assim, surge a necessidade de realizar a priorização dos requisitos elicitados.

A priorização costuma ser realizada com o uso de tabelas que possuem o objetivo de categorizar os requisitos elicitados em baixa, média ou alta prioridade. Além disso, a priorização deve ser feita levando em consideração as expectativas e necessidades dos clientes, não tendo, portanto, opinião exclusiva dos desenvolvedores.

Abaixo serão apresentadas algumas técnicas comuns para priorização de requisitos.

## MoSCoW
Essa técnica é simples e proporciona um esquema de quatro possíveis classificações de prioridade para os requisitos. São elas:

* **M**ust: o(s) requisito(s) que deve(m) ser satisfeitos para uma entrega ser considerada bem sucedida;
* **S**hould: são os requisitos importantes e que devem ser inclusos em uma solução caso possível, porém de maneira não obrigatória;
* **C**ould: se refere aos requisitos desejáveis, porém dispensáveis. Ou seja, são aqueles que serão implementados apenas caso o tempo e os recursos permitirem;
* **W**on't: requisito(s) que não será(ão) implementados em primeiro momento, mas que podem ser incluídos em versões futuras do produto.

A proposta dessa técnica é elaborar uma alternativa para a clássica divisão em três níveis (baixo, médio, alto) de prioridade. Sua aplicação é simples e rápida de realizar, porém pode apresentar furos relacionados à definição de tempo, afinal, "won't" irá significar que o requisito não será implementado na primeira release ou que nunca será implementado? Por esse fator, a técnica MoSCoW não deverá ser posta em prática sozinha nesse projeto, sendo portanto complementada pelas técnicas apresentadas abaixo.

## First Things First
A técnica First Things First é um pouco mais elaborada que a MoSCoW. Ela foca na importância de equilibrar os benefícios e os custos de cada requisito, além de propor a definição das consequências que cada um deles irá gerar na arquitetura do software, o alinhamento dos requisitos com as regras de negócios e o estabelecimento do risco técnico agregado a cada um dos requisitos.

Nessa técnica estão envolvidos: 

* Gerente, responsável por liderar o processo e lidar com conflitos;
* Representantes do(s) cliente(s), responsáveis por classificar benefícios e fraquezas;
* Representantes do desenvolvimento, responsáveis por identificar custos e riscos e lidar com a parte técnica.

Para colocar a técnica em prática, o gerente precisará criar uma planilha com todos os requisitos listados. Em seguida, os representantes dos clientes devem auxiliar na estimativa dos benefícios agregados por cada requisito e também na estimativa da penalidade que a falta da implementação de cada recurso acarretaria. Após esses passos, cria-se uma coluna que ilustra o valor total, formado pela seguinte fórmula:

*valor total = (benefício x peso) + (penalidade x peso)*

O próximo passo é, em uma escala de 1 a 9, estimar o custo de implementação de cada requisito. Essa etapa conta com participação especial dos desenvolvedores, que classificarão os custos levando em consideração a complexidade, a interface necessária, a capacidade de reutilização do código, os testes e a documentação relativa a cada requisito.

O mesmo explicado acima deverá ser feito para estimar o grau de risco para cada requisito, sendo que um grau elevado é indicativo de prováveis problemas sobre sua viabilidade, disponibilidade de pessoal e uso de tecnologias e/ou ferramentas desconhecidas. A prioridade pode ser calculada seguindo a seguinte fórmula:

*prioridade = (valor%) / (custo% x peso do custo + risco% x peso do risco)*

Por fim, deve-se ordenar a lista de acordo com a ordem crescente de prioridade, sendo os requisitos do topo da lista os mais equilibrados em termos de valor, custo e risco. Tendo isso em mente, tais requisitos devem ser priorizados.

## Priorização baseada no valor, custo e risco
Essa técnica de priorização propõe um método mais analítico, ideal para situações onde os stakeholders não entram em consenso sobre a prioridade de cada requisito por meio das outras técnicas. Ela utiliza, portanto, uma técnica conhecida como QFD (Quality Function Deployment), que é rigorosa na relação dos valores do cliente às features propostas pelo produto.

Para priorizar os requisitos, essa técnica utiliza, normalmente, uma planilha que classifica o valor do benefício oferecido ao cliente caso o requisito seja implementado e as penalidades que a falta desse recurso pode trazer para o mesmo. Assim, essa técnica providencia uma abordagem contínua dos requisitos, sem dividí-los em certos níveis pré-definidos de prioridades. Essa característica torna tal método especialmente atrativo para classificar requisitos que não possuem uma prioridade definida. Nessa análise, não devem ser incluídos itens relacionados às funções básicas da empresa, por exemplo.

Fazem parte desse processo:

* Gerente de projeto ou analista de negócios;
* Representantes do cliente;
* Representantes do desenvolvimento.

Para iniciar o uso desse modelo de priorização de requisitos, primeiro deve-se listar numa planilha todos os casos de uso, histórias de usuários, funcionalidades ou requisitos funcionais que devem ser classificados. Após realizar a listagem, os representantes do cliente devem estimar o benefício relativo que cada funcionalidade iria prover ao usuário, em uma escala de 1 a 9; deve-se fazer o mesmo para estimar as penalidades que o usuário sofreria com a ausência de tal funcionalidade. Em seguida, os desenvolvedores devem estimar um custo relativo à implementação e/ou complexidade de cada funcionalidade, repetindo o processo para estimar o risco técnico associado a cada funcionalidade. A planilha irá calcular a prioridade com base na equação abaixo:

*prioridade = (valor%) / (custo% + risco%)*

Por fim, classifica-se os requisitos em ordem descendente de prioridade, tendo as funcionalidades com bom balanceamento de valor, custo e risco no topo de prioridade.

## Conclusão
As técnicas apresentadas acima possuem diferentes níveis de complexidade. Portanto, é vantajoso aplicar todas as três técnicas citadas acima no projeto da disciplina, visto que serão fontes de grandes aprendizados e propiciarão avaliações completas e acertivas sobre a priorização de cada requisito elicitado.

Por fim, também deve-se ressaltar a ampla interação da equipe do projeto com o usuário que será incentivada pelas diversas técnicas. Seja o usuário uma pessoa real ou uma persona, a interação será uma parte crucial para a definição da importância dos requisitos e, consequentemente, para a definição de todo o andamento do projeto.

## Bibliografia
Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021)
Interação Humano-Computador e Experiência do usuário. Autopublicação.

Karl E. Wiegers, Joy Beatty; Software Requirements, Third Edition.
