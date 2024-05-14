
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Login Page</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        background-color: hsl(0, 0%, 100%);
    }
    
    .container {
        background-color: #000000;
        padding: 40px;
        border-radius: 8px;
        box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.1);
        width: 400px;
    }
    
    .container h2 {
        text-align: center;
        margin-bottom: 30px;
    }
    
    .container input[type="text"],
    .container input[type="password"] {
        width: calc(100% - 20px);
        padding: 10px;
        margin-bottom: 20px;
        border: 1px solid #ccc;
        border-radius: 5px;
    }
    
    .container input[type="submit"] {
        width: 100%;
        padding: 10px;
        border: none;
        border-radius: 5px;
        background-color: #4caf50;
        color: #fff;
        cursor: pointer;
        font-size: 16px;
        transition: background-color 0.3s ease;
    }
    
    .container input[type="submit"]:hover {
        background-color: #45a04e;
    }
</style>
</head>
<body>
    <div class="container">
        <h2>Login</h2>
        <form>
            <input type="text" placeholder="Username" required>
            <input type="password" placeholder="Password" required>
            <input type="submit" value="Login">
        </form>
    </div>
</body>
</html>
