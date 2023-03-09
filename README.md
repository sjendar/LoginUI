# LoginUI
<!DOCTYPE html>
<html lang="en" and dir="Itr">
    <head>
       <meta charset="utf-8">
      
       <title>
        Login UI
       </title> 
       <link rel="stylesheet" href="style.css"> 

    </head>
    
    <body>
         <div class="box">
            <div class="Login">

            <h1>
                Login
            </h1>
            <input type="text" name="username" id="hello" placeholder="username">
            <input type="password" name="password" id="happy" placeholder="password">
            <button type="submit" name="Login" id="Login-button">Sign In</button>

        </div>
    </body>
</html>

------------------------------------------------------------------------------------------------------------------------------
#styleCSS
.box{
    display: flex;
    flex-direction: column;
    justify-content: center;
    min-width: 100vw;
    min-height: 100vh;
    align-content: center;
   background-image: url(backdrop.jpg.webp);
   background-size: cover;
}



.Login{
    display: flex;
    flex-direction: column;
    align-self: center;
    align-items: center;
    justify-content: center;
    height: 40vh;
    width: 45vw;
    border-radius: 20%;
    background-color: rgb(206, 228, 11);
    border-color: rgb(119, 230, 8);
    border-width: 8px;
    border-style:double;
    
}

input{
    margin-top: 12px;
    border-radius: 20px;
}
#Login-button{
    margin-top: 12px;
    border-radius: 10em;
}
