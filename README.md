# FuncoesJs
## Function Declaration:
A Function Declaration é a mais comum de declarar uma função, ela se inicia com o comando **function**, o nome da função e seus parâmetros e dentro das chaves o conteúdo da sua função. Essa função em específico possui hoisting ou seja pode ser chamada antes da sua declaração e em qualquer local do algoritmo. Mas existe um problema nessa função, ela pode sobrescrever outras funções que estiverem com o mesmo nome dificultando o entendimento do que aconteceu na saída do algoritmo.
### Exemplo:
```js
Function Somar (A, B){
Return A + B;
}

```
## Function Expression:
Essa função é armazenada dentro de uma variável, ela pode ser tanto **nomeada** para fazer recursão, como também pode ser **anônima** sendo mais comum. Essa em questão não possui hoisting, ou seja, ela precisa ser declarada antes de ser usada. Sua estrutura se inicia com a variável, seguindo o comando **function** pois é uma função dentro da variável, os seus parâmetros e dentro das chaves a estrutura da função.
### Exemplo:
```js
Let Somar = Function (A, B){
Return A + B;
}
```
## Function Arrow:
É a função mais moderna entre as três, ela procura deixar o código mais limpo e fácil de entender. A sua sintaxe é bem simples, declara uma variável em seguida o nome da função, os seus parâmetros, o sinal "=>" para iniciar o arrow e dentro das chaves o conteúdo da sua função. Existe variação de sintaxe nessa função, ela pode ser criada com retorno explícito ou implícito (com ou sem chaves), também pode ser criada com ou sem parâmetros.
### Exemplo1:
```js
Let Somar = (A, B) => A + B
```
### Exemplo2:
```js
Let Somar = (A, B) => {
Let Resout = A + B;
Return Resout;
}
```
