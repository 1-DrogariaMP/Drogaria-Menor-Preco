<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Drogaria Menor Preço</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,700;0,900&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Montserrat', sans-serif;
      background: radial-gradient(circle at center, #ff4d4d, #990000);
      text-align: center;
      padding: 30px 20px;
      color: white;
    }

    h1 {
      font-weight: 900;
      font-size: 32px;
      margin-bottom: 10px;
    }

    .sub {
      font-size: 16px;
      margin-bottom: 6px;
    }

    .whatsapp-button, .map-button {
      display: block;
      margin: 12px auto;
      padding: 14px 25px;
      background-color: #25D366;
      color: white;
      font-size: 16px;
      font-weight: bold;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      text-decoration: none;
      animation: shake 2s infinite;
    }

    .map-button {
      background-color: #34A853;
      animation: none;
    }

    @keyframes shake {
      0% { transform: translateX(0); }
      20% { transform: translateX(-2px); }
      40% { transform: translateX(2px); }
      60% { transform: translateX(-2px); }
      80% { transform: translateX(2px); }
      100% { transform: translateX(0); }
    }

    .address-box {
      background-color: white;
      padding: 15px;
      border-radius: 15px;
      color: #990000;
      font-weight: 700;
      margin: 20px 0 10px;
    }
  </style>
</head>
<body>

  <h1>Drogaria Menor Preço</h1>
  <div class="sub">Entregas grátis com pedidos a partir de R$25</div>
  <div class="sub">Entrega em até 40 minutos em Águas Claras, Taguatinga, Vicente Pires e Colônia Agrícola</div>

  <a class="whatsapp-button" href="https://wa.me/556185925725" target="_blank">WhatsApp (61) 8592-5725</a>
  <a class="whatsapp-button" href="https://wa.me/556133518138" target="_blank">WhatsApp (61) 3351-8138</a>

  <div class="address-box">
    Colônia Agrícola Samambaia CH 131<br>
    LOTE 2A LOJA 4 - Taguatinga, Brasília - DF, 72001-810
  </div>

  <a class="map-button" href="https://www.google.com/maps/place/Col%C3%B4nia+Agr%C3%ADcola+Samambaia+CH+131+LOTE+2A+LOJA+4+-+Taguatinga,+Bras%C3%ADlia+-+DF,+72001-810" target="_blank">
    Ver no Google Maps
  </a>

</body>
</html>
