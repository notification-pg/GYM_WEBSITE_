# GYM_WEBSITE_

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PG Fitness</title>
</head>
<link rel="stylesheet" href="css/style.css">
<style>
    body{
        color: white;
        margin: 0px;
        padding: 0px;
        background: url('img/bg13.jpg');
    }
    .left{
        display: inline-block;
        position: absolute;
        left: 44px;
        top: 25px;
    }
    .left img{
        width: 100px;
        filter: invert(100%); 
    }
    .left div{
        line-height: 19px;
        font-size: 26px;
        text-align: center;
    }
    .mid{
        display: block;
        width: 40%;
        margin: 25px auto;
    }
    .right{
        position: absolute;
        right: 44px;
        top: 25px;
        display: inline-block;
    }
    .navbar{
        display: inline-block;
    }
    .navbar li{
        display: inline-block; 
    }
    .navbar li a{
        color: white;
        text-decoration: none;
        padding: 15px;
        font-size: 21px;
    }
    .navbar li a:hover {
        text-decoration: underline;
        color: aqua;
    }
    .btn{
        margin: 0px 9px;
        background-color: rgb(158, 229, 205);
        color: rgb(13, 2, 2);
        padding: 4px 14px;
        border: 2px solid gold;
        border-radius: 10px;
        font-size: 20px;
        cursor: pointer;
    }
    .btn:hover{
        background-color: rgb(191, 84, 84);
    }
    .container{
        margin: 100px 38px;
        padding: 55px;
        width: 40%;
        border-radius: 4px;
    }
    .form-group input{
        text-align: center;
        display: block;
        width: 508px;
        padding: 1px;
        border: 2px solid black;
        margin: 11px auto;
        font-size: 25px;
        border-radius: 6px;
    }
    .container h1{
        text-align: center;
    }
    .container button{
        display: block;
        width: 84%;
        margin: 15px auto;
    }
</style>
<body>
    <header class="header">

        <!-- Left box for Logo -->
        <div class="left">
            <img src="img/bg2.jpg" alt="">
            <div>PG Fitness</div>
        </div>

        <!-- Mid box for Navbar -->
        <div class="mid">
            <ul class="navbar">
                <li><a href='#' class="active">Home</a></li>
                <li><a href='#'>About Us</a></li>
                <li><a href='#'>Fitness Calculator</a></li>
                <li><a href='#'>Contact Us</a></li>
            </ul>
        </div>

        <!-- Right box for Buttons -->
        <div class="right">
            <button class="btn">Call Us</button>
            <button class="btn">Email Us</button>
        </div>
    </header>
    <div class="container">
        <h1> Join the best gym in Kolkata now </h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Name">      
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Age">      
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Gender">      
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Locality">      
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Phone No.">      
            </div>
            <button class="btn">Submit</button>
        </form>
    </div>
</body>
</html>
