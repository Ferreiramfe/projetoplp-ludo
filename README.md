
#Jogo Ludo
##Conceito:
  `O programa consiste em um sistema que forneça as mesmas opções de jogabilidade que um ludo de tabuleiro normal (jogo físico).`
##Especificações:
* ao ser executado, o jogo deve fornecer um menu de navegação com as opções de jogo que um jogo de ludo no tabuleiro físico tem, sendo possível selecioná-las.
* o usuário terá a opção de escolher quantos jogadores irão participar, sendo de 2 a 4 pessoas.
* o usuário terá a opção de escolher jogar contra o ‘computador’ e sua quantidade, sendo:
    * 2 jogadores: o usuário e um ‘computador’.
    * 3 jogadores: o usuário e dois ‘computadores’.
    *  4 jogadores: o usuário e três ‘computadores’.
* o usuário terá a opção de selecionar a cor de suas peças e dos demais jogadores (para o caso de pessoas reais).
* o usuário terá a opção de ‘jogar’ o dado para liberar uma de suas peças.
* o usuário terá a opção de ‘jogar’ o dado para avançar com suas peças no jogo.
* regras de jogo serão implantadas, como:
    * quando tirar o número 6, o jogador terá o direito de jogar novamente.
    * quando a peça de um jogador cair em uma das casas que tiver a peça de outro(s) jogador(es), a peça do(s) último(s) irá retornar para o início do trajeto.
    * demais regras que existem no jogo físico de ludo e forem viáveis de implementação.
* o usuário que chegar com todas as suas peças ao final do trajeto, será o vencedor da partida.
* após um dos jogadores vencer a partida, existem os possíveis cenários:
    * caso o usuário esteja jogando com um ou mais ‘computadores’, a partida se encerra.
    * caso o usuário esteja jogando com outras pessoas reais, o jogo continuará até que apenas um dos jogadores não tenham todas as suas peças no final do trajeto.
* o usuário terá a opção de encerrar a partida a qualquer momento (**não** sendo possível retornar para a mesma partida que foi encerrada)..
