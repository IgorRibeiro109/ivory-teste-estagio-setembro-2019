# ivory-teste-estagio-setembro-2019
 O objetivo do programa é realizar o cálculo do fatorial de 5, usando uma função recursiva chamada Calcular, porem o resultado exibido em tela do código originalmente implementado é 0, estando assim o resultado e o código incorreto.  
 O erro detectado, está dentro da função Calcular na condição “ if ”. Onde é detectado dois tipos de erros, matemático e lógico. Está escrito “Se numero menor ou igual 0, retorna zero”, o erro matemático e que a fatorial de 0 é 0 onde o correto seria que a fatorial de 0 é 1, e o erro lógico e que gera na função recursiva uma multiplicação indevida por zero, onde assim retorna para ser mostrado na tela 0. 
 Para corrigir esse erro basta mudar o if na função Calcular, e coloca-la ao invés de retornar 0, retornar 1. 
Assim: 
If (numero <= 0) {  return (1)};
