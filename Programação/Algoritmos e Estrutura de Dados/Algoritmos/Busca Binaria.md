

A **pesquisa** ou **busca binária** (em [inglês](https://pt.wikipedia.org/wiki/L%C3%ADngua_inglesa "Língua inglesa") _binary search algorithm_ ou _binary chop_) é um [algoritmo de busca](https://pt.wikipedia.org/wiki/Algoritmo_de_busca "Algoritmo de busca") em [vetores](https://pt.wikipedia.org/wiki/Arranjo_(computa%C3%A7%C3%A3o) "Arranjo (computação)") que segue o paradigma de [divisão e conquista](https://pt.wikipedia.org/wiki/Divis%C3%A3o_e_conquista "Divisão e conquista"). Ela parte do pressuposto de *que o vetor está ordenado* e realiza sucessivas divisões do espaço de busca comparando o elemento buscado (chave) com o elemento no meio do vetor. Se o elemento do meio do vetor for a chave, a busca termina com sucesso. Caso contrário, se o elemento do meio vier antes do elemento buscado, então a busca continua na metade posterior do vetor. E finalmente, se o elemento do meio vier depois da chave, a busca continua na metade anterior do vetor.


## Exemplo em JS
 