## Histórico de Versão
|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:-----------:| :------: | :-----------: | :---------: |:---------: |
|10/12/2022|11/12/2022|1.0|Criação do documento| [Arthur](https://github.com/Eruel6) e [Eduardo](https://github.com/edudsan) | [João Lucas](https://github.com/HacKairos) |
|04/01/2023|04/01/2023|1.1|Melhoria no documento| [Eduardo](https://github.com/edudsan) | [Ana Luiza](https://github.com/AnHoff) |

## Introdução 

A especificação suplementar em requisitos de software é um documento que fornece informações adicionais sobre os requisitos de um determinado sistema ou aplicativo de software. Esse documento pode incluir detalhes adicionais sobre como o sistema deve ser projetado e implementado, bem como quaisquer requisitos específicos que devem ser atendidos. É usado também para complementar a especificação de requisitos principal, que fornece uma visão geral dos requisitos do sistema.

## Metodologia FURPS+

Os requisitos não funcionais de um Microempreendedor Individual (MEI) são aqueles que especificam as características do sistema que não se relacionam diretamente com sua funcionalidade principal. Para compreender melhor tais requisitos, foi utlizada a metodologia FURPS+. 

A metodologia FURPS+ é utilizada para avaliar os requisitos de software e identificar quais devem ser incluídos em um projeto de desenvolvimento. A sigla FURPS+ representa cinco categorias de requisitos, sendo eles: Funcionalidade, Usabilidade, Confiabilidade, Performance e Suportabilidade.

## Funcionalidade

Funcionalidade representa os requisitos não funcionais do software e possui várias categorias que, por sua vez, possuem subcategorias que podem variar conforme necessário. Sua medição é realizada conforme o cumprimento dos requisitos especificados são alcançados. Os requisitos funcionais identificados podem ser conferidos [aqui](../Requisitos/tecnicas-priorizacao.md).

## Usabilidade

A usabilidade diz respeito à capacidade do usuário em usar e entender o sistema. Um sistema com boa usabilidade é fácil de ser usado e entendido, para que o MEI possa realizar suas atividades com eficiência e sem se deparar com problemas. Os requisitos identificados podem ser observados na tabela 2 abaixo.

<center>

|Descrição|Requisito relacionado|ID|
| :----------: | :------: | :---: |
| O aplicativo deve seguir uma padronização de design que seja minimalista e intuitiva | IS08 | U1 |
| O aplicativo deve ter destaque para recursos de acessibilidade | BS11 | U2 |
| O aplicativo deve ter caminhos curtos e não redundantes | IS08 | U3 |
| O aplicativo deve ter cores visíveis a usuários com deficiências visuais | BS11 | U4 |
| O aplicativo deve conter textos e ícones quem seja de fácil entendimento | BS12 | U5 |
| O aplicativo deve permitir identificar facilmente as funcionalidades | IS08 | U6 |

*Tabela 2 - Requisitos usabilidade*
 
</center>

## Confiabilidade

O sistema deve garantir a segurança dos dados do MEI e de seus clientes, para evitar fraudes e roubo de informações pessoais. Os requisitos identificados podem ser observados na tabela 3.

<center>
 
|Descrição|Requisito relacionado|ID|
| :----------: | :------: | :------: |
| O aplicativo deve possuir um sistema de autenticação | BS02 | C1 |
| O aplicativo deve possuir um sistema de sigilo de dados | BS05 | C2 |
| O aplicativo deve possuir um sistema de suporte ao usuário | BS07 | C3 |

*Tabela 3 - Requisitos de confiabilidade*

</center>
 
## Performance

O sistema deve ser capaz de lidar com grandes volumes de dados e transações sem sobrecarregar ou travar, garantindo a velocidade e a eficiência do processamento das informações. Os requisitos identificados podem ser observados na tabela 4.

<center>
 
|Descrição|Requisito relacionado|ID|
| :----------: | :------: | :------: |
| O aplicativo deve possuir uma interface leve  | IS08 | P1 |
| O aplicativo deve possuir armazenamento de dados básicos em cache  | ENT4 | P2 |
| O aplicativo deve possuir um acesso eficiente a dados locais  | BS04 | P3 |

*Tabela 4 - Requisito de performance*

</center>
  
## Suportabilidade

O sistema deve ser capaz de se adaptar e crescer de acordo com as necessidades do MEI, permitindo a expansão de suas atividades e a adição de novos recursos e funcionalidades. Os requisitos identificados podem ser observados na tabela 5.

<center>
 
|Descrição|Requisito relacionado|ID|
| :----------: | :------: | :------: |
| O aplicativo deve possuir compatibilidade com os principais tipos e modelos de aparelhos | BS08 | S1 |
| O aplicativo deve possuir compatibilidade com os principais SO | BS10 | S2 |

*Tabela 5 - Requisitos suportabilidade*

</center>
 
## Resultados

Esses são apenas alguns exemplos de requisitos não funcionais que podem ser aplicados a um MEI. É importante lembrar que cada negócio tem suas próprias necessidades e 
requisitos específicos, e que os requisitos não funcionais devem ser definidos de acordo com as necessidades e objetivos do negócio em questão. Conforme os dados coletados na etapa de elicitação de requisitos, os resultados foram baseados nos requisitos não funcionais, onde chegamos nos seguintes resultados 
que podem ser observados na tabela 6 com a legenda na tabela 7.

<center>

|Sigla|Categoria|Requisitos| 
| :----------: | :------: | :------: | 
|F| Funcionalidade | [Requisitos](../Requisitos/tecnicas-priorizacao.md) | 
|U| Usabilidade | IS 08, ENT 4, BS11, BS12   | 
|R|Confiabilidade |  ENT 3| 
|P|Desempenho| ENT 2 | 
|S|Suportabilidade| IS 06, BS08, BS10 | 
|+|Outros| BS04 | 

*Tabela 6 - Classificação dos requisitos não funcionais pelo FURPS+*

|Legenda| |
| :----------: | :----------: |
| Abreviação | Significado| 
| ENT | Entrevista |
| IS | Introspecção |
| BS | BrainStorm |

*Tabela 7 - Legenda*

</center>
 
## Bibliografia

- SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 13.
