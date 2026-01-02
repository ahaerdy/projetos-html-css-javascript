Dia 01 - Expanding Cards

## Vídeo 01 - Project Intro

<video width="60%" controls>
  <source src="000-Midia_e_Anexos/005 Project Intro.mp4" type="video/mp4">
    Seu navegador não suporta vídeo HTML5.
</video>

### Anotações

#### Projeto Expanding Cards

<p align="center">
<img src="000-Midia_e_Anexos/vlcsnap-2026-01-02-16h57m47s857.jpg" alt="" width="840">
</p>

Neste projeto, o objetivo é desenvolver **Expanding Cards** (cartões expansíveis). A interface inicial apresenta uma série de painéis verticais onde o primeiro cartão, com o título "Explore The World", aparece expandido, destacando-se dos demais que permanecem em um estado retraído. O layout utiliza **Flexbox** para o alinhamento dos componentes, garantindo que as imagens de fundo e os títulos sejam distribuídos de forma harmoniosa.

<p align="center">
<img src="000-Midia_e_Anexos/vlcsnap-2026-01-02-16h57m50s324.jpg" alt="" width="840">
</p>

A funcionalidade principal do projeto baseia-se na interação do usuário: ao clicar em um painel diferente, como o "Wild Forest", o estado do cartão é alterado. Através do **JavaScript**, adicionamos ouvintes de evento (*event listeners*) que alternam a classe CSS para `active`. Essa mudança dispara uma **transição CSS**, resultando em um efeito de expansão suave. Um detalhe importante da implementação é que o título do cartão só se torna visível após a conclusão da expansão total do painel.

