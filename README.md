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
            padding: 0;
        }

        header {
            background-color: #ffce30;
            color: black;
            padding: 15px;
            text-align: center;
        }

        main {
            padding: 20px;
        }

        .card {
            background-color: #ffffc5; /* cor alterada aqui */
            padding: 15px;
            margin-bottom: 15px;
            border-radius: 8px;
            box-shadow: 0 0 5px rgba(0,0,0,0.2);
        }

        img {
            width: 200px;
            border-radius: 8px;
        }

        a {
            color: #1f4e79;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            color: red;
        }

        button {
            background-color: #ffce30;
            color: black;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #ffce30;
        }

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
    <h1>Laboratório Web</h1>
    <p>Exemplo de página com HTML e CSS</p>
</header>

<main>
    <div class="card">
        <h2>Sobre o aluno</h2>
        <p>Nome: Isabelle Vitorya e Reis </p>
        <p>Turma: 301</p>
        <p>Data: 25 / 02 / 26 </p>
    </div>

  <div class="card">
        <h2>Conteúdos aprendidos no ano!</h2>
        <ul>
            <li>Estrutura de páginas web</li>
            <li>Criação de sites</li>
            <li>Uso de imagens e links</li>
            <li>Estilização com CSS</li>
        </ul>
    </div>

  <div class="card">
        <h2>Imagem aleatória!</h2>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTf_URvpU0_-_Uvx-02s2mfRMiiPb_aAaxbaQ&s">
    </div>

   <div class="card">
        <h2>Vídeo ilustrativo!</h2>
        <p>
            <a href="https://www.youtube.com/shorts/XavMa9bZDHI" target="_blank">
                Abrir o vídeo!
            </a>
        </p>
    </div>

<div class="card">
        <h2>Surpresa!</h2>
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
        "Van Gogh : O girassol é uma promessa de felicidade.";
    }
</script>

</body>
</html>
