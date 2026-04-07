<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Menús de Arte</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            background-color: #1a1a1a;
            padding: 40px;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        .menu-card {
            width: 400px;
            height: 550px;
            margin: 20px;
            padding: 30px;
            border: 10px double #ffffff;
            box-sizing: border-box;
            color: white;
            text-shadow: 2px 2px 4px rgba(0,0,0,1);
            border-radius: 15px;
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            display: flex;
            flex-direction: column;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
        }
        .breakfast {
            background-image: url('Copia de Claude-Monet-The-Waterlily-Pond-with-the-Japanese-Bridge-1899.jpg');
        }
        .lunch {
            background-image: url('Copia de MB-Mon-21_Monet_Steilkueste-von-Aval_1 2.jpg');
        }
        .dinner {
            background-image: url('cc4512ce9e2845f140221c0baa3de41e.jpg');
        }
        h1 { 
            text-align: center; 
            font-size: 2.5rem; 
            margin: 0; 
            border-bottom: 2px solid white;
            padding-bottom: 10px;
        }
        ul { list-style: none; padding: 0; margin-top: 40px; }
        li { 
            margin-bottom: 25px; 
            padding: 12px;
            background: rgba(0, 0, 0, 0.7); 
            border-radius: 8px;
            border-left: 5px solid #f1c40f;
        }
        strong { display: block; font-size: 1.2rem; color: #f1c40f; }
        span { font-size: 0.9rem; font-style: italic; }
    </style>
</head>
<body>
    <div class="menu-card breakfast">
        <h1>Breakfast</h1>
        <ul>
            <li><strong>Waterlily Eggs</strong> <span>Omelette con finas hierbas de Giverny.</span></li>
            <li><strong>Bridge Toast</strong> <span>Pan artesanal con mermelada de frutos.</span></li>
            <li><strong>Garden Coffee</strong> <span>Café recién molido con vainilla.</span></li>
        </ul>
    </div>
    <div class="menu-card lunch">
        <h1>Lunch</h1>
        <ul>
