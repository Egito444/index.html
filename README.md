<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Egito PetShop</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f6f6f6;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background-color: #009688;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product {
      background-color: white;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      text-align: center;
    }
    .product img {
      max-width: 100%;
      height: auto;
      border-radius: 6px;
    }
    .product h3 {
      margin: 10px 0 5px;
    }
    .product p {
      font-size: 14px;
      color: #555;
    }
    .whatsapp-button {
      margin-top: 10px;
      display: inline-block;
      background-color: #25d366;
      color: white;
      padding: 10px 15px;
      border-radius: 5px;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Egito PetShop</h1>
    <p>Produtos incríveis para seu pet, com entrega garantida!</p>
  </header>
  <div class="container">
    <div class="product">
      <img src="https://via.placeholder.com/250x200?text=Coleira+Personalizada" alt="Coleira Personalizada">
      <h3>Coleira com Nome</h3>
      <p>Gravação personalizada e material ajustável.</p>
      <a class="whatsapp-button" href="https://wa.me/5521983636221?text=Tenho%20interesse%20na%20coleira%20personalizada">Pedir no WhatsApp</a>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x200?text=Brinquedo+Gato" alt="Brinquedo Gato">
      <h3>Brinquedo Interativo</h3>
      <p>Diversão garantida para seu gato com movimento automático.</p>
      <a class="whatsapp-button" href="https://wa.me/5521983636221?text=Tenho%20interesse%20no%20brinquedo%20para%20gato">Pedir no WhatsApp</a>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x200?text=Caminha+Pet" alt="Caminha Pet">
      <h3>Caminha Dobrável</h3>
      <p>Conforto e praticidade para cães e gatos.</p>
      <a class="whatsapp-button" href="https://wa.me/5521983636221?text=Tenho%20interesse%20na%20caminha%20pet">Pedir no WhatsApp</a>
    </div>
    <!-- Adicione mais produtos seguindo o mesmo modelo -->
  </div>
</body>
</html>
