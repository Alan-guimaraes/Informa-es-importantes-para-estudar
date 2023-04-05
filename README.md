##Loops - Repetição
For - while - do while


***** Utilizando While
(O while é uma declaração de fluxo de controle que executa parte dos programas repetidamente com base na condição boolean especificada.)

Deve-se ter cuidado com a execução infinita. 

int numero = 0;
While (numero < 5) {
system.out.println ("executou"); 
numero = numero +1;
}
// ele vai dar um exe e add +1, até executar 5vezes. Assim definimos um limite. 

OUTRO EXEMPLO:
int numero = 1;
While (numero <= 5) {
system.out.println ("coisa aleatoria para incrementar");
system.out.println ("executou" + numero ); // + uma variável 
system.out.println ("coisa aleatoria para incrementar");
numero = numero +1;
}
// Vai retornar um padrão junto com os outros 2 system.out 


EXEMPLO UTILIZANDO UM ARRAY:
String [] postagens = {"Bom dia", "postagem 2", "postagem 3"}; //utizando um array 
system.out.println ( postagens.length );
int numero = 0; //inicia com 0
while( numero < postagens.length ){

system.out.println ( postagens [numero] );
system.out.println ("coisa aleatoria para incrementar");
numero = numero + 1; //seguir com +1 em cada postagem
}
*************************************************************************************************
Do - While executa primeiro para depois testar a execução 
(O do while é uma instrução de fluxo de controle que executa uma parte dos programas pelo menos uma vez e a execução posterior depende da condição boolean especificada.)

int numero = 1; 
do{
system.out.println ( numero );
numero = numero + 1;
}while ( numero < 1);
// retorna 1 - (Do - While executa primeiro para depois testar a execução )

*************************************************************************************************
For - Define as estruturas|condição - tudo dentro do "for"
(O for é uma declaração de fluxo de controle que itera parte dos programas várias vezes.)
int numero = 1; 
for( int n=1; n<5; n = n+1 ){ /*podemos usar o n++ para receber o n+n, ou melhor, mais 1*/
system.out.println ( n );
}

Retorno = 1, 2. 33, 4, 5.
