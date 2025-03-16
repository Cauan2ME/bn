<section id="tropicalia" class="my-5 pt-6 secao-tropicalia">
        <div class="container d-flex align-items-center">
                <div class="col-5">
                        <h2>O que foi a Tropicália?</h2>
                        <p class="p-2">A Tropicália, também conhecida como Tropicalismo, foi um movimento cultural
                                brasileiro que surgiu na década de 1960, tendo seu auge entre 1967 e 1968. Esse movimento
                                abrangeu várias expressões artísticas, como a música, o cinema, o teatro e as artes plásticas, e
                                teve como principal característica a mistura de elementos da cultura brasileira tradicional com
                                influências estrangeiras, especialmente do rock e da música pop. Fonte: Site Toda Matéria</p>
                </div>
        </div>
</section>
<section id="inicio" class="my-5">
    <div class="inicio-fundo d-flex justify-content-between align-items-center">
            <div class="esquerda-conteudo">
                    <h1 class="display-4 text-white fst-italic fw-bold">Boas-vindas a</h1>
                    <img src="img/logo-2.png" class="mb-3" width="563"
                            height="278" loading="lazy">
                    <a href="#tropicalia"
                            class="btn btn-primary btn-lg botao-inicio fw-semibold">Quero conhecer!</a>
            </div>
            <img src="img/lossy-page1-640px-Os_Mutantes.tif (1).png" class="img-fluid img-inicio">
        </div>
</section><section id="tropicalia" class="my-5 pt-6 secao-tropicalia">
    <div class="container d-flex align-items-center">
            <div class="col-4 d-flex justify-content-center">
                    <img src="img/image (1).png" class="rounded-pill" alt="" width="273" height="331" loading="lazy">
            </div>
            <div class="col-5">
                    <h2>O que foi a Tropicália?</h2>
                    <p class="p-2">A Tropicália, também conhecida como Tropicalismo, foi um movimento cultural
                            brasileiro que surgiu na década de 1960, tendo seu auge entre 1967 e 1968. Esse movimento
                            abrangeu várias expressões artísticas, como a música, o cinema, o teatro e as artes plásticas, e
                            teve como principal característica a mistura de elementos da cultura brasileira tradicional com
                            influências estrangeiras, especialmente do rock e da música pop. Fonte: Site Toda Matéria</p>
            </div>
    </div>
</section>

<section id="galeria">
    <h2 class="text-center pt-5">Galeria</h2>
    <div class="container p-3 mt-3 fundo-galeria">

            <div class="row justify-content-md-center">
                    <div class="col-md-4">
                            <img src="img/lossy-page1-640px-Jorge_Ben_e_o_Trio_Mocotó_no_Teatro_da_Lagoa,_1971.tif.jpg"
                                    class="img-fluid rounded-5" loading="lazy">
                    </div>
                    <div class="col-md-4">
                            <img src="img/lossy-page1-640px-Os_Mutantes_2.tif.jpg" class="img-fluid rounded-5"
                                    loading="lazy">
                    </div>
            </div>
            <div class="row mt-4 justify-content-md-center">
                    <div class="col-md-4">
                            <img src="img/lossy-page1-640px-Gilberto_Gil_nos_anos_1960.tif.jpg" class="img-fluid rounded-5" loading="lazy">
                    </div>
                    <div class="col-md-4">
                            <img src="img/lossy-page1-640px-Caetano_Veloso_no_III_Festival_da_Música_Popular.tif.jpg"
                                    class="img-fluid rounded-5" loading="lazy">
                    </div>
            </div>
     </div>
</section><section id="inicio" class="my-5">
    <div class="inicio-fundo d-flex justify-content-between align-items-center">
            <div class="esquerda-conteudo">
                    <h1 class="display-4 text-white fst-italic fw-bold">Boas-vindas a</h1>
                    <img src="img/logo-2.png" class="mb-3" width="563" height="278" loading="lazy">
                    <a href="#tropicalia" class="btn btn-primary btn-lg botao-inicio fw-semibold">Quero conhecer!</a>
            </div>
            <img src="img/lossy-page1-640px-Os_Mutantes.tif (1).png" alt="A imagem apresenta o grupo musical Os Mutantes. São três pessoas cantando em dois microfones" title="Os Mutantes - CC0 Domínio Público / Acervo Arquivo Nacional" class="img-fluid img-inicio">
    </div>
</section>//Código omitido

<body>
    <header class=" p-5">
        
        <nav class="container d-flex justify-content-between align-items-center" >
            <img src="img/logo.png" class="nav-img" loading="lazy">
            <ul class="nav mt-5">
                <li class="nav-item"><a class="nav-link" href="#inicio">Início</a></li>
                <li class="nav-item"><a class="nav-link" href="#galeria">Galeria</a></li>
                <li class="nav-item"><a class="nav-link" href="#contato">Contato</a></li>
            </ul>
                <div id="acessibilidade">
                    <button id="aumentar-fonte" class="btn btn-primary fw-bold">A+</button>
                    <button id="diminuir-fonte" class="btn btn-primary fw-bold">A-</button>
                </div>
        </nav>
</header>

//Código omitidodocument.addEventListener('DOMContentLoaded', function(){
    const aumentaFonteBotao = document.getElementById('aumentar-fonte');

    let tamanhoAtualFonte = 1;
    aumentaFonteBotao.addEventListener('click', function(){
        tamanhoAtualFonte += 0.1;
        document.body.style.fontSize = `${tamanhoAtualFonte}rem`;

    });
});//Código omitido

<script src="script.js"></script>

//Código omitidodocument.addEventListener('DOMContentLoaded', function(){
    const aumentaFonteBotao = document.getElementById('aumentar-fonte');
    const diminuiFonteBotao = document.getElementById('diminuir-fonte');

    let tamanhoAtualFonte = 1;
    aumentaFonteBotao.addEventListener('click', function(){
        tamanhoAtualFonte += 0.1;
        document.body.style.fontSize = `${tamanhoAtualFonte}rem`;

    });

    diminuiFonteBotao.addEventListener('click', function(){
        tamanhoAtualFonte -= 0.1;
        document.body.style.fontSize = `${tamanhoAtualFonte}rem`;

    });

});<button id="botao-acessibilidade" class="btn btn-primary fw-bold">acessibilidade</button> <div id="acessibilidade">
  <button id="botao-acessibilidade" class="btn btn-primary fw-bold">acessibilidade</button>
  <div id="opcoes-acessibilidade">
    <button id="aumentar-fonte" class="btn btn-primary fw-bold">A+</button>
    <button id="diminuir-fonte" class="btn btn-primary fw-bold">A-</button>
  </div>
</div><div id="acessibilidade" class="menu-acessibilidade">
  <button id="botao-acessibilidade" class="btn btn-primary fw-bold rotacao-botao">acessibilidade</button>
  <div id="opcoes-acessibilidade" class="opcoes-acessibilidade apresenta-lista">
    <button id="aumentar-fonte" class="btn btn-primary fw-bold">A+</button>
    <button id="diminuir-fonte" class="btn btn-primary fw-bold">A-</button>
  </div>
</div>.menu-acessibilidade{
    position: fixed;
    top:2rem;
    right:20px;
    z-index: 1000;
}   .rotacao-botao{ 
      transform: rotate(-90deg);
      transform-origin: right center;
}.opcoes-acessibilidade{
    margin-top:10px;
    display: flex;
    flex-direction: column;
}.opcoes-acessibilidade button{
    margin-bottom: 5px;
}const botaoDeAcessibilidade = document.getElementById('botao-acessibilidade')
const opcoesDeAcessibilidade = document.getElementById('opcoes-acessibilidade')botaoDeAcessibilidade.addEventListener('click', function (){
 botaoDeAcessibilidade.classList.toggle('rotacao-botao');
 opcoesDeAcessibilidade.classList.toggle('apresenta-lista')
})
