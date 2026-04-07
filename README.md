<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Menús de Arte Monet</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            background-color: #edeff2;
            padding: 40px;
            font-family: 'Georgia', serif;
        }
        .menu-card {
            width: 400px;
            height: 550px;
            margin: 20px;
            padding: 30px;
            border: 8px double #34495e;
            box-sizing: border-box;
            color: white;
            text-shadow: 2px 2px 4px rgba(0,0,0,1);
            border-radius: 12px;
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
        }
        .breakfast {
            background-image: url("Copia%20de%20Claude-Monet-The-Waterlily-Pond-with-the-Japanese-Bridge-1899.jpg");
        }
        .lunch {
            background-image: url("Copia%20de%20MB-Mon-21_Monet_Steilkueste-von-Aval_1%202.jpg");
        }
        .dinner {
            background-image: url("cc4512ce9e2845f140221c0baa3de41e.jpg");
        }
        h1 { 
            text-align: center; 
            font-size: 2.2rem;
            margin-top: 0;
            border-bottom: 1px solid rgba(255,255,255,0.5);
            padding-bottom: 10px;
        }
        ul { list-style: none; padding: 0; margin-top: 40px; }
        li { 
            margin-bottom: 25px; 
            padding: 10px;
            background: rgba(0, 0, 0, 0.5); /* Fondo oscuro para leer el texto sobre la pintura */
            border-radius: 8px;
        }
        strong { display: block; font-size: 1.2rem; color: #f1c40f; }
        span { font-size: 0.9rem; font-style: italic; }
    </style>
</head>
<body>
    <div class="menu-card breakfast">
        <h1>Breakfast</h1>
        <ul>
            <li><strong>Waterlily Eggs</strong> <span>Omelette con hierbas de Giverny.</span></li>
            <li><strong>Bridge Toast</strong> <span>Pan artesanal con mermelada.</span></li>
            <li><strong>Morning Tea</strong> <span>Selección de tés frutales.</span></li>
        </ul>
    </div>
    <div class="menu-card lunch">
        <h1>Lunch</h1>
        <ul>
            <li><strong>Cliffside Salad</strong> <span>Vegetales frescos y aderezo césar.</span></li>
            <li><strong>Ocean Salmon</strong> <span>Salmón sellado a la plancha.</span></li>
            <li><strong>Azure Drink</strong> <span>Limonada refrescante de menta.</span></li>
        </ul>
    </div>
    <div class="menu-card dinner">
        <h1>Dinner</h1>
        <ul>
            <li><strong>Silk Steak</strong> <span>Corte de res en salsa de vino.</span></li>
            <li><strong>Velvet Pasta</strong> <span>Pasta cremosa con trufa.</span></li>
            <li><strong>Royal Wine</strong> <span>Copa de vino tinto de la casa.</span></li>
        </ul>
    </div>
</body>
</html>
