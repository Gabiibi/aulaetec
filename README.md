# aulaetec
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet"  type="text/css"  href="./CSS/style.css">
</head>
<body>

    <DIV class="caixa">

    <h1>Login</h1>
    <form action="cadastro.html">
    <label for="login">Login:</label><br>
    <input type="text" id="login" name="login" placeholder="login"><br>
    <label for="senha">Senha:</label><br>
    <input type="text" id="senha" name="senha" placeholder="senha"><br>
    <input type="submit" value="entrar"
    
    </form>
    
    <a href="cadastro.html"></a>

    </DIV>
</body>
</html>



parte css
body {
    background-color: #f0f0f0;
    font-family: 'Courier New', Courier, monospace; 
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.caixa {
    background-color: #5a337a; 
    padding: 50px; 
    border: 1px solid #a13a3a; 
    border-radius: 8px; 
    text-align: center; 
}

a {
    color: #2b8da5; 
    text-decoration: none; 
}
a:hover {
    text-decoration: underline; 
}

form {
    margin-top: 20px; 
}

input[type="text"],
select {
    width: 100%; 
    padding: 10px; 
    margin-bottom: 10px; 
    border: 1px solid #4caf50; 
    border-radius: 5px; 
    box-sizing: border-box; 
}

input[type="submit"] {
    background-color: #4caf50; 
    color: #fff; 
    padding: 10px 20px; 
    border: none; 
    border-radius: 5px; 
    cursor: pointer; 
    transition: background-color 0.3s; 
}
input[type="submit"]:hover {
    background-color: #acd833; 
}
