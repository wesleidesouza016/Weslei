# ArtXadrez ♟

**ArtXadrez** é um jogo de xadrez para navegador, em português, pensado para partidas entre duas pessoas no mesmo dispositivo.

## Como jogar
1. Abra `index.html` no navegador.
2. Toque ou clique em uma peça da sua cor.
3. Escolha uma casa destacada para fazer um lance legal.
4. Ao promover um peão, escolha dama, torre, bispo ou cavalo.

## Recursos
- Tabuleiro responsivo para celular e computador.
- Regras legais de xadrez usando a biblioteca Chess.js.
- Roque, en passant e promoção.
- Detecção de xeque, xeque-mate, afogamento e empates previstos pela biblioteca.
- Histórico de lances, desfazer, nova partida e girar o tabuleiro.
- Destaque de jogadas legais e opção de som.

## Executar
Não precisa de instalação nem de compilação. Abra `index.html` em um navegador moderno com conexão à internet (a biblioteca Chess.js é carregada por CDN).

## Publicar com GitHub Pages
No repositório, entre em **Settings → Pages**, escolha **Deploy from a branch**, selecione `main` e a pasta `/ (root)`, depois salve. Quando o GitHub Pages terminar a publicação, o jogo estará disponível no endereço indicado nessa tela.

---
Feito com carinho para o projeto Weslei.


## Publicação automática
O GitHub Actions está configurado para ativar o GitHub Pages e publicar o site a cada atualização da branch `main`.
