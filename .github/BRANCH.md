# Politica de Branch

## Criação de _Branches_

![image](https://user-images.githubusercontent.com/57872849/181653398-26fa46ee-f50c-4b36-a94c-5c7b89bfa603.png)

* <p align = "justify">O repositório do projeto terá uma branch principal e estável, a <i>main</i>.

* Os PRs passaram por revisões e ao fim de cada release, ou em casos excepcionais, serão aceitos pelos mesmos.

* Deve-se ser criada uma nova branch para cada nova <i>feature, correção ou falha</i> a partir da branch <i>main</i>. 

## Para a criação de _branches_ siga os passos e exemplos a seguir:


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

### Exemplo prático
* Sem _tag_
```
OurPolicies
```

* Com _tag_
```
Issue01PascalCase
```
