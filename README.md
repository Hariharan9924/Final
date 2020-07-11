<!DOCTYPE html>
<html lang="en">
<head>
<title>Page Title</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: Arial, Helvetica, sans-serif;
  background: lightblue

</style>
<link rel="stylesheet" type="text/css" href="web.css">
</head>
<body>

<h1>My Website</h1>

<div class="container">

	<span class="text1">Welcome to our page</span>
		<span class="text1">Hello</span>
<ul>

	<li><a href="home.html">Home</li>
		<br>
		<li><a href="aboutus.html">About Us</li>
			<br>
         <li><a href="Skills.html">Our Works</li>
         	<br>

         <li><a href="Contact.html">Contact Us</li>

</ul>

<br>

<p> Website created by Sowbi and Hari </p>

</body>
</html>


*{
	padding: 0;
	margin: 0;
	font-family: sans-serif; 
} 
body{
	background: #000;

}
.container{
	text-align: center;
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%,-50%);
	width: 100%;

}
.container span{
	color: white;
	text-transform: uppercase;
	display: block;

}
.text1{
	font-size: 60px;
	font-weight: 700;
	letter-spacing: 8px;
	margin-bottom: 20px;


}
.text2{
	font-size: 30px;
	color: #6ab04c;

}
@keyframes text {
	0%{
		color: black;
		margin-bottom: -40px;

	}
	30%{
		letter-spacing: 25px;
		margin-bottom: -40px;

	}
	85%{
		letter-spacing: 8px;
		margin-bottom: -40px;

	}
}
