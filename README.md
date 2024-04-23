# -TrilhaGitTechForge
Exercício 1: Soma de Variáveis

// Criando variáveis a e b
let a = 5;
let b = 7;

// Calculando a soma de a e b
let soma = a + b;

// Imprimindo o resultado no console
console.log("A soma de", a, "e", b, "é", soma);

Exercício 2: Verificação de Paridade

// Definindo a função verificaNumero
function verificaNumero(numero) {
    if (numero % 2 === 0) {
        console.log(numero, "é par");
    } else {
        console.log(numero, "é ímpar");
    }
}

// Testando a função com diferentes números
verificaNumero(10); // Deve imprimir "É par"
verificaNumero(7);  // Deve imprimir "É ímpar"
verificaNumero(0);  // Deve imprimir "É par"

Exercício 3: Manipulação de Strings
// Declarando a string
let minhaString = "Olá, mundo!";

// Imprimindo o comprimento da string no console
console.log("Comprimento da string:", minhaString.length);

// Convertendo a string para letras maiúsculas
let stringMaiuscula = minhaString.toUpperCase();
console.log("String em maiúsculas:", stringMaiuscula);

// Dividindo a string em palavras e imprimindo cada palavra no console
let palavras = minhaString.split(" ");
console.log("Palavras na string:");
palavras.forEach(palavra => console.log(palavra));
