

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>
	<h1>Feedback Form</h1>
	<p>Please fill out this form to help us improve our site.</p>
	<label>  Name: <input name = "name" type = "text" size = "20" maxlength="10"> 
	</label></p>
	<p>Comments: </p>
	<textarea rows="4" cols="50">Enter comments here.</textarea></p>
	<label> E-mail Address: <input name = "address" type="text" size="30" maxlength="50" >

	<h3><strong> Things you liked:</strong></h3>
	<form action="/action_page.php" method ="get">
		Site design <input type ="checkbox" name="liked" value="site_design" >
		Links <input type ="checkbox" name="liked" value="links" >
		Ease of use <input type ="checkbox" name="liked" value="ease_of_use" >
		Images <input type ="checkbox" name="liked" value="images" >
		Source code <input type ="checkbox" name="liked" value="source_code" >
	</form>

	<h3><strong> How did you get to our site?:</strong></h3>
	<form action="/action_page.php" method="get">
		Search engine<input type="radio" name="how" value="search_engine">
		Links from another site<input type="radio" name="how" value="another_site">
		Deitel.com Web site<input type="radio" name="how" value="deitel">
		Reference in a book<input type="radio" name="how" value="reference">
		Other<input type="radio" name="how" value="other">
	</form>

	<h3> Rate our site: </h3>
	<form action ="/action_page.php">
		<select name="rating">
			<option value="amazing">amazing</option>
			<option value="very good">very good</option>
			<option value="good">good</option>
			<option value="fair">fair</option>
			<option value="poor">poor</option>
		</select>
	<br><br>
	<form method="post" action="https://www.deitel.com">
	
	<input type = "submit" value="Submit">
	<input type="reset" value="Clear" >
	<title></title>
</body>
</html>
