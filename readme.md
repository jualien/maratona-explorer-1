# HTML
- hypertext markup language

- Hiper texto?
- Marcação
  - tags
  - atributos
  - linguagem
  - maneira de escrever

# CSS
## declaração
- seletor
- propriedades e valor

## conceitos
- cascata
- especificidade
- box model

# JS
// 1. Variáveis
// let estaChovendo = true
// const meuNome = "mayk"
let - variável
const - nao muda o que eu coloquei de início

// 2. Tipos de dados
string - conjunto de caracteres
' ou "

// number
números integer (12) ou float (3.2)

// boolean
true ou false
const maiorDeDezoito = false

// undefined - indefinido

// 3. Operadores
// atribuição (ex: =)
// atribui valor
let n1 = 12
let n2 = 3

// aritméticos (ex: * / + -)
// calculos matemáticos simples
console.log(12 * 4)

// concatenação de string (+)

// comparação (ex: > < ==)
transforma a expressão em true ou false 
const maiorQue = 1 > 2 // false
const igualA = 1 == 1 // true

// 4. Condicional (if/else)
const idade = 17
const maiorDeDezoito = idade >= 18

if(maiorDeDezoito) {
  alert("pode tirar carteira de motorista")
} else {
  alert("Não pode tirar")
}

// 5. Estrutura de dados
Array - vetor - lista
array --------------- 0     1    2  3
const temperatura = {23.3, 32.2, 1, 5}


// Object
const pessoa = {
  nome: "mayk",
  idade: 38,
  filhos: [K, E, J, L, G]
}

// 6. Function
1. criação
function nomeDaFuncao() {
  console.log('código dentro da função')
}
2. execução nomeDaFunção()

// parâmetros
funciotion, soma (a, b) {
  console.log (a + b)
}
soma (34, 45)
soma (90, 54)

// Retorno
function soma (a, b) {
  return a + b
}

// 7. Extensões da linguagem (ex: math, date...)
math, random ()
math, floor (1.2)
math.ceil (1.2)
math.propriedades

// 8. DOM - documento object model 
window
window.alert ("alerta)
document
document.write ("texto")
manipular elementos
document.documetElement.style.background = "white"