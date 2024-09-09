<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>site de Suplementos</title>
 
 <style> 
  h1{color: blue;text-align: center;}
  h2{color: blue;text-align: center;}
  h3{color: blue;text-align: center;}
  
  body{background-color: rgb(180, 89, 223); font-family: cursive;}
  li{color: brown;}
  a{color: brown;}
 
  </style>
  </head>

<body>
    <header>
        <h1>Bacana</h1>
        <h2>Bacana</h2>
        <h3>Bacana</h3>
    </header>

    <main>
        <img src="Sonic.jpg" alt="sonic" width="120" height="120">
        <label>bacana</label>
        <textarea aria label="bacana" aria-pressed="true">bacana</textarea>
        <button aria label="botão" aria-pressed="true">Botão</button>
        <img src="Sonic.jpg" alt="sonic" width="120" height="120">

        <ol> lista ordenada
            <p></p>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
            <li>Item 4</li>
        </ol>

        <ul>lista desordenada
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
            <li>Item 4</li>
        </ul>

        <div>
            <ul>
                <li><a href="home">Home</a></li>
                <li><a href="servicos">Serviços</a></li>
                <li><a href="contato">Contato</a></li>
            </ul>
        </div>

        <nav role='navigation' aria-label='Menu principal'>
            <ul>
                <li><a href='index.html'>Página inicial</a></li>
                <li><a href='noticias.html'>Notícias</a></li>
                <li><a href='eventos.html'>Eventos</a></li>
                <li><a href='acessibilidade-web.html'>Acessibilidade Web</a>
                    <p><a href='class=' expandir>Expandir menu Acessibilidade Web</a></p>
                    <ul role='menu'>
                        <li role="menuitem"><a href="projetos.html">Projetos acessibilidade web</a></li>
                        <li role="menuitem"><a href="noticias.html">Notícias acessibilidade web</a></li>
                        <li role="menuitem"><a href="dicas.html">Dicas acessibilidade web</a></li>
                        <li role="menuitem"><a href="manuais.html">Manuais acessibilidade web</a></li>
                    </ul>
                </li>
            </ul>
        </nav>
        <hr>
        <!---hr é para colocar linha-->
        <img src="dancing-dog-2.gif" alt="dancing-dog-2" width="180" height="180">

        <a href=”caramelo.html” target=_blank>Caramelo</a>
        <br><br>
        <label>Loading:</label><progress value="77" max="100"><progress></progress></progress>
        <br>
        <label>Nome: Davi</label>
        <br>
        <label>Idade: 16 Anos</label>
        <br>
        <img src="indo ali.jpg" alt="Smurf indo ali" width="200" height="200">
        <br>

        <!--BR É PRA PULAR LINHA-->



        <cite>CAPS</cite>

        <blockquote>Aprender é Bacana</blockquote>


        <p>

            Meu time favorito é <ins>rayo vallecano</ins>
        </p>
        Time que não gosto é <del>iguaçu</del>



        <p></p>
        <p></p>


        <bdo dir=rtl>Ele é um cara bacana</bdo>
        <p></p>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/9C7HrtPM8J0" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen></iframe>

        <iframe width="560" height="315" src="https://www.youtube.com/embed/UPY13nR_7x8" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen></iframe>

        <iframe width="560" height="315" src="https://www.youtube.com/embed/kIXdKiWwHFo" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen></iframe>
            
        <iframe width="560" height="315" src="https://www.youtube.com/embed/niQLBYrGJaA" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen></iframe>
        
        <iframe width="560" height="315" src="https://www.youtube.com/embed/EEvopkbc4FE" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen></iframe>
        <br>
        ingressos <del>esgotados</del>
        e <u>disponiveis</u>


        <kbd>Senhor dos anéis</kbd>

        <p></p>
        <code>Senhor dos anéis</code>
        <P></P>
        <samp>Senhor dos anéis</samp>
        <p></p>
        <pre>Senhor dos anéis</pre>


        <dl>lista
            <dt> Whey</dt> <!--anTes-->
            <dd> Leite animal</dd><!--Depois-->
            <dd> Morango</dd>
            <dd> leite vegano</dd>
            <dt> Soja</dt>
        </dl>
        <br>
        <form>
            <label>HOMEM</label>
            <input type="man"><br>
            <input type="submit" value="ENVIAR">
        </form>
        <details> (Amigo você é um Amigo)

            <br>
            <form>
                <label>HOMEM</label>
                <input type="man"><br>
                <input type="submit" value="ENVIAR">
            </form>
        </details>
        <q>(na volta a gente compra!)</q>
        <br>
        <br>
        <select>
            <optgroup label="Carros europeus">
                <option>Toyota supra</option>
                <option>Porshe</option>
                <option>BMW</option>
            </optgroup>
        </select>
        <br>
        <br>
        <sup>Vai neymar</sup>
        <sub >Vai neymar</sub>

    </main>

    <footer>
        <address>
            escrito por Davi<br>
        </address>
    </footer>
</body>


</html>
