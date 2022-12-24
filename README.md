<!DOCTYPE HTML>
<html>
<head>
<title>MyWeb</title>
    
        <style>
         body 
            {
            background-image: url("Musician-art-wallpaper.jpg");
                background-size:cover;
            }
            .navigation-menu ul{
                margin: 0px;
                padding: 0px;
            }
            #ul-nb li a{
                text-align: center;
                padding: 10px;
                width: 100px;     
            }
            ul{
                padding: 0px;
                overflow: hidden;
                background-color:forestgreen;
            }
            li{
                float: left;
            }
            li a{
                display: inline-block;
                color: white;
                text-align: center;
                padding: 10px 20px;
                text-decoration: none;
            }
            li a:hover{
                background-color:black;
                border: 0px solid forestgreen;
                border-radius: 50px;  
            }
            #navigation ul{
                font-size:1em;
            }
            #navigation ul li{
                display: inline;
                 color: black;
            }
            #navigation li:not(:first-child):before{
                content: " | ";
            }
            .navigation-menu{
                border: 10px solid forestgreen;
                border-radius: 50px; 
                position: relative;
            }
            #navigation
            {
                animation:hello 8s infinite;
            }
            
            @keyframes hello
            {
              50%
                {
                    transform: rotateX(40deg);
                }
            }
            p
            {
                font-family: serif ;
                position: relative;  
                animation:mymove 30s infinite ;
            }
        @keyframes mymove
            {
              from
                {
                    left: 0px;
                    top: 0px;
                }
                to
                {
                    left: 1200px;
                }
            }
      </style>
</head>
    <body>
        <div class="navigation-menu">
          <div id="navigation">
            <ul>
                <li><a href="MyWeb.html"><b>HOME</b></a></li>
                <li><a href="register.html"><b>REGISTER</b></a></li>
                <li><a href="login.html"><b>LOGIN</b></a></li>
            </ul>
              </div>
        </div> <br> 
    <p style="color:white;font-family: cursive;font-size:0.8em"><b>Welcome to my WebPage!!</b></p>
        <hr>   
    </body>
</html>
