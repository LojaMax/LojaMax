<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Achadinhos Shopee</title>
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
            max-width: 700px;
            width: 100%;
            background: white;
            border-radius: 40px;
            box-shadow: 0 25px 50px -8px rgba(238, 77, 45, 0.25);
            padding: 50px 30px;
            text-align: center;
            border: 1px solid rgba(255, 115, 55, 0.2);
        }

        h1 {
            font-size: 2.8em;
            color: #ee4d2d;
            margin-bottom: 20px;
            font-weight: 800;
            letter-spacing: -1px;
        }

        .btn-vitrine {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            background: linear-gradient(145deg, #ee4d2d, #ff7337);
            color: white;
            padding: 22px 30px;
            border-radius: 60px;
            text-decoration: none;
            font-weight: 700;
            font-size: 1.8em;
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

        @media (max-width: 480px) {
            .container { padding: 40px 20px; }
            h1 { font-size: 2.2em; }
            .btn-vitrine { font-size: 1.5em; padding: 18px 25px; }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Achadinhos Shopee</h1>
        
        <a href="https://collshp.com/3409a?view=storefront" class="btn-vitrine" target="_blank">
            <span>🔗</span> VER VITRINE COMPLETA <span>→</span>
        </a>
    </div>
</body>
</html>
