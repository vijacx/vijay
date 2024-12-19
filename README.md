<!DOCTYPE html>

<html>



<head>

    <title>My Website</title>



    <style>

        body {

            font-family: Arial, sans-serif;

            margin: 0;

            background-color: #ffffff;

            color: #4e4746;

        }



        header {

            background: #000000;

      width: 640px;

            color: #ffffff;

            padding: 15px;

            text-align: left;

        }



        header h1 {

            margin: 0;

        }



        .hover-row {

            width: 640px;

            background-color: #000000;

            color: white;

            display: flex;

            flex-direction:row;

            justify-content: right;

        }



        .hover:

      {

            width: 300px;

        }



        .hover-row a 

      {

            text-decoration: none;

            color: white;

            margin: 15px ;

            font-size: 18px;

            text-align: right;

        }

        .hover-column 

      {

            width: 100px;

            background-color: #000000;

            color: white;

            display: flex;

            flex-direction: column;

            align-items: center;

        }



        .hover:

      {

            width: 300px;

        }



        .hover-column a 

      {

            text-decoration: none;

            color: white;

            margin: 19px;

            font-size: 18px;

            text-align: center;

        }

        .content 

      {

            flex: 1;

            background-color: #000000;

            padding: 20px;

        }



        footer {

            background: #000000;

            color: #fff;

            text-align: center;

            padding: 0px;

            width: 650px;

        }

    </style>

</head>



<body>

    <header>

        <h1>GITAM</h1>

    <div class="container">

       <div class="hover-row">

            <a href="#">Login in</a>

        </div>

      </header>

        <div class="hover-column">

            <a href="#">Home</a>

            <a href="#">Profile</a>

            <a href="#">Attendance </a>

            <a href="#">Timetable</a>

            <a href="#">Courses</a>

        </div>

    </div>

    <footer>

        <p>&copy; 2025 GITAM. All rights reserved.</p>

    </footer>

</body>



</html>
