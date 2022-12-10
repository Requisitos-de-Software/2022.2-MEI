# Cenários

## Histórico de Versão
|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:-----------:| :------: | :-----------: | :---------: |:---------: |
|09/12/2022|10/12/2022|1.0|Criação do documento| [Pedro Lucas](https://github.com/PedroLSF)| |

## Introdução
Um caso de uso define uma sequência de ações executadas pelo sistema que geram um resultado de valor observável para um ator em particular. Cada caso de uso deve gerar um significado de valor para o ator que utilia o sistema.

## Metodologia
Após a elicitação de requisitos funcionais, o grupo esolheu os principais requisitos para o desenvolvimento de tabelas e diagramas de casos de uso.

## Casos de Uso
Legenda:
* UC -> Caso de Uso

### UC01 - Fazer Login

|**UC01**|**Fazer Login**|
| :----------: |:-----------|
|Versão|Atual: 1.0 (10/12)|
|Autores|Pedro Lucas e Thiago|
|Descrição|Fazer Login no MEI|
|Atores|> Usuário <br> > MEI|
|Pré Condições|> Usuário <br> > MEI|
|Fluxo Principal|> Usuário acessa o MEI <br> > Usuário digita o CNPJ <br> > Usuário digita sua senha <br> > Usuário clica em "Acessar" <br> > Usuário ficará logado até sair|
|Fluxo Alternativo|Por ser um processo burocrático, não tem fluxo alternativo|
|Fluxo de Exceção|**Fluxo de Exceção 1 - CNPJ inválido** <br> > Aplicativo avisa que não foi possível realizar o login <br> **Fluxo de Exceção 2 - Esquecer a Senha** <br> > Usuário clica em "Esqueceu a Senha?" <br> Usuário recebe um e-mail e sms para recuperar |
|Pós Condições|Usuário fica logado e pode realizar todas as ações|
|Rastreabilidade|BS02|


### UC02 - Acesso a Suporte

|**UC02**|**Fazer Login**|
| :----------: |:-----------|
|Versão|Atual: 1.0 (10/12)|
|Autores|Pedro Lucas e Thiago|
|Descrição|Fazer Login no MEI|
|Atores|> Usuário <br> > MEI|
|Pré Condições|> Usuário <br> > MEI|
|Fluxo Principal|> Usuário acessa o MEI <br> > Usuário digita o CNPJ <br> > Usuário digita sua senha <br> > Usuário clica em "Acessar" <br> > Usuário ficará logado até sair|
|Fluxo Alternativo|Por ser um processo burocrático, não tem fluxo alternativo|
|Fluxo de Exceção|**Fluxo de Exceção 1 - CNPJ inválido** <br> > Aplicativo avisa que não foi possível realizar o login <br> **Fluxo de Exceção 2 - Esquecer a Senha** <br> > Usuário clica em "Esqueceu a Senha?" <br> Usuário recebe um e-mail e sms para recuperar |
|Pós Condições|Usuário fica logado e pode realizar todas as ações|
|Rastreabilidade|BS02|
