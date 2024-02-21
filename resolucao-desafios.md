# Desafio - Alura ONE
## Desafios - Parte 1

- Mostre um alerta com a mensagem "Boas vindas ao nosso site!".
 ```
  alert('Bem-vindo ao nosso site!');
```
- Declare uma variável chamada nome e atribua a ela o valor "Lua".
```
    let nome = "Lua";
```
- Crie uma variável chamada idade e atribua a ela o valor 25.
```
    let idade = 25;
```
- Defina uma variável numeroDeVendas e atribua a ela o valor 50.
```
    let numeroDeVendas = 50;
```
- Defina uma variável saldoDisponivel e atribua a ela o valor 1000.
```
    let saldoDisponivel = 1000;
```
- Exiba um alerta com o texto "Erro! Preencha todos os campos"
```
    alert('Erro! Preencha todos os campos');
```
- Declare uma variável chamada mensagemDeErro e atribua a ela o valor "Erro! Preencha todos os campos" Agora exiba um alerta com o valor da variável mensagemDeErro.
```
    let mensagemDeErro = 'Erro! Preencha todos os campos';
    alert(mensagemDeErro);
```
- Use um prompt para perguntar o nome do usuário e armazená-lo na variável nome.
```
    let nomeUsuario = prompt('Informe seu nome: ');
```
- Peça ao usuário para digitar sua idade usando um prompt e armazene-a na variável idade.
```
    let idadeUsuario = prompt('Informe sua idade: ');
```
- Agora, caso a idade seja maior ou igual que 18, exiba um alerta com a mensagem "Pode tirar a habilitação!".
```
    if (idadeUsuario >= 18){
        alert('Pode tirar a habilitação!')
    }
```

## Desafios - Parte 2

- Pergunte ao usuário qual é o dia da semana. Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". Caso contrário, mostre "Boa semana!".
```
    let diaDaSemana = prompt('Qual dia da semana é hoje?');
    let mensagemFDS = 'Bom fim de semana';
    let mensagemMDS = 'Boa semana!';

    if (diaDaSemana == 'Domingo' || diaDaSemana == 'Sábado') {
        alert(mensagemFDS);
    } else {
        alert(mensagemMDS);
    }
```
- Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.
```
    let numero = prompt("Informe um número: ")

    if (numero > 0) {
        alert('O número é positivo');
    } else if (numero < 0) {
        alert('O número é negativo');
    } else {
        alert('O número é o 0')
    }
```
- Crie um sistema de pontuação para um jogo. Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!". Caso contrário, mostre "Tente novamente para ganhar.".
```
    let pontos = 85;

    if (pontos >= 100) {
        console.log('Parabéns, você venceu!')
    } else {
        console.log('Tente novamente para ganhar.')
    }
```
- Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma template string para incluir o valor do saldo.
```
    let saldoConta = 1000;
    alert(`Seu saldo é de: ${saldoConta} reais`);
```
- Peça ao usuário para inserir seu nome usando prompt. Em seguida, mostre um alerta de boas-vindas usando esse nome. 
```
    let nomeUser = prompt('Informe seu nome: ');
    alert(`Seja bem-vindo ${nomeUser}!`);
```

## Desafios - Parte 3

- Crie um contador que comece em 1 e vá até 10 usando um loop while. Mostre cada número.
```
    let contador = 1;
    while (contador <= 10) {
    console.log(contador);
    contador++; 
    }
```
- Crie um contador que começa em 10 e vá até 0 usando um loop while. Mostre cada número.
```
    let contador = 10;
    while (contador <= 0) {
    console.log(contador);
    contador--; 
    }
```
- Crie um programa de contagem regressiva. Peça um número e conte deste número até 0, usando um loop while no console do navegador.
```
    let numeroMaximo = prompt("Digite um número para a contagem regressiva:");

    while (numeroMaximo >= 0) {
        console.log(numeroMaximo);
        numeroMaximo--;
    }
```
- Crie um programa de contagem progressiva. Peça um número e conte de 0 até esse número, usando um loop while no console do navegador.*/
```
    let numeroMaximo = prompt("Digite um número para a contagem progressiva:");

    let contador = 0;
    while (contador <= numeroMaximo) {
        console.log(contador);
        contador++;
    }
```
