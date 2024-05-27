<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="	https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css">


  <!-- Font Awesome -->
<link
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css"
rel="stylesheet"
/>
<!-- Google Fonts -->
<link
href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap"
rel="stylesheet"
/>
<!-- MDB -->
<link
href="https://cdnjs.cloudflare.com/ajax/libs/mdb-ui-kit/7.2.0/mdb.min.css"
rel="stylesheet"
/>
  <title>Document</title>
  <link rel="stylesheet" href="bootstarp.css">
</head>
<body>


  <!-- navbar -->
  <nav  class="navbar navbar-expand-lg bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand text-light" href="#">Navbar</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active text-light" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-light" href="#">Link</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle text-light" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Dropdown
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item text-light" href="#">Action</a></li>
              <li><a class="dropdown-item text-light" href="#">Another action</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item text-light" href="#">Something else here</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled text-light" aria-disabled="true">Disabled</a>
          </li>
        </ul>
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button  class="btn btn-outline-success" type="submit" >Subscribe</button>
        </form>
      </div>
    </div>
  </nav>
  <!-- navbar-end -->

  <!-- card1 -->
  <div style="margin-top: 40px;"  class="card-group" >
    <div class="card">
      <img src="card1.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">HeliCopter</h5>
        <p class="card-text">This is a Helicopter imoorted from the United  Kingdom.</p>
        <del>10000000$</del>
        <p>Rs : 100000$</p>
      </div>
    </div>
    <div class="card">
      <img src="card2.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">The super Bike</h5>
        <p class="card-text">This bike is very fast .it is fly in the air and its for sale .</p>
          <del>2000$</del>
          <p> Rs : 1200$</p>
      </div>
    </div>
    <div class="card">
      <img src="card3.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">CaR</h5>
        <p class="card-text">This car was made by Elon Musk.This is better than the Tesla</p>
        <del>250000$</del>
        <p> Rs : 200000$</p>
      </div>
    </div>
  </div>
  <!-- card1-end> -->

  <!-- card2 -->  
  <div style="margin-top: 40px;" class="card-group2">
    <div class="card">
      <img src="card4.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Clock</h5>
        <p class="card-text">The clock is very fast than the world.</p>
        <del>500$</del>
        <p> Rs : 399$</p>
      </div>
    </div>
    <div class="card">
      <img src="card5.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Coeffe</h5>
        <p class="card-text">This coeffe is very expensive.This is made  Abdullah</p>
        <del>100$</del>
        <p>Rs : 99$</p>
      </div>
    </div>
    <div class="card">
      <img src="card6.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Pop Corn</h5>
        <p class="card-text">This snacks is very tasty.Please try it.</p>
        <del>10$</del>
        <p>Rs : 7$</p>
      </div>
    </div>
  </div>
  <!-- card2-end> -->

  <!-- slidder -->
  <div style="margin-top: 30px;" id="carouselExampleIndicators" class="carousel slide">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="card7.png" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="card8.jpg" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="card9.jpg" class="d-block w-100" alt="...">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
  <!-- slidder-end --> 

  <!-- accordian -->
  <div class="accordion accordion-flush" id="accordionFlushExample">
    <div class="accordion-item">
      <h2 class="accordion-header">
        <button class="accordion-button collapsed bg-info" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
          Accordion Item #1
        </button>
      </h2>
      <div id="flush-collapseOne" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
        <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the first item's accordion body.</div>
      </div>
    </div>
    <div class="accordion-item">
      <h2 class="accordion-header">
        <button class="accordion-button collapsed bg-warning" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
          Accordion Item #2
        </button>
      </h2>
      <div id="flush-collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
        <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the second item's accordion body. Let's imagine this being filled with some actual content.</div>
      </div>
    </div>
    <div class="accordion-item">
      <h2 class="accordion-header">
        <button class="accordion-button collapsed bg-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
          Accordion Item #3
        </button>
      </h2>
      <div id="flush-collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
        <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the third item's accordion body. Nothing more exciting happening here in terms of content, but just filling up the space to make it look, at least at first glance, a bit more representative of how this would look in a real-world application.</div>
      </div>
    </div>
  </div>

  <!-- accordian-end -->

  <!-- video -->
  <div class="video1">
    <video height="580px" width="1000px" style="border-radius: 25px;" autoplay muted controls src="./DUBAI, United Arab Emirates In 8K ULTRA HD HDR 60 FPS._2.mp4"></video>
  </div>

  <!-- video-end -->

  <!-- footer -->
  <footer  class="text-center text-lg-start text-dark" style="background-color:#21D192">
    <!-- Section: Social media -->
    <section class="d-flex justify-content-between p-4 text-white" style="background-color: #21D192">
      <!-- Left -->
      <div class="me-5">
        <span>Get connected with us on social networks:</span>
      </div>
      <!-- Left -->

      <!-- Right -->
      <div>
        <a href="" class="text-white me-4">
          <i class="fab fa-facebook-f"></i>
        </a>
        <a href="" class="text-white me-4">
          <i class="fab fa-twitter"></i>
        </a>
        <a href="" class="text-white me-4">
          <i class="fab fa-google"></i>
        </a>
        <a href="" class="text-white me-4">
          <i class="fab fa-instagram"></i>
        </a>
        <a href="" class="text-white me-4">
          <i class="fab fa-linkedin"></i>
        </a>
        <a href="" class="text-white me-4">
          <i class="fab fa-github"></i>
        </a>
      </div>
      <!-- Right -->
    </section>
    <!-- Section: Social media -->

    <!-- Section: Links  -->
    <section class="">
      <div class="container text-center text-md-start mt-5">
        <!-- Grid row -->
        <div class="row mt-3">
          <!-- Grid column -->
          <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
            <!-- Content -->
            <h6 class="text-uppercase fw-bold">Abdullah Star</h6>
            <hr class="mb-4 mt-0 d-inline-block mx-auto" style="width: 60px; background-color: #7c4dff; height: 2px">
            <p>
              Here you can visit our studio to see the amimals and car and 
              helicopter.
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
            <!-- Links -->
            <h6 class="text-uppercase fw-bold">WebSites</h6>
            <hr class="mb-4 mt-0 d-inline-block mx-auto" style="width: 60px; background-color: #7c4dff; height: 2px">
            <p>
              <a href="https://mdbootstrap.com/docs/standard/navigation/footer/examples-and-customization/" class="text-dark">MDBootstrap</a>
            </p>
            <p>
              <a href="https://www.youtube.com/" class="text-dark">YouTube</a>
            </p>
            <p>
              <a href="https://api.whatsapp.com/send/?phone=923039236446&text&type=phone_number&app_absent=0" class="text-dark">WhatsAPP</a>
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">
            <!-- Links -->
            <h6 class="text-uppercase fw-bold">Useful links</h6>
            <hr class="mb-4 mt-0 d-inline-block mx-auto" style="width: 60px; background-color: #7c4dff; height: 2px">
            <p>
              <a href="https://myaccount.google.com/?hl=en&utm_source=OGB&utm_medium=act" class="text-dark">Your Account</a>
            </p>
            <p>
              <a href="#!" class="text-dark">Become an Affiliate</a>
            </p>
            <p>
              <a href="#!" class="text-dark">Shipping Rates</a>
            </p>
            <p>
              <a href="#!" class="text-dark">Help</a>
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4">
            <!-- Links -->
            <h6 class="text-uppercase fw-bold">Contact</h6>
            <hr class="mb-4 mt-0 d-inline-block mx-auto" style="width: 60px; background-color: #7c4dff; height: 2px">
            <a href="https://www.google.com/maps/place/Gatwala+Commercial+Hub/@31.4669996,73.1903323,17z/data=!4m6!3m5!1s0x39226ed08366fdf5:0x4b2ee86150cbfe11!8m2!3d31.4658329!4d73.1939909!16s%2Fg%2F11f3m97yww?authuser=0&entry=ttu"><p><i class="fas fa-home mr-3"></i> FSD , GataWala ,198 RB</p></a>
            <p><i class="fas fa-envelope mr-3"></i> info@example.com</p>
            <p><i class="fas fa-phone mr-3"></i> +92-3039236446</p>
            <p><i class="fas fa-print mr-3"></i> +92-3OO6674246</p>
          </div>
          <!-- Grid column -->
        </div>
        <!-- Grid row -->
      </div>
    </section>
    <!-- Section: Links  -->

    <!-- Copyright -->
    <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2)">
      © 2020 Copyright:
      <a class="text-dark" href="https://mdbootstrap.com/">MDBootstrap.com</a>
    </div>
    <!-- Copyright -->
  </footer>
   <!-- footer-end> -->

</body>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

<!-- MDB -->
<script
  type="text/javascript"
  src="https://cdnjs.cloudflare.com/ajax/libs/mdb-ui-kit/7.2.0/mdb.umd.min.js"
></script>

</html>
