<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VapeStyle - Sua Loja de Vapes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f4f4f9;
            color: #333;
        }
        header {
            background: linear-gradient(90deg, #ff8a00, #e52e71);
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            font-size: 2.5rem;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
        }
        nav a {
            text-decoration: none;
            color: #333;
            font-size: 1rem;
            font-weight: bold;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background: #ffe0b2;
        }
        .hero h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }
        .hero button {
            padding: 10px 20px;
            background: #ff8a00;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .product-card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 15px;
            text-align: center;
        }
        .product-card img {
            max-width: 100%;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        .product-card h3 {
            font-size: 1.2rem;
            margin-bottom: 10px;
        }
        .product-card button {
            padding: 10px;
            background: #e52e71;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>VapeStyle</h1>
        <nav>
            <a href="#produtos">Produtos</a>
            <a href="#sobre">Sobre Nós</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>

    <section class="hero">
        <h2>Encontre o Vape Perfeito para o Seu Estilo</h2>
        <button>Confira as Ofertas</button>
    </section>

    <section class="products" id="produtos">
        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Vape Colorido">
            <h3>Vape Colorido</h3>
            <p>R$ 99,90</p>
            <button>Comprar Agora</button>
        </div>
        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Vape Compacto">
            <h3>Vape Compacto</h3>
            <p>R$ 79,90</p>
            <button>Comprar Agora</button>
        </div>
        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Vape Premium">
            <h3>Vape Premium</h3>
            <p>R$ 149,90</p>
            <button>Comprar Agora</button>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 VapeStyle. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
