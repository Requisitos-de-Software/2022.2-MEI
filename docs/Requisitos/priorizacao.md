# Priorização de Requisitos

## Histórico de Versão
|Data|Versão|Descrição|Autor|Revisão|
| :----------: | :------: | :-----------: | :---------: |:---------: |
|27/11/2022|1.0|Criação do documento| [Ana](https://github.com/AnHoff) | - |

## Introdução
Para gerar valor agregado ao produto desde as primeiras entregas, é necessário saber quais requisitos elicitados serão desenvolvidos no início do processo para que haja um ponto de partida otimista para os clientes e/ou usuários. Assim, surge a necessidade de realizar a priorização dos requisitos elicitados.

A priorização costuma ser realizada com o uso de tabelas que possuem o objetivo de categorizar os requisitos elicitados em baixa, média ou alta prioridade. Além disso, a priorização deve ser feita levando em consideração as expectativas e necessidades dos clientes, não tendo, portanto, opinião exclusiva dos desenvolvedores.

Abaixo serão apresentadas algumas técnicas comuns para priorização de requisitos.

## MoSCoW

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

## Bibliografia
Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021)
Interação Humano-Computador e Experiência do usuário. Autopublicação.

Karl E. Wiegers; First Things First: Prioritizing Requirements. Software Development (1999).