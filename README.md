
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Faire un don – Fondation ZAIR</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f7f7f7;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
    }

    .container {
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      text-align: center;
    }

    h1 {
      margin-bottom: 10px;
      color: #333;
    }

    p {
      margin-bottom: 20px;
      color: #666;
    }

    input[type="submit"] {
      background-color: #0070ba;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }

    input[type="submit"]:hover {
      background-color: #005fa3;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Faire un don</h1>
    <p>Soutenez la fondation ZAIR avec un don sécurisé via PayPal.</p>

    <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
      <input type="hidden" name="cmd" value="_xclick">
      <input type="hidden" name="business" value="cecilelucia812@gmail.com">
      <input type="hidden" name="item_name" value="fondation ZAIR">
      <input type="hidden" name="amount" value="2.00">
      <input type="hidden" name="currency_code" value="USD">
      <input type="hidden" name="return" value="https://fondation-zair.com/succes">
      <input type="hidden" name="cancel_return" value="https://fondation-zair.com/annulation">
      <input type="submit" value="Faire un don via PayPal">
    </form>
  </div>
</body>
</html>
