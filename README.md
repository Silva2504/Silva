# Silva
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bai+Jamjuree:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;1,200;1,300;1,400;1,500;1,600;1,700&display=swap" rel="stylesheet">
    <title>Em busca da cidade perdida</title>
</head>
<body>
    <main>
        <div class="passo ativo" id="passo-0">
            <img src="cenario-passo0.png" alt="">
            <p>Um dia desses, dentro de um livro da biblioteca da escola, eu descobri uma carta antiga sobre uma cidade perdida, escondida por riquezas e belezas naturais. Nessa carta, a autora deixa algumas pistas para encontrar essa cidade e eu decidi segui-las!</p>
            <button class="btn-proximo" data-proximo="1">Rio de Janeiro</button>
            <button class="btn-proximo" data-proximo="2">Pernambuco</button>
        </div>
        <div class="passo" id="passo-1">
            <p>Você começa sua jornada no Rio de Janeiro, subindo o Pico da Tijuca ao amanhecer para encontrar a primeira pista.</p>
            <button class="btn-proximo" data-proximo="3">Procurar a pista no topo do pico</button>
            <button class="btn-proximo" data-proximo="4">Desistir e voltar para casa</button>
        </div>
        <div class="passo" id="passo-2">
            <p>Em Pernambuco, você visita a histórica cidade de Olinda. Na carta, uma das pistas indica que para localizar a entrada para a cidade perdida você deve procurar a próxima pista em um dos pontos turísticos da cidade. Por qual você começa?</p>
            <button class="btn-proximo" data-proximo="5">Investigar as igrejas antigas</button>
            <button class="btn-proximo" data-proximo="6">Explorar as praias próximas</button>
        </div>
    </main>
    <script src="script.js"></script>
</body>
</html>
