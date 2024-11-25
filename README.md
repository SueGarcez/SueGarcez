<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Mordor</title>
</head>
  <style>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Cinzel', serif; 
    background-color: #1a1a1a; 
    color: #e0e0e0; 
    line-height: 1.6;
}

/* Navbar */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
    background-color: #2c2c2c; 
    border-bottom: 2px solid #444;
}

.navbar .logo h1 {
    font-size: 2.5rem;
    color: #e63946; 
    text-shadow: 2px 2px 4px #000; 
}

.navbar .menu a {
    text-decoration: none;
    color: #f5f5f5;
    margin: 0 15px;
    font-size: 1.1rem;
    transition: color 0.3s ease;
}

.navbar .menu a:hover {
    color: #e63946; 
}

#botao {
    background-color: #e63946;
    color: #fff;
    padding: 5px 10px;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

#botao:hover {
    background-color: #ff4f5a; 
}

/* Cabeçalho */
header {
    background: url('https://www.reddit.com/media?url=https%3A%2F%2Fi.redd.it%2Fthe-two-towers-vs-return-of-the-king-mordor-v0-b352b0r01tyb1.jpg%3Fwidth%3D3816%26format%3Dpjpg%26auto%3Dwebp%26s%3Dc3f5494c21e1ccfc774b3bb8649fcfc8a2670ea3&rdt=41488') no-repeat center center/cover; 
    text-align: center;
    padding: 50px 20px;
    color: #fff;
}

header .linha-cabecalho h2 {
    font-size: 2.2rem;
    margin: 10px 0;
    text-shadow: 2px 2px 6px #000;
}

header .linha-cabecalho p {
    margin: 20px 0;
    max-width: 700px;
    margin-left: auto;
    margin-right: auto;
}

header .linha-cabecalho a {
    display: inline-block;
    padding: 10px 20px;
    background-color: #e63946;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 20px;
    transition: background-color 0.3s ease;
}

header .linha-cabecalho a:hover {
    background-color: #ff4f5a;
}

  </style>
<body>
    <nav class="navbar">
        <div class="logo">
            <h1>Mordor</h1>
        </div>
        <div class="menu">
            <a href="">Home</a>
            <a href="">Sobre os livros</a>
            <a href="">Sobre o Local</a>
            <a id="botao" href="">Faça seu comentário</a>
        </div>
    </nav>
    <header>
        <div class="linha-cabecalho">
            <h2>O melhor lugar para um vilão morar</h2>
            <h2>Mordor</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla, quo accusantium dignissimos eveniet possimus architecto. Nobis accusantium aperiam reprehenderit velit, quam excepturi nihil molestias. Debitis voluptatibus labore itaque sed vitae!</p>
            <a href="">Conheça no mapa</a>
        </div>
    </header>
</body>
</html>
