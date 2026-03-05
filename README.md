
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Laboratório Web</title>

<style>

body {
    font-family: Arial, sans-serif;
    background-color: #f0f2f5;
    margin: 0;
}

header {
    background-color: #ffce30;
    color: black;
    padding: 15px;
    text-align: center;
}

main {
    background-color: white;
    max-width: 900px;
    margin: 20px auto;
    padding: 20px;
    border-radius: 10px;
}

/* CARDS */

.card {
    background-color: #ffffc5;
    padding: 15px;
    margin-bottom: 20px;
    border-radius: 8px;
    box-shadow: 0 0 5px rgba(0,0,0,0.2);
}

/* IMAGENS */

img {
    width: 250px;
    border-radius: 8px;
    display: block;
    margin: 10px auto;
}

/* LINKS */

a {
    color: #1f4e79;
    text-decoration: none;
    font-weight: bold;
}

a:hover {
    color: red;
}

/* BOTÃO */

button {
    background-color: #ffce30;
    color: black;
    border: none;
    padding: 10px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #e6b800;
}

/* RODAPÉ */

footer {
    background-color: #ffce30;
    color: black;
    text-align: center;
    padding: 10px;
}

</style>
</head>

<body>

<header>
<h1>Recomendação de jogos</h1>
</header>

<main>

<div class="card">
<h2>Jogos pra passar o tempo!</h2>

</div>




<div class="card">
<h2>Subway Surfes</h2>
<p>
Subway Surfers é um jogo de corrida infinita em que o jogador controla um personagem que está fugindo de um inspetor e seu cachorro após fazer grafite em um trem. O objetivo é correr pelos trilhos do metrô desviando de obstáculos, trens e barreiras enquanto coleta moedas e itens especiais. Durante o jogo, é possível usar power-ups, como jetpack e ímã de moedas, que ajudam a aumentar a pontuação e continuar correndo por mais tempo.
</p>
</div>



<div class="card">

<img src="https://picsum.photos/400/250?1">
</div>




<div class="card">
<h2> Gartic </h2>
<p>
Gartic é um jogo online de desenho e adivinhação que pode ser jogado pelo celular com amigos ou outras pessoas. Em cada rodada, um jogador recebe uma palavra secreta e precisa desenhá-la para que os outros participantes tentem adivinhar o que é. Enquanto os jogadores enviam suas respostas no chat, quem acertar primeiro ganha mais pontos. O jogo continua com vários turnos até que todos tenham desenhado.
</p>
</div>



<div class="card">

<img src="https://picsum.photos/400/250?2">
</div>




<div class="card">
<h2>STOP</h2>
<p>
Stop, também conhecido como Adedonha, é um jogo de palavras que pode ser jogado no celular com várias categorias, como nome, animal, fruta ou cidade. Em cada rodada, uma letra do alfabeto é sorteada, e os jogadores precisam preencher todas as categorias com palavras que comecem com essa letra. Quando alguém termina primeiro, ele aperta o botão “Stop”, e todos os jogadores param de escrever. Depois disso, as respostas são conferidas e os pontos são distribuídos de acordo com as palavras corretas e únicas.
</p>
</div>



<div class="card">

<img src="https://picsum.photos/400/250?3">
</div>


<div class="card">
<h2>Veja um vídeo!</h2>
<button onclick="mostrarMensagem()">Clique aqui</button>
<p id="mensagem"></p>
</div>

</main>


<footer>
Página criada no Laboratório Web
</footer>


<script>
function mostrarMensagem() {
document.getElementById("mensagem").innerHTML =
"Seja como o girassol: busque sempre a luz, mantenha a cabeça erguida e vire as costas para a sombra 🌻";
}
</script>

</body>
</html>
```
