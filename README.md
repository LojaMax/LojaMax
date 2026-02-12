<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Achadinhos Shopee | Vitrine Oficial</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(145deg, #f5f5f5 0%, #ffffff 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 800px;
            width: 100%;
            background: white;
            border-radius: 40px;
            box-shadow: 0 25px 50px -8px rgba(238, 77, 45, 0.25);
            padding: 40px 30px;
            text-align: center;
            border: 1px solid rgba(255, 115, 55, 0.2);
        }

        .logo {
            font-size: 4em;
            margin-bottom: 15px;
            line-height: 1;
        }

        h1 {
            font-size: 2.4em;
            color: #ee4d2d;
            margin-bottom: 10px;
            font-weight: 800;
            letter-spacing: -0.5px;
        }

        .sub {
            font-size: 1.2em;
            color: #555;
            margin-bottom: 30px;
            font-weight: 400;
            max-width: 500px;
            margin-left: auto;
            margin-right: auto;
        }

        .btn-vitrine {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            background: linear-gradient(145deg, #ee4d2d, #ff7337);
            color: white;
            padding: 20px 25px;
            border-radius: 60px;
            text-decoration: none;
            font-weight: 700;
            font-size: 1.6em;
            margin: 30px 0 25px;
            transition: all 0.25s ease;
            box-shadow: 0 12px 25px rgba(238, 77, 45, 0.4);
            border: 2px solid rgba(255,255,255,0.3);
        }

        .btn-vitrine:hover {
            transform: scale(1.02);
            background: linear-gradient(145deg, #ff5733, #ff8c5a);
            box-shadow: 0 18px 35px rgba(238, 77, 45, 0.5);
            border-color: white;
        }

        .btn-vitrine:active {
            transform: scale(0.98);
        }

        .link-direto {
            background: #fef1ed;
            padding: 18px 20px;
            border-radius: 50px;
            margin: 20px 0 15px;
            word-break: break-all;
            border: 1px dashed #ee4d2d;
        }

        .link-direto a {
            color: #ee4d2d;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1em;
        }

        .link-direto a:hover {
            text-decoration: underline;
        }

        .info {
            display: flex;
            justify-content: center;
            gap: 25px;
            margin: 35px 0 20px;
            flex-wrap: wrap;
        }

        .badge {
            background: #f5f5f5;
            padding: 8px 18px;
            border-radius: 50px;
            color: #333;
            font-size: 0.95em;
            display: inline-flex;
            align-items: center;
            gap: 6px;
            border: 1px solid #e0e0e0;
        }

        footer {
            margin-top: 30px;
            color: #777;
            font-size: 0.9em;
            border-top: 1px solid #eee;
            padding-top: 25px;
        }

        @media (max-width: 480px) {
            .container { padding: 30px 20px; }
            h1 { font-size: 1.8em; }
            .btn-vitrine { font-size: 1.3em; padding: 16px 20px; }
            .badge { font-size: 0.85em; }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- EMOJI DE DESTAQUE -->
        <div class="logo">🛍️✨</div>
        
        <!-- TÍTULO DIRETO -->
        <h1>Achadinhos Shopee</h1>
        <div class="sub">
            Minha coleção pessoal com os melhores preços e produtos selecionados
        </div>

        <!-- BOTÃO PRINCIPAL GIGANTE - VER VITRINE COMPLETA -->
        <a href="https://collshp.com/3409a?view=storefront" class="btn-vitrine" target="_blank">
            <span>🔗</span> VER VITRINE COMPLETA <span>→</span>
        </a>

        <!-- LINK DIRETO COPIA E COLA -->
        <div class="link-direto">
            🔗 <strong>Link direto:</strong> 
            <a href="https://collshp.com/3409a?view=storefront" target="_blank">
                collshp.com/3409a?view=storefront
            </a>
        </div>

        <!-- SELOS DE CONFIABILIDADE (SIMPLES E OBJETIVOS) -->
        <div class="info">
            <span class="badge">⭐ +100 produtos</span>
            <span class="badge">💰 Preços exclusivos</span>
            <span class="badge">🚚 Frete grátis disponível</span>
        </div>

        <!-- CHAMADA FINAL SUPER OBJETIVA -->
        <div style="margin: 25px 0 10px; padding: 15px; background: #fff9f7; border-radius: 20px;">
            <p style="font-size: 1.2em; font-weight: 600; color: #ee4d2d;">
                👆 Clique no botão laranja acima 👆
            </p>
            <p style="color: #555; margin-top: 5px;">
                Você será redirecionado direto para minha vitrine na Shopee!
            </p>
        </div>

        <!-- RODAPÉ APENAS COM LINK -->
        <footer>
            <a href="https://collshp.com/3409a?view=storefront" 
               style="color: #ee4d2d; text-decoration: none; font-weight: 600;" 
               target="_blank">
                🔗 collshp.com/3409a?view=storefront
            </a>
            <p style="margin-top: 12px; color: #999;">
                © 2024 · Achadinhos Shopee · Vitrine oficial
            </p>
        </footer>
    </div>
</body>
</html>
