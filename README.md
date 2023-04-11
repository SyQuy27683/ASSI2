<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="./css/bootstrap.min.css">
  <script src="./js/bootstrap.bundle.min.js"></script>
  <title>HOME</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css" />
  <link rel="stylesheet" href="./css/style.css">
</head>

<body>
  <header>
    <nav class="navbar navbar-expand-lg navbar-light" style="background-color: #92d1ff;">
      <div class="container-fluid">
        <a class="navbar-brand" href="index.html">
          <img src="img/chelsea-fc-2.svg" alt="" width="95" height="75" class="d-inline-block align-text-top">
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="index.html">HOME</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="Men team.html">MEN'S TEAM</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="news.html">NEWS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="contract.html">CONTACT</a>
            </li>
          </ul>
          <div class="d-flex align-items-center">
            <i class='far fa-user-circle' style='font-size:36px'></i><a class="nav-link ms-3" data-bs-toggle="modal"
              data-bs-target="#myModal" href="#">Login / Sign
              Up</a>
          </div>
        </div>
      </div>
    </nav>
    <!-- The Modal -->
    <div class="modal" id="myModal">
      <div class="modal-dialog modal-lg modal-dialog-centered">
        <div class="modal-content">

          <!-- Modal Header -->
          <div class="modal-header">
            <h4 class="modal-title">Login</h4>
            <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
          </div>

          <!-- Modal body -->
          <div class="modal-body">
            <div class="card mb-3">
              <div class="row g-0 d-flex align-items-center">
                <div class="col-lg-4 d-none d-lg-flex">
                  <img src="./img/chelsea-fc-2.svg" alt="Trendy Pants and Shoes"
                    class="w-100 rounded-t-5 rounded-tr-lg-0 rounded-bl-lg-5" />
                </div>
                <div class="col-lg-8">
                  <div class="card-body py-5 px-md-5">

                    <form>
                      <!-- Email input -->
                      <div class="form-outline mb-4">
                        <input type="email" id="form2Example1" class="form-control" />
                        <label class="form-label" for="form2Example1">Email address</label>
                      </div>

                      <!-- Password input -->
                      <div class="form-outline mb-4">
                        <input type="password" id="form2Example2" class="form-control" />
                        <label class="form-label" for="form2Example2">Password</label>
                      </div>

                      <!-- 2 column grid layout for inline styling -->
                      <div class="row mb-4">
                        <div class="col d-flex justify-content-center">
                          <!-- Checkbox -->
                          <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="" id="form2Example31" checked />
                            <label class="form-check-label" for="form2Example31"> Remember me </label>
                          </div>
                        </div>

                        <div class="col">
                          <!-- Simple link -->
                          <a href="#!">Forgot password?</a>
                        </div>
                      </div>

                      <!-- Submit button -->
                      <button type="button" class="btn btn-primary btn-block mb-4">Sign in</button>

                    </form>

                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Modal footer -->
          <div class="modal-footer">
            <button type="button" class="btn btn-danger" data-bs-dismiss="modal">Close</button>
          </div>

        </div>
      </div>
    </div>
  </header>
  <div id="carouselBanner" class="carousel slide d-flex mx-auto p-2 bd-highligh justify-content-center"
    data-bs-ride="carousel" style="width: 85%;">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselBanner" data-bs-slide-to="0" class="active" aria-current="true"
        aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselBanner" data-bs-slide-to="1" aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselBanner" data-bs-slide-to="2" aria-label="Slide 3"></button>
      <button type="button" data-bs-target="#carouselBanner" data-bs-slide-to="3" aria-label="Slide 4"></button>
      <button type="button" data-bs-target="#carouselBanner" data-bs-slide-to="4" aria-label="Slide 5"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="img/HAVA.JPG" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="img/enzo.jpg" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="img/hv.jpg" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="img/child.jpg" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="img/CLB.JPG" class="d-block w-100" alt="...">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselBanner" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselBanner" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>

  <section class="quang-cao mt-5 mx-4">
    <div class="row">
      <div class="col-lg-3 col-md-6">
        <div class="card">
          <div class="card-body">
            <img src="./img/dv1.jpg" alt="">
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-6">
        <div class="card">
          <div class="card-body">
            <img src="./img/dv2.jpg" alt="">
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-6">
        <div class="card">
          <div class="card-body">
            <img src="./img/dv3.jpg" alt="">
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-6">
        <div class="card">
          <div class="card-body">
            <img src="./img/dv1.jpg" alt="">
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="trailer my-5">
    <div class="container row text-center mx-auto">
      <div class="col-lg-6">
        <div class="card">
          <div class="card-body">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/-VvNw8fHiA8" title="YouTube video player" 
            frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
          </div>
        </div>
      </div>
      <div class="col-lg-6">
        <div class="card">
          <div class="card-body">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/1yfEAN1xxcY" title="YouTube video player" 
            frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
          </div>
        </div>
      </div>
    </div>
  </section>
  <footer class="text-white py-3">
    <div class="container">
      <div class="row">
        <div class="col-md-3">
          <h5>About me</h5>
          <p>Le Sy Quy - PS27683 <br>Quylsps27683@fpt.edu.vn</p>
        
        </div>
        <div class="col-md-3">
          <h5>Links</h5>
          <ul class="list-unstyled">
            <li><a href="#">Link 1</a></li>
            <li><a href="#">Link 2</a></li>
            <li><a href="#">Link 3</a></li>
            <li><a href="#">Link 4</a></li>
          </ul>
        </div>
        <div class="col-md-3">
          <h5>Address</h5>
          <p>123 Le Van Viet St<br>Saigon/Ho Chi Minh city</p>
        </div>
        <div class="col-md-3">
          <h5>Subscribe</h5>
          <form>
            <div class="mb-3">
              <label for="email" class="form-label visually-hidden">Email address</label>
              <input type="email" class="form-control" id="email" placeholder="Enter email">
            </div>
            <button type="submit" class="btn btn-primary mb-2">Subscribe</button>
          </form>
        </div>
      </div>
    </div>
  </footer>
  
</body>

</html>
