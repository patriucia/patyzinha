HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=>, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="paty.css">
</head>
<body>
    <header class="cabecalho">
        <h1>TITULO TESTE</h1>
    </header>
        <h2>TITULO SECUNDÁRIO</h2>
        <p class="paragrafo1"> PARÁGRAFO 1 </p>
        <div class="paragrafos"> 
        <p> parágrafo 2 </p>
        <p> parágrafo 3 </p>
        </div>
        <p> parágrafo 4 </p>
        <p> parágrafo 5 </p>
        <h3> título terciário </h3>
        <ul class="lista">
    <img class="imagem" src="">
    <ul class="lista">
        <li>Escola</li>
        <li>Estudante</li>
    </ul>
</body>
</html>
  --------------------------------
  CSS
  .cabecalho
{
    background: color #383d58;
    color: white

}
.imagem{
    width: 20%

}
p {
    font-size: 18px
}
.paragrafo1 {
    font-size: 30px;
}
.paragrafos {
    font-size: 16px
}
.lista{
    display: inline-block;
    margin: 0 16px;
}
