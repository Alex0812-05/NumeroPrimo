Este programa em Java tem como objetivo verificar se um número informado pelo usuário é primo. O programa solicita que o usuário insira um número inteiro, e então verifica se ele é divisível apenas por 1 e por ele mesmo, que são as condições para que um número seja considerado primo.

Como Funciona:
.O programa começa solicitando que o usuário insira um número inteiro.

.Em seguida, o programa verifica se o número é menor ou igual a 1. Números menores ou iguais a 1 não são considerados primos.

.Se o número for maior que 1, o programa verifica se ele é divisível por qualquer número entre 2 e a raiz quadrada do número. A razão para limitar a verificação até a raiz quadrada é que qualquer divisor maior que a raiz quadrada do número terá um correspondente menor, que já teria sido verificado.

.Se o número for divisível por algum número que não seja 1 ou ele mesmo, o programa indica que o número não é primo.

.Se o número não for divisível por nenhum outro número além de 1 e ele mesmo, o programa indica que o número é primo.
