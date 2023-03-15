# my-html-work

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">



    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">


    <link
        href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;300;400;500;900&family=Ubuntu:wght@300;400;700&display=swap"
        rel="stylesheet">

    <link rel="stylesheet" href="pyt.css/boot.css">

    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"
        integrity="sha384-oBqDVmMz9ATKxIep9tiCxS/Z9fNfEXiDAYTujMAeBAsjFuCZSmKbSSUnQlmh/jp3"
        crossorigin="anonymous"></script>

    <script src="https://use.fontawesome.com/your-embed-code.js"></script>

    <script defer src="/your-path-to-fontawesome/js/brands.js"></script>
    <script defer src="/your-path-to-fontawesome/js/solid.js"></script>
    <script defer src="/your-path-to-fontawesome/js/fontawesome.js"></script>

    <script src="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.1/css/fontawesome.min.css"></script>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"
        integrity="sha384-mQ93GR66B00ZXjt0YO5KlohRA5SY2XofN4zfuZxLkoj1gXtW8ANNCe9d5Y3eG5eD"
        crossorigin="anonymous"></script>
    <title>Document</title>
</head>
<style>
	body{
    font-family: "Montserrat";
    
}
#title{
    background-color: #ff4c68;
    color: #fff;
}
h1{
      font-family: "Montserrat-Black";  
      font-size: 3rem;  
      line-height: 1.5;  
      font-weight: 900;
}
h2{
    font-family: "Montserrat-Black";
    font-size: 3rem;
    line-height: 1.5;

}
h3{
    font-family: "Montserrat-Black";

}
p{
    color: #8f8f8f;
}
.container-fluid{
    padding: 3% 15%;
}
.navbar-brand{
    font-size: 1.5rem;
}

#ntr{
    position: absolute;
    right: 20px;
}
.navbar{
    padding-bottom: 4.5rem;
}
.nav-item{
    padding: 0 18px;
}
.btn{
    margin: 5% 3%;
}
.title-image{
    width: 50%;
    transform: rotate(40deg);

}
#feature{
    color: #000;
    padding: 7% 15%;

}
.feature-box{
    text-align: center;
    padding: 5%;

}
#testimonials{
    background-color: #ff4c68;
    color: #fff;
    padding: 7% 15%;
    text-align: center;
}
.tind{
    border-radius: 100%;
    margin: 20px;
}
.carousel-item{
    padding: 7% 15%;   
}
@media  (min-width:900px) and (max-width:1000px){
    h1{
        color: chartreuse;
    }
}
@media (max-width:500px) {
    .title-image{
        position: static;
        transform: rotate(0);
    }
    
}

</style>

<body>
    <section id="title">
        <div class="container-fluid">
            <nav class=" navbar navbar-expand-lg navbar-dark ">
                <a href="" class="navbar-brand">TINDOG</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#ntr"
                    aria-controls="ntr" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <div class="collapse navbar-collapse" id="ntr">
                    <ul class="navbar-nav ml-3 p-2 mt-2">
                        <li class="nav-item ">
                            <a class="nav-link a " href="">CONTACT</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link b " href="">PRICE</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link c " href="">DOWNLOAD</a>
                        </li>
                    </ul>
                </div>
            </nav>
            <div class="row">
                <div class="col-lg-6 ">
                    <h1>Meet New and Exciting Dogs That are Neaarby</h1>
                    <button class="btn btn-dark btn-lg" type="button">
                        <i class="fab fa-apple"></i>DOWNLOAD</button>
                    <button class="btn btn-outline-light btn-lg" type="button">DOWNLOAD</button>
                </div>
                <div class="col-lg-6 ">
                    <img class="title-image" src="C:\Users\krish\Downloads\iphone6.png" alt="" >
                </div>
            </div>
        </div>
    </section>

    <section id="feature">
        <div class="row">
            <div class=" feature-box col-lg-4">
                <h3>EASY TO USE</h3>
                <p>It is so easy to use</p>
            </div>
            <div class=" feature-box col-lg-4">
                <h3>ELITE CLINTE</h3>
                <p>We have all types of dogs</p>
            </div>
            <div class="feature-box col-lg-4">
                <h3>Guarentee of Work</h3>
                <p>Find the mating dog or return Money</p>
            </div>
        </div>

    </section>
    <section id="testimonials">
        <h2>Now i have found the dog that i love . Now it's your turn</h2>
        <div id="carouselexample" class="carousel slide">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img class="d-block w-100" src="C:\Users\krish\Downloads\dog-tindog.jpg" alt="" width="10%">pebbels,us
                </div>
                <div class="carousel-item">
                    <img class="d-block w-100" src="C:\Users\krish\Downloads\dog-tindog-2.jpg" alt="" width="10%">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselexample" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselexample" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
    </section>
    <section id="car">
        <div class="row">
            <div class="col-lg-4 col-md-6">
                <div class="cards">
                    <div class="card-header">
                        head1
                    </div>
                    <div class="card-body">
                        <h3>$99</h3>
                        <button type="button" class="btn btn-secondary btn-lg">sign up</button>
                    </div>
            </div>
            </div>
            <div class="col-lg-4 col-md-6">
                <div class="cards">
                    <div class="card-header">
                        head2
                    </div>
                    <div class="card-body">
                        <h3>$199</h3>
                        <button type="button" class="btn btn-primary btn-lg">sign up</button>
                    </div>
                </div>
            </div>
            <div class="col-lg-4 col-md-6">
                <div class="cards">
                    <div class="card-header">
                        head3
                    </div>
                    <div class="card-body">
                        <h3>$399</h3>
                        <button type="button" class="btn btn-outline-dark btn-lg">sign up</button>
                    </div>
                </div>
            </div>    
        </div>
    </section>

</body>

</html>
