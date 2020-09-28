# Internship-Tasks
Tasks for Internship consideration


Task 1
<!DOCTYPE html>
<html>
<head>

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>

body {
	font-family: Arial;
	color: white;
}
.split {
	height: 100%;
	width: 50%;
	position: fixed;
	z-index: 1;
	top: 0;
	overflow-x: hidden;
	padding-top: 20px;
}
.left{
	left: 0;
	background-color: #111;
}
.right{
	right: 0;
	background-color: blue;
}
.centered{
	position: absolute;
	top: 50%;
	left: 50%;
	transorm: translate(-50%,-50%);
	text-align: center;
}

</style>

</head>

<body>
<div class="split left">
 <div class="centered">
 
	<p><a href="#T1">Introduction to CSS</a></p>
	<p><a href="#T2">Loading a age</a></p>
	<p><a href="#T3">Centered content</a></p>
	<p><a href="#T4">Colours</a></p>
	<p><a href="#T5">Background</a></p>
 
	<link rel="stylesheet"
		href="https;//cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0css/font-awesome.min.css">

	</div>
</div>

<div class="split right">
 <div class="centered">
		<h1 id="T1">Introduction to CSS</h1>
		<p>Welcome to the world of Cascading Style Sheets (CSS). With CSS, you can design gorgeous and highly effective Web sites. CSS offers power and flexibility to Web site developers and designers. This book shows you how to use CSS to make your Web pages come alive.</p>
		<h2 id="T2">Loading a page</h1>
		<p>If you’ve already worked with CSS, this book will sharpen your skills and show you lots of new techniques. You’ll take your Web design to the next level.</p>
		<h3 id="T3">Centered content</h1>
		<p>You see how to detect which browser and version the user has and how to take appropriate steps to deal with it in your Web page code</p>
		<h4 id="T4">Colours</h1>
		<p>Blue, Green, Yellow, Brown, Black, Grey, Beige, White, Orange, Tan, Charcoal, Lime, Peach, Gold</p>
		<h5 id="T5">Background</h1>
		<p>Firefox is fast, sleek, and overall pretty stable. In fact, it’s not under constant attack by hackers, as is IE. </p>
	</div>
</div>

</body>
<html/>

Task 3
<!DOCTYPE html>
<html>
<head>

<title>Covid-19 Self-check form</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0, charset=UTF-8">
<style>
body {
	font-family: Arial;
	color: white;
}
.centered{
	position: absolute;
	top: 50%;
	left: 50%;
	transorm: translate(-50%,-50%);
	text-align: center;
}
</style>
</head>
	<h2>Covid-19 Self-check</h2>
<body>
<form action="covid.php" method="post">

<label for='formAge[]'>Which age group do you belong to:</label><br>
	<select multiple="multiple" name="formAge[]">
		<option value="18"> less than 18</option>
		<option value="18-39">18-39</option>
		<option value="40-65">40-65</option>
		<option value="65"> above 65</option>
	</select>

<label for='formGender[]'>Please provide us with the gender you identify as:</label><br>
	<select multiple="multiple" name="formGender[]">
		<option value="M">Male</option>
		<option value="F">Female</option>
		<option value="O">Other</option>
		<option value="R">Rather Not Say</option>
	</select>

<label for='formProvince[]'>In which Province are you currently residing:</label><br>
	<select multiple="multiple" name="formProvince[]">
		<option value="EC">Eastern Cape</option>
		<option value="FS">Free State</option>
		<option value="G">Gauteng</option>
		<option value="KZN">Kwa-Zulu Natal</option>
		<option value="L">Limpopo</option>
		<option value="MP">Mpumalanga</option>
		<option value="NW">North West</option>
		<option value="NC">Northern Cape</option>
		<option value="WC">Western Cape</option>
	</select>

<label for='formMeds[]'>Do you have any other pre-existing medical conditions that we should be aware of:</label><br>
	<select multiple="multiple" name="formMeds[]">
		<option value="Y">Yes</option>
		<option value="N">No</option>
		<option value="NS">Not Sure</option>
	</select>

<label for='formFeel[]'>Do you feel very hot or cold? Are you sweating or shievering? When you touch your forehead, does it feel hot?:</label><br>
	<select multiple="multiple" name="formFeel[]">
		<option value="Y">Yes</option>
		<option value="N">No</option>
	</select>

<label for='formCough[]'>Do you have a cough that recently started?:</label><br>
	<select multiple="multiple" name="formCough[]">
		<option value="Y">Yes</option>
		<option value="N">No</option>
	</select>
	
<label for='formSore[]'>Do you have a sore throat or pain when swallowing?:</label><br>
	<select multiple="multiple" name="formSore[]">
		<option value="Y">Yes</option>
		<option value="N">No</option>
	</select>	
	
<label for='formBreath[]'>Do you have breathlessness or a difficulty breathing, that you've noticed recently?:</label><br>
	<select multiple="multiple" name="formBreath[]">
		<option value="Y">Yes</option>
		<option value="N">No</option>
	</select>	
	
<label for='formAbility[]'>Have you beenin close contact with someone confirmed to be infected with COVID-19?:</label><br>
	<select multiple="multiple" name="formAbility[]">
		<option value="Y">Yes</option>
		<option value="N">No</option>
		<option value="NO">Not Sure</option>
	</select>	
	
<label for='formAccurate[]'>Finally, please confirm that the information you shared is ACCURATE to the best of your knowledge and that you give the National Department of Health permission to contact you if necessary?:</label><br>
	<select multiple="multiple" name="formAccurate[]">
		<option value="Y">Yes</option>
		<option value="N">No</option>
	</select>

</form>
</body>
<html/>
