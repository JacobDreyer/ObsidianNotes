## HTML Form
```html
<form
	  action="http://example.com/join.php"
	  method="get">

		This is where the form controls will appear

</form>
```

#### Text Input
```html
<form
	  action="http://example.com/join.php">
	  Username:
	  <input type="text" name="username"
			size="15" maxlength="30" />
</form>
```

```html
<p> Username:
	<input type="text" name="username" size="15" maxlength="30" />
</p>

<p> Password:
	<input type="password" name="password" size="15" maxlength="30" />
</p>
```



#### Submit Button
```html
<form action="http://eg.com/email.php">
	<p> Subscribe To Our Email List: </p>

	<input type="text" name="email" />

	<input type="submit" value="Subscribe" />

</form>
```

#### Image Button
```html
<form action="http://eg.com/email.php">
	<p> Subscribe to our email list:</p>

	<input type="text" name="email" />

	<input type="image" src="images/subscribe.jpg" width="100"
		height="20" />

</form>
```

#### Buttons
```html
<form action="http://eg.com/add.php">
	<button>
		<img src="images/add.gif" alt="add" width="10" height="20" />
	</button>
</form>
```
