<?php
include("connection.php");
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="form">
        <h1>Login from </h1>
        <form name="form" action="" method="post">
       <label for="user">* User Name: </label><input type="text" id="user" name="user">
       <br>
       <br>
       <label for="pass">* password :</label><input type="text" name="password" id="pass">
       <br><br>
       <input type="submit" name="" id="btn" value="Login" name="submit">
        </form>
    </div>
</body>
</html>
