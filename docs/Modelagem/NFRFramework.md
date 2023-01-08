# NFR Framework

## <a>Histórico de Versão</a>
|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:-----------:| :------: | :-----------: | :---------: |:---------: |
|27/12/2022|27/12/2022|1.0|Criação do documento| [Ana Luiza](https://github.com/AnHoff) | [João Lucas](https://github.com/HacKairos) |
|28/12/2022|28/12/2022|1.1|Criação e adição dos SIG| [João Lucas](https://github.com/HacKairos) | [Ana Luiza](https://github.com/AnHoff) |

## <a>Introdução</a>

O NFR Framework utiliza requisitos não funcionais (*Non Functional Requirements*) para conduzir o processo geral de design, colocando esses requisitos em primeiro lugar na mente do desenvolvedor. Esse framework tem o objetivo de possibilitar que o desenvolvedor recorra ao conhecimento disponível relevante para a(s) etapa(s) na qual(is) ele esteja envolvido. 

Esse framework oferece uma estrutura feita para representar e/ou registrar o processo de design em SIGs, *Softgoal Interdependency Graphs*, além de promover a catalogação de requisitos não funcionais, designs e técnicas de desenvolvimento. [1]

Softgoal, um termo muito mencionado no framework em questão, é um objetivo sem uma definição clara nem critérios de satisfação precisos. Eles são utilizados para representar NFRs, podendo estar interligados e exercer influência sobre outros.

Os softgoals podem ser separados em três tipos, são eles:

* **Softgoals NFR:** são requisitos não funcionais, como critérios e atributos de qualidade, que desejam encontrar na análise a determinação de sua implementação ou não implementação;

* **Softgoals de Operacionalização:** são funcionalidades, representam uma forma concreta de viabilizar (ou não) características abstratas;

* **Softgoals de Afirmação:** são notações, feitas em linguagem natural, que podem ser acrescentadas ao modelo para argumentar sobre um ponto específico de modelagem. 

Cada um dos softgoals apresentados podem ser decompostos, seguindo os tipos de decomposição abaixo:

* **Decomposição de Softgoal NFR:** refina/divide um softgoal NFR em outros. Ajuda a dividir problemas em partes menores, sendo útil para lidar com ambiguidades e prioridades;

* **Decomposição de Operacionalização:** subdivide um softgoal de operacionalização em outros mais específicos, sendo útil para definir soluções gerais e transformá-las em soluções mais específicas;

* **Decomposição de Afirmação (*claims*):** refina um softgoal de afirmação em outros. É útil para apoiar ou não justificativas de projeto;

* **Priorização:** refina um softgoal em outro, com o mesmo tipo e tópicos, junto a uma prioridade associada. [2]

## <a>Contribuições</a>

As alterações no estado de um softgoal filho geram alterações no softgoal pai. Esse aspecto é chamado de contribuição, e seus tipos estão apresentados na tabela 1 abaixo.

<center>

| Contribuição | Representação | Descrição |
| :----------: | :-----------: | :-------: |
| AND | AND | PAI é satisfeito se somente se todos os FILHOS forem satisfeitos sob a perspectiva dos envolvidos. |
| OR | OR | PAI é satisfeito se somente se um dos FILHOS é satisfeito sob a perspectiva dos envolvidos. |
| MAKE | ++ | FILHO com contribuição tão positiva a ponto de satisfazer o PAI sob a perspectiva dos envolvidos. |
| HELP | + | FILHO com contribuição positiva parcial, que sozinho não chega a satisfazer o PAI sob a perspectiva dos envolvidos. |
| BREAK | -- | FILHO com contribuição tão negativa a ponto de negar o PAI sob a perspectiva dos envolvidos. |
| HURT | - | FILHO com contribuição negativa parcial, que sozinho não chega a negar o PAI sob a perspectiva dos envolvidos. |
| UNKNOWN | ? | FILHO não afeta o PAI. |
| EQUALS | = | Ambos compartilham o mesmo label. |
| SOME | SOME - | FILHO com contribuição negativa, cuja intensidade não se pode determinar. |
| SOME | SOME + | FILHO com contribuição positiva, cuja intensidade não se pode determinar. |

*Tabela 1 - Contribuições*

</center>

## <a>Legenda</a>

Para entender as figuras apresentadas mais abaixo nesse documento, faz-se necessário o uso da legenda apresentada na tabela 2 a seguir, com as imagens da dissertação de Reinaldo Antônio da Silva [3].

<center>

| Desenho | Descrição |
| :-----: | :-------: |
| <img src="./../../assets/NFR/softgoalNFR.png"> | Softgoal NFR |
| <img src="./../../assets/NFR/softgoalOp.png"> | Softgoal de operacionalização |
| <img src="./../../assets/NFR/softgoalAf.png"> | Softgoal de afirmação |
| <img src="./../../assets/NFR/satisfeito.png"> | Satisfeito |
| <img src="./../../assets/NFR/negado.png"> | Negado |
| <img src="./../../assets/NFR/indeterminado.png"> | Indeterminado |

*Tabela 2 - Legenda*

</center>

## <a>NFRs</a>

As figuras a seguir apresentam os SIG elaborados sobre Usabilidade, Confiabilidade, Desempenho e Suportabilidade.

### <a>Usabilidade</a>

<center>

#### <a>Sem Propagação</a>
<img src="./../../assets/NFR/NFR-Usabilidade.png">

*Figura 1 - SIG Usabilidade* <br><br>

#### <a>Propagação de erros</a>
<img src="./../../assets/NFR/NFR-Usabilidade-Propagado.png">

*Figura 2 - SIG Usabilidade Com Propagação de erros* <br><br>

</center>

### <a>Confiabilidade</a>

<center>

#### <a>Sem Propagação</a>
<img src="./../../assets/NFR/NFR-Confiabilidade.png">

*Figura 3 - SIG Confiabilidade* <br><br>

#### <a>Propagação de erros</a>
<img src="./../../assets/NFR/NFR-Confiabilidade-Propagado.png">

*Figura 4 - SIG Confiabilidade Com Propagação de erros* <br><br>

</center>

### <a>Desempenho</a>

<center>

#### <a>Sem Propagação</a>
<img src="./../../assets/NFR/NFR-Desempenho.png">

*Figura 5 - SIG Desempenho* <br><br>

#### <a>Propagação de erros</a>
<img src="./../../assets/NFR/NFR-Desempenho-Propagado.png">

*Figura 6 - SIG Desempenho Com Propagação de erros* <br><br>

</center>

### <a>Suportabilidade</a>

<center>

#### <a>Sem Propagação</a>
<img src="./../../assets/NFR/NFR-Suportabilidade.png">

*Figura 7 - SIG Suportabilidade* <br><br>

#### <a>Propagação de erros</a>
<img src="./../../assets/NFR/NFR-Suportabilidade-Propagado.png">

*Figura 8 - SIG Suportabilidade Com Propagação de erros* <br><br>

</center>

## <a>Bibliografia</a>
[1] Chung, Lawrence; A. Nixon, Brian; Mylopoulos, John. Non-Functional Requirements in Software Engineering. Acesso em 26 de Dezembro de 2022

[2] 2020.1-GuardioesdaSaude. Disponível em: https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude/modelagem/NFR/. Acesso em: 27 de Dezembro de 2022

[3] SILVA, R. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Tese (Mestrado em Engenharia de Software) - Centro de Informática, Universidade Federal de Pernambuco. Recife, p. 155. 2019. Acesso em: 25 de Dezembro de 2022