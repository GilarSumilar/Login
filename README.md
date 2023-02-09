<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    
    <!-- Style -->
    <link rel="stylesheet" href="style2.css">
     
    <!-- My Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Viga&display=swap" rel="stylesheet">

    <!-- Icons -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.7.1/font/bootstrap-icons.css">

    <title>Login . WEB | s i t e</title>
  </head>
  <body>

    <div class="container">        
      <div class="card login-form">
        <div class="card-body">
          <h2 class="card-title">Login</h2>
          <h6 class="card-subtitle text-muted mb-4">Don't have an account yet?</h6>

          <div class="d-grid mt-4 mb-4">
            <button type="submit" class="btn btn-light btn-gmail"><img src="img/google.png" class="img-style me-3" alt="gmail">Sign up with Gmail</button>
          </div>

          <form>
            <div class="mb-4">
              <label for="exampleInputEmail1" class="form-label">Email*</label>
              <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Your Email">
              <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
            </div>
            <div class="mb-3">
              <label for="exampleInputPassword1" class="form-label">Password*</label>
              <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Min 8 character">
            </div>

            <div class="d-flex justify-content-between">
              <div class="mb-3 form-check">
                <input type="checkbox" class="form-check-input" id="exampleCheck1">
                <label class="form-check-label" for="exampleCheck1">Remember me</label>
              </div>
              <div>
                <a href="#">Forgot Password ?</a>
              </div>
            </div>

            <div class="d-grid mt-4">
             <button type="submit" class="btn btn-primary btn btn-md btn-login">Login</button>
            </div>

            <div class="mt-3">
              <label>Not Registered Yet ? <a href="#">Create an acount</a></label>
            </div>

          </form>        
        </div>
      </div>
    </div>

    <!-- Footer -->
    
         <section class="footer" id="footer">
        <div class="container">
            <div class="box">
                <h2>About Us</h2>
                <p>
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Earum nisi dolorem reprehenderit? Eos quas
                    perferendis velit porro nemo tempora ab!
                </p>
                <div class="sosmed">
                    <div class="perSosmed">
                      <a class="facebook" href="#"><i class="bi bi-facebook btn-lg" data-bs-toggle="toolip" data-bs-placement="top" title="Facebook"></i></a>
                    </div>


                    <div class="perSosmed">
                      <a class="instagram" href="https://www.instagram.com/massa_gakenal/" target="_blank"><i class="bi bi-instagram btn-lg" data-bs-toggle="toolip" data-bs-placement="top" title="Instagram"></i></a>
                    </div>

                    <div class="perSosmed">
                      <a class="whatsapp" href="#"><i class="bi bi-whatsapp btn-lg" data-bs-toggle="toolip" data-bs-placement="top" title="Whatsapp"></i></a>
                    </div>

                    <div class="perSosmed">
                      <a class="email" href="#"><i class="bi bi-envelope btn-lg" data-bs-toggle="toolip" data-bs-placement="top" title="Email"></i></a>
                    </div>

                </div>
            </div>


            <div class="box">
                <h2 class="biji">Quick Link</h2>
                <a href="#">Home</a>
                <a href="#">About</a>
                <a href="#">Event</a>
                <a href="#">Login</a>
            </div>

        </div>
    </section>

  <!-- Akhir Footer -->

    <!-- Footer end -->

    <footer> 
      <div class="container">
        <div class="row">
          <div class="col-sm-12">
            <p class="text-center">&copy; Copyright 2021 | Build By. <a href="https://www.instagram.com/massa_gakenal/" target="_blank" target="_blank" >Timey</a></p>
          </div>
        </div>
      </div>
    </footer> 

  <!-- Akhir Footer end -->


    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>

  </body>
</html>
