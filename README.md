/*
EXERCICIO 1

let idade = Number(prompt("digite sua idade"));

if (idade >= 18) {
  alert("Maior de idade");
} else {
  alert("Menor de iade")
}
 */


 
/*
EXERCICIO 2
let numero = Number(prompt("digite um numero"));

if (numero %2 == 0){
    alert("Seu numero Par");
} else {
    alert("Numero impar")
}
*/





/*
EXERCICIO 3
let numero1 = parseFloat(prompt("Digite o primeiro número:"));
let operador = prompt("Digite a operação (+, -, x, %):");
let numero2 = parseFloat(prompt("Digite o segundo número:"));

let resultado;

if (operador === "+") {
    resultado = numero1 + numero2;
} else if (operador === "-") {
    resultado = numero1 - numero2;
} else if (operador === "x") {
    resultado = numero1 * numero2;
} else if (operador === "/") {
    resultado = numero1 / numero2;
} else {
    console.log("Operação inválida!");
}

if (resultado !== undefined) {
    console.log("Resultado: " + resultado);
}
    */




    
/*
EXERCICIO 4

let numero = Number(prompt("Digite um número para ver a tabuada:"));

for (let i = 1; i <= 10; i++) {
    console.log(numero + " x " + i + " = " + (numero * i));
}
    */





    
/*
EXERCICIO 5

let nota1 = Number(prompt("Digite a primeira nota:"));
let nota2 = Number(prompt("Digite a segunda nota:"));
let nota3 = Number(prompt("Digite a terceira nota:"));

let media = (nota1 + nota2 + nota3) / 3;

alert("Média: " + media.toFixed(2));

if (media >= 7) {
    alert("Aprovado ");
} else if (media >= 5) {
    alert("Recuperação ");
} else {
    alert("Reprovado ");
}
*/






/*
EXERCICIO 6

let n = Number(prompt("Digite um número inteiro positivo:"));

for (let i = 1; i <= n; i++) {
    console.log(i);
}
 */




 

/*
EXERCICIO 7

let soma = 0;
let numero;

do {
    numero = Number(prompt("Digite um número (0 para parar):"));
    soma += numero;
} while (numero !== 0);

alert("Soma total: " + soma);
*/






/*
EXERCICIO 8
let positivos = 0;

for (let i = 1; i <= 5; i++) {
    let numero = Number(prompt("Digite o " + i + "º número:"));
    
    if (numero > 0) {
        positivos++;
    }
}

alert("Quantidade de números positivos: " + positivos);
*/






/*
EXERCICIO 9
let usuarioCorreto = "admin";
let senhaCorreta = "1234";
let tentativas = 0;
let acesso = false;

while (tentativas < 3) {
    let usuario = prompt("Digite o usuário:");
    let senha = prompt("Digite a senha:");

    if (usuario === usuarioCorreto && senha === senhaCorreta) {
        alert("Login realizado com sucesso ");
        acesso = true;
        break;
    } else {
        tentativas++;
        alert("Usuário ou senha incorretos");
    }
}

if (!acesso) {
    alert("Acesso bloqueado");
}
    */





/*
EXERCICIO 10
let numero = Number(prompt("Digite um número inteiro positivo:"));
let fatorial = 1;

for (let i = 1; i <= numero; i++) {
    fatorial *= i;
}

alert("Fatorial de " + numero + " é: " + fatorial);
*/
