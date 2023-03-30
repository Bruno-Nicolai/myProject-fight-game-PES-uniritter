# Este é um jogo 2D feito com JavaScript e a API Canvas.
> Um cenário de batalha onde dois jogadores lutam até o tempo acabar. O jogo é executado dentro de um elemento de tela e os gráficos são desenhados usando o contexto 2D dela.
+ possui dois lutadores, um controlado pelo jogador da esquerda e outro controlado pelo da direita. Os jogadores podem mover seus lutadores para a esquerda ou para a direita, um usando as teclas 'a' e 'd', respectivamente, e também pode atacar usando a tecla 'e'; o outro lutador se move da direita para a esquerda com as teclas de flecha e ataca o jogador com a tecla enter quando o tiver ao alcance.
+ tem um cronômetro que começa em 60 segundos e faz a contagem regressiva até zero. Se nenhum lutador vencer quando o cronômetro chegar a zero, o jogo terminará empatado. O jogador com mais vida no final do jogo é declarado o vencedor.
+ detecta colisões entre os dois lutadores, verificando se a caixa de ataque de um lutador cruza com a do outro. Se um lutador for atingido, sua saúde diminui.
+ tem uma UI simples com um cronômetro, uma caixa de mensagem que exibe o vencedor e um botão de reinício.

<hr/>

# This is a 2D game made with JavaScript and the Canvas API. 
> It is a fighting game where two players battle it out until the time runs out. The game runs inside a canvas element and the graphics are drawn using the 2D context of the canvas.
+ it has two fighters, one controlled by the player on the left and the other controlled by the player on the right. Players can move their fighters left or right. One using the 'a' and 'd' keys respectively, and can also attack using the 'e' key; the other fighter moves from right to left with the arrow keys and attacks the player with the enter key when in range.
+ it has a timer that starts at 60 seconds and counts down to zero. If no fighter has won when the timer reaches zero, the game ends in a draw. The player with more health at the end of the game is declared the winner.
+ it detects collisions between the two fighters by checking if the attack box of one fighter intersects with the hitbox of the other fighter. If a fighter is hit, its health decreases.
+ it has a simple user interface with a timer, a message box that displays the winner, and a restart button.
