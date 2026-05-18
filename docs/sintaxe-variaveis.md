
# Sintaxe Básica e Variáveis em Go

Go é uma linguagem com sintaxe simples e objetiva.

## Declaração de variáveis

Existem duas formas principais:

```go
var nome string = "João"
var idade int = 25
```


```go
package main

import "fmt"

func main() {
    var nome string = "João"
    idade := 25

    fmt.Println(nome)
    fmt.Println(idade)
}
```
