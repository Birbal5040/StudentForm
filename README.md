<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>STUDENT FORM</title>
    <style>
        //this is css
        #re{
          
           background-color: red;
           color: green; border: 2px solid black;
           
        }
        #su{
           
            background-color: greenyellow;
            color: blue;
            border: 2px solid black;
          
        }
    </style>
</head>
<body>
    <form action="">
        <fieldset>
            <legend>Please fill out the form accurately::</legend>
            <label for="">Name:</label>
            <input type="text" name="name" id="ne"> <br id="brr"><br>
            <label for="">Email:</label>
            <input type="email" name="email" id="em"> <br> <br>
            <label for="">Password:</label>
            <input type="password" name="password" id=""> <br> <br>
            <label for="">Gender:</label>
            <input type="radio" name="gender">
            <label for="">Male</label>
            <input type="radio" name="gender" >
            <label for="">Female</label> <br> <br>
            <label for="">Select Language:</label>
            <input type="checkbox" >
            <label for="">HTML5</label>
            <input type="checkbox" >
            <label for="">CSS</label>
            <input type="checkbox" >
            <label for="">JS</label>
            <input type="checkbox" >
            <label for="">REACT</label>
            <input type="checkbox" >
            <label for="">C</label>
            <input type="checkbox" >
            <label for="">C++</label>
            <input type="checkbox" >
            <label for="">PYTHON</label>
            <input type="checkbox" >
            <label for="">JAVA</label>
            <input type="checkbox" >
            <label for="">SQL</label>
            <br><br>
            <label for="">Select:</label>
            <select name="" id="">
                <optgroup label="Frontend Language:">
                   <option value="">HTML5</option>
                   <option value="">CSS</option>
                   <option value="">JS</option>
                   <option value="">REACT</option>
                </optgroup>
                <OPtgroup label="Backend">
                    <option value="">MongoDB</option>
                    <option value="">PYTHON</option>
                    <option value="">NODE JS</option>
                </OPtgroup>
            </select>
            <br><br>
            <label for="">Select College:</label>
            <input list="college">
            <datalist id="college">
                <option value="DCE,Darbhanga"></option>
                <option value="BCE,Bhagalpur"></option>
                <option value="BCE,Baktiyarpur"></option>
                <option value="VCE Vaisali"></option>
            </datalist>
            <br> <br>
            <label for=""> Give me any opinion.</label> <br>
            <label for="">Optional Message:</label> <br>
            <textarea  cols="15" rows="5"></textarea>
            <br>
            <button id="su">Submit</button> 
            <button id="re">Reset</button>


        </fieldset>
    </form>
</body>
</html>
