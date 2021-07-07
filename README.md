# bootstrap-header-design
Bootstrap Header and Banner design
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  
  <script src="https://kit.fontawesome.com/b99e675b6e.js"></script>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
   <link rel="stylesheet" type="text/css" href="style.css">
  <style>
 html{
      scroll-behavior: smooth;
    }
    body{
   font-family: 'Montserrat',sans-serif;
    }
    h1,h2,h3,h4,h5,h6{
       font-family: 'Roboto', sans-serif;
    }
    header{
      background:url(https://images.pexels.com/photos/6567331/pexels-photo-6567331.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500);
      background-position: center;
      background-attachment:fixed;
      background-repeat: no-repeat;
      background-size:cover;
      max-height: full;
        }
        .banner-container{
          height:100vh;
        }
.navbar{
    padding: 1% 10%;
    color: rgba(0,0,0,0.3);
}
.navbar-icon{
  color: white;
}
.navbar-brand img{
  width:90px;
  height:auto;
}
.nav-link{
  color: white;
  margin: 10px;
  border-radius: 5px;
  transition: 4s;
}
.nav-link:hover{
  background:#2980b9;
  outline:white;
  transform: scale(1.1);
}
.banner-container h1{
  font-size: 3.5rem;
 /* background-color: rgba(7,101,189,0.5);*/
  padding: 10px 20px;
  font-family:'Handlee', cursive;
}                             
  </style>
  
  <title>My Website</title>
</head>
<body> 
  <div class="container">
    
    <header>
       <div>
      <nav class="navbar navbar-expand-md">
  
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
    <span><i class="fas fa-bars navbar-icon"></i></span>
  </button>
  <a class="navbar-brand" href="#">
    <img src="D:\New image1\logo1a.jpg">
  </a>

  <div class="collapse navbar-collapse" id="navbarNavDropdown">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link text-center text-md-left" href="#">Home</a>
      </li>
      <li class="nav-item">
        <a class="nav-link text-center text-md-left" href="#">About Me</a>
      </li>
      <li class="nav-item">
        <a class="nav-link text-center text-md-left" href="#">Tutorial</a>
      </li>
       <li class="nav-item">
        <a class="nav-link text-center text-md-left" href="#">Contect</a>
      </li>
       <li class="nav-item">
        <a class="nav-link text-center text-md-left" href="#">Services</a>
      </li>
       <li class="nav-item">
        <a class="nav-link text-center text-md-left" href="#">Feedback</a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Dropdown link
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <a class="dropdown-item" href="#">Something else here</a>
        </div>
      </li>
    </ul>
  </div>
</nav>
      <section id="banner">
        <div class="banner-container d-flex justify-content-center align-items-center">
          <div class="banner-contents text-center">
            <h1 class="font-weight-bold text-white mb-5">Learn Something New!!!</h1>
            <button class="btn btn-primary mr-3" onclick="location.href'#tutorial'"><i class="fas fa-play mr-2"></i>Tutorial</button>
            <button class="btn btn-primary mr-3" onclick="window.open('https://www.youtube.com/channel/UClzMRrxuW2SQwog7Wil2J7Q')" class="request-callback"><i class="fab fa-youtube mr-2"></i>Subcribe</button>
          </div>
        </div>
      </section>
    </div>
    </header>
    <main>
      
    </main>
    <footer>
      
    </footer>
  </div>
 <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html> 


