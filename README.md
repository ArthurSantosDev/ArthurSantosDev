<h2 align="center"> 👋 𝑶𝒑𝒂, 𝒄𝒐𝒎𝒐 𝒗𝒂𝒊? 𝑨𝒓𝒕𝒉𝒖𝒓 𝒂𝒒𝒖𝒊 :𝑫 ^^ </h2>
<h3 align="center"> 
💤📿 Apenas mais um ser trilhando o Caminho da Programação :D 📿💤
 </h3>
<h2> 𝑺𝒐𝒃𝒓𝒆 𝒎𝒊𝒎: </h2> 

<p>
 🎂 → 16y
</p>

<p> 
  <strong> 📌 → Front-End </strong>
</p>
<ul>
  <li> HTML / CSS
  <li> Estudando as Linguagens Javascript e Python
</ul>   

<h2> Meus Projetos </h2>

<ul>
  <li> Ainda estou aprendendo, então no momento ainda não tenho nenhum projeto publicado, mas sinta-se livre para dar uma olhada em alguns repositórios :)
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta name="author" content="Arthur Santos">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="icon" sizes="25x25" href="https://freepngimg.com/download/symbol/86331-emoticon-comic-sans-symmetry-undertale-free-download-image.png">

    <style>
        html {
        scroll-behavior: smooth;
    }

    ::-webkit-scrollbar {
        width: 10px;
        background: black; 
    }
  

    ::-webkit-scrollbar-track {
        box-shadow: inset 0 0 5px #474747; 
        border-radius: 10px;
    }

    ::-webkit-scrollbar-thumb {
    background: grey; 
    border-radius: 10px;
    }
    /*Configurações de reset*/
    * {
        margin: 0;
        padding: 0;
        list-style: none;
        color: inherit;
        text-decoration: none;
    }

    body {
        background-color: #000000;
        color: white;
        font-family: Arial;
    }

    header {
        background-image: 
        url('https://cdn130.picsart.com/7382f29d-536b-4256-93f4-cb6736fe75af/387683102030201.png?to=crop&amp;type=webp&amp;r=1456x815&amp;q=85');
        height: 250px;
        background-size: 850px;
    }

    .pfp {
        height: 140px;
        width: 140px;
        border: 6px #000000 solid;
        border-radius: 150px;
        padding: 5px;
        background: #000000;
    }

    .flex-relative {
        position: relative;
        top: 170px;
        display: flex;
        justify-content: center;
    }

    .info {
        position: relative;
        top: 90px;
        display: grid;
        justify-content: center;
    }
    .info h1 {
        font-size: 33px;
        text-align: center;
        font-family: Georgia;
    }

    .buttons {
        margin-bottom: 20px;
    }

    .legenda {
        color: grey;
        text-align: center;
        margin-top: 8px;
        font-size: 20px;
    }
    .desc {
        color: #fff;
        margin-top: 25px;
        color: lightgrey;
    }

    .skills {
        margin-top: 30px;
    }

    .list-item {
        display: inline-block;
        padding: 10px;
        border: 1.9px #fff solid;
        border-radius: 60px;
        margin-left: 5px;
        margin-bottom: 15px;
        text-align: center;
    }

    .item-bottom {
        margin-left: 40px;
    }
    #html {
        color: orange;
    }
    #css {
        color: aqua;
    }
    #js {
        color: yellow;
    }
    #py {
        color: lightblue;
    }

    .social {
        margin-top: 15px;
        display: flex;
        margin: auto;
    }

    .logos {
        height: 50px;
        margin: 3px;
    }

    .discord {
        height: 45px;
    }

    .projects {
        margin-top: 40px;
    }

    .projeto {
        background-image: linear-gradient(to right, #302e2e, grey);
        width: 250px;
        height: 40px;
        font-size: 30px;
        border-radius: 30px;
        text-align: center;
        padding-top: 10px;
        padding-bottom: 10px;
        text-shadow: 1px 1px black;
    }
    .projeto:hover {
        border: 2px solid whitesmoke;
        background-image: linear-gradient(to right, #2b2a2a, #6d6c6c);
        box-shadow: 5px 5px 10px #ffffff65;
        transition: border 0.5s;
    }

    footer {
        padding-bottom: 130px;
    }

    div.copy {
        margin-top: 45px;
    }
    span {
        font-style: italic;
        color: blueviolet;
        font-weight: bold;
    }
    span#span1 {
        color: orange;
        text-transform: uppercase;
    }
    span#span2 {
        color: aqua;
        text-transform: uppercase;
    }

    div.button{
        width: 110px;
    }
    #dark-light {
        background-color:#302e2e;
        border-radius: 20px;
        height: 50px;
        font-size: larger;
        width: 175px;
        position: fixed;
    }
    /*
    main {
        margin: 33%;
        margin-top: 10px;
        background-color: #2c2a2a;
        border-radius: 15px;
        width: 450px;
    }

    @media (max-width: 950px) {
        * {
           font-size: small;
        }
        main {
            width: 400px;
        }
    }
    @media (max-width: 664px) {
        main {
            margin: 15%;
            margin-top: 10px;
        }
    }
    @media (max-width: 500px) {
        main {
            margin: 7%;
            margin-top: 10px;
        }
    }
    */
        </style>

    <title>Perfil - Arthur Santos</title>
</head>
<body class="flex" id="principal">
    <header class="block">
        <div class="button">
            <input 
            type="button" name="mostrar" 
            value="Modo Claro/Escuro" id="dark-light" 
            onclick="MudarTema();">
        </div>
        <div class="flex-relative">
            <img 
            src="http://pm1.narvii.com/8260/caf2e43615b7bd5d679d166b2a51a775062c98b3r1-500-500v2_00.jpg" 
            class="pfp">
        </div>
    </header>
    <main>
        <div class="info">
            <h1>
                Arthur Santos
            </h1>
            <p class="legenda link">
                <a href="https://meu-portfolio-inky.vercel.app/#skills" target="_blank">
                    16 anos, ITB Brasílio Flores de Azevedo
                </a>
            </p>
            <p class="legenda desc">
                Desenvolvedor Front-End iniciante.
            </p>
        </div>
        <div class="info buttons">
            <ul class="skills">
                <li class="list-item">
                    Designer &#x1F3A8
                </li>
                <li class="list-item">
                    Artist &#x1F58B
                </li>
                <li class="list-item">
                    Gamer &#x1F3AE
                </li>
                <li class="list-item">
                    Editor &#x1F3A5
                </li>
                <br>
                <li class="list-item item-bottom" id="html">
                    HTML 5
                </li>
                <li class="list-item" id="css">
                    CSS 3
                </li>
                <li class="list-item" id="js">
                    JavaScript
                </li>
                <li class="list-item" id="py">
                    Python
                </li>
            </ul>
        </div>
        <div class="info social">
            <a href="#">
                <img 
                src="data:image/png;base64,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"
                class="logos">
            </a>
            <a href="#">
                <img
                src="https://www.freepnglogos.com/uploads/spotify-logo-png/image-gallery-spotify-logo-21.png"
                class="logos">
            </a>
            <a href="#">
                <img
                src="https://logodownload.org/wp-content/uploads/2017/11/discord-logo-2-1.png"
                class="logos discord">
            </a>
            <a href="#">
                <img
                src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Twitter-logo.svg/292px-Twitter-logo.svg.png"
                class="logos twitter">
            </a>
            <a href="">
                <img
                src="https://www.freepnglogos.com/uploads/logo-ig-png/logo-ig-stunning-instagram-logo-vector-download-for-new-7.png"
                class="logos">
            </a>
        </div>
        <div class="info projects">
            <ul class="ul-flex">
                <a href="https://meu-portfolio-inky.vercel.app/" target="_blank">
                    <li class="projeto">
                        Meu Portfólio
                    </li>
                </a>
            </ul>
        </div>
    </main>
    <footer>
        <div class="info copy">
            <p>
                Made with <span id="span1">html5</span> and <span id="span2">css3</span>
            </p>
        </div>
    </footer>
    <script charset="UTF-8" defer>
        // JavaScript :>

        let button = document.querySelector('input#dark-light');
        let body = document.querySelector('body#principal');

        function MudarTema() {
            button.style.background = 'grey';
            body.style.background = 'white';
            body.style.color = 'black;';
        }
    </script>
</body>
</html>
