<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Achadinhos Shopee | Minha Vitrine</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #f5f7fa 0%, #e9f0f5 100%);
            color: #333;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background: linear-gradient(135deg, #ee4d2d, #ff7337);
            color: white;
            padding: 40px 20px;
            border-radius: 20px 20px 20px 20px;
            margin-bottom: 30px;
            box-shadow: 0 10px 25px rgba(238, 77, 45, 0.3);
            text-align: center;
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            letter-spacing: 2px;
        }

        .subtitle {
            font-size: 1.2em;
            opacity: 0.95;
            margin-bottom: 20px;
        }

        .btn-shopee {
            display: inline-block;
            background: white;
            color: #ee4d2d;
            padding: 15px 35px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.2em;
            transition: transform 0.3s, box-shadow 0.3s;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            border: 2px solid white;
        }

        .btn-shopee:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 25px rgba(0,0,0,0.3);
            background: #fff8e7;
        }

        .section-title {
            font-size: 1.8em;
            color: #ee4d2d;
            margin-bottom: 25px;
            border-left: 8px solid #ff7337;
            padding-left: 20px;
        }

        .featured-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            margin-bottom: 40px;
        }

        .product-card {
            background: white;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            transition: transform 0.3s, box-shadow 0.3s;
            border: 1px solid #ffdbd0;
        }

        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(238, 77, 45, 0.15);
            border-color: #ff7337;
        }

        .product-image {
            height: 200px;
            background: linear-gradient(145deg, #fee0d6, #ffe8e0);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3em;
            color: #ee4d2d;
            border-bottom: 3px solid #ffd3c0;
        }

        .product-info {
            padding: 20px;
            text-align: center;
        }

        .product-info h3 {
            color: #222;
            margin-bottom: 10px;
            font-size: 1.3em;
        }

        .product-info p {
            color: #666;
            margin-bottom: 15px;
        }

        .price {
            font-size: 1.5em;
            font-weight: bold;
            color: #ee4d2d;
        }

        .badge {
            background: #ff7337;
            color: white;
            padding: 5px 12px;
            border-radius: 25px;
            font-size: 0.8em;
            display: inline-block;
            margin-top: 10px;
        }

        .cta-section {
            background: linear-gradient(145deg, #2a2a2a, #1a1a1a);
            color: white;
            padding: 50px 30px;
            border-radius: 30px;
            text-align: center;
            margin: 50px 0;
            box-shadow: 0 15px 30px rgba(0,0,0,0.3);
        }

        .cta-section h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }

        .btn-white {
            background: #ff7337;
            color: white;
            padding: 18px 45px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.3em;
            display: inline-block;
            margin-top: 20px;
            transition: all 0.3s;
            border: 2px solid #ff7337;
        }

        .btn-white:hover {
            background: #ee4d2d;
            border-color: white;
            transform: scale(1.05);
        }

        footer {
            text-align: center;
            padding: 30px;
            color: #777;
            border-top: 1px solid #ffd3c0;
            margin-top: 30px;
        }

        .shopee-icon {
            font-size: 1.5em;
            vertical-align: middle;
        }

        @media (max-width: 768px) {
            h1 { font-size: 1.8em; }
            .btn-shopee, .btn-white { padding: 12px 25px; font-size: 1em; }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- HEADER PRINCIPAL COM LINK DA SUA LOJA -->
        <header>
            <h1>🛍️ ACHADINHOS SHOPEE</h1>
            <p class="subtitle">Os melhores produtos com preços incríveis! Ofertas exclusivas esperando por você.</p>
            <a href="https://collshp.com/3409a?view=storefront" class="btn-shopee" target="_blank">
                🔗 VER VITRINE COMPLETA
            </a>
            <p style="margin-top: 15px; font-size: 0.9em;">👉 Clique no botão acima para acessar todos os meus achadinhos!</p>
        </header>

        <!-- SEÇÃO DE DESTAQUES (EXEMPLOS VISUAIS) -->
        <h2 class="section-title">✨ Destaques da Semana</h2>
        <div class="featured-grid">
            <div class="product-card">
                <div class="product-image">📱</div>
                <div class="product-info">
                    <h3>Acessórios Tech</h3>
                    <p>Capinhas, cabos e carregadores com até 50% OFF</p>
                    <span class="price">R$ 19,90</span>
                    <div><span class="badge">Mais vendido</span></div>
                </div>
            </div>
            <div class="product-card">
                <div class="product-image">🏠</div>
                <div class="product-info">
                    <h3>Organização para Casa</h3>
                    <p>Caixas, prateleiras e itens de decoração</p>
                    <span class="price">R$ 29,90</span>
                    <div><span class="badge">Frete grátis</span></div>
                </div>
            </div>
            <div class="product-card">
                <div class="product-image">👕</div>
                <div class="product-info">
                    <h3>Moda e Estilo</h3>
                    <p>Roupas, calçados e acessórios</p>
                    <span class="price">R$ 39,90</span>
                    <div><span class="badge">Novidade</span></div>
                </div>
            </div>
        </div>

        <!-- CALL TO ACTION PRINCIPAL - LINK DA SUA VITRINE -->
        <div class="cta-section">
            <h2>🚀 QUERO VER TODOS OS ACHADINHOS!</h2>
            <p style="font-size: 1.2em; margin-bottom: 20px; opacity: 0.9;">
                Mais de 100+ produtos selecionados com os melhores preços da Shopee.
            </p>
            <a href="https://collshp.com/3409a?view=storefront" class="btn-white" target="_blank">
                🛒 ACESSAR MINHA VITRINE AGORA
            </a>
            <p style="margin-top: 25px; font-size: 0.95em;">
                🔥 Clique no link acima e confira todas as ofertas da minha coleção pessoal!
            </p>
        </div>

        <!-- SEÇÃO INFORMATIVA -->
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 30px; margin: 40px 0;">
            <div style="text-align: center; padding: 25px; background: white; border-radius: 20px; box-shadow: 0 5px 15px rgba(0,0,0,0.05);">
                <span style="font-size: 2.5em;">💰</span>
                <h3 style="color: #ee4d2d; margin: 15px 0;">Preços Imbatíveis</h3>
                <p>Os melhores preços da Shopee reunidos em um só lugar. Economia garantida!</p>
            </div>
            <div style="text-align: center; padding: 25px; background: white; border-radius: 20px; box-shadow: 0 5px 15px rgba(0,0,0,0.05);">
                <span style="font-size: 2.5em;">⭐</span>
                <h3 style="color: #ee4d2d; margin: 15px 0;">Produtos Avaliados</h3>
                <p>Selecionei apenas produtos bem avaliados por outros compradores.</p>
            </div>
            <div style="text-align: center; padding: 25px; background: white; border-radius: 20px; box-shadow: 0 5px 15px rgba(0,0,0,0.05);">
                <span style="font-size: 2.5em;">🚚</span>
                <h3 style="color: #ee4d2d; margin: 15px 0;">Entrega Rápida</h3>
                <p>Compre com tranquilidade, muitos produtos com frete grátis e entrega expressa.</p>
            </div>
        </div>

        <!-- LINK DIRETO REPETIDO PARA FACILITAR -->
        <div style="text-align: center; margin: 30px 0; padding: 20px; background: #fff3ef; border-radius: 15px;">
            <p style="font-size: 1.2em; margin-bottom: 10px;">🔽 ACESSE AGORA MINHA COLEÇÃO COMPLETA NA SHOPEE 🔽</p>
            <a href="https://collshp.com/3409a?view=storefront" style="color: #ee4d2d; font-weight: bold; font-size: 1.3em; word-break: break-all;" target="_blank">
                https://collshp.com/3409a?view=storefront
            </a>
        </div>

        <!-- RODAPÉ -->
        <footer>
            <p>🛍️ Achadinhos Shopee - Minha coleção pessoal de produtos incríveis</p>
            <p style="margin: 10px 0;">© 2024 - Todos os links direcionam para minha vitrine oficial na Shopee</p>
            <p style="margin-top: 15px;">
                <a href="https://collshp.com/3409a?view=storefront" style="color: #ee4d2d; text-decoration: none;" target="_blank">
                    🔗 Clique aqui para ver a vitrine completa
                </a>
            </p>
        </footer>
    </div>
</body>
</html>
