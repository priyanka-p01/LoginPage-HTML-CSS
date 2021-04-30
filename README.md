# LoginPage-HTML-CSS
# A simple login page using basic HTML and CSS knowledge

<!DOCTYPE html>
<html>
    <head>
<b><title> LOGIN Page</title> </b>
    </head>
    
<body>
    <h2> Welcome to the Login Page!</h2><h3>Let's get started! </h3>
    <div class = "Intro">
        <form id = "login" action="login.php">
            <label><em> User ID</em></label><br>
            <input type="text" placeholder="Enter the unique ID" name= "UID" id="User ID"><br>
            <br>
            <label><em>Password</em></label><br>
            <input type="password" name= "PW" placeholder="Enter Password" id="Password"><br>
            <br>            
            <input type="button" id="log" name="LogIn" value="Submit"><br>
            <input type="checkbox" id="check"> Always remember me <br>
            <br>
             <em>Forgot <a href = "">User ID?</a></em><br>
            <em>Forgot <a href = ""> Password?</a></em><br>
                        
        </form id="new"><br>
        <label>New to this site?</label>
        <label><a href=""> Register Here!</a></label>
        <form>

        </form>
    </div>

    <style>
        .Intro{
            margin: 0;
            padding: 2px;
            text-align: center;
            font-family: Arial, Helvetica, sans-serif;
            font-size: medium;
            background-color: #cacdceba;
            width: 600px;
            height: 250px;
            margin: auto;
            margin: 20 20 20 20px;
            
        }

        body{
            background-color: rgb(112, 245, 201);
        }

        h2{
            width: 250 px;
            padding-left: 10px;
            padding-top: 15px;
            border-radius: 25px;
            background-color: whitesmoke;
            text-align: center;
            overflow: hidden;  
            border-radius: 15px
        }
        
        h3{
            width: 250 px;
            padding-left: 10px;
            padding-top: 15px;
            border-radius: 25px;
            background-color: whitesmoke;
            text-align: center;
        }
            
        label{
            color: black;
            font: 30px;
            }

        #UID{
            width: 250px;
            height: 25px;
        }

        #PW{
            width: 250px;
            height: 25px;
        }

        #LogIn{
            width: 250px;
            height: 25px;
            border-radius: 15px;
        }

        span{
            font-size: 20 px;
        }                
          </style>
</body>
</html>
