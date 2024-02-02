<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="favicon-men.png" type="image/x-icon">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <title>LigarePoo - entre ou cadastre-se</title>
    <style>
        body {/* Aqui é elaborada a cor de fundo do site. */
            font-family: Arial, Helvetica, sans-serif;
            background-image: linear-gradient(45deg, cyan, yellow);
        }

        div{/* Esta é a estilização de todas as tags presente no site. */
            background-color: rgba(0, 0, 0, 0.9);
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            padding: 80px;
            border-radius: 15px;
            color: white;

        }
        input{/* Este é o comando que vai aumentar e dar estilo aos campos de digitação. */
            padding: 15px;
            border: none;
            outline: none;
            font-size: 15px;

        }
        button{ /* Este é o comando para dar cor aos botões. */
            background-color: dodgerblue;
            border: none;
            padding: 15px;
            width: 100%;
            border-radius: 10px;
            color: white;
            font-size: 15px;
            cursor: pointer;
        }
        button:hover{ /*Este é o comando para deixar o botão esmaecer (Mudar de cor ao passar o mouse por cima.) */
            background-color: deepskyblue;
        }
        
        #container-botoes{ /*esse é o container dos botôes */
            width: 300px;
            display: flex;
            margin-top: 325px;
            justify-content: space-around;
        }
    </style>
</head>
<body> 
    <div1 class="container-aplicativo">
        <div>
            <h1>Login</h1>
            <input type="text" placeholder="Email">
            <br> <br>
            <input type="password" placeholder="Senha">
            <br> <br>
            <button> Enviar</button>
        </div>

        <div id="container-botoes">
            <button id="anterior" class="bi bi-skip-backward-circle-fill"></i></button>
            <button id="play-pause" class="bi bi-play-circle-fill"></i></button>
            <button id="proximo" class="bi bi-skip-forward-circle-fill"></i></button>
        </div>
    </div1>
<script> 
    alert ("Olá Mundo!")
    const botaoPlayPause = document.getElementById('play-pause');
</script>
</body>
</html>
