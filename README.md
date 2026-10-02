# Projeto Calculadora

Projeto desenvolvido como atividade prática do curso, reunindo uma calculadora desenvolvida em Python e uma versão em Bash.

## Arquivos do projeto

* `Atividade_Pratica_Calculadora_Pyth (2).ipynb` — código da calculadora desenvolvido em Python.
* `calculadora.sh` — versão da calculadora desenvolvida em Bash.

## Como executar o arquivo Bash

Para executar a calculadora Bash, abra o terminal na pasta do projeto:

```bash
cd /home/waldemar/modulo1/projeto-calculadora
```

Caso necessário, dê permissão de execução ao arquivo:

```bash
chmod 744 calculadora.sh
```

Depois, execute o programa:

```bash
./calculadora.sh
```

O programa solicita dois números, apresenta as opções de operação e exibe o resultado.

## Como funciona o código Python

O código Python começa solicitando ao usuário dois números por meio da função `input()`. Os valores recebidos são convertidos para o tipo `float`, permitindo trabalhar também com números decimais.

Em seguida, o programa apresenta quatro opções de operação:

1. Soma
2. Subtração
3. Multiplicação
4. Divisão

A escolha do usuário é armazenada na variável `opcao`. Estruturas condicionais `if` e `elif` verificam qual operação foi escolhida e realizam o cálculo correspondente.

Na versão principal do programa, foi utilizado um laço `while True`, permitindo que o usuário realize várias operações consecutivamente.

Na divisão, o programa verifica se o segundo número é diferente de zero. Caso seja zero, uma mensagem de erro é exibida e uma nova operação é solicitada.

Após apresentar o resultado, o programa pergunta ao usuário se deseja sair. Caso a resposta seja `s`, o comando `break` encerra o laço e finaliza o programa.

## Objetivos praticados

O projeto permite praticar conceitos básicos de programação, incluindo:

* Entrada de dados com `input()`;
* Conversão de tipos com `float()`;
* Operações matemáticas;
* Estruturas condicionais `if`, `elif` e `else`;
* Laços de repetição com `while`;
* Validação de divisão por zero;
* Controle de fluxo com `continue` e `break`;
* Execução de scripts Bash e gerenciamento de permissões no Linux.
