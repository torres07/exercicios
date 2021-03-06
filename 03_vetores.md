## EXERCÍCIOS DE VETORES

####Lembre-se, tenha o link de resposta como sua ultima opção!
####
```
Do or do not. There is no try.
- Yoda.
```

## FÁCEIS

**menor_vetor:** Leia um vetor de inteiros e imprima o menor valor.  
[Respostas](03_vetores/menor_vetor.md)
<details><summary>_Clique para a Dica_</summary>
```
	percorra o vetor usando uma variavel auxiliar para guardar o menor valor encontrado
	sempre que achar alguem menor atualize o valor da variavel auxiliar no final o menor
	valor estara armazenado na variavel auxilliar.
```
</details>

	>> 3 7 2 4 5
	<< 2


**fibonacci:** Crie uma função que receba a quantidade n de termos e imprima os n termos da sequência de fibonacci.
[Respostas](03_vetores/fibonacci.md)
<details><summary>_Clique para a Dica_</summary>
```
inicie as duas primeiras posicoes com 0, 1 respectivamente
depois é so fazer um loop somando a posicao vet[n-1] + vet[n-2] ate o enesimo termo
```
</details>

	>> 6
	<< 0 1 1 2 3 5

Curioso sobre a sequencia de fibbonaci? veja mais sobre https://en.wikipedia.org/wiki/Fibonacci_number

**busca_linear:** A Busca Linear é um processo de busca de um elemento x em um vetor L que testa sequencialmente cada elemento de L e encerra quando x é encontrado (busca com sucesso) ou quando o final de L é extrapolado(busca sem sucesso). Dados como 
entrada um vetor de números L e um número x, determinar utilizando busca linear se x está ou não presente em L.
[Respostas](03_vetores/busca_linear.md)
<details><summary>_Clique para ver a Dica_</summary>
```
	leia o numero
	de i <- 0 ate n-1
		se v[i] = numero
		retorne verdade
	retorne falso
```
</details>

	>> 3
	>> 2 4 3 2 5
	<< verdade

	>> 3
	>> 1 2 5 6 8
	>> falso 

**maior_menor:** Faça um programa que leia 15 números inteiros e os armazene em um vetor A. Determine então qual o maior e o menor destes números e quantas vezes este maior e este menor ocorrem no vetor. No final, apresente esses valores.
[Respostas](03_vetores/maior_menor.md)
<details><summary>_Clique para ver a Dica_</summary>
```
	uma das formas de fazer eh a seguinte
	faca menor = A[0], maior = A[0]
	percorra o vetor sempre que encontrar um valor menor que a variavel menor atualize a variavel
	da mesma forma para o maior, no final voce tera o maior e menor
	entao basta percorrer o vetor novamente contando o numero de vezes que cada uma delas aparece
```
</details>

	>> 1 3 4 5 5 2
	<< maior: 5
	<< apareceu: 2x
	<< menor 1: 
	<< apareceu: 1x

**vetor_reverso:** Faça um programa que receba um vetor A de 10 elementos e construa um vetor B que possui os mesmos números de A, sendo que na ordem invertida.
[Respostas](03_vetores/vetor_reverso.md)
<details><summary>_Clique para ver a Dica_</summary>
```
	depois de preencher o vetor A faca
	de i <- 0 até n-1 faca
		B[i] = A[n-1-i]
```
</details>

	>> 3 4 2 1 5
	<< 5 1 2 4 3

**vetor_primos:** Escreva um programa que determine os 30 primeiros números primos e armazene-os em um vetor chamado PRIMOS. No final, apresente o conteúdo do vetor.
[Respostas](03_vetores/vetor_primos.md)
<details><summary>_Clique para ver a Dica_</summary>
```
	use uma funcao que determina se um numero eh primo
	se tiver duvidas com isto olhe esta resolucao que fizemos na secao de lacos [Resolucao eh_primo](02_lacos/eh_primo.md)
	depois disto basta fazer um laco indo de 2 ate 100 (ate la voce ja tera encontrado 30 primos)
	e sempre que encontra um numero primo atraves da funcao eh_primo adicione ao vetor, quando tiver 30 numeros pare o laco
```
</details>

	<< 2 3 5 7 11 13 17 19 23 29 31 37 41 43 47 53 59 61 67 71 73 79 83 89 97 101 103 107 109 113 

**uniao_vetores:** Faça um programa que leia dois vetores A e B de 6 elementos. A só deverá aceitar valores pares enquanto que B só receberá valores ímpares. O programa deve alertar caso valores errados sejam passados e pedir pro usuário informar um valor correto. Apresentar um vetor C formado pela união dos elementos de A e B (C deverá ter 12 elementos).
[Respostas](03_vetores/uniao_vetores.md)

**iguaisa30:** Faça um programa que preencha um vetor com quinze elementos inteiros e verifique a existência de elementos iguais a 30, mostrando as posições em que apareceram.
[Respostas](03_vetores/iguaisa30.md)

**busca_rep:** Faça um programa que receba um vetor de 10 elementos positivos e que o usuário possa pesquisar se um determinado elemento existe no vetor. Caso exista o programa exibirá o índice no qual o valor está posicionado; caso contrário, mostrar que o elemento não existe no vetor. O programa deve possibilitar que o usuário faça quantas pesquisas ele quiser, só encerrando quando o usuário informar um número negativo.
[Respostas](03_vetores/busca_rep.md)

**vetor_semrep:** Faça um programa que receba 20 números do usuário e armazene-os em um vetor. O programa não pode aceitar valores repetidos, pedindo para o usuário informar outro número até que este apresente um número não repetido.
[Respostas](03_vetores/vetor_semrep.md)

## MÉDIAS

11. Faça um programa que preencha um vetor de dez números inteiros e um segundo vetor com cinco números inteiros, calcule e mostre dois vetores resultantes. O primeiro vetor resultante será composto pela soma dos números pares do primeiro vetor somado a cada elemento do segundo vetor. O segundo vetor resultante será composto pela soma de números impares do primeiro vetor somado com cada elemento do segundo vetor.

12. Dado um vetor de números inteiros, determinar,
(a) A soma dos elementos.
(b) A média dos elementos.
(c) A soma dos elementos pares subtraída da soma dos elementos ímpares.
(d) Os valores máximo e mínimo entre seus elementos.
(e) Os dois elementos de maior valor presentes.

14. Rotacionar à direita um vetor significa colocar seus elementos uma posição adiante com exceção do último elemento que é transferido para a primeira posição. Rotacionar à esquerda um vetor significa colocar seus elementos uma posição para trás com exceção do primeiro elemento que é transferido para a última posição. Construir separadamente as rotações à direita e à esquerda para um vetor de inteiros dado como entrada.

15. Faça um programa que preencha dois vetores, X e Y com dez números inteiros cada. Calcule e mostre os seguintes vetores resultantes:
a) A união de X com Y(todos os elementos de X e de Y sem repetições);
b) A diferença entre X e Y (todos os elementos de X que não existam em Y, sem repetições);
c) A soma entre X e Y (soma de cada elemento de X com o elemento de mesma posição de em Y);
d) O produto entre X e Y (Multiplicação de cada elemento de X com o elemento de mesma posição em Y);
e) Interseção entre X e Y (Apenas os elementos que aparecem nos dois vetores, sem repetições);

17. Escreva um programa para receber 10 números reais e armazená-los em um vetor. Depois disso,  mostre  o  somatório  dos  números,  através  do  uso  da  função  somatório,  que  não recebe  parâmetro  nenhum,  acessa  o  vetor  definido  globalmente  e  retorna  o  somatório dos elementos do vetor.

18. Faça uma  função  que  receba  como  parâmetro  um  vetor  A  de  dez  elementos  inteiros  já populado  como  parâmetro.  Ao final  dessa  função,  deverá  ter  sido  gerado  um  vetor  B contendo o fatorial de cada elementos de A. O vetor B deverá ser mostrado no main.

20. Faça um programa que receba dois vetores de inteiros ordenados e imprima os valores dos vetores de maneira que eles continuem ordenados.

22. Implemente o selection sort.

23. A mediana de um conjunto finito de números é um elemento deste conjunto cuja quantidade de elementos menores ou iguais a ele é no máximo uma unidade a menos que os elementos maiores que ele. Dado um conjunto de entrada Q em forma de vetor, determinar sua mediana.

24. Dado um vetor de números naturais, reorganizar seus elementos de forma que dois números pares não fiquem vizinhos. Informar quando não for possível.

25. O embaralhamento de vetor, ou shuffle, consiste em redispor seus elementos em ordem aleatória. Dado um vetor de inteiros de entrada, embaralhar seus elementos.

27. Uma representação dígito-vetorial de um número natural n é um vetor contendo os dígitos de n justificados à direita e complementados com zeros à esquerda quando necessário. Por exemplo, a representação dígito vetorial de 15867 pode ser o vetor [1, 5, 8, 6, 7]. Dado um número natural como entrada construir sua representação dígito-vetorial.


# DIFÍCEIS

30. Um número é dito pandigital se seus dígitos são todos distintos entre si. Construir função que determine se um número passado como argumento é ou não pandigital.

35. Implemente a busca binária.
