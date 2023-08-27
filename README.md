# Weather Application
<!DOCTYPE html>
<html>
<head>
	<title>My Weather Application</title>
	<link rel="stylesheet" type="text/css" href="weather.css">
	<link rel="stylesheet" type="text/css" href="https://fonts.google.com/">
</head>
<body>
	<div class="container">
		<div class="heading">
			<h1>Weather Application</h1>
		</div>
		<div class="input">
			<input type="text" name="search" class="input-search" placeholder="Search for the city..">
		</div>
		<div class="box">
		<div class="location">
			<div class="location-city"></div>
			<div class="location-date"></div>
		</div>
		<div class="temperature">
			<div class="temperature-temp"><span></span></div>
			<div class="temperature-type"></div>
			<div class="temperature-range"></div>
		</div>
		</div>
	</div>

	<script src="weather.js"></script>
</body>
</html>
