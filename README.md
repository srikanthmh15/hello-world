<head>
	<title> HTML Cheat Sheets </title>
</head> 
<body>
	<a href="blog.html"> Go to Blog </a>
	<!--Headings-->
  <h1><i><b><u>My Website</u></b></i></h1>
	<!--Paragarph-->
	<p>
		<strong>Lorem ipsum dolor sit amet,</strong> consectetur adipisicing elit, sed do eiusmod
		tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
		quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
		consequat. Duis aute irure <strong><em>dolor</em></strong> in reprehenderit in voluptate velit esse
		cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
		proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
	</p>
	<!--lists-->
	<ul>
		<li>Home</li>
		<li>Products</li>
		<li>Services</li>
		<li>About Us</li>
		<li>Contact Us</li>
	</ul>
	<ol>
		<li>Home</li>
		<li>Products</li>
		<li>Services</li>
		<li>About Us</li>
		<li>Contact Us</li>
	</ol>
	<!--Table-->
	<table>
		<thead>
			<tr>
				<th>Name:</th>
				<th>Age:</th>
				<th>Email:</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Srikanth</td>
				<td>29</td>
				<td>srikanth@menet.in</td>
			</tr>
		</tbody>
	</table>
	<br>
	<!--formes-->
	<form action="process.php" method="POST">
		<dev>
			<label>First Name</label>
			<input type="text" name="First Name">
		</dev>
		<br>
		<br>
		<div>
			<label>Last Name</label>
			<input type="text" name="Last Name">
		</div>
		<br>
		<div>
			<label>Email</label>
			<input type="Email" name="Email">
		</div>
		<br>
		<div>
			<label>Message</label>
		</div>
		<br>
		<div>
			<label>Gender</label>
			<select name="Gender">
				<option value="Male">Male</option>
				<option value="Female">Female</option>
				<option value="Others">Others</option>
			</select>
		</div>
</body>
</html>
