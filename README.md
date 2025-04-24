# Calculadora_Metabolica
Esse projeto consiste em uma calculadora de Metobolica Basal

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">


</head>
<body>

  <div class="container">
    <h2>Calculadora de TMB</h2>
    <label for="sexo">Sexo:</label>
    <select id="sexo">
      <option value="masculino">Masculino</option>
      <option value="feminino">Feminino</option>
    </select>

    <label for="peso">Peso (kg):</label>
    <input type="number" id="peso" required>

    <label for="altura">Altura (cm):</label>
    <input type="number" id="altura" required>

    <label for="idade">Idade (anos):</label>
    <input type="number" id="idade" required>

    <button onclick="calcularTMB()">Calcular TMB</button>

    <div class="resultado" id="resultado"></div>
  </div>

  <script>
    
    }
  </script>

</body>
</html>


