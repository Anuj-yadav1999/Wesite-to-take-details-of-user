# Wesite-to-take-details-of-user
Here is my code of the website



    // Starting with the html 
    <!DOCTYPE html>
    <html>
	<head>
		<title>Form</title>
		<style>         // Here is the format or style or dimentions
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
        //  Body i.e. content of the website starts from here
	<body style="background-color:#2ecc71">
		<div class="resume">       // Here the style from the head is used
		<div class="resume_class">  // Here again the other style used
			<h1><center>CONTACT INFORMATION</center></h1>
			<hr><br>
			// Form starts from here and write all the attributes you want to take from user
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
			<input type="Submit" name="submit" value="Submit">    // Here the submit button 
			<input type="reset" name="reset" value="Reset"></center>   // The reset button here
	</body>
    </html>
