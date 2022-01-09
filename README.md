# -Rpg
web-development, Programing
<!DOCTYPE html>
<html lang="en">

<head>
    <meta http-equiv="content-type" content="text/html; charset=UTF-8">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welocome to Travel Form</title>
    <link rel="preconnect" href="https://fonts.gstatic.com/">
    <link href="Welocome%20to%20Travel%20Form_files/css2.css" rel="stylesheet">
    <link rel="stylesheet" href="Welocome%20to%20Travel%20Form_files/style.css">
</head>

<body>
    <img class="bg" src="Welocome%20to%20Travel%20Form_files/bg.jpg" alt="IIT Kharagpur">
    <div class="container">
        <h1>Welocome to IIT KHARAGPUR US Trip Travel Form</h1>
        <p> Enter your details and submit this form to confirm your participation in the trip</p>
        <form action="index.php" method="post">
            <input type="name" class="name" id="name" placeholder="Enter your Name">
            <input type="age" class="age" id="age" placeholder="Enter your Age">
            <input type="email" class="email" id="email" placeholder="Enter your Email">
            <input type="phone" class="phone" id="phone" placeholder="Enter your Phone">
            <textarea name="desc" id="desc" cols="30" rows="10"
                placeholder="Enter any other information here"></textarea>
            <button class="btn">Submit</button>
        </form>
    </div>
    <script src="Welocome%20to%20Travel%20Form_files/index.html"></script>
    <style>
        * {
            margin: 0;
            padding: 0%;
            box-sizing: border-box;
        }

        .container {
            max-width: 80%;
            margin: auto;
            padding: 34px;

        }

        p {
            font-size: 17px;
        }

        .container h1,
        p {
            text-align: center;

        }

        input,
        textarea {
            border: 2px solid black;
            border-radius: 6px;
            outline: none;
            font-size: 25px;
            width: 80%;
            margin: 11px;
            padding: 7px;
        }

        .form {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
        }

        .bg {
            width: 100%;
            position: absolute;
            opacity: 0.6;
            z-index: -1;
        }
    </style>




</body>

</html>
