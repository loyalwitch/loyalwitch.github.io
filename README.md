<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>loyal</title>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    min-height: 100vh;
    background: #080808;
    color: white;
    font-family: Arial, Helvetica, sans-serif;
    display: flex;
    align-items: center;
    justify-content: center;
}

.container {
    width: 90%;
    max-width: 500px;
    text-align: center;
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
    color: #aaa;
}

h1 {
    font-size: 32px;
    font-weight: 600;
    margin-bottom: 10px;
}

.username {
    color: #777;
    font-size: 15px;
    margin-bottom: 28px;
}

.link {
    display: block;
    padding: 14px;

    border: 1px solid #252525;
    border-radius: 10px;

    background: #0d0d0d;
    color: #ddd;
    text-decoration: none;

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

<div class="container">

    <div class="avatar">L</div>

    <h1>loyal</h1>

    <div class="username">@loyalwitch</div>

    <a class="link" href="https://github.com/loyalwitch" target="_blank">
        GitHub
    </a>

    <div class="footer">
        loyalwitch.github.io
    </div>

</div>

</body>
</html>
