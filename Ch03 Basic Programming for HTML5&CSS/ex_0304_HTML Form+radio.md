* ex_0304_HTML Form+radio

```
<!DOCTYPE>
<html>
<body>

    <h1>HTML Forms</h1>
    <link rel="stylesheet" href="ex_0304.css">
    
<form action="/action_page.php">
    First name:
    <input type="text" name="firstname" style="background-color:orange" value="Yu-Xiang">
    <br>
    Last name:
    <input type="text" style="background-color:orange" name="lastname" value="Su">
    <br>
    Your student ID:
    <input type="text" style="background-color:orange" name="Your student ID" value="4070E021">
    <br>
    <input type="radio" name="dept" value="Male" checked> Male<br>
    <input type="radio" name="dept" value="Male" checked> Female<br>
    <input type="radio" name="dept" value="Male" checked> Other<br><br>
    <input type="submit" style="background-color:orange" value="Submit">
</form>
    
    <p>If you click the "submit" button, the form-data will be sent to a page called "/action_page.php".</p>
    
</body>
</html>
```
