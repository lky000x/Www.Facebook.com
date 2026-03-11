<!DOCTYPE html>
<html>
<head>
    <title>Facebook - Iniciar Sesión</title>
    <style>
        body {
            background-color: #f0f2f5;
            font-family: Arial, sans-serif;
        }
        .login-box {
            width: 360px;
            margin: 100px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            text-align: center;
        }
        .logo {
            color: #1877f2;
            font-size: 40px;
            font-weight: bold;
            margin-bottom: 20px;
        }
        input {
            width: 100%;
            padding: 14px;
            margin: 8px 0;
            border: 1px solid #dddfe2;
            border-radius: 6px;
            font-size: 17px;
            box-sizing: border-box;
        }
        button {
            background-color: #1877f2;
            color: white;
            padding: 14px;
            width: 100%;
            border: none;
            border-radius: 6px;
            font-size: 20px;
            font-weight: bold;
            margin: 10px 0;
            cursor: pointer;
        }
        a {
            text-decoration: none;
            color: #1877f2;
            font-size: 14px;
        }
    </style>
</head>
<body>

<div class="login-box">
    <div class="logo">facebook</div>
    <form>
        <input type="text" placeholder="Correo electrónico o número de teléfono">
        <input type="password" placeholder="Contraseña">
        <button type="button">Iniciar sesión</button>
        <br>
        <a href="#">¿Olvidaste tu contraseña?</a>
    </form>
</div>

</body>
</html>
