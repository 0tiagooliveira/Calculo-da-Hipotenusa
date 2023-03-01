# Calculo-da-Hipotenusa
Esse código pede ao usuário o comprimento do cateto oposto e do cateto adjacente de um triângulo retângulo e, em seguida, calcula e exibe o comprimento da hipotenusa desse triângulo retângulo.

Para isso, o código utiliza a fórmula matemática que relaciona os comprimentos dos catetos e da hipotenusa em um triângulo retângulo: hipotenusa = raiz quadrada de (cateto oposto ao quadrado + cateto adjacente ao quadrado).

O código usa as entradas do usuário para calcular o valor da hipotenusa e exibe o resultado com três casas decimais usando a função format().

Vou explicar o código linha por linha:

co = float(input('Comprimento do cateto oposto? '))
Nesta linha, a variável co é criada e recebe um valor de ponto flutuante (float) que é obtido através da função input(), que solicita ao usuário que insira um valor.
A mensagem entre parênteses dentro da função input() é mostrada ao usuário para indicar o que é esperado dele. No caso, é solicitado o comprimento do cateto oposto.
ca = float(input('Comprimento do cateto adjacente? '))
Nesta linha, a variável ca é criada e recebe um valor de ponto flutuante (float) que é obtido através da função input(), que solicita ao usuário que insira um valor.
A mensagem entre parênteses dentro da função input() é mostrada ao usuário para indicar o que é esperado dele. No caso, é solicitado o comprimento do cateto adjacente.
hi = (co ** 2 + ca ** (1/2))
Nesta linha, a variável hi é criada e recebe o valor da hipotenusa calculada a partir do comprimento do cateto oposto (co) e do comprimento do cateto adjacente (ca).
A fórmula utilizada para calcular a hipotenusa é: hipotenusa = raiz quadrada de (cateto oposto ao quadrado + cateto adjacente ao quadrado).
No código, co ** 2 significa co elevado ao quadrado, enquanto ca ** (1/2) significa ca elevado à raiz quadrada (ou seja, a metade do expoente 2).
Os valores de co e ca são inseridos na fórmula e o resultado é armazenado na variável hi.
print('A hipotenusa vai medir {:.3f}'.format(hi))
Nesta linha, a mensagem que será exibida para o usuário é formatada e mostrada na tela.
A mensagem é "A hipotenusa vai medir" seguida do valor da hipotenusa (que está armazenado na variável hi).
O valor de hi é formatado com 3 casas decimais usando :.3f.
A função format() é usada para inserir o valor de hi no lugar onde está o marcador de posição {:.3f} na mensagem.
