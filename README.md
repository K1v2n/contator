<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>super contador</title>
    <link rel="stylesheet" href="estilo3.css">
</head>
<body>
    <header>
        <h1>Vamos contar</h1>
    </header>
    <section>
        <div id="data">
            <p>inicio: <input type="number" name="inicio" id="txti"></p>
            <p>fim: <input type="number" name="fim" id="txtf"></p>
            <p>passo: <input type="number" name="passo" id="txtp"></p>
             <p><input type="button" value="contar" onclick="contar()"></p>
           
        </div>
        <div id="res">
          prepara a contagem 
        </div>
    </section>
    <footer>
        <p>&copy; cursoemvideo</p>
    </footer>
