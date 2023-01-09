# Firstgymwebsite
My First Ever selfmade Gym Website
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gym Website</title>
    <link rel="stylesheet" href="CSS/style2.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Fredoka+One&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Fredoka One', cursive;
            height: 4000px;
            width: 100%;
            padding: 0;
            margin: 0;
            background-repeat: no-repeat;
            background: url('img/abs.jpg')
        }

        .logo {
            width: 61px;
            height: 48px;
        }

        .left div {
            text-align: center;
            line-height: 1;
            font-size: 11px;
            padding: 0px 0px 0px 2px;
        }

        .left {
            display: inline-block;
            color: white;
            display: inline-block;
            /* border: 2px solid yellow; */
            position: absolute;
            left: 33px;
            top: 20px;
        }

        .mid {
            display: block;
            color: white;
            /* border: 2px solid yellow; */
            width: 33%;
            margin: 7px auto;
        }

        .right {
            position: absolute;
            right: 33px;
            top: 20px;
            color: white;
            display: inline-block;
            /* border: 2px solid yellow; */
        }

        .navbar {
            display: inline-block;
        }

        .navbar li {
            display: inline-block;
            font-size: 20px;
        }

        .navbar li a {
            color: white;
            text-decoration: none;
            padding: 6px;
        }

        .navbar li a:hover {
            text-decoration: underline;
            color: #9d9999;
            font-size: 21px;
        }

        .btn {
            font-family: 'Fredoka One', cursive;
            margin: 4px 16px;
            padding: 3px 16px;
            border: 2px solid white;
            background-color: Black;
            border-radius: 15px;
            color: white;
            cursor: pointer;
        }

        .btn:hover {
            background-color: rgb(41, 40, 40);
        }

        .container {
            border: 2px solid White;
            margin: 79px 20px 28px 919px;
            padding: 41px 52px 43px 62px;
            border-radius: 48px;
            color: white;
            font-size: 10px;
        }

        .form-group input {
            font-family: 'Fredoka One', cursive;
            text-align: center;
            border-radius: 6px;
            display: block;
            width: 449px;
            padding: 6px 2px;
            margin: 4px auto;
            font-size: 16px;
        }

        .container h2 {
            text-align: center;
        }

        .container button {
            display: block;
            width: 445px;
            margin: 10px auto;
            padding: 9px;
        }
    </style>
</head>

<body>
    <header>
        <div class="left">
            <img class="logo"
                src="https://img.freepik.com/free-vector/muscle-man-bodybuilder-holding-large-barbell-with-big-weights_1284-43350.jpg?w=740&t=st=1672813222~exp=1672813822~hmac=218fed8b9545bdd0e0383b65b716322a0c335be0e110d91a1ec22d79225aece0"
                alt="Gym Logo">
            <div>Ashu Fitness</div>
        </div>
        <div class="mid">
            <ul class="navbar">
                <li><a href="#">Home</a></li>
                <li><a href="#">Pricing</a></li>
                <li><a href="#">About us</a></li>
                <li><a href="#">Contact us</a></li>
            </ul>
        </div>
        <div class="right">
            <button class="btn">Join Us</button>
            <button class="btn">About Us</button>
        </div>
    </header>
    <div class="container">
        <h2>Welcome to Ashu's Gym</h2>
        <form action="noaction.php"></form>
        <div class="form-group">
            <input type="text" name="" placeholder="Enter Your name">
        </div>
        <div class="form-group">
            <input type="text" name="" placeholder="Enter Your Age">
        </div>
        <div class="form-group">
            <input type="text" name="" placeholder="Enter Your Gender">
        </div>
        <div class="form-group">
            <input type="text" name="" placeholder="Enter Your Locality">
        </div>
        <button class="btn">
            Submit
        </button>
    </div>
</body>

</html>
