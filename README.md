# Wesite-to-take-details-of-user
Here is my code of the website

<!DOCTYPE html>
<html>
	<head>
		<title>Form</title>
		<style>
			.resume{   
			margin-right: 2%;
			}
			.resume_class{
			display: inline-block;
			width: 77%;
			height: 510px;
			margin-top:20%;
			margin-left:10%;
			background:#1abc9c;
			position:absolute;
			border-style:solid;
			border-width:2.5px;
			}
		</style>

	</head>
	<body style="background-color:#2ecc71">
		<div class="resume">
		<div class="resume_class">
			<h1><center>CONTACT INFORMATION</center></h1>
			<hr><br>
			<form action="Result.html" method="post"><center>
				First Name:<input type="text" name="fname" placeholder="For example John"><br><br>
				Last Name:<input type="text" name="lname" placeholder="For example Smith"><br>
				<br>Mobile Number:<input type="tel" name="no" placeholder="0123456789" title="Don't put Area Code"><br>
				<br>E-mail ID:<input type="username@domainname" name="email" placeholder="username@domainname.com" title="@ and . are mandatory"><br>
				<br>Organisation:<input type="text" name="org" placeholder="For example KIIT"><br>
				<br>Address:<input type="text" name="add" placeholder="#123, ABC Street, XYZ City"><br>
				<br>Date of Birth:<input type="Date" name="DOB"><br>
				<br>Gender:<input type="radio" name="Age">Male
					<input type="radio" name="Age">Female
					<input type="radio" name="Age">Others<br><br>
			</form><br>
			<input type="Submit" name="submit" value="Submit">
			<input type="reset" name="reset" value="Reset"></center>
	</body>
</html>
