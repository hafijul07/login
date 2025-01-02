<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f4f4;
        }
        .container {
            text-align: center;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 300px;
        }
        h1 {
            color: #39b;
        }
        input[type="text"], input[type="password"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            background-color: #39b;
            color: white;
            border-radius: 4px;
            font-size: 16px;
            cursor: pointer;
        }
        button:hover {
            background-color: #2d8cbf;
        }
        a {
            display: block;
            margin-top: 10px;
            color: #666;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Login</h1>
        <p>Sign in to your account</p>
        <form>
            <input type="text" placeholder="username" name="username" required>
            <input type="password" placeholder="password" name="password" required>
            <button type="submit">Login</button>
        </form>
        <a href="#">I forgot my password. Click here to reset</a>
        <button onclick="window.location.href='register.html'">Register New Account</button>
    </div>
</body>
</html>
