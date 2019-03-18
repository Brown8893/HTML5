* ex_0321_text

```
<!DOCTYPE html>
<html>
<body>

<h2>The pattern Attribute</h2>
<p>The pattern attribute specifies a regular expression that the input element's value is checked against.</p>
    
<form action="/action_page.php">
    Country code: <input type="text" name="country" pattern="[A-Za-z]{3}" title="Three letter">
    <input type="submit">
</form>
    
<p><strong>Note:</strong> The pattern attribute of the input tag is not supported in Internet Explorer 9 and earlier versions, or Safari 10 and earler versions.</p>
    
</body>
</html>
```
