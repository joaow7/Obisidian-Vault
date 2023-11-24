### Inclusão:
**array.unshift()** = inclui o dado no inicio do array

O método **`unshift()`** adiciona um ou mais elementos no início de um array e retorna o número de elementos (propriedade `length`) atualizado.

**array.push()** = inclui o dado no final do array

O método **push()** adiciona um ou mais elementos ao final de um array e retorna o novo comprimento desse array.

### Exclusão:

**array.pop()** = exclui o ultimo dado do array

O método **`pop()`** remove o **último** elemento de um array e retorna aquele elemento.

**array.shift()** = exclui o primeiro dado do array

O método **`shift()`** remove o **primeiro** elemento de um array e retorna esse elemento. Este método muda o tamanho do array.
Remover um item pela posição do índice:

O método **splice()** altera o conteúdo de uma lista, adicionando novos elementos enquanto remove elementos antigos.

```
var removedItem = frutas.splice(pos, 1); // é assim que se remove um item
// ['Morango', 'Manga']
```