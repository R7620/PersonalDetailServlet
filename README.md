# PersonalDetailServlet html code 
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Personal Detail</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column; 
      height: 100vh; 
      margin: 0;
      text-align: center;
    }

    div {
      border-radius: 8px;
      text-align: center;
      border: 2px solid red; 
      padding: 20px;
    }
    
  </style>
</head>
<body>
  <div>
    <h1 style="background-color: fuchsia;">Person Detail :</h1>

    <form action="PersonalDetailServlet" method="post">
      Name: <input type="text" name="name"><br><br>
      Age: <input type="text" name="age"><br><br>
      Mobile: <input type="text" name="mobile"><br><br>

      Select your Gender:<br>
      <input type="radio" name="gender" value="Male">Male
      <input type="radio" name="gender" value="Female">Female
      <br><br>

      Select Your Hobbies:<br>
      <input type="checkbox" name="hobbies" value="Reading">Reading
      <input type="checkbox" name="hobbies" value="Searching">Searching
      <input type="checkbox" name="hobbies" value="Sleeping">Sleeping
      <input type="checkbox" name="hobbies" value="Watching">Watching
      <br><br>

      <input type="submit" value="Click here ->">
    </form>
  </div>
</body>
</html>
