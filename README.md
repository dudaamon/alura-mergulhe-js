## Desafios

1. Crie um programa que utilize o console.log para exibir uma mensagem de boas-vindas. R: 
```js
let mensagem = "Boas vindas!";

console.log(mensagem);
```

2. Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o console.log para exibir a mensagem "Olá, [seu nome]!" no console do navegador. R: 
```js
let nome = "Eduarda";

console.log(`Olá, ${nome}!`);
```

3. Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o alert para exibir a mensagem "Olá, [seu nome]!" . R: 
```js
let nome = "Eduarda";

alert(`Olá, ${nome}!`);
```

4. Utilize o prompt e faça a seguinte pergunta: Qual a linguagem de programação que você mais gosta?. Em seguida, armazene a resposta em uma variável e mostre no console do navegador. R:
```js
let respostaDaPergunta = prompt("Qual a linguagem de programação que você mais gosta?");

console.log(respostaDaPergunta);
```

5. Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a soma desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A soma de [valor1] e [valor2] é igual a [resultado]." no console. R:
```js
let valor1 = 18;
let valor2 = 19;
let resultado = valor1 + valor2;

console.log(`A soma de ${valor1} e ${valor2} é igual a ${resultado}.`)
```

6. Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a subtração desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A diferença entre [valor1] e [valor2] é igual a [resultado]." no console. R:
```js
let valor1 = 70;
let valor2 = 30;
let resultado = valor1 - valor2;

console.log(`A diferença de ${valor1} e ${valor2} é igual a ${resultado}.`)

```

7. Peça ao usuário para inserir sua idade com prompt. Com base na idade inserida, utilize um if para verificar se a pessoa é maior ou menor de idade, exibindo uma mensagem apropriada no console. R:
```js
let idade = prompt("Informe sua idade:");

if (idade >= 18) {
    console.log("É maior de idade.");
} else {
    console.log("É menor de idade.");
}
```

8. Pergunte ao usuário qual é o dia da semana. Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". Caso contrário, mostre "Boa semana!". R:
```js
let diaDaSemana = prompt("Qual é o dia da semana?");

if (diaDaSemana == "Sábado" || diaDaSemana == "Domingo") {
    alert("Bom fim de semana!");
} else {
    alert("Boa semana!");
}
```

9. Crie um sistema de pontuação para um jogo. Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!". Caso contrário, mostre "Tente novamente para ganhar.". R:
```js
let pontuacao = prompt("Digite sua pontuação no jogo:");

if (pontuacao >= 100) {
    alert("Parabéns, você venceu!");
} else {
    alert("Tente novamente para ganhar.");
}
```

10. Crie um programa de contagem progressiva. Peça um número e conte de 0 até esse número, usando um loop while no console do navegador.R:
```js
 let numero = prompt("Insira um número para a contagem regressiva:");
let contagemRegressiva = 0;

while (contagemRegressiva <= numero) {
    console.log(contagemRegressiva);
    contagemRegressiva++;
}
```

11. Crie uma variável "numero" e peça um valor com prompt verifique se é positivo, negativo ou zero. Use if-else para imprimir a respectiva mensagem. R:
```js
let numero = prompt("Digite um numero:");

if (numero > 0){
  console.log("Você digitou um número positivo.");
} else if (numero < 0) {
    console.log("Você digitou um número negativo.");
} else {
    console.log("Você digitou zero.")
}
```

12. Use um loop while para imprimir os números de 1 a 10 no console. R:
```js
let contador = 1;

while (contador <= 10) {
    console.log(contador);
    contador++;
}
```

13. Crie uma variável "nota" e atribua um valor numérico a ela. Use if-else para determinar se a nota é maior ou igual a 7 e exiba "Aprovado" ou "Reprovado" no console. R: 
```js
let nota = 8

if (nota >= 7) {
    console.log("Aprovado");
} else {
    console.log("Reprovado");
}
```

14. Use o Math.random para gerar qualquer número aleatório e exiba esse número no console. R:
```js
let numeroAleatorio = Math.random();

console.log(numeroAleatorio);
```

15. Use o Math.random para gerar um número inteiro entre 1 e 10 e exiba esse número no console. R:
```js
let numero1e10 = parseInt(Math.random() * 10) + 1;

console.log(numero1e10);
```

16. Use o Math.random para gerar um número inteiro entre 1 e 1000 e exiba esse número no console. R:
```js
let numero1e1000 = parseInt(Math.random() * 1000) + 1;

console.log(numero1e1000);
```
