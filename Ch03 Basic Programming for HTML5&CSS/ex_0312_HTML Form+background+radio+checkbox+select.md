* ex_0312_HTML Form+background+radio+checkbox+select

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
    
    <h1>Radio Buttons</h1>
    <input type="radio" name="dept" value="Male" checked> IS department<br>
    <input type="radio" name="dept" value="Male" > IM department<br>
    <input type="radio" name="dept" value="Male" > IC department<br>
    
    <h1>Checkboxes</h1>
    <input type="checkbox" name="vehicle1" value="apple" checked> apple<br>
    <input type="checkbox" name="vehicle2" value="orange" checked> orange<br>
    <input type="checkbox" name="vehicle3" value="cherry"> cherry<br><br>
    <input type="submit" style="background-color:orange" value="Submit">
</form>
    
    <p>If you click the "submit" button, the form-data will be sent to a page called "/action_page.php".</p>
    
</body>
</html>
```
