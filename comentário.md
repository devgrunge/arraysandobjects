# Comentários

# OBJECTS

Possui propriedades e funcionalidades e/ou métodos
ex : {Propriedade : "valor"}

# ARRAY

Uma lista , agrupamento de dados
ex: [mayk, 36]

# VARIAVEIS

Podem ser chamados de identificadores ou identifiers
VAR / LET / CONST
O js é uma lingua fracamente tipada e dinâmica

- Podemos mudar o conteúdo da váriavel

# SCOPE

- Determina a visibilidade de uma variável no javascript

# BLOCK STATEMENT

{
// O código iria aqui

}

var - é global e também local

## (HOISTING)

const e let - São locais e só funcionam no escopo onde foram criadas

# AGRUPAMENTO DE DECLARAÇÕES

let age , isHuman

age = 22
isHuman = true

console.log(typeof isHuman)

# typeof

verifica o tipo de dado inserido
ex:
var numero = 18
typeof numero - number

interpolando valores

# Template strig

interpolando valores com template strings ou template literals
ex:
var years = 22
var name = alex
console.log(`Meu nome é ${name} e tenho ${years} anos`)

# OBJECT

ex:
const person {
name : john
age: 30
weigth: 88.6
isAdmin: true

} ;

para usar o template string em um atributo de um objeto , é necessário

para acessar os dados dentro de um objeto como no exemplo acima:
console.log(person.name)

# ARRAYS

const animals [
'lion',
'monkey',
'cat',
]

para acessar um dado dentro do array , é necessário indicar sua posição como no exemplo :
console.log(animals[0])

# Exercicios

# 1

let student = {
name: 'julia',
age: 22,
stars: 5,
isSubscribed: true,
weight: 52
}

console.log(
`${student.name} com ${student.age} anos pesa ${student.weight} Kg `
)

# 2

let julia = {
name: 'julia de assis',
age: 22,
isSubscribed: true,
weight: 52
}

const alex = {
name: 'alexander marcondes',
age: 22,
isSubscribed: false,
weight: 58
}

let students = [julia, alex]

console.log(students[1])
