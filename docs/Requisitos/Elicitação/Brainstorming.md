# Brainstorming

## Histórico de Versão

|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:----------:| :------: | :-----------: | :---------: |:---------: |
|03/12/2022|04/12/2022|1.0|Criação do documento| [Pedro Lucas](https://github.com/PedroLSF) |[Ana Luiza](https://github.com/AnHoff)|
|04/12/2022|05/12/2022|1.1|Adição de links e detalhamento do texto| [Joao Lucas](https://github.com/HacKairo) |[Pedro Lucas](https://github.com/PedroLSF)|

## Introdução
Caso deseje entender mais sobre a técnica utilizada nesse documento clique [*aqui*](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicita%C3%A7%C3%A3o/tecnicas-elicitacao/)

O brainstorming foi realizado durante a 5ª Reunião do grupo, no dia 3 de dezembro de 2022.

Instruções do Brainstorming da equipe:

A equipe irá se dividir em 1 mediador e 3 possíveis personas, a fim de se colocar no lugar do usuário e elicitar alguns requisitos.

* Mediador: Thiago Oliveira.
* Personas: Pedro Lucas, João Lucas e Eduardo.

Os seguintes dados serão a introduzação das personas que iremos utilizar no brainstorming:

#### João Silva - Pedro Lucas
* **Idade**: 35 anos;
* **Tipo**: Primário;
* **Sexo**: Masculino;
* **Local de trabalho**: Casa Própria;
* **Meios utilizados**: Redes Sociais e site próprio para divulgação e venda;
* **Acesso**: Celular;
* **Funcionários**: Não Possui;
* **Atividades extra**: Cuida de um filho deficiente;
* **Status socioeconômico**: Classe Baixa;
* **Descrição**: Produz cerâmica para ter uma renda;
* **Motivação**: realizou um curso profissionalizante de produção de cerâmica e precisava de uma renda;
* **Afinidade com tecnologia**: Alta.

#### Isabela Menezes - Eduardo
* **Idade**: 22 anos;
* **Tipo**: Primário;
* **Sexo**: Feminino;
* **Local de trabalho**: Casa própria;
* **Meios utilizados**: Redes sociais para divulgação;
* **Acesso**: Computador e Celular;
* **Funcionários**: Não Possui;
* **Atividades extra**: Faculdade;
* **Status socioeconômico**: Classe Média;
* **Descrição**: Começou a produzir vestuário e está começando a empreender;
* **Motivação**: Já produzia peças de roupa para si mesma e recebeu indicações para iniciar um trabalho autônomo de confecção e venda de vestuário;
* **Afinidade com tecnologia**: Média.

#### Salete Camargo - João Lucas
* **Idade**: 65 anos;
* **Tipo**: Secundária;
* **Sexo**: Feminino;
* **Local de trabalho**: Casa Própria;
* **Meios utilizados**: Venda Local;
* **Acesso**: Celular;
* **Funcionários**: Não possui;
* **Atividades extra**: Nenhuma;
* **Status socioeconômico**: Classe Média;
* **Descrição**: Devido a sua idade, não consegue exercer bem os trabalhos que necessitam de esforço fisíco e para se distrair começou a produzir manufaturado;
* **Motivação**: Queria entreter-se no tempo livre e seu hobby virou uma fonte de renda extra;
* **Afinidade com tecnologia**: Baixa.

Após a definição dos perfis, o brainstorming será realizado e o desenvolvimento pode ser encontrado [**aqui**](https://youtu.be/IEj32_Gj0Vo) (Link com o video completo do *Brainstorming*).

Tabela de requisitos funcionais:

|ID|Requisito|Descrição|Nível de Benefício| Penalidade |
| :----------: |:----------:| :------: | :-----------: | :---------: |
|BS01|Cadastro|O aplicativo deve instruir o usuário para a criação do CNPJ|9|9|
|BS02|Login|Implementação de um sistema de login|9|9|
|BS03|Lembrete|O aplicativo deve emitir um lembrete para o pagamento do DAS|4|5|
|BS04|Depedência|O aplicativo deve obter dados dentro do próprio aplicativo|6|7|
|BS05|Plataforma Única|O aplicativo deve solicitar autorização para pegar dados de outros sites do governo|6|6|
|BS06|Avisos|O aplicativo deve mostrar de forma clara se uma ação foi realizada com sucesso ou não|4|3|
|BS07|Suporte|O aplicativo deve fornecer suporte para os usuários|4|6|


Tabela de requisitos não funcionais:

|ID|Requisito|Descrição|Nível de Benefício| Penalidade |
| :----------: |:----------:| :------: | :-----------: | :---------: |
|BS08|Diversificação|O aplicativo deve ser possível de ser utilizado na maioria dos modelos de dispositivos|7|7|
|BS09|Segurança|O aplicativo deve validar a pessoa que está utilizando o CNPJ|8|8|
|BS10|Diversificação|O aplicativo deve ser possível de ser utilizado na maioria dos modelos de SO|9|7|
|BS11|Acessibilidade|O aplicativo deve ser acessível para usuário com algum tipo de deficiência|5|6|
|BS12|Detalhar Texto|O aplicativo deve conter texto que seja de fácil entendimento|5|5|

**Legendas**:

* BS -> Brainstorming
* Nível de Benefício -> Vaira de 1 a 9, onde 1 é pouco benéfico e 9 é muito benéfico
* Penalidade -> Varia de 1 a 9, onde 1 não gera muitos problemas e 9 impossibilita o uso do usuário
