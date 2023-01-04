## Histórico de Versão
|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:-----------:| :------: | :-----------: | :---------: |:---------: |
|10/12/2022|11/12/2022|1.0|Criação do documento| [Arthur](https://github.com/Eruel6) e [Eduardo](https://github.com/edudsan) | [João Lucas](https://github.com/HacKairos) |
|04/01/2023|04/01/2023|1.1|Melhoria no documento| [Eduardo](https://github.com/edudsan) | - |

## Introdução 

Especificação suplementar em requisitos de software é um documento que fornece informações adicionais sobre os requisitos de um determinado sistema ou aplicativo de 
software. Esse documento pode incluir detalhes adicionais sobre como o sistema deve ser projetado e implementado, bem como quaisquer requisitos específicos que devem 
ser atendidos. A especificação suplementar é usada para complementar a especificação de requisitos principal, que fornece uma visão geral dos requisitos do sistema.

## Metodologia FURPS+

Os requisitos não funcionais de um Microempreendedor Individual (MEI) são aqueles que especificam as características do sistema que não se relacionam diretamente 
com sua funcionalidade principal. Para compreender melhor essse reuisitos não funcionais foi utlizado a metodologia FURPS+. FURPS+ é uma metodologia utilizada para avaliar os requisitos de software e identificar quais devem ser incluídos em um projeto de desenvolvimento de software. A sigla FURPS+ representa cinco categorias de requisitos sendo eles: Funcionalidade, Usabilidade, Confiabilidade, Performance e Suportabilidade.

## Funcionalidade

Representa os requisitos funcionais do software. Possui várias categorias e essas possuem várias subcategorias que variam conforme o software. 
Sendo realizado sua medição conforme o cumprimento dos requisitos especificados são alcançados. Os requisitos identificados podem ser observado na tabela 1.

<center>
 
|Descrição|Requisitos| 
| :----------: | :------: |
| O aplicativo deve solicitar o CNPJ apenas uma vez | ENT 1 |
| Deve se exigir um CNPJ para acesso do aplicativo | IS07
| O aplicativo deve solicitar autorização para pegar dados de outros sites do governo | BS05 |
| O aplicativo deve validar a pessoa que está utilizando o CNPJ | BS09 |

Tabela 1: Requisitos de funcionalidade.
 
</center>

## Usabilidade

O sistema deve ser fácil de usar e entender, para que o MEI possa realizar suas atividades com eficiência e sem problemas. Os requisitos identificados podem ser observado na tabela 2.

<center>

|Descrição|Requisitos| 
| :----------: | :------: |
| O aplicativo deve ser de fácil entendimento e uso por seus usuários | IS 08 |
| O aplicativo deve salvar as informações | ENT 4 |
| O aplicativo deve ser acessível para usuário com algum tipo de deficiência | BS11 |
| O aplicativo deve conter texto que seja de fácil entendimento | BS12 |
Tabela 2: Requisitos usabilidade.
 
</center>

## Confiabilidade

O sistema deve garantir a segurança dos dados do MEI e de seus clientes, para evitar fraudes e roubo de informações pessoais. Os requisitos identificados podem ser observado na tabela 3.

<center>
 
|Descrição|Requisitos| 
| :----------: | :------: |
| O aplicativo deve evitar os erros e telas brancas através do uso | ENT 3 |

Tabela 3: Requisitos de confiabilidade

</center>
 
## Performance

O sistema deve ser capaz de lidar com grandes volumes de dados e transações sem sobrecarregar ou travar, garantindo a velocidade e eficiência do 
processamento das informações. Os requisitos identificados podem ser observado na tabela 4.

<center>
 
|Descrição|Requisitos| 
| :----------: | :------: |
| O aplicativo deve ir até o final da operação antes de realizar qualquer outra etapa  | ENT 2 |

Tabela 4: Requisito de performance

</center>
  
## Suportabilidade

O sistema deve ser capaz de se adaptar e crescer de acordo com as necessidades do MEI, permitindo a expansão de suas atividades e a adição de novos 
recursos e funcionalidades. Os requisitos identificados podem ser observado na tabela 5.

<center>
 
|Descrição|Requisitos| 
| :----------: | :------: |
| O aplicativo deve ser suportado pelos principais sistemas mobile  | IS 06 |
| O aplicativo deve ser possível de ser utilizado na maioria dos modelos de dispositivos | BS08 |
| O aplicativo deve ser possível de ser utilizado na maioria dos modelos de SO | BS10 |

Tabela 5: Requisitos suportabilidade

</center>

##  +

Representação para especificação de restrições, podendo essas serem restrições físicas, restrições de design, restrições de implementação, restrições de interface 
ou restrições de negócio. Os requisitos identificados podem ser observado na tabela 6.

<center>
 
|Descrição|Requisitos| 
| :----------: | :------: |
| O aplicativo deve obter dados dentro do próprio aplicativo | BS04 |

Tabela 6: Tabela para especificação de restrições:

</center>
 
## Resultados

Esses são apenas alguns exemplos de requisitos não funcionais que podem ser aplicados a um MEI. É importante lembrar que cada negócio tem suas próprias necessidades e 
requisitos específicos, e que os requisitos não funcionais devem ser definidos de acordo com as necessidades e objetivos do negócio em questão. Conforme os dados coletados na etapa de elicitação de requisitos, os resultados foram baseados nos requisitos não funcionais, onde chegamos nos seguintes resultados 
que podem ser observados na tabela 7 com a legenda na tabela 8.

<center>

|Sigla|Categoria|Requisitos| 
| :----------: | :------: | :------: | 
|F| Funcionalidade | ENT 1, IS07, BS05, BS09 | 
|U| Usabilidade | IS 08, ENT 4, BS11, BS12   | 
|R|Confiabilidade |  ENT 3| 
|P|Desempenho| ENT 2 | 
|S|Suportabilidade| IS 06, BS08, BS10 | 
|+|Outros| BS04 | 

Tabela 7 - Classificação dos requisitos não funcionais pela metodologia FURPS+

|Legenda||
| :----------: | :----------: |
| Abreviação | Significado| 
| ENT | Entrevista |
| IS | Introspecção |
| BS | BrainStorm |

Tabela 8 - Legenda tabela 7

</center>
 
## Bibliografia

- SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 13.
