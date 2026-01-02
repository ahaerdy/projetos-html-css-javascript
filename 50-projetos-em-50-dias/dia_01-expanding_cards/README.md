Dia 01 - Expanding Cards

## Vídeo 01 - Project Intro

<video width="60%" controls>
  <source src="000-Midia_e_Anexos/005.Project.Intro.mp4" type="video/mp4">
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

## Vídeo 02 - 

<video width="60%" controls>
  <source src="000-Midia_e_Anexos/006.Initial.Cards.mp4" type="video/mp4">
    Seu navegador não suporta vídeo HTML5.
</video>

### Anotações

<p align="center">
<img src="000-Midia_e_Anexos/vlcsnap-2026-01-02-16h31m47s960.jpg" alt="" width="840">
</p>

A estrutura inicial do projeto é definida através do HTML, estabelecendo a base para os cartões expansíveis. O documento utiliza um contêiner principal para agrupar cinco elementos `div` com a classe `panel`. O primeiro painel recebe adicionalmente a classe `active`, que servirá para identificar qual cartão deve aparecer expandido por padrão.

Cada painel possui um título `h3` e utiliza estilos inline para definir a `background-image` com URLs provenientes do Unsplash. Ao final do corpo do documento, é feita a chamada para o arquivo de scripts que gerenciará a interatividade.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Expanding Cards</title>
</head>
<body>
    <div class="container">
        <div class="panel active" style="background-image: url('https://images.unsplash.com/photo-1558981806-ec527fa84c39?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80')">
            <h3>Explore The World</h3>
        </div>
        <div class="panel" style="background-image: url('https://images.unsplash.com/photo-1572276596237-5db2c3e16c5d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80')">
            <h3>Wild Forest</h3>
        </div>
        <div class="panel" style="background-image: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80')">
            <h3>Sunny Beach</h3>
        </div>
        <div class="panel" style="background-image: url('https://images.unsplash.com/photo-1551009175-8a68da93d5f9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80')">
            <h3>City on Winter</h3>
        </div>
        <div class="panel" style="background-image: url('https://images.uns      
