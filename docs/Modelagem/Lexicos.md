# Léxicos

## Histórico de Versão

|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: | :------: | :------: | :-----------: | :---------: |:---------: |
|09/12/2022|10/12/2022|1.0|Criação do documento| [Ana Luiza](https://github.com/AnHoff) | [João Lucas](https://github.com/HacKairos) |

## Introdução

Uma parte importante do processo de elicitar requisitos é identificar palavras-chave e frases, também chamados de símbolos, pertencentes à área do aplicativo analisado. Com isso em mente, tem-se a atuação do Léxico, uma técnica utilizada para descrever símbolos de uma linguagem. Cada símbolo identificado se torna um léxico e é descrito com uma noção, relacionada ao símbolo em si, e um impacto, relacionado ao efeito do símbolo na aplicação ou da aplicação sobre o símbolo.

## Metodologia

Os léxicos apresentados foram identificados a partir dos requisitos elicitados e priorizados, que podem ser conferidos [aqui](../Requisitos/tecnicas-priorizacao.md), e pelo uso do aplicativo MEI. Será seguido o princípio do vocabulário mínimo, que visa descrever de modo claro e em poucas palavras, juntamente com o princípio circular, que promove a referência a outros léxicos a partir da descrição.

Os léxicos serão apresentados de acordo com o exemplo presente na tabela 1.<br><br>

<center style="max-width: 500px; margin: auto; align-items: center;">

|**LXX**|_Nome do Léxico._|
|:---|:---|
|**Autor**|_Autor do Léxico_|
|**Classificação**|_Classificação do léxico (estado, objeto ou verbo)_|
|**Sinônimos**|_Sinônimos do léxico no contexto_|
|**Noção**|_Noções do léxico_|
|**Impacto**|_Impacto do léxico na aplicação_|
|**Rastro**| XX00 |

Tabela 1 - Exemplificação dos léxicos<br><br>

</center>

## Léxicos Identificados

<center style="max-width: 500px; margin: auto; align-items: center;">

### L01 - Usuário
|**L01**|_Usuário_|
|:---|:---|
|**Autor**|_Ana Luiza_|
|**Classificação**|_Objeto_|
|**Sinônimos**|_Utilizador, cliente, consumidor, utente_|
|**Noção**|_Pessoa(s) que utiliza o MEI_|
|**Impacto**|_Os usuários possuem acesso a todas as funcionalidades do MEI_|
|**Rastro**|[BS02](../Requisitos/Elicitacao/Brainstorming.md)|

Tabela 2 - Léxico 1 <br><br>

<hr>

### L02 - Conta
|**L02**|Conta|
|:---|:---|
|**Autor**|_Ana Luiza_|
|**Classificação**|_Objeto_|
|**Sinônimos**|_-_|
|**Noção**|_Conjunto de dados e permissões do usuário_|
|**Impacto**| _Os usuários podem ter acesso às próprias informações e alterá-las_|
|**Rastro**|[BS02](../Requisitos/Elicitacao/Brainstorming.md)|

Tabela 3 - Léxico 2<br><br>

<hr>

### L03 - Acessar
|**L03**|Acessar|
|:---|:---|
|**Autor**|_Ana Luiza_|
|**Classificação**|_Verbo_|
|**Sinônimos**|_Conectar, entrar, ingressar_|
|**Noção**|_O usuário acessa o MEI ou alguma de suas funcionalidades_|
|**Impacto**| _Os usuários podem ter acesso a qualquer função do aplicativo por meio de qualquer dispositivo_|
|**Rastro**|[BS02](../Requisitos/Elicitacao/Brainstorming.md)|

Tabela 4 - Léxico 3<br><br>

<hr>

### L04 - Emitir
|**L04**|Emitir|
|:---|:---|
|**Autor**|_Ana Luiza_|
|**Classificação**|_Verbo_|
|**Sinônimos**|_Lançar, soltar, libertar_|
|**Noção**|_Emissão de um documento_|
|**Impacto**| _Os usuários podem emitir um documento selecionado para pagamento ou consulta_|
|**Rastro**|[IS02](../Requisitos/Elicitacao/Introspeccao.md)|

Tabela 5 - Léxico 4<br><br>

<hr>

### L05 - DAS
|**L05**|DAS|
|:---|:---|
|**Autor**|_Ana Luiza_|
|**Classificação**|_Objeto_|
|**Sinônimos**|_Documento de Arrecadação do Simples Nacional_|
|**Noção**|_Meio do empresário recolher os impostos_|
|**Impacto**| _Permite que o(s) usuário(s) recolham e vejam informações sobre os impostos_|
|**Rastro**|[IS02](../Requisitos/Elicitacao/Introspeccao.md)|

Tabela 6 - Léxico 5<br><br>

<hr>

### L06 - Liquidado
|**L06**|Liquidado|
|:---|:---|
|**Autor**|_Ana Luiza_|
|**Classificação**|_Estado_|
|**Sinônimos**|_Pagar, resolver, saldar_|
|**Noção**|_Classificação que mostra ao usuário o que foi pago_|
|**Impacto**| _O usuário poderá conferir quais documentos já foram pagos em seu CNPJ_|
|**Rastro**|[IS02](../Requisitos/Elicitacao/Introspeccao.md)|

Tabela 7 - Léxico 6<br><br>

<hr>

### L07 - A vencer
|**L07**|A vencer|
|:---|:---|
|**Autor**|_Ana Luiza_|
|**Classificação**|_Estado_|
|**Sinônimos**|_Arrasar, exceder_|
|**Noção**|_Classificação que mostra ao usuário o que não foi pago_|
|**Impacto**| _O usuário poderá conferir quais documentos ainda não foram pagos em seu CNPJ_|
|**Rastro**|[IS02](../Requisitos/Elicitacao/Introspeccao.md)|

Tabela 8 - Léxico 7<br><br>

<hr>

### L08 - Exibir
|**L08**|Exibir|
|:---|:---|
|**Autor**|_Ana Luiza_|
|**Classificação**|_Verbo_|
|**Sinônimos**|_Manifestar, apresentar, transparecer_|
|**Noção**|_Função que mostra informações sobre algo_|
|**Impacto**| _O usuário pode exibir legendas e dados específicos que não aparecem em primeiro plano_|
|**Rastro**|[IS08](../Requisitos/Elicitacao/Introspeccao.md)|

Tabela 9 - Léxico 8<br><br>

<hr>

### L09 - CNPJ
|**L09**|CNPJ|
|:---|:---|
|**Autor**|_Ana Luiza_|
|**Classificação**|_Objeto_|
|**Sinônimos**|_Cadastro Nacional de Pessoa Jurídica_|
|**Noção**|_Número único de identificação de uma pessoa jurídica_|
|**Impacto**| _O usuário pode ter acesso a todas as funcionalidades do MEI e legalização de seu trabalho a partir da criação de um CNPJ_|
|**Rastro**|[BS01](../Requisitos/Elicitacao/Brainstorming.md)|

Tabela 10 - Léxico 9<br><br>

<hr>

### L10 - Pessoa Jurídica
|**L10**|Pessoa Jurídica|
|:---|:---|
|**Autor**|_Ana Luiza_|
|**Classificação**|_Objeto_|
|**Sinônimos**|_Empresa, sociedade, organização, PJ_|
|**Noção**|_Entidade formada por uma ou mais Pessoas Físicas com propósitos e finalidades específicos_|
|**Impacto**| _Pessoas Jurídicas obtém acesso ao MEI e a todos os recursos disponíveis às entidades_|
|**Rastro**|[BS01](../Requisitos/Elicitacao/Brainstorming.md)|

Tabela 11 - Léxico 10<br><br>

<hr>

### L11 - Legenda
|**L11**|Legenda|
|:---|:---|
|**Autor**|_Ana Luiza_|
|**Classificação**|_Objeto_|
|**Sinônimos**|_Rótulo, descrição, etiqueta_|
|**Noção**|_Textos que explicam uma tabela ou imagem, agregando significado ou esclarecimento_|
|**Impacto**| _O usuário poderá ativar e desativar as legendas de acordo com o necessário para entender o que precisa_|
|**Rastro**|[BS12](../Requisitos/Elicitacao/Brainstorming.md)|

Tabela 12 - Léxico 11<br><br>

</center>

## Conclusão

O vocabulário do MEI é simples e não possui muitos símbolos próprios da sua área de atuação. Esse fato é vantajoso para os usuários, visto que muitos não possuem experiência com vocabulário financeiro específico. Por outro lado, as palavras-chave específicas não são explicadas para o usuário e isso pode tornar o uso complicado para quem acessa o aplicativo pela primeira vez.

Pode-se dizer então que o MEI possui uma boa escolha de vocabulário e é fácil de se acostumar com as palavras-chave novas encaradas pelos usuários. No entanto, deveriam haver mais legendas ou descrições para esclarecer melhor e mais rápido qualquer vocabulário que esteja fora da zona de conforto de um usuário leigo.

## Bibliografia
SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 10;

Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) _Interação Humano-Computador e Experiência do usuário_. Autopublicação. ISBN: 978-65-00-19677-1.
