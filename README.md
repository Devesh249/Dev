# Dev
Web-Development
## html.code
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Registration form for Games</title>
    <link rel="stylesheet" href="styleform.css" />
  </head>
  <body>
   
    <div class="heading">
       Game-Form 
    </div>
    <div class="form-Details">
        <form>
            <label for="name">Name<br>
            <input type="name" class="input"
        id="name">
    </label><br>
    <label for="DOBInput" >DOB <br>

        <input type="date" class="input" id="number">
    </label><br>
    <label for="selection" >Select Your Game <br>
        <input type="checkbox" name="power1" id="power" value="WWE2023">
        <label for="power1">WWE2023</label><br>
        <input type="checkbox" name="power2" id="power" value="MORTAL-COMBACT">
        <label for="power2">MORTAL-COMBACT</label><br>
        <input type="checkbox" name="power3" id="power" value="F1-RACING">
        <label for="power3">F1-RACING</label><br>
        <input type="checkbox" name="power1" id="power4" value="FIFA">
        <label for="power4">FIFA</label><br><br>
    </label><br>
    <label for="q1">ARE U MASTER IN THIS GAME <br>
        <textarea name="ans1" id="EXpow" cols="30" rows="10" class="input"></textarea><br>
        <label for='genderInput'>what is your gender<br>
            <input type="checkbox" class="checkbox" name="gender1" id="gender" value="male">
            <label for="gender1">male</label>
            <input type="checkbox" class="checkbox" name="gender2" id="gender" value="female">
            <label for="gender2">female</label>
            <input type="checkbox" class="checkbox" name="gender3" id="gender" value="other">
            <label for="gender3">other</label>
            
       
        </label>

        <button type="submit" id="submit" class="button">
            submit
        </button>

</form>
    
    </div>
  </body>
</html>

  
  
  
  
  ## css.code
  body {
  background-image: url("img2.webp");
  margin: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  color:white;
  font-family: Arial, Helvetica, sans-serif;
}
.heading{
    margin-top: 2% ;
    background-color:green;
    width: 50%;
    padding: 3% 0% 3% 0%;
    text-align: center;
    font-size: 28px;
   font-weight: 700;
   letter-spacing: 3px;
   text-transform: uppercase;
   }
   .form-body{
    margin-top: 2% ;
    background-color:rgba(238, 6, 6, 0.7);
    width: 50%;
    padding: 3% 5%; 
}
.formdetails-input{
    height: 10px;
    font-size: 15px;
    border: none;
    background-color: black;

}
.input{
    outline: none;
    width:100% ;
    margin: top 2%; ;
    margin: bottom 1.5%; 
    color:black;
}
.button{
    width: 100%;
    text-align:center ;
    padding: top 2%; 
    padding-bottom: 2%;
    font-size: 15px;
    font: weight 700px; ;
    border:2px ;
    background-color: rgb(9, 230, 193);
}

.button:hover{
    cursor: pointer;
    background-color: rgba(130, 228, 19, 0.7);
    transition: 0.4s;
    border-color: black;

}
 ## form.url
  http://127.0.0.1:5500/form.html?power1=WWE2023&power2=MORTAL-COMBACT&power3=F1-RACING&power1=FIFA&ans1=&gender1=male
