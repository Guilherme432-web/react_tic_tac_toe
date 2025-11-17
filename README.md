#Jogo da velha com react

##Descrição
>Este projeto é uma implementação simples do clássico jogo da velha (tic-tac-toe) utilizando React. Ele permite que dois jogadores joguem alternadamente, registra o histórico das jogadas, e possibilita navegar
>entre os diferentes estados do jogo (time travel).

##Funcionalidades
-Dois jogadores (X e O) jogando alternadamente.
-Indicação do próximo jogador.
-Detecção do vencedor e indicação do mesmo.
-Registro do histórico do jogo.
-Navegação entre jogadas anteriores ("time travel").
-Interface simples e interativa.

##Estrutura de código
-**Square**:Componente que representa uma casa individual do tabuleiro. Recebe valores e callback para tratar cliques.
-**Board**:Componente que gerencia o estado do tabuleiro e renderiza 9 componentes Square organizados em linhas.
-**Game**:Componente principal que mantém o histórico do jogo, o movimento atual, e lógica para manipular o estado e navegação entre jogadas.

##Como rodar
>1.Clone o repositório
>2.Instale as dependências: npm install, depois inicie com npm start.
>3. Abra o navegador no endereço 'http://localhost:3000' para jogar.
