# Jogo-da-velha
A seguir, segue os códigos de 3 estratégias usadas para um código de jogo da velha;

O primeiro código consiste em uma IA, que vai usar de jogadas aleatórias dentre os espaços vazios no código.

O segundo código é o mais implementado dentre os 3, pois nele a IA usa o Algoritmo MINIMAX, tal algoritmo funciona da seguinte forma:


  -O algoritmo começa com o estado atual do jogo, representado por um tabuleiro com todas as jogadas já realizadas.
  
  -Ele cria um novo tabuleiro para cada possível jogada que o jogador atual pode fazer.
 
  -Para cada novo tabuleiro criado, ele analisa todos os movimentos possíveis do adversário e escolhe aquele que minimiza o resultado final para o jogador atual.
  
  -Ele repete esses passos recursivamente para cada novo tabuleiro criado, até que todas as possíveis sequências de jogadas tenham sido exploradas. 
  
  -Quando todas as possíveis sequências de jogadas foram analisadas, o algoritmo escolhe o movimento que maximiza o resultado final para o jogador atual.
  
Ou seja, ele desce os nós da game tree, criando situacoes hipoteticas onde ele tenta predeterminar qual a melhor jogada dada a jogada da outra pessoa, por iso se chama MINIMAX, onde tem alguem fazendo uma jogada minima(pontuacao minima) e outra maxima(pontuacao maxima), onde ele tenta achar a melhor posicao que ele possa jogar dada a jogada anterior, buscando favorecer ele mesmo e 'prejudicar' o outro jogador.


O terceiro código é quase uma cópia do primeiro, no entanto, em vez da IA jogar aleatoriamente, ela joga aleatoriamente tambem, no entanto ela faz uma verificacao de posições previamente ocupadas, para depois jogar.


Portanto é possível concluir que cada tipo de código oferece um nível de dificuldade ao jogador, cabendo ao mesmo decidir qual nível ele deseja jogar.
