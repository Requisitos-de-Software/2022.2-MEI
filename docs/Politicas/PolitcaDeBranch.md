# Politica de Branch

## <a>Histórico de Versão</a>
|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:-----------:| :------: | :-----------: | :---------: |:---------: |
|11/11/2022|11/11/2022|1.0|Criação do Documento de Políticas| [Joao Lucas](https://github.com/HacKairos)|[Pedro Lucas](https://github.com/PedroLSF)

## <a>Criação de _Branches_</a>
Ilustração do funcionamentos das branches na Figura 1 :

<img src='./../../assets/images/BranchPolicy.png'>Figura 1 - Politica de Branch </img>

* <p align = "justify">O repositório do projeto terá uma branch principal e estável, a <i>main</i>.

* Os PRs passaram por revisões e ao fim de cada release, ou em casos excepcionais, serão aceitos pelos mesmos.

* Deve-se ser criada uma nova branch para cada nova <i>feature, correção ou falha</i> a partir da branch <i>main</i>. 

## <a>Para a criação de _branches_ siga os passos e exemplos a seguir:</a>


* O nome da _branch_ (NomeDaBranch) deverá ser uma abstração do nome da história de usuário (_US_), técnica (_TS_) ou correção (_HF_) a qual se refere.

* Caso não tenha _tag_.
```
NomeDaBranch
```

* Caso tenha _tag_, ela será o número da _issue_ a qual a se refere a história de usuário (_US_), técnica (_TS_) ou correção (_HF_) .
```
NumeroDaIssueNomeDaBranch
```

* O NomeDaBranch deverá ser escrito seguindo o padrão PascalCase
```
NumeroDaIssueNomeDaBranch
```

### <a>Exemplo prático</a>
* Sem _tag_
```
OurPolicies
```

* Com _tag_
```
Issue01PascalCase
```
