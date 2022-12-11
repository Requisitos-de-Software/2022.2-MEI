# Casos de Uso

## Histórico de Versão
|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:-----------:| :------: | :-----------: | :---------: |:---------: |
|09/12/2022|10/12/2022|1.0|Criação do documento| [Pedro Lucas](https://github.com/PedroLSF)|[Thiago Oliveira](https://github.com/Thiab394) |
|10/12/2022|11/12/2022|1.1|Adição Dos Diagramas de Caso de Uso| [Thiago Oliveira](https://github.com/Thiab394)| [Pedro Lucas](https://github.com/PedroLSF)|

## Introdução
Um caso de uso define uma sequência de ações executadas pelo sistema que geram um resultado de valor observável para um ator em particular. Cada caso de uso deve gerar um significado de valor para o ator que utiliza o sistema.

## Metodologia
Após a elicitação de requisitos funcionais, o grupo escolheu os principais requisitos para o desenvolvimento de tabelas e diagramas de casos de uso.

## Casos de Uso
Legenda:
* UC -> Caso de Uso
### **Casos de Uso Geral**

<center>
<img src='./../../assets/images/Casos de Uso/Diagrama de caso de uso - UC Geral.png'pngwidth="1000"> Figura 1 - Diagrama Do UC Geral</img>
</center>

### **UC01 - Fazer Login**
<center>
<img src='./../../assets/images/Casos de Uso/Diagrama de caso de uso - UC 01.png'pngwidth="1000">Figura 2 - Diagrama Do UC 01</img>
</center>

|**UC01**|**Fazer Login**|
| :----------: |:-----------|
|Versão|Atual: 1.0 (10/12)|
|Autores|Pedro Lucas e Thiago|
|Descrição|Fazer Login no MEI|
|Atores|> Usuário <br> > MEI|
|Pré Condições|> Estar deslogado|
|Fluxo Principal|> Usuário acessa o MEI <br> > Usuário digita o CNPJ <br> > Usuário digita sua senha <br> > Usuário clica em "Acessar" <br> > Usuário ficará logado até sair|
|Fluxo Alternativo|Por ser um processo burocrático, não tem fluxo alternativo|
|Fluxo de Exceção|**Fluxo de Exceção 1 - CNPJ inválido** <br> > Aplicativo avisa que não foi possível realizar o login <br> **Fluxo de Exceção 2 - Esquecer a Senha** <br> > Usuário clica em "Esqueceu a Senha?" <br> Usuário recebe um e-mail e sms para recuperar |
|Pós Condições|Usuário fica logado e pode realizar todas as ações|
|Rastreabilidade|BS02|

### **UC02 - Cadastro**
<center>
<img src='./../../assets/images/Casos de Uso/Diagrama de caso de uso - UC 02.png'pngwidth="1000">Figura 3 - Diagrama Do UC 02</img>
</center>

|**UC02**|**Realizar Cadastro**|
| :----------: |:-----------|
|Versão|Atual: 1.0 (10/12)|
|Autores|Pedro Lucas e Thiago|
|Descrição|Enviar as documentações necessárias para virar MEI|
|Atores|> Usuário <br> > MEI|
|Pré Condições|> Não ser MEI|
|Fluxo Principal|> Usuário acessa o MEI <br> > Usuário clica em "Criar CNPJ" <br> > Usuário envia todas as documentações <br>|
|Fluxo Alternativo|Por ser um processo burocrático, não tem fluxo alternativo|
|Fluxo de Exceção|**Fluxo de Exceção 1 - Usuário já é MEI** <br> > Aplicativo indica que a pessoa em questão já é MEI|
|Pós Condições|Usuário volta para a página de Login|
|Rastreabilidade|BS01|



### **UC03 - Acesso a Suporte**
<center>
<img src='./../../assets/images/Casos de Uso/Diagrama de caso de uso - UC 03.png'pngwidth="1000">Figura 4 - Diagrama Do UC 03</img>
</center>

|**UC03**|**Acesso a Suporte**|
| :----------: |:-----------|
|Versão|Atual: 1.0 (10/12)|
|Autores|Pedro Lucas e Thiago|
|Descrição|Fazer uma pergunta no chat|
|Atores|> Usuário <br> > MEI|
|Pré Condições|> Estar Logado|
|Fluxo Principal|> Usuário acessa o MEI <br> > Usuário digita o CNPJ <br> > Usuário digita sua senha <br> > Usuário clica em "Acessar" <br> > Usuário clica no balão de texto no canto inferior esquerdo <br> > Usuário pergunta no chat para receber logo em seguida uma resposta do Suporte|
|Fluxo Alternativo|Por ser um processo burocrático, não tem fluxo alternativo|
|Fluxo de Exceção|**Fluxo de Exceção 1 - Vaga consta no FAQ** <br> > Aplicativo indica um guia presente no FAQ|
|Pós Condições|Usuário volta para a página inicial|
|Rastreabilidade|BS07|

### **UC04 - Lembrete**
<center>
<img src='./../../assets/images/Casos de Uso/Diagrama de caso de uso - UC 04.png'pngwidth="1000">Figura 5 - Diagrama Do UC 04</img>
</center>

|**UC04**|**Receber Lembrete de Pagamento**|
| :----------: |:-----------|
|Versão|Atual: 1.0 (10/12)|
|Autores|Pedro Lucas e Thiago|
|Descrição|Receber uma notificação para lembrar do pagamento do DAS|
|Atores|> Usuário <br> > MEI|
|Pré Condições|> Estar Logado|
|Fluxo Principal|> Usuário acessa o MEI <br> > Usuário digita o CNPJ <br> > Usuário digita sua senha <br> > Usuário clica em "Acessar" <br> > Ligar "Lembrete"|
|Fluxo Alternativo|> Usuário acessa o MEI <br> > Usuário digita o CNPJ <br> > Usuário digita sua senha <br> > Usuário recebe o lembrete como primeira mensagem antes de utilizar o MEI|
|Fluxo de Exceção|**Fluxo de Exceção 1 - Lembrete Desligado** <br> > Usuário deixa desligado os lembretes <br> **Fluxo de Exceção 2 - Silencioso** <br> > Usuário deixa  o celular no silencioso|
|Pós Condições|Usuário segue para a página principal|
|Rastreabilidade|BS03|

### **UC05 - Plataforma Unica**
<center>
<img src='./../../assets/images/Casos de Uso/Diagrama de caso de uso - UC 05.png'pngwidth="1000">Figura 6 - Diagrama Do UC 05</img>
</center>

|**UC05**|**Utilizar apenas o MEI**|
| :----------: |:-----------|
|Versão|Atual: 1.0 (10/12)|
|Autores|Pedro Lucas e Thiago|
|Descrição|Autorizar acesso a dados externos|
|Atores|> Usuário <br> > MEI|
|Pré Condições|> Estar Logado|
|Fluxo Principal|> Usuário acessa o MEI <br> > Usuário digita o CNPJ <br> > Usuário digita sua senha <br> > Usuário clica em "Acessar" <br> > Usuário autoriza a utilização de outros sites do governo|
|Fluxo Alternativo|Não será utilizado|
|Fluxo de Exceção|**Fluxo de Exceção 1 - Recusar** <br> > Usuário recusa a utilização|
|Pós Condições|Usuário pode realizar outras operações sem necessitar de sites externos do Governo|
|Rastreabilidade|BS04 e BS05|

## Referências Bibliográficas
- Duolingo Github Requisitos de Software, disponivel em: https://github.com/Requisitos-de-Software/2019.2-Duolingo Acesso em: 10 de dezembro de 2022

