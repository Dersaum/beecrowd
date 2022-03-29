# Iniciante
## [Desafios 1038 até 1073](https://www.beecrowd.com.br/judge/pt/problems/index/1?page=2)



## [1038 - Lanche](https://www.beecrowd.com.br/judge/pt/problems/view/1038)
Com base na tabela abaixo, escreva um programa que leia o código de um item e a quantidade deste item. A seguir, calcule e mostre o valor da conta a pagar.

<p align="center">
 <img src="https://user-images.githubusercontent.com/86378481/159371927-050b3dbf-0d4b-4eba-bae1-03807a16f69b.png">
</p>

### Entrada
O arquivo de entrada contém dois valores inteiros correspondentes ao código e à quantidade de um item conforme tabela acima.

### Saída
O arquivo de saída deve conter a mensagem "Total: R$ " seguido pelo valor a ser pago, com 2 casas após o ponto decimal.



## [1040 - Média 3](https://www.beecrowd.com.br/judge/pt/problems/view/1040)
Leia quatro números (N1, N2, N3, N4), cada um deles com uma casa decimal, correspondente às quatro notas de um aluno. Calcule a média com pesos 2, 3, 4 e 1, respectivamente, para cada uma destas notas e mostre esta média acompanhada pela mensagem "Media: ". Se esta média for maior ou igual a 7.0, imprima a mensagem "Aluno aprovado.". Se a média calculada for inferior a 5.0, imprima a mensagem "Aluno reprovado.". Se a média calculada for um valor entre 5.0 e 6.9, inclusive estas, o programa deve imprimir a mensagem "Aluno em exame.".

No caso do aluno estar em exame, leia um valor correspondente à nota do exame obtida pelo aluno. Imprima então a mensagem "Nota do exame: " acompanhada pela nota digitada. Recalcule a média (some a pontuação do exame com a média anteriormente calculada e divida por 2). e imprima a mensagem "Aluno aprovado." (caso a média final seja 5.0 ou mais ) ou "Aluno reprovado.", (caso a média tenha ficado 4.9 ou menos). Para estes dois casos (aprovado ou reprovado após ter pego exame) apresente na última linha uma mensagem "Media final: " seguido da média final para esse aluno.

### Entrada
A entrada contém quatro números de ponto flutuante correspendentes as notas dos alunos.

### Saída
Todas as respostas devem ser apresentadas com uma casa decimal. As mensagens devem ser impressas conforme a descrição do problema. Não esqueça de imprimir o enter após o final de cada linha, caso contrário obterá "Presentation Error".


## [1041 - Coordenadas de um Ponto](https://www.beecrowd.com.br/judge/pt/problems/view/1041)
Leia 2 valores com uma casa decimal (x e y), que devem representar as coordenadas de um ponto em um plano. A seguir, determine qual o quadrante ao qual pertence o ponto, ou se está sobre um dos eixos cartesianos ou na origem (x = y = 0).

<p align="center">
 <img src="https://user-images.githubusercontent.com/86378481/159577324-c09049e5-9718-4196-9cb1-e62f06146404.png">
</p>

Se o ponto estiver na origem, escreva a mensagem “Origem”.

Se o ponto estiver sobre um dos eixos escreva “Eixo X” ou “Eixo Y”, conforme for a situação.

### Entrada
A entrada contem as coordenadas de um ponto.

### Saída
A saída deve apresentar o quadrante em que o ponto se encontra.



## [1042 - Sort Simples](https://www.beecrowd.com.br/judge/pt/problems/view/1042)
Leia 3 valores inteiros e ordene-os em ordem crescente. No final, mostre os valores em ordem crescente, uma linha em branco e em seguida, os valores na sequência como foram lidos.

### Entrada
A entrada contem três números inteiros.

### Saída
Imprima a saída conforme foi especificado.



## [1043 - Triângulo](https://www.beecrowd.com.br/judge/pt/problems/view/1043)
Leia 3 valores reais (A, B e C) e verifique se eles formam ou não um triângulo. Em caso positivo, calcule o perímetro do triângulo e apresente a mensagem:


Perimetro = XX.X


Em caso negativo, calcule a área do trapézio que tem A e B como base e C como altura, mostrando a mensagem


Area = XX.X

### Entrada
A entrada contém três valores reais.

### Saída
O resultado deve ser apresentado com uma casa decimal.


## [1044 - Múltiplos](https://www.beecrowd.com.br/judge/pt/problems/view/1044)
Leia 2 valores inteiros (A e B). Após, o programa deve mostrar uma mensagem "Sao Multiplos" ou "Nao sao Multiplos", indicando se os valores lidos são múltiplos entre si.

### Entrada
A entrada contém valores inteiros.

### Saída
A saída deve conter uma das mensagens conforme descrito acima.



## [1045 - Tipos de Triângulos](https://www.beecrowd.com.br/judge/pt/problems/view/1045)
Leia 3 valores de ponto flutuante A, B e C e ordene-os em ordem decrescente, de modo que o lado A representa o maior dos 3 lados. A seguir, determine o tipo de triângulo que estes três lados formam, com base nos seguintes casos, sempre escrevendo uma mensagem adequada:
- se A ≥ B+C, apresente a mensagem: NAO FORMA TRIANGULO
- se A2 = B2 + C2, apresente a mensagem: TRIANGULO RETANGULO
- se A2 > B2 + C2, apresente a mensagem: TRIANGULO OBTUSANGULO
- se A2 < B2 + C2, apresente a mensagem: TRIANGULO ACUTANGULO
- se os três lados forem iguais, apresente a mensagem: TRIANGULO EQUILATERO
- se apenas dois dos lados forem iguais, apresente a mensagem: TRIANGULO ISOSCELES

### Entrada
A entrada contem três valores de ponto flutuante de dupla precisão A (0 < A) , B (0 < B) e C (0 < C).

### Saída
Imprima todas as classificações do triângulo especificado na entrada.



## [1046 - Tempo de Jogo](https://www.beecrowd.com.br/judge/pt/problems/view/1046)
Leia a hora inicial e a hora final de um jogo. A seguir calcule a duração do jogo, sabendo que o mesmo pode começar em um dia e terminar em outro, tendo uma duração mínima de 1 hora e máxima de 24 horas.

### Entrada
A entrada contém dois valores inteiros representando a hora de início e a hora de fim do jogo.

### Saída
Apresente a duração do jogo conforme exemplo abaixo.



## [1047 - Tempo de Jogo com Minutos](https://www.beecrowd.com.br/judge/pt/problems/view/1047)
Leia a hora inicial, minuto inicial, hora final e minuto final de um jogo. A seguir calcule a duração do jogo.

Obs: O jogo tem duração mínima de um (1) minuto e duração máxima de 24 horas.

### Entrada
Quatro números inteiros representando a hora de início e fim do jogo.

### Saída
Mostre a seguinte mensagem: “O JOGO DUROU XXX HORA(S) E YYY MINUTO(S)” .



## [1048 - Aumento de Salário](https://www.beecrowd.com.br/judge/pt/problems/view/1048)
A empresa ABC resolveu conceder um aumento de salários a seus funcionários de acordo com a tabela abaixo:


Salário | Percentual de Reajuste
:-------------------: | :-----:
0 - 400.00 | 15%
400.01 - 800.00 | 12%
800.01 - 1200.00 | 10%
1200.01 - 2000.00 | 7%
Acima de 2000.00 | 4%

 
Leia o salário do funcionário e calcule e mostre o novo salário, bem como o valor de reajuste ganho e o índice reajustado, em percentual.

### Entrada
A entrada contém apenas um valor de ponto flutuante, com duas casas decimais.

### Saída
Imprima 3 linhas na saída: o novo salário, o valor ganho de reajuste e o percentual de reajuste ganho, conforme exemplo abaixo.



## [1049 - Animal](https://www.beecrowd.com.br/judge/pt/problems/view/1049)
Neste problema, você deverá ler 3 palavras que definem o tipo de animal possível segundo o esquema abaixo, da esquerda para a direita.  Em seguida conclua qual dos animais seguintes foi escolhido, através das três palavras fornecidas.

<p align="center">
 <img src="https://user-images.githubusercontent.com/86378481/160508519-45b6d6b4-3950-46c2-814a-21a837d3a3d0.png">
</p>


### Entrada
A entrada contém 3 palavras, uma em cada linha, necessárias para identificar o animal segundo a figura acima, com todas as letras minúsculas.

### Saída
Imprima o nome do animal correspondente à entrada fornecida



## [1050 - DDD](https://www.beecrowd.com.br/judge/pt/problems/view/1050)
Leia um número inteiro que representa um código de DDD para discagem interurbana. Em seguida, informe à qual cidade o DDD pertence, considerando a tabela abaixo:

<p align="center">
 <img src="https://user-images.githubusercontent.com/86378481/160511076-5f066135-e972-4eae-8318-78b00d684555.png">
</p>

Se a entrada for qualquer outro DDD que não esteja presente na tabela acima, o programa deverá informar:
DDD nao cadastrado

### Entrada
A entrada consiste de um único valor inteiro.

### Saída
Imprima o nome da cidade correspondente ao DDD existente na entrada. Imprima DDD nao cadastrado caso não existir DDD correspondente ao número digitado.



## [1051 - Imposto de Renda](https://www.beecrowd.com.br/judge/pt/problems/view/1051)
Em um país imaginário denominado Lisarb, todos os habitantes ficam felizes em pagar seus impostos, pois sabem que nele não existem políticos corruptos e os recursos arrecadados são utilizados em benefício da população, sem qualquer desvio. A moeda deste país é o Rombus, cujo símbolo é o R$.

Leia um valor com duas casas decimais, equivalente ao salário de uma pessoa de Lisarb. Em seguida, calcule e mostre o valor que esta pessoa deve pagar de Imposto de Renda, segundo a tabela abaixo.

<p align="center">
 <img src="https://user-images.githubusercontent.com/86378481/160514521-d5f77b4f-0293-42dd-b4f3-00abed1970f0.png">
</p>

Lembre que, se o salário for R$ 3002.00, a taxa que incide é de 8% apenas sobre R$ 1000.00, pois a faixa de salário que fica de R$ 0.00 até R$ 2000.00 é isenta de Imposto de Renda. No exemplo fornecido (abaixo), a taxa é de 8% sobre R$ 1000.00 + 18% sobre R$ 2.00, o que resulta em R$ 80.36 no total. O valor deve ser impresso com duas casas decimais.

### Entrada
A entrada contém apenas um valor de ponto flutuante, com duas casas decimais.

### Saída
Imprima o texto "R$" seguido de um espaço e do valor total devido de Imposto de Renda, com duas casas após o ponto. Se o valor de entrada for menor ou igual a 2000, deverá ser impressa a mensagem "Isento".



## [1052 - Mês](https://www.beecrowd.com.br/judge/pt/problems/view/1052)
Leia um valor inteiro entre 1 e 12, inclusive. Correspondente a este valor, deve ser apresentado como resposta o mês do ano por extenso, em inglês, com a primeira letra maiúscula.

### Entrada
A entrada contém um único valor inteiro.

### Saída
Imprima por extenso o nome do mês correspondente ao número existente na entrada, com a primeira letra em maiúscula.



## []()
## []()
## []()
## []()
## []()
## []()
## []()
## []()
## []()
## []()
## []()
## []()
