<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flashcard</title>
</head>
<body>
    
</body>
</html><body>
    <main>
    </main>
    <footer>
        -*/rojeto desenvolvido pela Alura, sem fins lucrativos</p>
    </footer>
<script src="app.js"></script>
<script src="perguntas.js"></script>
</body><main>
        <section id="container">
                <article class="cartao">
                        <div class="cartao__conteudo">
                                <h3>Programação</h3>
                                <div class="cartao__conteudo__pergunta">
                                        O que é JavaScript?
                                </div>
                                <div class="cartao__conteudo__resposta">
                                        O JavaScript é uma linguagem de programação
                                </div>
                        -</div>
                </article>
        </section>
<article class="cartao">
        <div class="cartao__conteudo">
                <h3>Programação</h3>
                <div class="cartao__conteudo__pergunta">
                        O que é CSS?
                </div>
                <div class="cartao__conteudo__resposta">
                        O CSS é uma linguagem de estilização
                </div>
        </div>
</article>
<link rel="stylesheet" href="assets/style.css">
<!-- código omitido -->

<main>
    <section id="container">

<!-- código omitido -->string
body {
    background-color: bisque;
}
footer {
    background-color: black;
    color: white;
    position: fixed;
    bottom: 0;
width: 100%;}
height: 2rem;
 /* código omitido */

#container {
    display: flex
    flex-wrap: wrap;
     justify-content: space-between;
     padding: 4rem;
     gap: 3rem;  
}

.cartao {
    margin: 1rem 1rem;
    background-color: aqua;
    height: 20rem;
    flex-grow: 1;
    flex-basis: calc(33% - 6rem);
}
.cartao__conteudo {text-align: center;
    /*background-color: aquamarine;*/
     height: 100%;
    transform-style: preserve-3d;
    transition: transform 300ms ease-in-out;
}
.cartao__conteudo h3 {
    color: var(--text-color);
    border: 1px solid var(--text-color);
    text-align: left;
    padding: 0.5rem;
    position: absolute;
    margin: 0.6rem;
    border-radius: 0.6rem;
    font-size: 1vw;
    backface-visibility: hidden;
}
.cartao__conteudo__pergunta p {
    color: var(--text-color);
    font-weight: 500;
    backface-visibility: hidden;
}position: absolute;
    height: 100%;
    width: 100%;
}
.cartao__conteudo__resposta p {
    color: var(--card-back-color);
    font-weight: 700;
    backface-visibility: hidden;
    position: absolute;
    height: 100%;
    width: 100%;
 transform: rotateY(180deg);
}
/* código omitido */.cartao__conteudo p {
    margin-top: 1rem;
    padding: 2rem;
    margin-top: 4rem;
}
.cartao.active .cartao__conteudo {
    transform: rotateY(180deg);
}
/* código omitido */

.cartao__conteudo__resposta{
    transform: rotateY(180deg);
    background-color: rdba(0, 244, 191, 0.2);
    border: 4px solid var(--card-back-color);;
}

/* código omitido */
/* código omitido */

.cartao_conteudo_pergunta,
.cartao_conteudo_resposta {
    backface-visibility: hidden;
    position: absolute;
    height: 100%;
    width: 100%;
    box-sizing: border-box;
}

/* código omitido */
/* código omitido */

.cartao__conteudo p {
    margin-top: 1rem;
    padding: 2rem;
    margin-top: 4rem;
    font-size: 1.4vw;
}

/* código omitido */
/* código omitido */

@media (max-width: 560 px) {

    body {
        background: url('img/bd-mobile.webp');
    }
    
    .cartao {
        flex: 1 0 calc(100% - 1rem);
    }
    
    .cartao__conteudo h3 {
        font-size: 3vw;
    }
    
    .cartao__conteudo p {
        font-size: 3.8vw;
    }
}
Cria'Cartão'(
    'Programação',
    'O que é Python?',
    'O Python é uma linguagem de programação'
)

criaCartao(Cria'Cartão'(
    'Programação',
    'O que é Python?',
    'O Python é uma linguagem de programação'
)

criaCartao(
    'Geografia',
    'Qual a capital da França?',
    'A capital da França é Paris'
)

criaCartao(
    'Programação',
    'O que é uma função?',
    'Uma função é um bloco de código que executa alguma tarefa'
)
function criaCartao(categoria, pergunta, resposta) {
  let container = document.getElementById('container')
        let cartao = document.createElement('article')
        cartao.className = 'cartao'
    console.log(categoria, pergunta, resposta)
}
    'Geografia',
    'Qual a capital da França?',
    'A capital da França é Paris'
)

criaCartao(
    'Programação',
    'O que é uma função?',
    'Uma função é um bloco de código que executa alguma tarefa'
)
function criaCartao(categoria, pergunta, resposta) {
  let container = document.getElementById('container')
        let cartao = document.createElement('article')
        cartao.className = 'cartao'
    console.log(categoria, pergunta, resposta)
}
let respostaEstaVisivel = false
let respostaEstaVisivel = true
.cartao.active .cartao__conteudo {
    transform: rotateY(180deg);
}
function viraCartao() {
    respostaEstaVisivel = !respostaEstaVisivel
    cartao.classList.toggle('active', respostaEstaVisivel)
}string
cartao.addEventListener('click', viraCartao)
