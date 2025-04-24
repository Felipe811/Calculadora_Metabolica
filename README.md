# Calculadora_Metabolica
Esse projeto consiste em uma calculadora de Metobolica Basal

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Calculadora de TMB</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      padding: 20px;
    }
    .container {
      max-width: 500px;
      background-color: white;
      padding: 20px;
      border-radius: 8px;
      margin: auto;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    h2 {
      text-align: center;
    }
    label {
      display: block;
      margin-top: 10px;
    }
    input, select {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
    }
    button {
      margin-top: 20px;
      width: 100%;
      padding: 10px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }
    .resultado {
      margin-top: 20px;
      text-align: center;
      font-weight: bold;
    }
  </style>
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


