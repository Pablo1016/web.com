<html>
<head>
    <title>Página de Inicio de Sesión</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0B66A2;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .login-container {
            background: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
            text-align: center;
            color: black;
        }

        .logo {
            max-width: 300px;
            margin: 0 auto;
        }

        .decorative-image {
            max-width: 300px;
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <img class="logo" src="Logo.JPG" alt="Logo de la empresa">
        <h2>Puedes Iniciar Sesion Aquí</h2>
        <form action="Write.php" method="POST">
            <input type="text" id="usuario" name="usuario"   
              placeholder="Usuario" required>
            <input type="password" id="password" name="password" 
              placeholder="Contraseña" required>
            <input type="submit" value="Ingresar" button="color: blue";>
        </form>
        <img class="decorative-image" src="cafe.JPG"   
         alt="Imagen decorativa">
    </div>
</body>
</html>
