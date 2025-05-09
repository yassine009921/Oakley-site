<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Oakley Store</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Oakley Store</h1>
    <nav>
      <ul>
        <li><a href="#">Accueil</a></li>
        <li><a href="#">Produits</a></li>
        <li><a href="#">À propos</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h2>Lunettes de soleil hautes performances</h2>
    <p>Découvrez la nouvelle collection Oakley</p>
  </section>

  <section class="products">
    <h2>Nos Lunettes</h2>
    <div class="product-list">
      <div class="product">
        <img src="https://images.oakley.com/is/image/OakleyEYE/OO9208-9438_main?$gallery$" alt="Oakley Jawbreaker" />
        <h3>Oakley Jawbreaker</h3>
        <p>189,00 €</p>
        <button onclick="addToCart('Oakley Jawbreaker')">Ajouter au panier</button>
      </div>
      <div class="product">
        <img src="https://images.oakley.com/is/image/OakleyEYE/OO9406-0137_main?$gallery$" alt="Oakley Sutro" />
        <h3>Oakley Sutro</h3>
        <p>169,00 €</p>
        <button onclick="addToCart('Oakley Sutro')">Ajouter au panier</button>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2025 Oakley Store - Site démo</p>
  </footer>

  <script>
    function addToCart(productName) {
      alert(productName + " a été ajouté au panier !");
    }
  </script>
</body>
</html>
