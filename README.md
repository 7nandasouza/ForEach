# ForEach
 Execução do forEach e seus argumentos

## ForEach

O método forEach()  itera por um array, chamando uma função especificada para cada elemento.Portanto, podemos chama a função com três argumentos: o valor do elemento do array, o índice do elemento e o array em si. Assim, também se pode escrever uma função com apenas um parâmetro – os argumentos adicionais serão ignorados.

O forEach executa callback fornecido uma vez para cada elemento, levando três argumentos:

   * o valor do elemento
   * o índice do elemento
   * o vetor (array) que está a ser percorrido


**Sintaxe** 

vet.forEach(function callback(presenteValor[, indice[, vetor]]) {
    //o teu iterador
}[, argThis]);


Se estiver um único argumento e podendo ser escrito na mesma linha não preciso de parentes e chaves de fechamento.

array1.forEach(element => console.log(element));


**Exercício ** 


1- Uma const imgs para seleciona todas as imagens com  querySelectorAll(),forEach chamando o argumento valor e índice.

2- Uma variável i =0  começando com 0 e chamado essa variável com forEach fazendo um loop para cada elemento.
