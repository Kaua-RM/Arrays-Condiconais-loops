# Arrays-Condiconais-loops


### Arrays

Imagine que você precisa armazenar várias informações de um mesmo tipo , seguindo a lógica deveriamos criar várias variaveis , entretanto, isso não seria viavel , por que consumiria muita memória, para isso nós temos o array, um array é como se você uma variavel mutante , pois ela consegue armazenar várias informações do mesmo tipo dentro de sí . Mas como a informação pode ser encontrada ? No array nós temos o índice , o índice informa em que parte do array a informação está contida, ela funciona como uma escala númerica normal , só que ela começa do 0 ao ínves do 1 . 

```
// Criando um array

// Tipo  nome       informando que essa será um array

String[] frutas = new String[2];

// no java , o array em sua inicialização precisa ter sua quantidade de espaços definido.


```


### Condicionais 

As estruturas Condicionais , são ferramentas que mudam o caminho/fluxo do sistema, por que ? Pois elas são estruturas que fazem o sistema realizar decisões por meio das informações colocadas pelo usuario. As estruturas de condição encontradas no Java são IF/ELSE (Se/Senão) - Condicionais Simples , Else if(condição) - Condicionais Encadeadas , variavel = condição ? resultado1 : resultado2 - Condicional Ternário, Switch(variavel){ case condição : resultado breack} .

```

//Condicionais Simples

if(condição) {
}else{
}

//Condicionais Encadeadas

if(condição) {
}else if(outra condição){
}else{
}

//Condicional Ternario

String Aprovado = nota >= 7 ? "Aprovado" : "Reprovado";

// Switch Case

Switch(fruta){

case "Morango" : "Esta fruta é um Morango";
break
case "Maracuja" : "Esta fruta é um Maracuja"
break
}

// o break informa que o código para naquela linha , ele pode ser usado em if e else e todas as outras condições.

```
