<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>loyalwitching</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            min-height: 100vh;
            background: #080808;
            color: #fff;
            font-family: Arial, Helvetica, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            text-align: center;
            width: 90%;
            max-width: 500px;
        }

        .avatar {
            width: 110px;
            height: 110px;
            margin: 0 auto 25px;
            border-radius: 50%;
            background: #151515;
            border: 1px solid #292929;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 42px;
            font-weight: 600;
            color: #aaa;
        }

        h1 {
            font-size: 32px;
            font-weight: 600;
            letter-spacing: -1px;
            margin-bottom: 10px;
        }

        .username {
            color: #777;
            font-size: 15px;
            margin-bottom: 28px;
        }

        .links {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .link {
            display: block;
            padding: 14px;
            border: 1px solid #252525;
            border-radius: 10px;
            color: #ddd;
            text-decoration: none;
            background: #0d0d0d;
            transition: 0.2s ease;
        }

        .link:hover {
            background: #151515;
            border-color: #444;
            transform: translateY(-2px);
        }

        .footer {
            margin-top: 30px;
            color: #444;
            font-size: 12px;
        }
    </style>
</head>

<body>

    <main class="container">

        <div class="avatar">L</div>

        <h1>loyalwitching</h1>

        <div class="username">@loyalwitching</div>

        <div class="links">
            <a class="link" href="https://github.com/loyalwitching" target="_blank">
                GitHub
            </a>
        </div>

        <div class="footer">
            loyalwitching.github.io
        </div>

    </main>

</body>
</html>
