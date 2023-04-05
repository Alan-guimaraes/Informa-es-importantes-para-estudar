##Loops - Repetição
For - while - do while


***** Utilizando While
Deve-se ter cuidado com a execusão infinita. 

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
