# Exercício 11 — Maior de idade

**1. Entradas:** idade da pessoa.

**2. Processamento:** verificar se idade ≥ 18.

**3. Saídas:** "Maior de idade" ou "Menor de idade".

**4. Pseudocódigo**

```
algoritmo "MaiorDeIdade"
var
   idade: inteiro
inicio
   escreva("Digite a idade: ")
   leia(idade)
   se idade >= 18 entao
      escreval("Maior de idade")
   senao
      escreval("Menor de idade")
   fimse
fimalgoritmo
```

**5. Fluxograma**

```mermaid
flowchart TD
    A(["Início"]) --> B[/"Ler idade"/]
    B --> C{"idade ≥ 18?"}
    C -->|V| D[/"Mostrar 'Maior de idade'"/]
    C -->|F| E[/"Mostrar 'Menor de idade'"/]
    D --> F(["Fim"])
    E --> F
```
