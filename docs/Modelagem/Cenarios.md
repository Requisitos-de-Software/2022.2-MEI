# Cenários

## Histórico de Versão
|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:-----------:| :------: | :-----------: | :---------: |:---------: |
|09/12/2022|10/12/2022|1.0|Criação do documento| [João Lucas](https://github.com/HacKairos) e [Eduardo](https://github.com/edudsan) | [ ](https://github.com/) |

## Introdução
Cenários são representações do contexto do sistema por meio de histórias de pessoas realizando atividades e são específicos e ricos em detalhes de contexto de uso do aplicativo, incluindo usuários, processos e dados reais ou potenciais. , texto ou narrativa visual. Os cenários não são apenas poderosos, mas também são uma ferramenta importante no processo geral de design porque representam um investimento de custo e tempo menor em comparação com os protótipos.

## Metodologia
Este projeto utiliza personas para representar situações em que a plataforma pode ser utilizada e para representar problemas enfrentados tanto pela plataforma quanto pelos usuários.

## Representação dos Cenários
A seguir na Tabela 1 a forma a qual sera representada os cenários.
<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**     | **Número do Cenário** |
| :--------------:| :-------------- |
| **Titulo**      | _Nome do Cenário._ |
| **Objetivo**    | _Objetivo do Cenário._ |
| **Contexto**    | Local: _Local onde acontece o Cenário._<br>Tempo: _Tempo do Cenário._<br>Pré-condição: _Condição para que o Cenário aconteça._ |
| **Atores**      | _Autor(es) do Cenário._ |
| **Recursos**    | _Recursos do Cenário._ |
| **Episódios**   | _Episódios do Cenário da aplicação._ |
| **Restrição**   | _Restrição do Cenário._ |
| **Exceção**     | _Exceção do Cenário._ |

Tabela 1 - representação dos cenários.
</center>

## Cenários

Nas tabelas a seguir estão representados alguns cenários.<br></br><br>
<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**     | **001** |
| :--------------:| :-------------- |
| **Titulo**      | _Emissão de DAS em aberto, do ano atual._ |
| **Objetivo**    | _Emitir boleto  em aberto do DAS recente._ |
| **Contexto**    | Local: _Tela de Emitir DAS._<br>Tempo: _Indeterminado._<br>Pré-condição: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet, Smartphone e o MEI instalado._ |
| **Episódios**   | _Usúario acessa o app com o CNPJ, acessa a opção Emitir DAS,<br> escolhe o mes em aberto para realizar o pagamento e tem acesso ao boleto._ |
| **Restrição**   | _Internet indisponível, todos os DAS pagos._ |
| **Exceção**     | _CNPJ invalido, Não ter acesso ao smartphone, Internet indisponivel._ |

Tabela 2 - Cenario 001<br></br><br>


| **Cenário**     | **002** |
| :--------------:| :-------------- |
| **Titulo**      | _Perguntas e Respostas._ |
| **Objetivo**    | _Ter acesso as perguntas e respostas do app._ |
| **Contexto**    | Local: _Tela após acessar o CNPJ, a opção Perguntas e respostas._<br>Tempo: _Indeterminado._<br>Pré-condição: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet, Smartphone e o MEI instalado._ |
| **Episódios**   | _Usúario acessa o app com o CNPJ, acessa a opção Perguntas e Respostas,<br>após isso o aplicativo baixa um pdf no celular do usuario mostrando as perguntas<br> mais frequentes e suas respostas._ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido, Não ter acesso ao smartphone, Internet indisponivel._ |

Tabela 3 - Cenario 002<br></br><br>

| **Cenário**     | **003** |
| :--------------:| :-------------- |
| **Titulo**      | _Favoritar CNPJ._ |
| **Objetivo**    | _Deixar CNPJ salvo nos favoritos._ |
| **Contexto**    | Local: _Tela apos acessar com CNPJ._<br>Tempo: _Rapido._<br>Pré-condição: _CNPJ não estar favoritado._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet, Smartphone e o MEI instalado._ |
| **Episódios**   | _Usúario acessa o app com o CNPJ e clica na estrela do lado do número do CNPJ._ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido, Não ter acesso ao smartphone, Internet indisponivel._ |

Tabela 4 - Cenario 003<br></br><br>

| **Cenário**     | **004** |
| :--------------:| :-------------- |
| **Titulo**      | _Exibir Legenda._ |
| **Objetivo**    | _Exibir Legenda do estado do DAS._ |
| **Contexto**    | Local: _Tela de Emitir DAS._<br>Tempo: _Indeterminado._<br>Pré-condição: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet, Smartphone e o MEI instalado._ |
| **Episódios**   | _Usúario acessa o app com o CNPJ, acessa a opção Emitir DAS,<br> clica na opção Exibir legenda._ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido, Não ter acesso ao smartphone, Internet indisponivel._ |

Tabela 5 - Cenario 004<br></br><br>

| **Cenário**     | **005** |
| :--------------:| :-------------- |
| **Titulo**      | _Compartilhar estado do DAS._ |
| **Objetivo**    | _Compartilhar imagem contendo a informação de quais DAS foram liquidados._ |
| **Contexto**    | Local: _Tela de Emitir DAS._<br>Tempo: _Indeterminado._<br>Pré-condição: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet, Smartphone e o MEI instalado._ |
| **Episódios**   | _Usúario acessa o app com o CNPJ, acessa a opção Emitir DAS,<br> clica no botão de compartilhar._ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido, Não ter acesso ao smartphone, Internet indisponivel._ |

Tabela 6 - Cenario 005<br></br><br>

| **Cenário**     | **006** |
| :--------------:| :-------------- |
| **Titulo**      | _Consultar CNPJ._ |
| **Objetivo**    | _Realizar uma consulta sobre o status do próprio CNPJ._ |
| **Contexto**    | Local: _Tela de Consultar CNPJ._<br>Tempo: _Indeterminado._<br>Pré-condição: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet, Smartphone e o MEI instalado._ |
| **Episódios**   | _Usuário acessa o app com o CNPJ, acessa a opção de Consulta CNPJ._ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido, Não ter acesso ao smartphone, Internet indisponivel._ |

Tabela 7 - Cenario 006<br></br><br>

| **Cenário**     | **007** |
| :--------------:| :-------------- |
| **Titulo**      | _Compartilhar consulta do CNPJ._ |
| **Objetivo**    | _Compartilhar imagem contendo a informação da consulta do CNPJ._ |
| **Contexto**    | Local: _Tela de Consulta CNPJ._<br>Tempo: _Indeterminado._<br>Pré-condição: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet, Smartphone e o MEI instalado._ |
| **Episódios**   | _Usuário acessa o app com o CNPJ, clica na opção Consulta CNPJ,<br> resolve o captcha, clica no botão de compartilhar._ |
| **Restrição**   | _Internet indisponivel._ |
| **Exceção**     | _CNPJ invalido, Não ter acesso ao smartphone, Internet indisponivel, Errar o captcha._ |

Tabela 8 - Cenario 007<br></br><br>

| **Cenário**     | **008** |
| :--------------:| :-------------- |
| **Titulo**      | _Consultar SIMEI._ |
| **Objetivo**    | _Realizar uma consulta sobre o status do SIMEI._ |
| **Contexto**    | Local: _Tela de Consulta SIMEI._<br>Tempo: _Indeterminado._<br>Pré-condição: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet, Smartphone e o MEI instalado._ |
| **Episódios**   | _Usuário acessa o app com o CNPJ, acessa a opção de Consulta SIMEI._ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido, Não ter acesso ao smartphone, Internet indisponivel._ |

Tabela 9 - Cenario 008<br></br><br>

| **Cenário**     | **009** |
| :--------------:| :-------------- |
| **Titulo**      | _Compartilhar consulta do SIMEI._ |
| **Objetivo**    | _Compartilhar imagem contendo a informação da consulta do SIMEI._ |
| **Contexto**    | Local: _Tela de Consulta SIMEI._<br>Tempo: _Indeterminado._<br>Pré-condição: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet, Smartphone e o MEI instalado._ |
| **Episódios**   | _Usuário acessa o app com o CNPJ, clica na opção Consulta SIMEI,<br> clica no botão de compartilhar._ |
| **Restrição**   | _Internet indisponivel._ |
| **Exceção**     | _CNPJ invalido, Não ter acesso ao smartphone, Internet indisponivel._ |

Tabela 10 - Cenario 009<br></br><br>

| **Cenário**     | **010** |
| :--------------:| :-------------- |
| **Titulo**      | _Pedido de Restituição._ |
| **Objetivo**    | _Solicitar a restituição de um pagamento realizado indevidamente._ |
| **Contexto**    | Local: _Tela de Pedido de Restituição._<br>Tempo: _Indeterminado._<br>Pré-condição: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet, Smartphone e o MEI instalado._ |
| **Episódios**   | _Usuário acessa o app com o CNPJ, clica na opção Pedido de Restituição,<br> clica no botão de "+", informa o período desejado, clica no DAS que for exibido,<br> depois clica em Solicitar Restituição._ |
| **Restrição**   | _Internet indisponivel._ |
| **Exceção**     | _CNPJ invalido, Não ter acesso ao smartphone, Internet indisponivel,<br> Data não estar mais disponível para restituição._ |

Tabela 11 - Cenario 010

</center>

## Bibliografia
Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) _Interação Humano-Computador e Experiência do usuário_. Autopublicação. ISBN: 978-65-00-19677-1.
