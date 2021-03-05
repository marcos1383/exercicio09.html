# exercicio09
Exercício 

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!--questão 01-->
    <script type="text/javascript">
        function somarValores() {
            var a = document.getElementById("a").value;
            var b = document.getElementById("b").value;
            var somarValores = parseInt(a) + parseInt(b);
            document.getElementById("resultado1").innerHTML = "Resultado: A soma dos 2 valores é: " + (somarValores);
        }
    </script>

    <!--questão 02-->
    <script type="text/javascript">
        function calcular() {
            var funcionario = document.getElementById("funcionario").value;
            var hora = document.getElementById("hora").value;
            var totalHora = document.getElementById("totalHora").value;
            var calcular = parseInt(hora) * parseInt(totalHora);
            document.getElementById("resultado2").innerHTML = "Resultado: O funcionario " + (funcionario) + " vai receber: " + (calcular);
        }
    </script>

    <!--questão 03-->
    <script type="text/javascript">
        function distanciamento() {
            var distancia = document.getElementById("distancia").value;
            var gasto = document.getElementById("gasto").value;
            var distanciamento = parseInt(distancia) / parseInt(gasto);
            document.getElementById("resultado3").innerHTML = "Resultado: O automóvel fez o consumo médio de: " + (distanciamento);
        }
    </script>

    <title>Exercicio09</title>
</head>
<style>
    input {
        display: block;
    }

    h1 {
        font-size: 16px;
        margin-bottom: 0px;
        margin-top: 20px;
    }

    span {
        font-size: 13px;
        font-family: Arial, Helvetica, sans-serif;
        color: darkblue;
    }

    p {
        margin: 0px;
    }
</style>

<body>
    <div class="questao">
        <h1>Questã 01:<span> Somar 2 valores <a href="https://www.urionlinejudge.com.br/repository/UOJ_1001.html"
                    target="_blank">link da questão</a></span></h1>
        <p id="resultado1">Resultado: A soma dos 2 valores é xx.</p>
        <label for="">A</label>
        <input type="text" id="a">
        <label for="">B</label>
        <input type="text" id="b">
        <button id="somar" onclick="somarValores()">Calcular</button>
    </div>
    <div class="questao">
        <h1>Questã 02:<span> Calcular o salário de um funcionário <a
                    href="https://www.urionlinejudge.com.br/repository/UOJ_1008.html" target="_blank">link da
                    questão</a></span></h1>
        <p id="resultado2">Resultado: O funcionario xxxxxx vai receber xxx.</p>
        <label for="">Nome Funcionário</label>
        <input type="text" id="funcionario">
        <label for="">Valor Hora</label>
        <input type="text" id="hora">
        <label for="">Total de Horas Trabalhado</label>
        <input type="text" id="totalHora">
        <button id="total" onclick="calcular()">Calcular</button>

    </div>
    <div class="questao">
        <h1>Questã 03:<span> Calcular o consumo médio de um automóvel <a
                    href="https://www.urionlinejudge.com.br/repository/UOJ_1014.html" target="_blank">link da
                    questão</a></span></h1>
        <p id="resultado3">Resultado: O automóvel fez o consumo médio de xxx.</p>
        <label for="">Distância percorrida</label>
        <input type="text" id="distancia">
        <label for="">Combustível gasto</label>
        <input type="text" id="gasto">
        <button id="mediaConsumo" onclick="distanciamento()">Calcular</button>
    </div>
</body>

</html>
