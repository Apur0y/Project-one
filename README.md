<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    
</head>
<body>
    <form>
     <H1>Servey Form</H1>

     <fieldset>
               <legend>Personal information </legend>
              <label for="name">Name:</label><br/>
              <label for="First name">First name:</label>
              <input type="text" id="First name" placeholder="">
              <label for="Last name">Last name:</label>
              <input type="text" id="Last name"><br/>
              <label for="id">ID number:</label> <br/>
              <input type="text" id="id"> <br/>
              <label for="gender">Gender:</label>
              <input type="radio" name="male" id="male">
              <label for="male">Male</label>
              <input type="radio" name="female" id="female">
              <label for="female">Female</label><br/>


              <label for="number">Age:</label>
              <input type="id="number">
              <br/>
              <label for="age">Date of birth:</label> <br/>

              <input type="date" id="date">
            </fieldset>
            <br/>
<label for="resume">Resume:</label> 
            <input type="file" id="resume">
            <br/><br/>
            <label for="occ">Occupation:</label>
            <select name="occ" id="occ">
                <option value="--Chooise--">--Choose one--</option>
                <option value="BCS cadre">BCS cadre</option>
               <option value="Banker">Banker</option>
               <option value="Student">Student</option>
               <option value="Farmar">Farmar</option>
               <option value="Others">Others</option>
               
               
                
            </select>
            <br/><br/>

            <label for="ex">Exprience(in years):</label>
            <input type="number" max="100" min="0">
            <br/> <br/>

            <fieldset>
                <legend>Type of interest:</legend>
                <label for="Football">Football</label>
                <input type="checkbox" id="Football">
                <label for="cr">Cricket</label>
                <input type="checkbox" name="c" id="cr">
                <label for="bad">Badminton</label>
                


            </fieldset>
            <br><br>

      <label for="comment">Comment:</label><br/>
            <textarea name="Comment" id="comment" placeholder="text here only..." cols="30" rows="10" ></textarea>
           
 <button>Register</button>
        </form>





     


</body>
</html>
