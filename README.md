# Laboratório Instável

Jogo de cartas para o navegador. Tira cartas do baralho, evita as Poções Instáveis e sê o último cientista inteiro.

Joga com 2 a 4 pessoas, cada uma no seu computador, ou sozinho contra robôs. Não é preciso instalar nada nem criar conta.

## Jogar com colegas

1. Abre o site e escreve o teu nome.
2. Carrega em **Criar sala** e envia o código de 5 letras aos teus colegas.
3. Eles abrem o mesmo site, escrevem o código e carregam em **Entrar**.
4. O anfitrião escolhe se quer robôs na partida (de "Sem robôs" até 3) e carrega em **Começar partida**.

A janela de quem cria a sala tem de ficar aberta durante a partida, porque é lá que o jogo corre. Se um colega perder a ligação a meio, sai da partida. Se o anfitrião tiver ligado a opção de substituição, um robô fica com o lugar dele.

## Regras

1. Cada cientista começa com 1 Neutralizador e 7 cartas.
2. No teu turno, joga as cartas de ação que quiseres e depois tira uma carta do baralho.
3. Se tirares uma Poção Instável, usa um Neutralizador e escolhe onde a esconder. Sem Neutralizador, explodes.
4. Ganha o último que ficar.

## Como funciona

Todo o jogo está num único ficheiro, `index.html`. Os jogadores ligam-se diretamente entre navegadores através do [PeerJS](https://peerjs.com), que usa um servidor público e gratuito só para pôr os jogadores em contacto. Não há servidor próprio para manter.
