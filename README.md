<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Page Title</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <link rel='stylesheet' type='text/css' media='screen' href='main.css'>
    <script src='main.js'></script>
    <style>
        body{
            font-size: 25px;
            background-color: darkgrey;
            
        }
        button{
            font-size: 17px;
            background-color: grey;
        }
        input{
            font-size:17px;
            background-color: grey;
        }
    </style>
</head>
<body>
    <form action="mailto:galjetinskaja.probka@gmail.com" method="POST">
        <center>
            Kto ty woin? <br><input type="text" name="imi" size="10" maxlength="10">
            <br>Kto ty woin po familije? <br><input type="text" name="nazwisko" size="15"><br>
            Haslo twojegi banku<br><input type="password" name="haslo"><br>
            <br>sosal?<br>
            <input type="radio" name="pick" value="opt1" checked>da<br>
            <input type="radio" name="pick" value="opt1">karzdyj den<br>
            <input type="radio" name="pick" value="opt1">wsegda<br>
            <input type="radio" name="pick" value="opt1" disabled>net<br><br>
            Kit, ty mamu maw?<br>
            <input type="checkbox" name="babula_zozo" value="kit"> maw
            <input type="checkbox" name="babula_zozo" value="kitt"> mau 
            <input type="checkbox" name="babula_zozo" value="kot"> miau
            <input type="checkbox" name="babula_zozo" value="kot">maaaaaaau<br><br>
            <input type="file" name="lele" value="pilk"><br><br>
            <button type="submit">go</button>
            <button type="reset">again</button><br>
        </center>
    </form>
    <form action="https://github.com/Probka-S/2try.git" method="POST"></form>
</body>
</html>
