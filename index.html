<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Calcul Monnaie</title>
  <style>
    body {
      font-family: sans-serif;
      padding: 20px;
      max-width: 400px;
      margin: auto;
      background-color: #f9f9f9;
    }
    h1 {
      text-align: center;
      color: #333;
    }
    .champ {
      background-color: #fff;
      border: 1px solid #ccc;
      border-radius: 10px;
      padding: 15px;
      margin-bottom: 15px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
    }
    label {
      font-weight: bold;
      margin-bottom: 5px;
      display: block;
    }
    input {
      width: 100%;
      font-size: 1.1em;
      padding: 8px;
      border-radius: 6px;
      border: 1px solid #ccc;
      margin-top: 5px;
    }
    .ticket-buttons {
      display: flex;
      justify-content: space-around;
      gap: 10px;
      margin-bottom: 10px;
    }
    .ticket-buttons button {
      flex: 1;
      padding: 15px;
      font-size: 1.1em;
      border: none;
      border-radius: 8px;
      color: white;
      background-color: #4CAF50;
    }
    .ticket-buttons button.selected {
      background-color: #388E3C;
    }
    button {
      width: 100%;
      padding: 10px;
      font-size: 1.2em;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 8px;
      margin-top: 10px;
    }
    .resultat {
      margin-top: 20px;
      font-size: 1.3em;
      text-align: center;
    }
    .pieces {
      display: flex;
      flex-wrap: wrap;
      gap: 5px;
      justify-content: center;
      margin-top: 10px;
    }
    .pieces button {
      width: 70px;
      padding: 8px;
      background-color: #2196F3;
      color: white;
      border: none;
      border-radius: 6px;
    }
    #reset {
      background-color: #f44336;
    }
  </style>
</head>
<body>
  <h1>Rendu Monnaie</h1>

  <div class="champ">
    <label>Type de ticket :</label>
    <div class="ticket-buttons">
      <button id="btn1h" onclick="selectTicket(1.3)">1,30 €</button>
      <button id="btn1j" onclick="selectTicket(3)">3 €</button>
    </div>
  </div>

  <div class="champ">
    <label for="quantite">Nombre de tickets :</label>
    <input type="number" id="quantite" min="1" value="1">
  </div>

  <div class="champ">
    <label for="somme">Somme donnée (€) :</label>
    <input type="number" id="somme" min="0" step="0.01" placeholder="0.00">
  </div>

  <div class="pieces">
    <button onclick="ajouterMontant(0.01)">0,01 €</button>
    <button onclick="ajouterMontant(0.02)">0,02 €</button>
    <button onclick="ajouterMontant(0.05)">0,05 €</button>
    <button onclick="ajouterMontant(0.10)">0,10 €</button>
    <button onclick="ajouterMontant(0.20)">0,20 €</button>
    <button onclick="ajouterMontant(0.50)">0,50 €</button>
    <button onclick="ajouterMontant(1)">1 €</button>
    <button onclick="ajouterMontant(2)">2 €</button>
    <button onclick="ajouterMontant(5)">5 €</button>
    <button onclick="ajouterMontant(10)">10 €</button>
  </div>

  <button onclick="calculer()">Calculer</button>
  <button id="reset" onclick="resetForm()">Remise à zéro</button>

  <div class="resultat" id="resultat"></div>

  <script>
    let ticketType = 1.3;
    document.getElementById('btn1h').classList.add('selected');

    function selectTicket(value) {
      ticketType = value;
      document.getElementById('btn1h').classList.remove('selected');
      document.getElementById('btn1j').classList.remove('selected');
      if (value === 1.3) {
        document.getElementById('btn1h').classList.add('selected');
      } else {
        document.getElementById('btn1j').classList.add('selected');
      }
    }

    function calculer() {
      const quantite = parseInt(document.getElementById('quantite').value);
      const somme = parseFloat(document.getElementById('somme').value) || 0;

      const total = ticketType * quantite;
      const rendu = somme - total;

      let message = `Total à payer : ${total.toFixed(2)} €<br>`;

      if (rendu >= 0) {
        message += `Monnaie à rendre : ${rendu.toFixed(2)} €`;
      } else {
        message += `Somme insuffisante : manque ${Math.abs(rendu).toFixed(2)} €`;
      }

      document.getElementById('resultat').innerHTML = message;
    }

    function ajouterMontant(valeur) {
      const input = document.getElementById('somme');
      let actuel = parseFloat(input.value) || 0;
      input.value = (actuel + valeur).toFixed(2);
    }

    function resetForm() {
      selectTicket(1.3);
      document.getElementById('quantite').value = 1;
      document.getElementById('somme').value = "";
      document.getElementById('resultat').innerHTML = "";
    }
  </script>
</body>
</html>
