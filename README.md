<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dr. Alexandre Cesár</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #008080;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #004c4c;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #006666;
        }
        .container {
            padding: 20px;
        }
        .home, .sobre, .projetos, .contato {
            margin-bottom: 40px;
        }
        .home h1 {
            font-size: 2em;
            margin-bottom: 20px;
        }
        .home p {
            font-size: 1.2em;
        }
        .projetos img {
            width: 100%;
            max-width: 600px;
            height: auto;
        }
        footer {
            background-color: #004c4c;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Dr. Alexandre Cesár</h1>
        <p>Médico por vocação e altruísta por convicção.</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#sobre">Sobre Mim</a>
        <a href="#projetos">Projetos</a>
        <a href="#contato">Contato</a>
    </nav>
    <div class="container">
        <section id="home" class="home">
            <h1>Bem-vindo ao meu Portfólio</h1>
            <p>Eu sou Dr. Alexandre Cesár, diretor do Complexo Hospitalar de Mangabeira, com uma longa trajetória na medicina e uma paixão pelo cuidado com o próximo.</p>
        </section>
        <section id="sobre" class="sobre">
            <h2>Sobre Mim</h2>
            <p><strong>Formação:</strong> Médico formado pela UFPB.</p>
            <p><strong>Experiência:</strong></p>
            <ul>
                <li>Clínica Médica HUNE</li>
                <li>Diretor Geral do Complexo Hospitalar de Mangabeira</li>
                <li>Preceptor de UE/ Medicina Intensiva</li>
            </ul>
        </section>
        <section id="projetos" class="projetos">
            <h2>Projetos</h2>
            <p>Aqui estão alguns dos projetos e realizações que lidero no Complexo Hospitalar.</p>
            <img src="sua-imagem.jpg" alt="Imagem de Projeto">
        </section>
        <section id="contato" class="contato">
            <h2>Contato</h2>
            <p>Entre em contato comigo através das redes sociais:</p>
            <p><a href="https://www.instagram.com/alexandrecesarcl/" target="_blank">Instagram</a></p>
            <p><a href="https://www.facebook.com/alexandre.cesar.18/" target="_blank">Facebook</a></p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Dr. Alexandre Cesár. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
