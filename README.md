# HTML_Weather
<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<title>Weather App</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<div class="container">
		<h1>Weather App</h1>
		<input type="text" id="city" placeholder="Enter City">
		<button id="submit" onclick="getWeather()">Get Weather</button>
		<div id="output"></div>
	</div>
	<script src="script.js"></script>
</body>
</html>
