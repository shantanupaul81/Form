HTML CODE

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feedback Form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h2 id="ff">Feedback form</h2>
    
    <hr><br><br>

    <form action="" id="f">
<label for="First Name">First Name</label>
<input type="text" required placeholder="Shantanu">
<br><br>
<label for="Last Name">Last Name</label>
<input type="text" required placeholder="Paul">
<br><br>

<label for="Gender">Gender</label>
<input type="radio" name="gender">Male
<input type="Radio" name="gender">Female
<br><br>

<label for="Enail">Email ID</label>
<input type="Email" placeholder="abcd@gmail.com" required>
<br><br>

<label for="FeedBack Form">Share Your Feedback</label>
<br><br>
<textarea name="" id="" cols="30" rows="10"></textarea>
<br><br>
<SELECT Name="Countychooser">
    <OPTION Value="Face wash">Face wash</OPTION>
    <OPTION Value="Dress">Dress</OPTION>
    <OPTION Value="Cream">Cream</OPTION>
    <OPTION Value="Others">Others</OPTION>
  </SELECT>
<br><br>

<input type="Submit" value="Send feedback">
<input type="Reset" value="Reset">
    </form>


</body>
</html>




CSS Code


#ff{
    color: blue;
    text-align: center;
}
#f{
    text-align: center;
}
