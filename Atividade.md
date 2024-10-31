# Atividade de Encapsulamento 

1 - Crie uma classe chamada JogadorDeFutebol contendo os atributos públicos nome,
posição, data de nascimento, nacionalidade, altura e peso. Crie o construtor para
inicializar todos os atributos e um método chamado calculaIdade( ) que retorna a
idade do jogador. Crie o método que exibe todos os dados na forma:

Nome: Fulano
Ano de Nascimento: xxxx
Altura: 1,80 m
Peso: 85,0 kg
Nacionalidade: Brasileiro
Posição: Meio de Campo


2 - Crie a classe chamada App contendo o método main( ) que instancia a classe
JogadorDeFutebol uma vez. Essa classe contém o método de leitura dos dados
chamado leDados( ) e o método que mostra quanto tempo (em anos) falta para o
jogador se aposentar sabendo que, em média, se o jogador for atacante ele aposenta
aos 35 anos, se for da defesa ele aposenta aos 40 anos e se for meio de campo ele
aposenta aos 38 anos. Esse método deve retornar uma String na forma:

Faltam xx anos para o jogador Fulano se aposentar.


## Responda : 

b) Coloque o atributo nome como privativo e execute o programa. O que acontece?
Explique.

    Deu erro na classe App,  pois o atributo nome foi declarado como privado na classe JogadorDeFutebol.
    "The method nome() is undefined for the type JogadorDeFutebolJava(67108964)"
    
c) Crie um método getter na classe JogadorDeFutebol para solucionar o problema
anterior e execute.