# Bootcamp Data Analytics | WoMaKersCode 2024 T7 

### erros-e-excecoes

### Este exercício faz parte da aprendizagem em Python 

##

### 1. O programa abaixo deve calcular a média dos valores digitados pelo usuário. No entanto, ele não está funcionando bem. Você pode consertá-lo?

##

## Resolução e melhorias feitas:

### 

1 - Correção no cálculo da média: A variável tamanho deve ser igual ao número de elementos na lista valores. No código original, tamanho estava fixado como 1, o que é incorreto.

2 - Correção no loop de entrada de valores: O loop while agora termina corretamente quando o usuário digita "ok". No código original, a variável calcular estava sendo usada incorretamente e False estava com a inicial minúscula.

3 - Conversão de entrada para número: Agora, a entrada é convertida para float e adicionada à lista valores. Se a entrada não for um número válido, uma mensagem de erro é exibida.

4 - Média de lista vazia: Adicionada uma verificação para retornar 0.0 se a lista estiver vazia, evitando divisão por zero.

5 - Formatação da saída: A formatação da string final foi mantida, apenas corrigindo a capitalização e pontuação.

### Aluna:

Alexsandra Tavares
