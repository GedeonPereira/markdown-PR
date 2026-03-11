# stile guide do projeto
## Linguagem typescript
### variaveis
```
  sempre adicione tipagens primitivas

```
```
  \\ruim
  nome = "Matheus"

  \\bom
  relação_amorosa: string = "matheus + marcos = "marctheus"


```

---
```

 Evite o uso do else

```
```
\\ruim
if (a == b) {
console.log('iguais')
} else {
  console.log('diferente')
}

\\bom
if (a == b){
console.log('iguais')
}
if (a != b){
  console.log('diferentes')
}
```