# Desafio da semana #2

Nesse exercício, você está livre para escolher os nomes para suas variáveis e funções! :smile:

```js
// Crie uma função que receba dois argumentos e retorne a soma dos mesmos.
function soma (x,y){
	resultado = x + y;
	return resultado;
}


}
// Declare uma variável que receba a invocação da função criada acima, passando dois números quaisquer por argumento, e somando `5` ao resultado retornado da função.
var desafio;
desafio = soma (2,3) + 5;
desafio = 10;

// Qual o valor atualizado dessa variável?
10

// Declare uma nova variável, sem valor.
var valor;

/*
Crie uma função que adicione um valor à variável criada acima, e retorne a string:
    O valor da variável agora é VALOR.
Onde VALOR é o novo valor da variável.
*/
function funcao(){
	valor = 20;
	return 'O valor da variável agora é ' + valor;
}

//correção

functio addValue(){
	valor = 20;
	return 'O valor da variável agora é ' + valor;
}
// Invoque a função criada acima.
funcao();

// Qual o retorno da função? (Use comentários de bloco).
*/
'O valor da variável agora é 20'
/*

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos;
2. Se qualquer um dos três argumentos não estiverem preenchidos, a função deve retornar a string:
    Preencha todos os valores corretamente!
3. O retorno da função deve ser a multiplicação dos 3 argumentos, somando `2` ao resultado da multiplicação.
*/
functions args (x,y,z){
	if (x === undefined || y === undefined || z === undefined ||) {
		return 'Preencha todos os campos corretamente';

	}else {
		resultado = x * y * z + 2;
		return resultado;
	}
}

//correção

function newFunction (a,b,c){
	if (a === undefined || b === undefined || c === undefined){return 'Preencha todos os valores corretamente';
	} else {
		resultado = (x * y * z) + 2;
		return resultado;
	}
}

//ou pode ser feito da seguinte forma;
function newFunction (a,b,c){
	if (a === undefined || b === undefined || c === undefined){return 'Preencha todos os valores corretamente';
	} 
	resultado = (x * y * z) + 2;
	return resultado;
	
}


// Invoque a função criada acima, passando só dois números como argumento.
args (2,2);


// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).

//'preencha todos os campos corretamente'

// Agora invoque novamente a função criada acima, mas passando todos os três argumentos necessários.
args (2,2,2);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
//10

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos.
2. Se somente um argumento for passado, retorne o valor do argumento.
3. Se dois argumentos forem passados, retorne a soma dos dois argumentos.
4. Se todos os argumentos forem passados, retorne a soma do primeiro com o segundo, e o resultado, dividido pelo terceiro.
5. Se nenhum argumento for passado, retorne o valor booleano `false`.
6. E ainda, se nenhuma das condições acima forem atendidas, retorne `null`.
*/
function funcao (x,y,z){
	if (x !== undefined && y === undefined && z === undefined){
		return x;
	}else if(x !== undefined && y !== undefined && z === undefined){
		resultado = x + y;
		return 'O resultado da soma de dois argumentos é ' + resultado;
	}else if (x !== undefined || y !== undefined || z !== undefined){
		// o erro estava somente na expressao da funcao;
		// Logica da function estava correta;
		return x + y / z;
	}else if(x === undefined || y === undefined || z === undefined){
		return false;
	}else{
		return 'null';
	}
}
//correcao;
function threeArgs(x,y,z){
	if( x!== undefined && y === undefined && z === undefined){
		return x;
	} 

	else if ( x !== undefined && y ==! undefined && z === undefined) {
		return x + y;
	}
	else if (x !== undefined && y !== undefined && z !== undefined){
		//sempre usar os parenteses, pois se não ele vai fazer primeiro a divisão;
		return (x + y) / z;
	}else if (x === undefined && y === undefined && z === undefined){
		return false;
	}else {
		return 'null';
	}
}

// Invoque a função acima utilizando todas as possibilidades (com nenhum argumento, com um, com dois e com três.) Coloque um comentário de linha ao lado da função com o resultado de cada invocação.


```