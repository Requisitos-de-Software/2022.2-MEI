# Cenários

## Histórico de Versão
|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:-----------:| :------: | :-----------: | :---------: |:---------: |
|09/12/2022|10/12/2022|1.0|Criação do documento| [João Lucas](https://github.com/HacKairos) e [Eduardo](https://github.com/edudsan) | [Ana Luiza](https://github.com/AnHoff) |

## Introdução
Cenários são representações do contexto do sistema por meio de histórias de pessoas realizando atividades, sendo específicos e ricos em detalhes de contexto de uso do aplicativo. Os cenários incluem usuários, processos e dados reais ou potenciais; eles podem ser expostos em formato de texto ou narrativa visual. Os cenários não são apenas poderosos; eles também são uma ferramenta importante no processo geral de design porque representam um investimento de custo e tempo menor em comparação com os protótipos.

## Metodologia
Este projeto utiliza personas para representar situações em que a plataforma pode ser utilizada e para representar problemas enfrentados tanto pela plataforma quanto pelos usuários.

## Representação dos Cenários
A seguir, na Tabela 1, está representada a forma como os cenários serão representados.

<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**     | **Número do Cenário** |
| :--------------:| :-------------- |
| **Titulo**      | _Nome do Cenário._ |
| **Objetivo**    | _Objetivo do Cenário._ |
| **Contexto**    | Local: _Local onde acontece o Cenário._<br>Tempo: _Tempo do Cenário._<br>Pré-condição: _Condição para que o Cenário aconteça._ |
| **Atores**      | _Ator(es) do Cenário._ |
| **Recursos**    | _Recursos do Cenário._ |
| **Episódios**   | _Episódios do Cenário da aplicação._ |
| **Restrição**   | _Restrição do Cenário._ |
| **Exceção**     | _Exceção do Cenário._ |

Tabela 1 - Representação dos cenários

</center>

## Cenários

Nas tabelas de 2 a 11 a seguir estão representados alguns cenários.<br></br><br>

<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**     | **001** |
| :--------------:| :-------------- |
| **Titulo**      | _Emissão de DAS em aberto, do ano atual._ |
| **Objetivo**    | _Emitir boleto  em aberto do DAS recente._ |
| **Contexto**    | **Local**: _Tela de Emitir DAS._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet<br>Smartphone com o MEI instalado_ |
| **Episódios**   | _Usúario acessa o app com o CNPJ<br>Usário acessa a opção Emitir DAS<br>Usuário escolhe o mês em aberto para realizar o pagamento<br>Usuário tem acesso ao boleto_ |
| **Restrição**   | _Internet indisponível<br>Todos os DAS pagos_ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone<br>Internet indisponivel._ |

Tabela 2 - Cenário 001<br></br><br>


| **Cenário**     | **002** |
| :--------------:| :-------------- |
| **Titulo**      | _Perguntas e Respostas._ |
| **Objetivo**    | _Ter acesso as perguntas e respostas do app._ |
| **Contexto**    | **Local**: _Tela após acessar o CNPJ, a opção Perguntas e respostas._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet<br>Smartphone com o MEI instalado._ |
| **Episódios**   | _Usúario acessa o app com o CNPJ<br>Usuário acessa a opção Perguntas e Respostas<br>O aplicativo baixa um pdf no celular do usuario mostrando as perguntas mais frequentes e suas respostas_ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone<br>Internet indisponivel_ |

Tabela 3 - Cenário 002<br></br><br>

| **Cenário**     | **003** |
| :--------------:| :-------------- |
| **Titulo**      | _Favoritar CNPJ._ |
| **Objetivo**    | _Deixar CNPJ salvo nos favoritos._ |
| **Contexto**    | **Local**: _Tela apos acessar com CNPJ._<br>**Tempo**: _Rapido._<br>**Pré-condição**: _CNPJ não estar favoritado._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet<br>Smartphone com o MEI instalado._ |
| **Episódios**   | _Usúario acessa o app com o CNPJ<br>Usuário clica na estrela ao lado do número do CNPJ_ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone<br>Internet indisponivel_ |

Tabela 4 - Cenário 003<br></br><br>

| **Cenário**     | **004** |
| :--------------:| :-------------- |
| **Titulo**      | _Exibir Legenda._ |
| **Objetivo**    | _Exibir Legenda do estado do DAS._ |
| **Contexto**    | **Local**: _Tela de Emitir DAS._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet<br>Smartphone com o MEI instalado._ |
| **Episódios**   | _Usúario acessa o app com o CNPJ<br>Usuário acessa a opção Emitir DAS<br>Usuário clica na opção Exibir legenda_ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone<br>Internet indisponivel_ |

Tabela 5 - Cenário 004<br></br><br>

| **Cenário**     | **005** |
| :--------------:| :-------------- |
| **Titulo**      | _Compartilhar estado do DAS._ |
| **Objetivo**    | _Compartilhar imagem contendo a informação de quais DAS foram liquidados._ |
| **Contexto**    | **Local**: _Tela de Emitir DAS._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet<br>Smartphone com o MEI instalado._ |
| **Episódios**   | _Usúario acessa o app com o CNPJ<br>Usuário acessa a opção Emitir DAS<br>Usuário clica no botão de compartilhar._ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone<br>Internet indisponivel._ |

Tabela 6 - Cenário 005<br></br><br>

| **Cenário**     | **006** |
| :--------------:| :-------------- |
| **Titulo**      | _Consultar CNPJ._ |
| **Objetivo**    | _Realizar uma consulta sobre o status do próprio CNPJ._ |
| **Contexto**    | **Local**: _Tela de Consultar CNPJ._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet<br>Smartphone com o MEI instalado._ |
| **Episódios**   | _Usuário acessa o app com o CNPJ<br>Usuário acessa a opção de Consulta CNPJ._ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone<br>Internet indisponivel._ |

Tabela 7 - Cenário 006<br></br><br>

| **Cenário**     | **007** |
| :--------------:| :-------------- |
| **Titulo**      | _Compartilhar consulta do CNPJ._ |
| **Objetivo**    | _Compartilhar imagem contendo a informação da consulta do CNPJ._ |
| **Contexto**    | **Local**: _Tela de Consulta CNPJ._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet, Smartphone e o MEI instalado._ |
| **Episódios**   | _Usuário acessa o app com o CNPJ<br>Usuário clica na opção Consulta CNPJ<br>Usuário resolve o captcha<br>Usuário clica no botão de compartilhar._ |
| **Restrição**   | _Internet indisponivel._ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone<br>Internet indisponivel<br>Errar o captcha._ |

Tabela 8 - Cenário 007<br></br><br>

| **Cenário**     | **008** |
| :--------------:| :-------------- |
| **Titulo**      | _Consultar SIMEI._ |
| **Objetivo**    | _Realizar uma consulta sobre o status do SIMEI._ |
| **Contexto**    | **Local**: _Tela de Consulta SIMEI._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet, Smartphone e o MEI instalado._ |
| **Episódios**   | _Usuário acessa o app com o CNPJ<br>Usuário acessa a opção de Consulta SIMEI_ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone<br>Internet indisponivel_ |

Tabela 9 - Cenário 008<br></br><br>

| **Cenário**     | **009** |
| :--------------:| :-------------- |
| **Titulo**      | _Compartilhar consulta do SIMEI._ |
| **Objetivo**    | _Compartilhar imagem contendo a informação da consulta do SIMEI._ |
| **Contexto**    | **Local**: _Tela de Consulta SIMEI._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet<br>Smartphone com o MEI instalado_ |
| **Episódios**   | _Usuário acessa o app com o CNPJ<br>Usuário clica na opção Consulta SIMEI<br>Usuário clica no botão de compartilhar_ |
| **Restrição**   | _Internet indisponivel._ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone<br>Internet indisponivel_ |

Tabela 10 - Cenário 009<br></br><br>

| **Cenário**     | **010** |
| :--------------:| :-------------- |
| **Titulo**      | _Pedido de Restituição._ |
| **Objetivo**    | _Solicitar a restituição de um pagamento realizado indevidamente._ |
| **Contexto**    | **Local**: _Tela de Pedido de Restituição._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _[Usuário](../Lexicos/#l01-usuario) com CNPJ ativo._ |
| **Recursos**    | _Internet<br>Smartphone com o MEI instalado_ |
| **Episódios**   | _Usuário acessa o app com o CNPJ<br>Usuário clica na opção Pedido de Restituição<br> Usuário clica no botão de "+"<br>Usuário informa o período desejado<br>Usuário clica no DAS que for exibido<br>Usuário solicita restituição_ |
| **Restrição**   | _Internet indisponivel_ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone<br>Internet indisponivel<br>Data não estar mais disponível para restituição._ |

Tabela 11 - Cenário 010

</center>

## Bibliografia
Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) _Interação Humano-Computador e Experiência do usuário_. Autopublicação. ISBN: 978-65-00-19677-1.
