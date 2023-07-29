# Atividade_4
<!DOCTYPE html>
<html>
<head>
  <title>Calculadora de Área de Triângulo</title>
</head>
<body>
  <h1>Calculadora de Área de Triângulo</h1>
  <label for="base">Digite o valor da base do triângulo:</label>
  <input type="number" id="base" />
  <br />
  <label for="altura">Digite o valor da altura do triângulo:</label>
  <input type="number" id="altura" />
  <br />
  <button onclick="calcularArea()">Calcular Área</button>
  <br />
  <p id="resultado"></p>

  <script>
    function calcularArea() {
      // Obtém os valores digitados pelo usuário
      var base = parseFloat(document.getElementById('base').value);
      var altura = parseFloat(document.getElementById('altura').value);

      // Calcula a área do triângulo (base * altura / 2)
      var area = (base * altura) / 2;

      // Exibe o resultado da área
      var resultadoElement = document.getElementById('resultado');
      resultadoElement.innerHTML = 'A área do triângulo é: ' + area;
    }
  </script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
  <title>Calculadora de Área de Triângulo</title>
</head>
<body>
  <h1>Calculadora de Área de Triângulo</h1>
  <label for="base">Digite o valor da base do triângulo:</label>
  <input type="number" id="base" />
  <br />
  <label for="altura">Digite o valor da altura do triângulo:</label>
  <input type="number" id="altura" />
  <br />
  <button onclick="calcularArea()">Calcular Área</button>
  <br />
  <p id="resultado"></p>

  <script>
    function calcularArea() {
      // Obtém os valores digitados pelo usuário
      var base = parseFloat(document.getElementById('base').value);
      var altura = parseFloat(document.getElementById('altura').value);

      // Calcula a área do triângulo (base * altura / 2)
      var area = (base * altura) / 2;

      // Exibe o resultado da área
      var resultadoElement = document.getElementById('resultado');
      resultadoElement.innerHTML = 'A área do triângulo é: ' + area;
    }
  </script>
</body>
</html>
