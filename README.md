# victor_gabriel_alves_de_carvalho_xavier
   O trabalho apresentado é de um jogo popularmente chamado de racha cuca ou jogo dos 15, o objetivo do jogo é ordenar 15 números de forma crescente, quando ordenado o jogo é finalizado. 
   Para a criação do código foi utilizando as seguintes bibliotecas:
stdio.h; ncurses.h; time.h e stdlib.h. Além disso, foram criadas algumas funções para melhor aplicação e organização do código, a seguir estão as funções utilizadas e a explicação sobre cada uma. 
funções:
embaralhar: Esta função tem como objetivo embaralhar, como seu nome já diz, os números do tabuleiro, ela pega um vetor como entrada e troca os elementos aleatoriamente, assim o tabuleiro é iniciado sempre embaralhado.

troca: Troca os valores de duas variáveis inteiras.

contagem: Garante que o tabuleiro tenha solução;

validacao: Junto com a função contagem a validacao verifica se o tabuleiro é válido para jogar.

verificar: Verifica se o tabuleiro está ordenado.

fim_do_jogo: Compara as duas matrizes para verificar se o jogo chegou ao fim na ordem desejada.

   Finalizando as funções entramos na função principal, main, onde ocorre a criação de uma matriz representando o tabuleiro formado com os números de 1 até 15 e o espaço em branco representada por -1,em seguida iniciamos a interface ncurses onde será criada a janela que exibirá o tabuleiro e outras “configurações” importantes como a movimentação das peças pelas setas do teclado, dentro da ncurses e criado um loop onde só terá fim quando o usuário terminar de montar o tabuleiro ou pressionar “F1”, após completar o objetivo do jogo a mensagem “parabéns!!!” por 10 segundos e o programa é finalizado.
