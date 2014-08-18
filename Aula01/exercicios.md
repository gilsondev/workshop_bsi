# Dia 01 - Exercícios

## Considerações

As questões abaixo envolve o que foi ensinado nesse dia. Não se preocupem se as questões são simples, elas servem somente para praticar e fixar o que aprenderam. Praticamente todas as questões exigem entrada de dados, e para isso podem usar esses exemplos:

```java
// Preparando objeto para entrada de dados
Scanner entradaDados = new Scanner(System.in);

// Para receber entrada do tipo String
entradaDados.nextLine();

// Para receber entrada do tipo Integer, Long, Double e Float respectivamente
entradaDados.nextInt();
entradaDados.nextLong();
entradaDados.nextDouble();
entradaDados.nextFloat();
```

No decorrer do curso irei explicar a criação de objetos e classes Java. Para mais informações sobre a classe Scanner:

- Como funciona a classe Scanner do Java: http://www.devmedia.com.br/como-funciona-a-classe-scanner-do-java/28448
- API Scanner: http://docs.oracle.com/javase/6/docs/api/java/util/Scanner.html

## Questões

1. Escreva um programa em Java que recebe 3 números, calcule e mostre a soma.

2. Escreva um programa em Java que lê três números inteiros, calcula e imprime a média aritmética desses números.

3. Escreva um programa em Java que leia dois números inteiros e determine qual é o menor.

4. Escreva um programa para ler 3 notas de um aluno e informar se o alunos está aprovado, reprovado ou se deverá fazer a prova final.
    ```
    - O aluno será Aprovado a média de suas notas for > 6
    - O aluno será Reprovado se a média de suas notas for < 4
    - O aluno deverá fazer a prova se a média de suas notas for >= 4 e < 6
    - Média das notas: (Nota1 + Nota2 + Nota3) / 3
    ```

5. Crie um programa que recebe uma lista de números inteiros positivos decimais (0-9) *, o programa termina quando inserido o (– 1), e imprime para cada número n a sequência de 0s e 1s que formam os bits (do mais significativo para o menos significativo) deste número representado em binário, a sequência de bits deve ser apresentada na mesma linha e concluída por “\n”. Use o método print para imprimir cada um dos bits, e o método println para pular de linha.

6. Escreva um programa para ler o salário de uma pessoa e imprimir o
desconto do INSS segundo a tabela abaixo:
    ```
    - menor ou igual a R$ 600,00 - Isento
    - maior do que R$ 600,00 e menor ou igual a R$ 1.200,00 - 20%
    - maior do que R$ 1.200,00 e menor ou igual a R$ 2.000,00 - 25%
    - maior do que R$ 2.000,00 - 30%
    ```

6. Escreva um programa para calcular a quantidade de litros de combustível necessária para se fazer uma viagem, sabendo-se que o carro faz 12 Km com um litro. Deverão ser fornecidos o tempo gasto na viagem e a velocidade média. Utilizar as seguintes fórmulas:
    ```
    distância = tempo x velocidade
    litros usados = distância / 12
    ```

7. Escreva um programa para imprimir o menu abaixo:
    ```
    1 - Solteiro(a)
    2 - Desquitado(a)
    3 - Casado(a)
    4 - Divorciado(a)
    5 - Viúvo(a)
    ```
    O usuário deverá selecionar uma das opções do menu e este deverá escrever
    o estado civil da pessoa. Emitir mensagem de erro caso seja escolhida uma
    opção inexistente.

8. Escreva um programa para ler um conjunto de funcionários de uma empresa
com número, idade, número de horas trabalhadas e salário hora. O programa deverá imprimir:
    ```
    - O número, idade salário hora e horas trabalhadas para cada um
    - A quantidade de homens
    - A média salarial de todas as mulheres
    - A média salarial das mulheres com menos de 30 anos
    - A média salarial de todos os empregados
    ```

O número da última pessoa (que não deve ser considerada) deve ser 999.
