* ex_0309_HTML Form+background+option+size3

* html
```
<!DOCTYPE>
<html>
<body>

    <h1>HTML Forms</h1>
    <link rel="stylesheet" href="ex_0309.css">
    
<form action="/action_page.php">
    First name:
    <input type="text" name="firstname" style="background-color:orange" value="Yu-Xiang">
    <br>
    Last name:
    <input type="text" style="background-color:orange" name="lastname" value="Su">
    <br>
    Your student ID:
    <input type="text" style="background-color:orange" name="Your student ID" value="4070E021">
    <br><br>
            <select name="goods" size=3>
            <option value="op1">TV</option>
            <option value="op1" selected style="background-color:lawngreen">Android phone</option>
            <option value="op1">iPhone</option>
            <option value="op1">Bick</option>
        </select><br><br>
    <input type="submit" style="background-color:orange" value="Submit">
</form>
    
    <p>If you click the "submit" button, the form-data will be sent to a page called "/action_page.php".</p>
    
</body>
</html>
```

* css
```
input {
  color: blue;
  background-color: orange;
  border: 2px solid black;
}

option {
  color: white;
  background-color: dodgerblue;
}

p {
  color: blue;
}
```
