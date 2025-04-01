# projeto-esportes-
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <title>homem aranha</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.3/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-icons/1.11.3/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header class=" p-5">

        <nav class="container d-flex justify-content-between align-items-center" >
            <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAt1BMVEX///8AAAD/9vMdHRv6+vqwsLCNjYzg4OBHR0bo6Ojz8/P39/fs7OwaGhgYGBYMDAioqKjW1tbOzs7FxcV8fHx2dnWYmJfb29sGBgA2NjXj4+NqamrBwcGEhINXV1bS0tFCQkHqnZ5RUVBhYWCJiYmgoKAvLy64uLglJSOVlZVeXl6srKv7yMlpaWk7Ozrwvb3wrK0LGhgLFBFbJyaKOTl0CAqVTU343t8pNDKlP0CQCw6cKiv77+81cRyEAAAJU0lEQVR4nO2bC5eqRhLHqRVE3jSoKKIYR8XRqzf7yD6y+/0/11Y1DbSPuclNZsKYU79zZuRZ9p+urqoGNAyGYRiGYRiGYRiGYRiGYRiGYRiGYRiGYRiGYRiGYRiGYRiGYRiGYRiGYRiGYRiGYRjmNyD6bsBHI+y+W/DRjPtuwEfjTvpuwUezs/puwUcT5s1SMY39PlvyQeSgFpwDINNeG/Mh7A5qIQwHCFS9tuYjWL/UnxaQwEF4+Pbhz4cJE1cuLGdS4QDMnlv03iQw9avd0LK3kVLYd4vemx3s6ENMV7WXRi99t+i9maDC2k3PJDGEY5z8uVLGGhWSIlQ5xGQxqpZ7/FiPT4nbd9PeCYChIRzbkSt5rUqcJjI3braW8Pps3LsA0YT6sBSiLDLD6ARl1nJEMuE4rLIeG/h78SDcUMdRH/pemVRp4mvd5qS7CXktHBa71Omrkb8LDwbQKKQ/XM6qNE0TvTtz1LkmneulJZ4tXZqosMBeQ0f1XNWVtD1LUuxOVx+Frqhez9ih0Xn3VFEIFVqGn5SiTM1anXRGh7rTTLAzpXNqHUdCF5f9+WnmXPsgOtfK8ixJqsSRy75Zf9CfkyRlmksH1rt0ueylvd/POaJKtOk7H8eclaYi77pTdqHniaTMbNrWdOfYSnpq8neyQzfddR1W/3kYbCwsbXSVtFzatp2ZsgZKLWPRX6u/BwGDIHRSUSaiE0n/fCNLKxyFNypRtp+5rnF2jE2f7f4OwmAgi2/XTSgbulKhU8ca9MgsTZIkNVqVSqh58LPtkyTIV+xEUGEUw6egbChqT2y6zrAzIdLMpOShthUTw62KPtv96/FxSkHhlCSpEtwQKWZDYTYOSgumi0HItnO73nauDD/b9dnuX02JUwqc9o7JG2W9ppT6hlfiMCxtw9AiLXqt42d4HPhG6n+qfCGKR5O+ckx3g4MQJdKzi4wyH8ZKUtl0J47CsvBbleqjGBXCNz7XrWR/GM0XrxamOh/JRXrajiCiEGJk2IkB5JTqJuEmK9FFZb1molaP0p/v0zDMjU7o2HJR/+dSiIihnCa0bJpIUUmJOEUaQxDN5SaUmRZ1IdMkEVNkdi7qVfB9w80+4wMPL9mNj+v9fHR+LbQSLJYSC+MSyjtRZl2feVivFUk9aTSV4/o+jkMvnxlJkbufahz+AhWQtmEMEXSuRw7qGZ5IhciaYenKLBkvBZZsT6XQsA8UUUfD7el6e60SPTzLbOE1gfaY4pKbPJVCug8VDUIYPthjNn9+njkOTSOBbnJk5qODPzP+BGbBDKbfmsTTiMw9scp2GIW9Z1OIfbTFGTzA8O16s3baU1z36esf1rR3Yoz+l05kHqm+eTdm4cix+XQKd+qJhdi9kMg4f/PIkZoHP41CMx0uzhsAbargJ/FydTlPi4cym4r7aRQSvv3wYQVFz7cdtvyw5jAMwzDMmxTdw5CxNlWfb+tUVq1m+gwe5+rbVD/dAm3uVzx6sJIvrpOiO6FHo8k5vLo1gJauplgZwJ7eB1DM9uf23TFzur46lUoEd9veaYiO1/cjXYC2JF7OBvqZdG9hRUWzxoG+da09W7DocW9n60G14gAsu+dm7lIeNLyxC3RL4KC9OZVBiFdzHOktmsgbCP7s+kyamwnQNkZw1r9/HnbvK40jiE2vJoZwL2fpI9/UQYVRCKNWo67wEj5698mBwazR6G0Br2Ju5BCE2Y3dGAJNY6MQTnWL7HiPKugCTmbR0rs5dx7CTjXczAdXpeIEgmDWvOyC9qzuGwKgunl299LdJBpEM9iUdwrJ1oMXZxya5wNsPdIHEJDCBMK7A2Mgu/viRmHn+FsII/xYhXD3BkAUQPdKspvnnc9YEBxIf6MwuGxGkguEcJLXdT9qWI+Vwmi4wuu5EdcKK7R1aW1dK6xo0NGgiqp9IBUODqPOsFIYTXC6rDQ+UEjaYvofXtpTL5U6N4TVUfKy1ONEDgPIsAUglELl9WEYwryor6vm4CulECqjHGFbVpmmkGyJzpauMJgZxinCE2bYwINSqAca1crZEMMSHjbHNtoPFFbyu1ahPjZjtUvfduiiwUBelAr+Cl6tcDbNbTuZkPDmui4du8HpFGIwlBrzolF4Y+tWIdoKZPcqheGms2s3Crd0pc5o95I4DxRO5RHYk1Xentr6o1PWYOvD9j3BY/S3v3/5+vXLP3766Z9fvv5Ljmu5YyvDTP2td9M1pRA1rul6B7XCW1v3ChWNwuOtXaUQu++FfDW4U+hjaBBS4d0PHRxHu0eyaBqIlyT8948/ID/+5+ef//vD/zqFxkbd4aQ+fFOhYaQ4XAdS4Z2tX1Q4elMhDsIj3aKrFbbRtZqFQAegwvT23AC0K7FuDijRF5VyF30rNTSFJgYnS7YuhMVQY3qlEDXOZca/t/VthUYURSvd7vJKIWrERCwVhudXecCC4oF0c4yO0VI7dVvQ254hHJWlIIL66vl4RtvSBCgPj9uBSyWF9AVxuM6umO8W+vXCOuaweGRLVwj626WY6XHc+aObtE0KQfcXsQm1moZYqqImvs/4hrhoG9SFKk6WVkIUFq6lp7jNNGl8qnVklaVR0Z74Oh8JPFG3lVr6muGdruoxyzrJ6JBf2cUjRHy6fg8Dr3DSHlDoP8FJrk6tR2Vr70le5mCYd8Cv41i94mK826qxJ7YUcpuU6+6GTRWc0AmqpjMxGL7KCCrXpjIIqkphh7aagNcnMFogappyuOCyirAVTBaLucp2AuZnUO8AxYAHHeqC2zwuXuC8UFl/NCdbx1rh+UC2+n/E5ugJwJTZIauDWDUwKD/WeyiSe6oYj0lp0Z7ndj/BAD1OypmPf5fT/3AcmXiaGdCZVtTz90JLSULq2a3lSp3Gdp2FtqSUOwZqZaob7hEHElGW7bUXSZJE9eCpIls0vx/NaoW1y8aXrIBYs9AptNBWW2vaaGvd/wsZV15qbKhim9SdWIXaDhpPrpIVo9DpoN2lK9QriDM5u+r2XokuNN2sZ4zGCxyPG1XxV7r2DAarxuXii0Hd1ezSFK4OZGtTR5pXtLX6DL91c3dTpJlaWa/TaeOZV7c9vNO0qaIS6sqiHYfutptHxmRrqNaL1+krV14MwzAMwzAMwzAMwzAMwzAMwzAMwzAMwzAMwzAMwzAMwzAMwzAMwzAMwzAMwzAMwzAMwzB98Zc/O/8H13uhqk+TY6IAAAAASUVORK5CYII=" class="nav-img " loading="lazy">
            <ul class="nav mt-5">
                <li class="nav-item"><a class="nav-link" href="#inicio">Início</a></li>
                <li class="nav-item"><a class="nav-link" href="#galeria">Galeria</a></li>
                <li class="nav-item"><a class="nav-link" href="#contato">sua encomenda</a></li>
            </ul>
            <div id="acessibilidade" class="menu-acessibilidade"> 
                <button id="botao-acessibilidade" class="btn btn-primary fw-bold rotacao-botao" aria-expanded="false">acessibilidade</button>
                <div id="opcoes-acessibilidade" class="opcoes-acessibilidade apresenta-lista">
                    <button id="aumentar-fonte" class="btn btn-primary fw-bold" aria-label="Aumentar o tamanho da fonte">A+</button>
                    <button id="diminuir-fonte" class="btn btn-primary fw-bold" aria-label="diminuir o tamanho da fonte">A-</button>
                    <button id="alterna-contraste" class="btn btn-primary fw-bold" aria-label="Alterna o contraste de cores"> <i class="bi bi-shadows"></i></button>         
                </div>
            </div>
        </nav>
       
    </header>


    <main class="container my-5">

        <section id="inicio" class="my-5">
            <div class="inicio-fundo d-flex justify-content-between align-items-center">
                <div class="esquerda-conteudo">
                    <h1 class="display-4 text-white fst-italic fw-bold">
                  arena mendes esportes</h1>
                    <img src="https://st4.depositphotos.com/1005563/25369/i/450/depositphotos_253697550-stock-photo-award-winning-championship-concept-trophy.jpg" class="mb-3" width="563"
                        height="278" loading="lazy">
                    <a href="#tropicalia"
                        class="btn btn-primary btn-lg botao-inicio fw-semibold">ofertas!</a>
                </div>
                <img src="https://img.freepik.com/vetores-gratis/equipamento-de-futebol-voleibol-beisebol-e-rugby_1441-4026.jpg" alt="a nossa loja vendes os melhores produtos esportivos para você e sua familia" title="Os mutantes - CC0 Domínio Público / Acervo Arquivo Nacional" class="img-fluid img-inicio">

              </div>
        </section>

        <section id="" class="my-5 pt-6 secao-tropicalia" tabindex="0" aria-label="Seção explicativa sobre a tropicália">
            <div class="container d-flex align-items-center ">
                <div class="col-4 d-flex justify-content-center ">
                    <img src="img/image (1).png" class="rounded-pill" width="273" height="331" loading="lazy">
                </div>
                <div class="col-5">
                    <h2>como funciona nossa loja?</h2>
                    <p class="p-2">A Sport Mendes é uma loja especializada em artigos esportivos, oferecendo uma ampla variedade de produtos para diferentes modalidades, como futebol, corrida, basquete, ginástica, e muito mais. Nosso objetivo é proporcionar aos nossos clientes uma experiência de compra única, com produtos de qualidade, das melhores marcas do mercado, e atendimento personalizado. Na Sport Mendes, você encontra desde roupas e calçados esportivos até acessórios e equipamentos para suas atividades favoritas. Acreditamos no poder do esporte para transformar vidas e, por isso, nos dedicamos a oferecer tudo o que você precisa para atingir seus objetivos e se manter ativo!


</p>
                </div>
            </div>
        </section>

        <section id="galeria" tabindex="0" aria-label="Seção de galeria de imagens">
            <h2 class="text-center pt-5">artigos esportivos</h2>
            <div class="container p-3 mt-3 fundo-galeria ">

                <div class="row justify-content-md-center">
                    <div class="col-md-4">
                        <img src="https://images.puma.com/image/upload/f_auto,q_auto,b_rgb:fafafa/global/084606/01/fnd/BRA/w/640/h/640/fmt/png"
                            class="img-fluid rounded-5" loading="lazy">
                    </div>
                    <div class="col-md-4">
                        <img src="img/lossy-page1-640px-Os_Mutantes_2.tif.jpg" class="img-fluid rounded-5"
                            loading="lazy">
                    </div>
                </div>
                <div class="row mt-4  justify-content-md-center">
                    <div class="col-md-4">
                        <img src="https://www.drogariaminasbrasil.com.br/media/webp/catalog/product/cache/b450faf3073917bf18118fe0a38023b9/image/1045010f03/bolas-de-futebol-sortidas-com-1-unidade-ref-529_jpg.webp" class="img-fluid rounded-5" loading="lazy">
                    </div>
                    <div class="col-md-4">
                        <img src=""
                            class="" loading="lazy">
                    </div>
                </div>
             </div>
        </section>

        <section id="contato">
            <div class="container p-5 d-flex justify-content-center">
                <div class="col-md-8 col-lg-10 rounded-5 formulario"> <!-- Caixa do formulário com 60% de largura -->
                    <h2 class="mb-3">Entre em contato</h2>
                    <form>
                        <div class="form-group mb-3">
                            <label for="nome">Nome</label>
                            <input type="text" id="nome" name="nome" class="form-control rounded-3 mt-1"
                                placeholder="Digite seu nome completo">
                        </div>
                        <div class="form-group mb-3">
                            <label for="email">Email</label>
                            <input type="email" id="email" name="email" class="form-control rounded-3 mt-1"
                                placeholder="Digite seu email">
                        </div>
                        <div class="form-group mb-3">
                            <label for="mensagem">faça sua encomenda</label>
                            <textarea id="mensagem" name="mensagem" class="form-control rounded-4 mt-2" rows="4"
                                placeholder="Escreva sua mensagem"></textarea>
                        </div>
                        <div class="d-grid gap-2">
                            <button type="submit" class="btn btn-primary btn-lg rounded-pill">Enviar
                                mensagem</button>
                        </div>
                    </form>
                </div>
            </div>
        </section>
    </main>
    <footer class="text-center p-3 fst-italic">
        <p>Acesse nossas redes:</p>
        <i class="bi bi-whatsapp"></i>
        <i class="bi bi-instagram"></i>
        <i class="bi bi-tiktok"></i>
        <p class="mt-3">@davix_z7</p>
    </footer>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/scrollReveal.js/4.0.9/scrollreveal.js"></script>
    <script src="script.js"></script>
  
</body>

</html>

@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lemon&display=swap');

:root {
    --laranja-claro: #FF862A;
    --alto-contraste-fundo: #000000;
    --alto-contraste-texto: #ffffff;
    --alto-contraste-link: #ffd700;
}

body {
    font-size: 1rem;
    font-family: 'Montserrat';
}

header {
    background-color: ADD8E6;
}


section {
    padding-bottom: 5rem;
}


.nav-link {
    color: #CB6D43;
    font-weight: 600;
}

.inicio-fundo {
    /* aula 3 */
    background-image: url('img/4965007.jpg');
    /* Substitua pelo caminho da sua imagem */
    background-size: cover;
    background-position: right;
    border-radius: 80px;
    width: 100%;
    height: 606px;
    padding: 40px;
    margin: 0 auto;
}

/* posicionamento para a imagem à direita */
.img-inicio {
    position: absolute;
    right: 0;
    top: 18rem;
    width: 45rem;
    height: auto;
}


.esquerda-conteudo {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 1rem;
}


.botao-inicio {
    background-color: var(--laranja-claro);
    border-radius: 30px;
    border: none;
    width: 14em;
    height: 3em;
    align-content: center;

}

.display-4 {
    text-shadow: -5px 5px var(--laranja-claro);
}


#tropicalia {
    position: relative;
    padding-top: 5rem;
    margin-top: 3rem;
    margin-bottom: 3rem;
    background: url('img/flor.png') top right no-repeat,
        url('img/flor-esquerda.png') bottom left no-repeat;
    background-size: 200px 180px;
    /* Ajuste o tamanho conforme necessário */
}

#tropicalia .container {
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    z-index: 1;
    /* Garante que o conteúdo fica acima das imagens do background */
}


h2 {
    font-family: 'Lemon', serif;
    font-size: 2.5em;
    font-style: normal;
    color: var(--laranja-claro);
}

#galeria {
    background-color: #808080;

}

.fundo-galeria {
    background: url('img/flor-bottom-direita.png') bottom right no-repeat;
    background-size: 150px 150px;
}

#contato {
    background-image: url('img/4965007.jpg');
    background-size: cover;
    padding: 4rem 0;
    /* Espaçamento interno para a seção de contato */

}

.formulario {
    background-color: #ffffff;
    padding: 2rem;
    /* Espaçamento interno dentro do formulário */
    border-radius: 10px;
    /* Borda arredondada para o formulário */
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    /* Sombra suave para destacar o formulário */
    font-weight: bold;
}

.formulario button {
    background-color: #CB6D43;
    border: none;
    font-weight: bold;
}

.form-control {
    background-color: #F1EDEF;
}
.menu-acessibilidade{
    position: fixed;
    top:2rem;
    right:20px;
    z-index: 1000;
}

.rotacao-botao{
    transform: rotate(-90deg);
    transform-origin: right center;
}

.opcoes-acessibilidade{
    margin-top:10px;
    display: flex;
    flex-direction: column;
}

.opcoes-acessibilidade button{
    margin-bottom: 5px;
}
.apresenta-lista{
    display: none;
}

.alto-contraste{
    background-color: var(--alto-contraste-fundo);
    color: var(--alto-contraste-texto);
}

.alto-contraste header,
.alto-contraste footer,
.alto-contraste .formulario{
    background-color: var(--alto-contraste-fundo);
    color: var(--alto-contraste-texto);
}

.alto-contraste .nav-link{
    color: var(--alto-contraste-link);
}

.alto-contraste .botao-inicio,
.alto-contraste .formulario button,
.alto-contraste .btn-primary{
    background-color: var(--alto-contraste-link);
    color: var(--alto-contraste-fundo)
}

.alto-contraste #tropicalia {
    background: none;
}

.alto-contraste #galeria {
    background-color: var(--alto-contraste-fundo);
}
.alto-contraste .fundo-galeria {
    background: none;
}

document.addEventListener('DOMContentLoaded', function(){
    const botaoDeAcessibilidade = document.getElementById('botao-acessibilidade')
    const opcoesDeAcessibilidade = document.getElementById('opcoes-acessibilidade')
 
    botaoDeAcessibilidade.addEventListener('click', function (){
     botaoDeAcessibilidade.classList.toggle('rotacao-botao');
     opcoesDeAcessibilidade.classList.toggle('apresenta-lista')
 
     const botaoSelecionado = botaoDeAcessibilidade.getAttribute('aria-expanded') === 'true';
     botaoDeAcessibilidade.setAttribute('aria-expanded', !botaoSelecionado)
   
    })
 
     const aumentaFonteBotao = document.getElementById('aumentar-fonte');
     const diminuiFonteBotao = document.getElementById('diminuir-fonte');
     
     const alternaContraste = document.getElementById('alterna-contraste')
 
     let tamanhoAtualFonte = 1;
 
     aumentaFonteBotao.addEventListener('click', function(){
         tamanhoAtualFonte += 0.1;
         document.body.style.fontSize = `${tamanhoAtualFonte}rem`
 
     })
 
     diminuiFonteBotao.addEventListener('click', function(){
         tamanhoAtualFonte -= 0.1;
         document.body.style.fontSize = `${tamanhoAtualFonte}rem`
 
     })
 
     alternaContraste.addEventListener('click', function(){
         document.body.classList.toggle('alto-contraste')
     })
 
 
 })
 
 ScrollReveal().reveal('#inicio', { delay: 500 });
 ScrollReveal().reveal('#tropicalia', { delay: 500 });
 ScrollReveal().reveal('#galeria', { delay: 500 });
 ScrollReveal().reveal('#contato', { delay: 500 });

 
