# exercicio_css
# exercicio_css
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu portal de notícias</title>
    <style>
        h1 {
            color: rgb(0, 0, 0);
        }
    </style>
    <link rel="stylesheet" href="./main.css" />
</head>
<body>
    <header>
        <div class = "container"></div>
            <h1>Meu portal de notícias</h1>
        <nav>
            <ul>
                <li>
                    <a href="#Sports" title="Ir para a seção de esportes">Esportes</a>
                </li>
                <li>
                    <a href="#Economy" title="Ir para a seção de notícias">Economia</a>
                </li>
                <li>
                    <a href="#Entertainment" title="Ir para a seção de entreterimento">Entreterimento</a>
                </li>
                <li>
                    <a href="#Art" title="Ir para a seção de arte">Arte</a>
                </li>
            </ul>
        </nav>
            </div>
        </header>
    
        <section id="sports">
        <div class="container">
        <h2>Esportes</h2>
        <div class="articles">
            <article>
                <img src="./imagens/futebol.jpg" alt="Bola de futebol no gramado" />
                <header>
                    <time class="creation-date">13/07/2022 às 12:35</time>
                </header>
                <h3>Grande clássico na noite de hoje</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur consequuntur doloremque totam labore architecto. Corporis adipisci optio placeat quibusdam totam iure veritatis quam, ullam tenetur error? Laborum, modi itaque. Sunt.
                </p>
                <a href="#" title="Leia a notícia completa">Ler mais</a>
            </article>
            <article>
                <img src="./imagens/futebol-americano.jpg" alt="Jogador de futebol americano correndo com a bola na mão" />
                <header>
                    <time>13/07/2022 às 12:35</time>
                </header>
                <h3>Noite do Superbowl</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur consequuntur doloremque totam labore architecto. Corporis adipisci optio placeat quibusdam totam iure veritatis quam, ullam tenetur error? Laborum, modi itaque. Sunt.
                </p>
                <a href="#" title="Leia a notícia completa">Ler mais</a>
            </article>
            <article>
                <img src="./imagens/basquete.jpg" title="Vista aérea de uma quadra de basquete" />
                <header>
                    <time>13/07/2022 às 12:35</time>
                </header>
                <h3>Notícia sobre a NBA</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur consequuntur doloremque totam labore architecto. Corporis adipisci optio placeat quibusdam totam iure veritatis quam, ullam tenetur error? Laborum, modi itaque. Sunt.
                </p>
                <a href="#" title="Leia a notícia completa">Ler mais</a>
            </article>
            <article>
                <img src="./imagens/basquete.jpg" title="Vista aérea de uma quadra de basquete" />
                <header>
                    <time>13/07/2022 às 12:35</time>
                </header>
                <h3>Notícia sobre a NBA</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur consequuntur doloremque totam labore architecto. Corporis adipisci optio placeat quibusdam totam iure veritatis quam, ullam tenetur error? Laborum, modi itaque. Sunt.
                </p>
                <a href="#" title="Leia a notícia completa">Ler mais</a>
            </article>
        </div>
    </div>
    
    </section>
    <section id="economy">
        <div class="container">
            <h2>Economia</h2>
            <div class="articles">
                <article>
                    <img src="./imagens/dolares.jpg" alt="Muitos dólares" />
                    <header>
                        <time>13/07/2022 às 12:35</time>
                    </header>
                    <h3>Dólar em alta de 0.50%</h3>
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur consequuntur doloremque totam labore architecto. Corporis adipisci optio placeat quibusdam totam iure veritatis quam, ullam tenetur error? Laborum, modi itaque. Sunt.
                    </p>
                    <a href="#" title="Leia a notícia completa">Ler mais</a>
                </article>
                <article>
                    <img src="./imagens/euro.jpg" alt="Várias notas de euro" />
                    <header>
                        <time>13/07/2022 às 12:35</time>
                    </header>
                    <h3>Euro em queda de 0.40%</h3>
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur consequuntur doloremque totam labore architecto. Corporis adipisci optio placeat quibusdam totam iure veritatis quam, ullam tenetur error? Laborum, modi itaque. Sunt.
                    </p>
                    <a href="#" title="Leia a notícia completa">Ler mais</a>
                </article>
                <article>
                    <img src="./imagens/petroleo.jpg" alt="Extração de petróleo" />
                    <header>
                        <time>13/07/2022 às 12:35</time>
                    </header>
                    <h3>Alta no preço do barril do petróleo</h3>
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur consequuntur doloremque totam labore architecto. Corporis adipisci optio placeat quibusdam totam iure veritatis quam, ullam tenetur error? Laborum, modi itaque. Sunt.
                    </p>
                    <a href="#" title="Leia a notícia completa">Ler mais</a>
                </article>
            </div>
        </div>
    </section>

    <section id="entertainment">
        <div class="container">
        <h2>Entreterimento</h2>
        <div class="articles">
            <article>
                <img src="./imagens/entreterimento.jpg" alt="Cinema" />
                <header>
                    <time class="creation-date">13/07/2022 às 12:35</time>
                </header>
                <h3>O que é entreterimento?</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur consequuntur doloremque totam labore architecto. Corporis adipisci optio placeat quibusdam totam iure veritatis quam, ullam tenetur error? Laborum, modi itaque. Sunt.
                </p>
                <a href="#" title="Leia a notícia completa">Ler mais</a>
            </article>
            <article>
                <img src="./imagens/entreterimento-arlivre.jpg" alt=" ao ar livre" />
                <header>
                    <time>13/07/2022 às 12:35</time>
                </header>
                <h3>Lazer ao ar livre</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur consequuntur doloremque totam labore architecto. Corporis adipisci optio placeat quibusdam totam iure veritatis quam, ullam tenetur error? Laborum, modi itaque. Sunt.
                </p>
                <a href="#" title="Leia a notícia completa">Ler mais</a>
            </article>
            
            <article>
                <img src="./imagens/parque.jpg" alt="Roda gigante" />
                <header>
                    <time>13/07/2022 às 12:35</time>
                </header>
                <h3>Parque de diversões</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur consequuntur doloremque totam labore architecto. Corporis adipisci optio placeat quibusdam totam iure veritatis quam, ullam tenetur error? Laborum, modi itaque. Sunt.
                </p>
                <a href="#" title="Leia a notícia completa">Ler mais</a>
            </article>
        </div>
    </div>

    <section id="art">
        <div class="container">
        <h2>Arte</h2>
        <div class="articles">
            <article>
                <img src="./imagens/arte.jpg" alt="Museu" />
                <header>
                    <time class="creation-date">13/07/2022 às 12:35</time>
                </header>
                <h3>Arte, arquitetura e muito mais</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur consequuntur doloremque totam labore architecto. Corporis adipisci optio placeat quibusdam totam iure veritatis quam, ullam tenetur error? Laborum, modi itaque. Sunt.
                </p>
                <a href="#" title="Leia a notícia completa">Ler mais</a>
            </article>
            
            <article>
                <img src="./imagens/show.jpg" alt=" música" />
                <header>
                    <time>13/07/2022 às 12:35</time>
                </header>
                <h3>Música também é arte!!!</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur consequuntur doloremque totam labore architecto. Corporis adipisci optio placeat quibusdam totam iure veritatis quam, ullam tenetur error? Laborum, modi itaque. Sunt.
                </p>
                <a href="#" title="Leia a notícia completa">Ler mais</a>
            </article>
            
            <article>
                <img src="./imagens/teatro.jpg" alt="teatro" />
                <header>
                    <time>13/07/2022 às 12:35</time>
                </header>
                <h3>Teatro, palco de diversas expressões artísticas!</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur consequuntur doloremque totam labore architecto. Corporis adipisci optio placeat quibusdam totam iure veritatis quam, ullam tenetur error? Laborum, modi itaque. Sunt.
                </p>
                <a href="#" title="Leia a notícia completa">Ler mais</a>
            </article>
        </div>
    </div>
</body>
</html>