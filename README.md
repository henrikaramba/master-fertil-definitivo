# Missão Fertilidade — Alimentação em Jogo

PWA educativo completo com 30 questões, 5 cenários, dois personagens selecionáveis (um jogador por partida), pontos, moedas, som procedural, acessibilidade e funcionamento offline.

## Como publicar no GitHub Pages
1. Extraia o ZIP.
2. Envie **todos os arquivos e pastas** para a raiz do repositório.
3. No GitHub: Settings → Pages → Deploy from a branch → `main` / root.
4. Abra a página publicada uma vez com internet. O service worker armazenará o jogo para uso offline.

## Controles
- Computador: ←/→ ou A/D para andar; Espaço/W/↑ para pular; E/Enter para responder.
- Celular/tablet: botões na parte inferior da tela.

## Acessibilidade
- Texto ampliado
- Alto contraste
- Redução de animações
- Leitura das perguntas em voz alta (quando o navegador tiver voz pt-BR instalada)
- Controle de volume
- Navegação por teclado e controles por toque

## Observação científica
O jogo usa linguagem educativa: alimentação pode contribuir para fatores ligados à saúde reprodutiva, mas não garante gravidez. Dificuldade para engravidar pode ter diferentes causas e deve ser avaliada por profissionais de saúde.


## Atualizações desta versão
- Capa com escolha direta entre Maya e Theo.
- Direção de caminhada corrigida: o personagem olha para o lado em que se desloca.
- Obstáculos agora bloqueiam lateralmente e exigem salto para ultrapassar.
- Áudios enviados incorporados para abertura de desafio, pulo, acerto e vitória.

## Atualização v5 — obstáculos
- Pulo mais alto e deslocamento horizontal mais fluido.
- Colisão lateral tolerante nas quinas para evitar que Maya/Theo fiquem presos.
- Obstáculos recalibrados para serem ultrapassáveis.
- Cache do PWA atualizado para carregar a nova física.
