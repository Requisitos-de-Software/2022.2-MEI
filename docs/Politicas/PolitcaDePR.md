# Politica de Pull Request

## Histórico de Versão
|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:-----------:| :------: | :-----------: | :---------: |:---------: |
|11/11/2022|11/11/2022|1.0|Criação do Documento de Políticas| [Joao Lucas](https://github.com/HacKairos)| [Ana](https://github.com/AnHoff) |

## Criação de _Pull Request_

Considere uma situação hipotética onde estamos querendo criar um PR de uma _branch_ chamada **Sprints** para a _master_.

## Nota

- A criação do PR deve ser feita logo após o início do trabalho em uma issue. Para isso trabalhamos com a flag de _status_ **WIP**.


 Para a criação de um _pull request_ direcionado a branch _master_, deve-se seguir os seguintes passos:

### Passo a passo

#### Adicione a flag de _status_

* Titule o PR com a tag **WIP** (ou seja _work in progress_) 

#### Adicione uma descrição

* Utilize o _template_ de _issue_ destinada ao _pull request_.
* Lembrando que o _pull request_ tem a _branch_ base a **main** e a _compare_ a branch que se deseja juntar.
* **Lembrando**: assim que for realmente finalizado as alterações referentes ao _pull request_, deve-se retirar a tag **WIP**.

Exemplo de como abrir um PR na figura 1 :

<img src="https://user-images.githubusercontent.com/57872849/181664869-28a47783-943e-45ff-88e2-884cec043d67.png" width="800">Figura 1 - Abrir um PR</img>
 
#### Adicione os _reviewers_ 

* Assinale os _reviewers_, ou seja, aqueles responsáveis pela análise do _pull request_. Por exemplo, caso sua _feature_ esteja relacionada a arquitetura do projeto, assinale o **EPS** que desempenha esse papel.

Exemplo de como adcionar revisores na figura 2 :

<img src="https://user-images.githubusercontent.com/57872849/181664313-2dd4bbaa-c42b-41f0-87d9-6ec3d8312724.png" width="400"><br>Figura 2 - Adicionar um Revisor</img>


#### Adicione os _assignees_

* Assinale os colaboradores do _pull request_

Exemplo de como adcionar colaboradores na figura 3 :

<img src="https://user-images.githubusercontent.com/57872849/181663332-1f52c00f-183e-457d-9ba2-31bb6525b382.png" width="500"><br>Figura 3 - Adicionar Colaboradores

#### Adicione as devidas _labels_

* Marque as _labels_ relacionadas ao _pull request_. Geralmente será as mesmas assinaladas na issue referente.

Exemplo de como selecionar marcadores na figura 4 :

<img src="https://user-images.githubusercontent.com/57872849/181663149-7622a2f1-0cb0-4e47-b6e0-6c056cf2eddc.png" width="500"><br>Figura 4 - Adicionar Marcadores

#### Adicione a devida _milestone_

* Marque a _Milestone_, ou seja, a _sprint_ ou _release_ atual.

Exemplo de como selecionar a milestone na figura 5 :

<img src="https://user-images.githubusercontent.com/57872849/181663407-91a910ae-6c51-493d-ac2a-61fc37f798a0.png" width="500"><br>Figura 5 - Adicionar Milestone

#### Explicite a _issue_ relacionada ao PR

* Conecte a _issue_ trabalhada neste _pull request_ por meio de _closing keywords_.


| Issue a ser _linkada_ | Sintaxe | Examplo |
|:----------:|:------:|:--------------------:|
|Issue dentro deste repositório|KEYWORD #ISSUE-NUMBER|**Closes #10**|

## Conflitos

* Se um pull request causar algum tipo de conflito, deve ser resolvido primeiro pela equipe que desenvolveu o que está causando conflito, prezando pela integridade e organização do histórico de commits, e então deve ser refeito o pedido para avaliação do merge.

## Política de Aprovação do Código

* Para a aprovação do código, este deve ser aprovado por ao menos um dos integrantes do grupo
