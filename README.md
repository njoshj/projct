
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <link rel="stylesheet" href="css/bootstrap.css">
    <link rel="stylesheet" href="custom.css">
    <link rel="stylesheet" href="">
    <style>
        /* Make the image fully responsive */
        .carousel-inner img {
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body>
<nav class="navbar navbar-expand-sm navbar-light bg-dark fixed-top">
    <a href="#" class="navbar-brand"><i><img src="images/53d9d679-7944-4ebc-8b25-72977d81e918.jpg" alt="" width="50dp" height="50dp"></i></a>
    <div class="collapse navbar-collapse">
        <ul class="navbar-nav">
            <li class="nav-item"><a class="nav-link text-light text-uppercase font-weight-bold px-3" href="#Home">Home</a></li>
            <li class="nav-item"><a class="nav-link text-light text-uppercase font-weight-bold px-3" href="#About us">About us</a></li>
            <li class="nav-item dropdown" data-toggle="dropdown"><a class="nav-link text-light text-uppercase font-weight-bold px-3 dropdown-toggle" href="#Type">Type</a>
                <div class="dropdown-menu">
                    <a class="dropdown-item" href="#Local">Local</a>
                    <a class="dropdown-item" href="#International">International</a>
                </div>
            </li>
            <li class="nav-item"><a class="nav-link text-light text-uppercase font-weight-bold px-3" href="#Contact us">Contact us</a></li>
        </ul>
        <ul>
            <div class="container">
                <!-- Button to Open the Modal -->
                <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#myModal">
                    sign in
                </button>

                <!-- The Modal -->
                <div class="modal fade" id="myModal">
                    <div class="modal-dialog">
                        <div class="modal-content">

                            <!-- Modal Header -->
                            <div class="modal-header">
                                <h4 class="modal-title">sign in</h4>
                                <button type="button" class="close" data-dismiss="modal">&times;</button>
                            </div>

                            <!-- Modal body -->
                            <div class="modal-body">
                                <div class="container">
                                    <h2>Sign in</h2>
                                    <form action="/action_page.php">
                                        <div class="form-group">
                                            <label for="nm">Name:</label>
                                            <input type="text" class="form-control" id="nm" placeholder="Enter name" name="name">

                                            <div class="form-group">
                                                <label for="emil">Email:</label>
                                                <input type="email" class="form-control" id="emil" placeholder="Enter email" name="email">
                                            </div>
                                            <div class="form-group">
                                                <label for="pwd">Password:</label>
                                                <input type="password" class="form-control" id="pwd" placeholder="Enter password" name="pswd">
                                            </div>
                                            <div class="form-check">
                                                <label class="form-check-label">
                                                    <input class="form-check-input" type="checkbox" name="remember"> Remember me
                                                </label>
                                            </div>
                                            <button type="submit" class="btn btn-primary">Submit</button>
                                        </div>
                                    </form>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>

        </ul>
        <form class="form-inline ml-auto">
            <div>
                <input type="text" class="form-control" placeholder="search">
                <div class="input-group-append">
                    <button type="button" class="btn"><i class="fas fa-search text-muted"></i></button>
                </div>
            </div>
        </form>
    </div>
</nav>

<hr>
<header class="m-3">
    <h1>PRIME TIME</h1>
</header>
<section>
    <div class="container-fluid m-4 mt-4" id="Home">
        <h1 class="font-weight-bold text-uppercase m-3">time dynasty</h1>
        <div class="row text-center">
            <div  class="col-md-4 col-sm-10 col-5 font-weight-normal text-muted font-italic">
                <p class="font-weight-bolder m-3">Time is the only thing that explains everything and thus makes it <br> a neccesity in life. <br>
                    <br>One needs a watch in various ways;like waking up or punctuality.
                    <br> <br>Thus the dynasty brings time closer to you. </p>
                <button type="button" class="btn-success">Learn more</button>
            </div>
            <div class="col-md-6 col-sm-10 col-5">
                <img src="images/Rolex_Submariner_16610-5D3_2391-Edit.jpg" alt="" width="400dp" height="300dp">
            </div>
        </div>
    </div>
</section>
<section>
    <div class="container-fluid m-5" id="About us">
        <div id="demo" class="carousel slide" data-ride="carousel">

            <!-- Indicators -->
            <ul class="carousel-indicators">
                <li data-target="#demo" data-slide-to="0" class="active"></li>
                <li data-target="#demo" data-slide-to="1"></li>
                <li data-target="#demo" data-slide-to="2"></li>
            </ul>

            <!-- The slideshow -->
            <div class="carousel-inner col-md-10 col-sm-10 col-8 ml-4">
                <div class="carousel-item active">
                    <img src="images/black.jpg" alt="Rolex" width="500dp" height="300dp">
                </div>
                <div class="carousel-item">
                    <img src="images/Guide-to-Quartz-Watches-gear-patrol-lead-full%20(1).jpg" alt="Seiko" width="500dp" height="200dp">
                </div>
                <div class="carousel-item">
                    <img src="images/images%20(14)%20(1).jpeg" alt="Curren" width="500dp" height="200dp">
                </div>
            </div>

            <!-- Left and right controls -->
            <a class="carousel-control-prev" href="tryit.asp-filename=trybs_carousel.html#demo" data-slide="prev">
                <span class="carousel-control-prev-icon"></span>
            </a>
            <a class="carousel-control-next" href="tryit.asp-filename=trybs_carousel.html#demo" data-slide="next">
                <span class="carousel-control-next-icon"></span>
            </a>
        </div>
    </div>
</section>
<section id="Type">
    <div class="container-fluid">
        <h2 class="text-light ml-3 m-2">display</h2>
        <div class="row m-4" id="Local">
            <div class="col-md-4 col-sm-10 col-5">
                <img src="images/images%20(9).jpeg" class="img-thumbnail">
                <p>Nike <br>$2700</p>
                <a href="#" type="button" class="btn btn-outline-dark">Buy</a>
            </div>
            <div class="col-md-4 col-sm-10 col-5">
                <img src="images/images%20(8).jpeg" class="img-thumbnail">
                <p>Seiko <br>$2000</p>
                <a href="#" type="button" class="btn btn-outline-dark">Buy</a>
            </div>
            <div class="col-md-4 col-sm-10 col-5">
                <img src="images/images%20(10).jpeg" class="img-thumbnail">
                <p>Rolex <br>$3000</p>
                <a href="#" type="button" class="btn btn-outline-dark">Buy</a>
            </div>
        </div>
        <div class="row m-4" id="International">
            <div class="col-md-4 col-sm-10 col-5">
                <img src="images/images%20(13).jpeg" class="img-thumbnail">
                <p>Tagheur <br>$2200</p>
                <a href="#" type="button" class="btn btn-outline-dark">Buy</a>
            </div>
            <div class="col-md-4 col-sm-10 col-5">
                <img src="images/images%20(11).jpeg" class="img-thumbnail">
                <p>Gucci <br>$2000</p>
                <a href="#" type="button" class="btn btn-outline-dark">Buy</a>
            </div>
            <div class="col-md-4 col-sm-10 col-5">
                <img src="images/Rolex-Submariner-min-min.jpg" class="img-thumbnail">
                <p>Omega <br>$2250</p>
                <a href="#" type="button" class="btn btn-outline-dark">Buy</a>
            </div>
        </div>
    </div>
</section>
<section>
    <div class="form-group text-center m-2 bg-secondary">
        <h2>Contact us</h2>
        <p class="font-italic">Your feedback is highly valued.</p>
        <div class="container-fluid form-group text-center" id="Contact us">
            <div class="form-group">
                <label for="usr">Name</label>
                <input type="text" id="usr" placeholder="Name">
            </div>
        </div>
        <div class="container-fluid">
            <div class="form-group">
                <label for="Email">Email</label>
                <input type="email" id="Email" placeholder="Email">
            </div>
        </div>
        <div class="container form-group">
            <label for="fb">Comment</label>
            <textarea name="feedback" id="fb" cols="20" rows="10"></textarea>
        </div>
        <button type="submit" class="btn btn-primary">submit</button>
    </div>
</section>
<section>
    <footer class="container-fluid bg-dark text-center">
        <div>
            <h1 class="text-light">social media</h1>
            <p class="text-light font-weight-bolder text-uppercase">like,tweet and follow.</p>
        </div>
        <div class="row py-2 justify-content-center">
            <div class="m-3">
                <a href="#" class="fab fa-facebook fa-2x"></a>
            </div>
            <div class="m-3">
                <a href="#" class="fab fa-twitter fa-2x"></a>
            </div>
            <div class="m-3">
                <a href="#" class="fab fa-instagram fa-2x"></a>
            </div>
        </div>
        <p class="text-light">&copy;copyright 2019-phpstorm</p>
    </footer>
</section>
<script src="js/jquery.js"></script>
<script src="js/bootstrap.js"></script>
</body>
</html>
