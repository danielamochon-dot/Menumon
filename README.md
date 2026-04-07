<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mis Menús de Arte</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            background-color: #2c3e50;
            padding: 40px;
            font-family: 'Segoe UI', sans-serif;
        }
        .menu-card {
            /* Medidas obligatorias */
            width: 400px; 
            height: 550px;
            /* Margen, Padding y Borde solicitados */
            margin: 20px;
            padding: 30px;
            border: 10px double #ffffff; 
            box-sizing: border-box;
            color: white;
            text-shadow: 2px 2px 8px rgba(0,0,0,0.9);
            border-radius: 15px;
            /* Propiedades de fondo solicitadas */
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            display: flex;
            flex-direction: column;
        }
        .breakfast {
            background-image: url("Copia de Claude-Monet-The-Waterlily-Pond-with-the-Japanese-Bridge-1899.jpg");
        }
        .lunch {
            background-image: url("Copia de MB-Mon-21_Monet_Steilkueste-von-Aval_1 2.jpg");
        }
        .dinner {
            background-image: url("cc4512ce9e2845f140221c0baa3de41e.jpg");
        }
        h1 { 
            text-align: center; 
            font-size: 2.5rem;
            margin-top: 0;
            border-bottom: 2px solid white;
        }
        ul { list-style: none; padding: 0; margin-top: 30px; }
        li { 
            margin-bottom: 20px; 
            padding: 10px;
            background: rgba(0, 0, 0, 0.6); /* Esto hace que el texto se lea perfecto */
            border-radius: 8px;
        }
        strong { display: block; font-size: 1.2rem; color: #f1c40f; }
        span { font-size: 0.9rem; font-style: italic; color: #ecf0f1; }
    </style>
</head>
<body>
    <div class="menu-card breakfast">
        <h1>Breakfast</h1>
        <ul>
            <li><strong>Waterlily Eggs</strong> <span>Omelette con hierbas de Giverny.</span></li>
            <li><strong>Bridge Toast</strong> <span>Pan artesanal con mermelada.</span></li>
            <li><strong>Artist Tea</strong> <span>Selección de tés frutales.</span></li>
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
