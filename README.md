# Menumon
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Menús Artísticos</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            background-color: #f0f0f0;
            padding: 40px;
            font-family: 'Garamond', serif;
        }
        .menu-card {
            width: 400px;
            height: 550px;
            margin: 20px; 
            padding: 35px; 
            border: 10px double #2c3e50; 
            box-sizing: border-box;
            color: white;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.9);
            border-radius: 10px;
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
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
            border-bottom: 2px solid white; 
            padding-bottom: 10px;
            margin-top: 0;
        }
        .menu-list {
            list-style: none;
            padding: 0;
            margin-top: 30px;
        }
        .menu-item {
            margin-bottom: 20px;
            font-size: 1.3rem;
            background: rgba(0, 0, 0, 0.4); /* Para que el texto se lea mejor */
            padding: 10px;
            border-radius: 5px;
        }
        .description {
            display: block;
            font-size: 0.9rem;
            font-style: italic;
            opacity: 0.9;
        }
    </style>
</head>
<body>
    <div class="menu-card breakfast">
        <h1>Breakfast</h1>
        <ul class="menu-list">
            <li class="menu-item">
                <strong>Waterlily Omelette</strong>
                <span class="description">Huevos orgánicos con finas hierbas del jardín.</span>
            </li>
            <li class="menu-item">
                <strong>Bridge Croissants</strong>
                <span class="description">Pan recién horneado con mantequilla francesa.</span>
            </li>
            <li class="menu-item">
                <strong>Giverny Fruit Bowl</strong>
                <span class="description">Frutas de temporada con miel de lavanda.</span>
            </li>
            <li class="menu-item">
                <strong>Artist's Latte</strong>
                <span class="description">Café artesanal con espuma de vainilla.</span>
            </li>
        </ul>
    </div>
    <div class="menu-card lunch">
        <h1>Lunch</h1>
        <ul class="menu-list">
            <li class="menu-item">
                <strong>Cliffside Salmon</strong>
                <span class="description">Salmón fresco con costra de cítricos.</span>
            </li>
            <li class="menu-item">
                <strong>Ocean Breeze Salad</strong>
                <span class="description">Arúgula, queso feta y vinagreta marina.</span>
            </li>
            <li class="menu-item">
                <strong>Seaside Risotto</strong>
                <span class="description">Arroz cremoso con espárragos y parmesano.</span>
            </li>
            <li class="menu-item">
                <strong>Azure Lemonade</strong>
                <span class="description">Limonada con menta y arándanos azules.</span>
            </li>
        </ul>
    </div>
    <div class="menu-card dinner">
        <h1>Dinner</h1>
        <ul class="menu-list">
            <li class="menu-item">
                <strong>Velvet Beef Roast</strong>
                <span class="description">Corte premium en salsa de vino tinto.</span>
            </li>
            <li class="menu-item">
                <strong>Silk Truffle Pasta</strong>
                <span class="description">Pasta artesanal con aceite de trufa blanca.</span>
            </li>
            <li class="menu-item">
                <strong>Pink Lace Tart</strong>
                <span class="description">Tarta de frambuesa y chocolate blanco.</span>
            </li>
            <li class="menu-item">
                <strong>Vintage Red Wine</strong>
                <span class="description">Copa de vino reserva de la casa.</span>
            </li>
        </ul>
    </div>

</body>
</html>
