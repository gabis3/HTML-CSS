# HTML
Lembretes e comandos HTML CSS

<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Gabriella Sousa</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <h1 title="eu apareço se vc passar o mouse por cima do texto" id="titulo">Eu sou o titulo principal</h1>
       
        <h2>Eu sou o subtitulo e assim por diante :p</h2>

        <div title="eu apareço se vc passar o mouse por cima do texto">
            Eu sou um bloco de conteudo diverso ;D la la la la la la la la la la la la la la la la la la la la la la la la la la la la 
        </div>

        <!--Posso escrever comentarios aqui-->
        <hr> <!--Esse cria uma linha horizontal na tela-->

        <p>Eu sou um paragrafo, beijo. 
            <br>e eu pulo pra linha de baixo
        </p>
        <p>Nesse paragrafo a linha pode ser quebrada caso for preciso. <wbr>Nesse paragrafo a linha pode ser quebrada caso for preciso. 
        <wbr>Nesse paragrafo a linha pode ser quebrada caso for preciso. <wbr> Nesse paragrafo a linha pode ser quebrada caso for preciso. 
        <wbr>Nesse paragrafo a linha pode ser quebrada caso for preciso. <wbr>Nesse paragrafo a linha pode ser quebrada caso for preciso. </p>
        
        <q>sou uma citação</q> 

        <div><strong>eu fico em negrito</strong></div>

        <div><em>Eu sou o italico, gatinha</em></div>

        <div><ins>Hii, eu sublinho</ins></div>

        <div><del>Eu não quero mais estar aqui</del></div>

        <div>UuUuU<sup>eu levito haha</sup></div>

        <div><sub>Eu sou rebaixado</sub>H<sub>2</sub>O</div>

        <div><mark>sou um marca texto</mark></div>

        <p>Aqui conseguimos colocar códigos <code>&lt;html&gt;&lt;/html&gt;</code></p>
    <!--podemos escrever varios elementos com o &(complemento);-->        
        
        <time datetime="22h40m">aqui fala pro compo que são 22h40min</time>
        <p>
        <ruby>
            愛してます
            <rt>Aishitemasu</rt>
        </ruby> 
        (te amo) </p>

        <span class="uu" title="oiu">eu sou o span, eu me limito ao espaço que o texto ocupa (o div não) <wbr>euuuuuu</span>
        <div class="oi">olaaaaaa</div>

        <ul>
            <li>item não ordenado</li>
        </ul>
        <ol>
            <li>item ordenado</li>
        </ol>
        <li>item sem espaçamento inicial</li>
        <p></p>
        <input type="text" value="você pode escrever aqui"> <br>
        <input type="text" readonly value="aqui não">
            <input type="text" disabled value="desabilitado"><br>
        <input type="number" value="0"><br>
        <input type="time"><br>
        <input type="checkbox"> <span>eu mudo de cor</span> <br>
        <input type="date">
        <hr>
        <p></p>
        
        <p><a href="pp.jpg" 
            target="_blank"
            rel="noreferrer noopener">foto</a></p>
        <a href="#titulo">
            <b>volte para o topo</b></a>

        <footer>  
        </footer>
    </body>
</html>


# CSS

/*comentario*/

body { background-color: rgb(236, 236, 236);}

 .uu, .oi {
     background-color: white;
     border: 1px solid red;
 }

 input[readonly] {
     width: 60px;
     color: red;
 }

 input:disabled {
     width: 80px;
 }

 a:active[href*="pp" i], div:active {
     color: rgb(43, 226, 76);
 }

 input:checked + span {
     color: coral;
 }

 input:hover, p:hover {
     color: rgb(214, 131, 255);
 }

