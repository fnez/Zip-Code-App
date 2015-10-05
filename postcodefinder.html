<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Postal Code Finder</title>
	<link href='https://fonts.googleapis.com/css?family=Montserrat:400,700' rel='stylesheet' type='text/css'>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
	<style type="text/css">
	body {
		background: url('city_img.jpg');
		background-repeat: no-repeat;
		background-size: cover;
		font-family: 'Montserrat', sans-serif;
	}
	#container {
		margin: 15em auto;
		text-align: center;
		background-color: rgba(102, 153, 153, .4);
		width: 70%;
		padding: 60px 30px;
		border-radius: 5%;
	}
	#container h1 {
		font-size: 4em;
	}
	#container p {
		font-size: 2em;
		color: white;
	}
	#myButton {
		padding: 15px 20px;
		border-style: none;
		border-radius: 5%;
		color: white;
		background-color: #339933;
		font-size: 1.2em;
		top: 300px;
		left: 240px;
		display: block;
		margin: 20px auto;
		width: 192px;
	}
	#myButton:hover {
		cursor: pointer;
	}
	.form-control {
		padding: 10px;
		border-style: none;
		width: 260px;
	}
	.zipCodeContainer {
		color: white;
		padding-top: 10px;
		font-size: 1.5em;
		font-style: bold;
	}
	.error {
		color: tomato;
	}

	</style>
</head>
<body>
<div id="container">
	<h1>Zip Code Finder</h1>
	<p>Enter an address to find the zip code</p>
	<input type="text" class="form-control" name="address" id="address" placeholder="New York, London, Dubai...">
	<div id="zipCode" class="zipCodeContainer"></div>
	<button id="myButton">Find My Zip Code</button>
</div>



<script>
$("#myButton").click(function (event) {

	var result = 0;

	$.ajax({
	type: 'GET',
	url: "https://maps.googleapis.com/maps/api/geocode/xml?address="+encodeURIComponent($('#address').val())+"&key=AIzaSyAXjxXYQnYNCaLXDErmVIBvAsculIJ8DK4",
	dataType: 'xml',
	success: processXML
});

	function processXML(xml) {
		$(xml).find('address_component').each(function() {
			if ($(this).find('type').text() == 'postal_code') {
				$("#zipCode").html("The Zip Code is " + $(this).find('long_name').text()).fadeIn();
				result = 1;
			} 
		});
	}

	if (result === 0) {
		$("#zipCode").html("Please enter a valid address");
	}

});	



</script>

<script type="text/javascript">


// BELOW IS THE ORIGINAL GOOGLE GEOCODE URL FOR XML DATA

/*
"https://maps.googleapis.com/maps/api/geocode/xml?address="+encodeURIComponent($('#address').val())+"sensor=false&key=AIzaSyAXjxXYQnYNCaLXDErmVIBvAsculIJ8DK4"
*/



</script>
</body>
</html>