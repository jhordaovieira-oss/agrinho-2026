<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>AgroInsights</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <section class="container">
    <h1>🌱 AgroInsights</h1>
    <p>Inteligência de mercado para o agronegócio</p>

    <div class="form">
      <select id="cultura">
        <option value="soja">Soja</option>
        <option value="milho">Milho</option>
        <option value="cafe">Café</option>
        <option value="boi">Boi Gordo</option>
      </select>

      <select id="estado">
        <option value="SP">São Paulo</option>
        <option value="PR">Paraná</option>
        <option value="MG">Minas Gerais</option>
        <option value="GO">Goiás</option>
      </select>

      <button onclick="analisar()">Analisar Mercado</button>
    </div>

    <div id="resultado" class="resultado"></div>
  </section>

  <script src="script.js"></script>
</body>
</html>
