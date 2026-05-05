# exercicios_js
Exercícios JS


✏️ Exercícios (Estruturas e Funções)
Nível 1 — Iniciante
Exercício 1: Peça ao usuário um número com prompt. Use if/else para exibir se o número é positivo, negativo ou zero.

Resolução: <! -- let valor = Number(prompt('Digite um número: '))

if (valor < 0){
    console.log (`${valor} é um número negativo.`)
} else if (valor > 0) { 
    console.log (`${valor} é um número positivo.`)
} else{
    console.log (`Zero.`)
} -->

Exercício 2: Peça a temperatura em graus Celsius. Use if/else if para classificar:

Abaixo de 15°C → "Frio"
Entre 15°C e 25°C → "Agradável"
Acima de 25°C → "Quente"

Resolução: <! -- let temp = Number(prompt('Informe a temperatura: '))

if (temp <= 15) {
    console.log('Frio')
} else if (temp <= 25) {
    console.log ('Agradável')
} else {
    console.log ('Quente')
} -->

✏️ Nível 2 — Intermediário

Exercício 3: Crie uma função calcularDesconto(preco, tipocliente) que use switch para aplicar descontos:

"vip" → 30% de desconto
"comum" → 10% de desconto
"novo" → 15% de desconto
Qualquer outro → sem desconto
Exiba o preço final com console.log.

Exercício 4: Reescreva o exercício 1 usando operador ternário no lugar do if/else.

Nível 3 — Avançado
Exercício 5: Crie uma função calcularFrete(distancia, tipoProduto) que determine o valor do frete com base em duas condições combinadas:

Se distancia <= 50:
Produto "fragil" → R$ 25,00
Outros → R$ 10,00
Se distancia > 50 && distancia <= 200:
Produto "fragil" → R$ 60,00
Outros → R$ 30,00
Se distancia > 200:
Produto "fragil" → R$ 120,00
Outros → R$ 70,00
Teste a função com ao menos 3 combinações diferentes.


✏️ Exercícios
Nível 1 — Iniciante
Exercício 1: Crie uma função saudacao(nome) que receba um nome e exiba "Olá, [nome]! Bem-vindo ao curso de JavaScript." no console.

Exercício 2: Crie uma função calcularPerimetro(lado) que receba o lado de um quadrado e retorne seu perímetro (lado * 4). Exiba o resultado com console.log.

Exercício 3: Reescreva a função do exercício 2 como arrow function.

Nível 2 — Intermediário
Exercício 4: Crie uma função converterTemperatura(celsius) que converta graus Celsius para Fahrenheit.
Fórmula: F = (C × 9/5) + 32

Exercício 5: Crie uma função maiorNumero(a, b, c) que receba três números e retorne o maior deles. Use if/else — sem usar Math.max().

Exercício 6: Crie uma função calcularTroco(valorProduto, valorPago) que:

Retorne o troco se valorPago >= valorProduto
Retorne "Valor insuficiente" caso contrário
Nível 3 — Avançado
Exercício 7: Crie uma função validarSenha(senha) que retorne:

"Senha forte" se tiver 8 ou mais caracteres
"Senha média" se tiver entre 5 e 7 caracteres
"Senha fraca" se tiver menos de 5 caracteres
Use senha.length para verificar o tamanho.

Exercício 8: Crie três funções separadas e uma função principal que as combine:

dobrar(n) → retorna o dobro de n
somarCinco(n) → retorna n + 5
ehPositivo(n) → retorna true ou false
processar(n) → dobra o número, soma cinco e exibe se o resultado é positivo

