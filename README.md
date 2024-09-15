                                               # Movimento-mouse
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eventos DOM</title>
    <style>
        div#area {
            font: normal 20pt Arial;
            background: rgb(147, 221, 147);
            color: white;
            width: 200px;
            height: 200px;
            line-height: 200px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div id="area" 
   interaja...
    </div>
          <script>
        var a = window.document.getElementById ('area')
        a.addEventListener('click' ,clicar)
        a.addEventListener('mouseenter' , entrar)
        a.addEventListener('mouseout' , sair)


        function clicar() {
            a.innerText = 'Clicou!'
            a.style.background  = 'red'
        }
        function entrar() {
            a.innerText = 'Entrou!'
        }
        function sair() {
            a.innerText = 'Saiu!'
            a.style.background = 'green'
        }
    </script>
</body>
</html>
  
