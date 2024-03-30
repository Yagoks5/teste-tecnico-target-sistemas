# teste-tecnico-target-sistemas
Desafio Target Sistem

// EXERCICIO 1

let indice = 13;
soma = 0;
k = 0;

while (k < 13) {
  k = k + 1;
  soma = soma + k;
}
console.log(soma);

O valor da soma será 91

// EXERCICIO 2 - SEQUÊNCIA DE FIBONACCI

function fibonacciLoop(n) {
  let fibArray = [0, 1];

  for (let i = 2; i <= n; i++) {
    fibArray.push(fibArray[i - 1] + fibArray[i - 2]);
  }

  return fibArray;
}

// Exemplo de uso:
console.log(fibonacciLoop(10)); // Imprime os primeiros 10 números da sequência de Fibonacci

// EXERCICIO 3 - DESCUBRA A LÓGICA
a) 1, 3, 5, 7, 9

b) 2, 4, 8, 16, 32, 64, 128

c) 0, 1, 4, 9, 16, 25, 36, 49

d) 4, 16, 36, 64, 100

e) 1, 1, 2, 3, 5, 8, 13

f) 2,10, 12, 16, 17, 18, 19, 27


// EXERCICIO 4
Como são três salas com cada uma com uma lampada apenas:
Primeira ida:
- Eu ligo o interruptor 1 e deixo por um bom tempo, depois desligo e ligo o interruptor 2, após isso, vou a uma das salas com três hipóteses:
- Se a lampada estiver acessa, é a lampada do interruptor 2, se estiver desligada e quente, é do interruptor 1 e se estiver desligada e 'gelada' é do interruptor 3
Segunda ida:
- Como eu ja sei um interruptor, basta ligar o outro e ir para outra sala diferente, caso a lampada estiver acesa é do interrputor que eu liguei, caso não seja do outro interruptor.

// EXERCICIO 5
function inverterPalavra(palavra) {
  let novaPalavra = "";
  for (let i = palavra.length - 1; i >= 0; i--) {
    novaPalavra += palavra[i];
  }
  return novaPalavra;
}
