
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modas Boutique</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        footer {
            background: linear-gradient(135deg, #ff6f61, #ffcc00, #f6e58d);
            padding: 40px;
            text-align: center;
            border-top: 5px solid #d63031;
            margin-top: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.15);
        }
        footer h2 {
            color: #2c3e50;
            margin-bottom: 15px;
            font-size: 2em;
            text-shadow: 1px 1px 2px rgba(255, 255, 255, 0.8);
        }
        .contacto {
            display: flex;
            justify-content: space-around;
            align-items: center;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .contacto div {
            background: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            padding: 15px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            width: 150px;
            text-align: center;
            margin: 10px;
            position: relative;
        }
        .contacto div img {
            width: 40px;
            height: 40px;
            margin-bottom: 10px;
        }
        .contacto a {
            color: #2980b9;
            text-decoration: none;
            font-weight: bold;
        }
        .contacto a:hover {
            color: #e67e22;
        }
        .direccion {
            margin-top: 20px;
            padding: 15px;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            font-size: 1.2em;
            color: #34495e;
        }
    </style>
</head>
<body>
    <footer>
        <h2>Contacto</h2>
        <div class="contacto">
            <div>
                <img src="https://img.icons8.com/ios-filled/50/000000/email.png" alt="Correo">
                <p><a href="mailto:modasbayola@gmail.com">Correo</a></p>
            </div>
            <div>
                <img src="https://img.icons8.com/ios-filled/50/000000/phone.png" alt="Teléfono">
                <p><a href="tel:03564383297">Teléfono</a></p>
            </div>
            <div>
                <img src="https://img.icons8.com/ios-filled/50/000000/instagram-new.png" alt="Instagram">
                <p><a href="https://www.instagram.com/modasbayola?igsh=MTloZXk3Yzd5c2N1Yw==" target="_blank">Instagram</a></p>
            </div>
        </div>
        <div class="direccion">
            <h2>Dirección</h2>
            <p>San Martin 226, Devoto, Córdoba, Argentina 2424</p>
        </div>
    </footer>
</body>
</html>
