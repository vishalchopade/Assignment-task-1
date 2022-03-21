# Assignment-task-1
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Navigation</title>
    <style>
        .navbar {
            background-color:skyblue;
            border-radius: 35px;
        }

        .navbar ul {
            overflow: auto;
        }

        .navbar li {
            float: left;
            list-style: none;
            margin: 30px 20px;

        }

        .navbar li a {
            padding: 3px 3px;
            text-decoration: none;
            color: white;
        }
    </style>
</head>

<body>
    <div>

    
    <header>
        <nav class="navbar">
            <div>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Contact Us</a></li>

            </div>
            </ul>
        </nav>
    </header>
</div>

    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">


        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
            integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

        <title>Reponsive Slider</title>
    </head>

    <div id="carouselExampleCaptions" class="container-fluid carousel slide" data-bs-ride="carousel" height="50%">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
                aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
                aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
                aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="img/3.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">

                </div>
            </div>
            <div class="carousel-item">
                <img src="img/6.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">

                </div>
            </div>
            <div class="carousel-item">
                <img src="img/7.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">

                </div>


            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions"
                data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions"
                data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>

        <!-- Optional JavaScript; choose one of the two! -->

        <!-- Option 1: Bootstrap Bundle with Popper -->
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
            integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
            crossorigin="anonymous"></script>

        <!-- Option 2: Separate Popper and Bootstrap JS -->
        <!--
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
        -->

</html>
<header>
    <div class="container">
        <div class="row">
            <div class="col-7">
                <h1>
                    Latest News

                    <h1> LyrArc Article Gist</h1>
                    Defense experts in Britain say the part of the Russian army that is modern is not large,
                    and the part that is large is not modern. The Russian advance attack in Ukraine has floundered,
                    says this report in the WSJ. About 25% of the Russian army is made up of conscripts.
                    The hundreds of billions of dollars spent on modernization of the Russian armed forces have been
                    spread thinly,
                    and dissipated also because of corruption and poor management.

                    
                </h1>

            </div>

            <div class="col-5">
                <div class="container">
                    <div class="row">
                        <div class="col-6">
                            <h1>Login</h1>
                            <div class="input-box">
                                <span class="details">Email Id</span>
                                <input type="text" placeholder="Enter your email" required>
                            </div>
                            <div class="input-box">
                                <span class="details">Password</span>
                                <input type="text" placeholder="Enter your password" required>
                            </div>
                            <p></p>
                            <div class="button">

                                <input type="submit" value="Submit" onclick="myFunction()">


                            </div>

                        </div>
                        <br>
                        <div class="col-6">
                            <h1>SignUp</h1>
                            <div class="content">
                                <form action="#">
                                    <div class="user-details">
                                        <div class="input-box">
                                            <span class="details">Full Name</span>
                                            <input type="text" placeholder="Enter your name" required>
                                        </div>
                                        <div class="input-box">
                                            <span class="details">Email Id</span>
                                            <input type="text" placeholder="Enter your email" required>
                                        </div>
                                        <div class="input-box">
                                            <span class="details">Phone Number</span>
                                            <input type="text" placeholder="Enter your number" required>
                                        </div>
                                        <div class="input-box">
                                            <span class="details">Address</span>
                                            <input type="text" placeholder="Enter your email" required>
                                        </div>
                                        <div class="input-box">
                                            <span class="details">Password</span>
                                            <input type="text" placeholder="Enter your password" required>
                                        </div>
                                        <div class="input-box">
                                            <span class="details">Confirm Password</span>
                                            <input type="text" placeholder="Confirm your password" required>
                                        </div>



                                    </div>

                            </div>
                            <div class="button">

                                <input type="submit" value="Submit" onclick="myFunction()">


                            </div>
                        </div></br>


                    </div>
                    <div class="col-5">
                        <div class="container">


                            <script>
                                function myFunction() {
                                    var txt;
                                    if (confirm("Are You Want To Sumbit")) {
                                        txt = "You pressed Ok";
                                    }
                                    else {
                                        txt = "You pressed Cancel";
                                    }
                                }
                            </script>

                            </form>
                        </div>
                    </div>
                </div>
            </div>
            <html lang="en" dir="ltr">

            <head>
                <meta charset="UTF-8">
                <title>Responsive JOB APPLICATION FORM | CodingLab </title>
                <link rel="stylesheet" href="style.css">
                <meta name="viewport" content="width=device-width, initial-scale=1.0">
            </head>


        </div>


        </html>



    </div>
    </div>
    <footer class="d-flex flex-wrap justify-content-between align-items-center py-3 my-4 border-top">
        <div class="col-md-4 d-flex align-items-center">
          <a href="/" class="mb-3 me-2 mb-md-0 text-muted text-decoration-none lh-1">
            <svg class="bi" width="30" height="24"><use xlink:href="#bootstrap"></use></svg>
          </a>
          <span class="text-muted">© 2021 Company, Inc</span>
        </div>
    
        <ul class="nav col-md-4 justify-content-end list-unstyled d-flex">
          <li class="ms-3"><a class="text-muted" href="#"><svg class="bi" width="24" height="24"><use xlink:href="#twitter"></use></svg></a></li>
          <li class="ms-3"><a class="text-muted" href="#"><svg class="bi" width="24" height="24"><use xlink:href="#instagram"></use></svg></a></li>
          <li class="ms-3"><a class="text-muted" href="#"><svg class="bi" width="24" height="24"><use xlink:href="#facebook"></use></svg></a></li>
        </ul>
      </footer>
    </body>

    </html>
