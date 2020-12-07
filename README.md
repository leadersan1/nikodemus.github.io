<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

<!-- jQuery library -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

<!-- Popper JS -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>

<!-- Latest compiled JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <title>Belajar bootstrap</title>
</head>
<style>
     .carousel-inner img {
    width: 100%;
    height: 100%;
  }
</style>
<body>
    <div class="jumbotron jumbotron-fluid bg-success text-center" style="margin-bottom: 0;">
        <div class="container">
          <h1>Fakultas Teknik Informatika</h1> 

          <p>Universitas Advent Indonesia</p>
        </div>        
    </div>
    <nav class="container-fluid bg-dark " >
        <div class="btn-group">
            <button type="button" class="btn btn-dark dropdown-toggle p-3" data-toggle="dropdown" style="color: lightgray">Tentang
            </button>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="#">Visi Misi</a>
              <a class="dropdown-item" href="#">Sejarah</a>
              <a class="dropdown-item" href="#">Sambutan Dekan</a>
            </div>
          </div>
          <div class="btn-group">
            <button type="button" class="btn btn-dark dropdown-toggle " data-toggle="dropdown" style="color: lightgray">Akademik
            </button>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="">Prodi Teknik Informatika</a>
              <a class="dropdown-item" href="">Prodi Sistem Informasi</a>
              <a class="dropdown-item" href="">Persyaratan</a>
            </div>
          </div>
          <div class="btn-group">
            <button type="button" class="btn btn-dark dropdown-toggle" data-toggle="dropdown" style="color: lightgray">Penelitian
            </button>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="#">Minat Penelitian</a>
              <a class="dropdown-item" href="#">Group Penelitian</a>
              <a class="dropdown-item" href="#">Jurnal Teika</a>
            </div>
          </div>
    </nav>
    <div id="demo" class="carousel slide" data-ride="carousel">

        <!-- Indicators -->
        <ul class="carousel-indicators">
          <li data-target="#demo" data-slide-to="0" class="active"></li>
          <li data-target="#demo" data-slide-to="1"></li>
          <li data-target="#demo" data-slide-to="2"></li>
        </ul>
        
        <!-- The slideshow -->
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://fti.unai.edu/wp-content/uploads/2017/07/Fieldtrip-IT.jpg"  width="1100" height="500">
          </div>
          <div class="carousel-item">
            <img src="https://fti.unai.edu/wp-content/uploads/2017/07/Tugu-UNAI.jpg"  width="1100" height="500">
          </div>
          <div class="carousel-item">
            <img src="https://fti.unai.edu/wp-content/uploads/2017/07/Tugu-UNAI.jpg"  width="1100" height="500">
          </div>
        </div>
        
        <!-- Left and right controls -->
        <a class="carousel-control-prev" href="#demo" data-slide="prev">
          <span class="carousel-control-prev-icon"></span>
        </a>
        <a class="carousel-control-next" href="#demo" data-slide="next">
          <span class="carousel-control-next-icon"></span>
        </a>
      </div>
      
    <div class="container">

        <div class="row">
          <div class="col-sm-4">
            <img src="https://scontent-cgk1-1.xx.fbcdn.net/v/t1.0-9/87963285_1135889213414872_8725765432406966272_n.jpg?_nc_cat=111&ccb=2&_nc_sid=730e14&_nc_eui2=AeERcqMYxO0tunyFlXkabzQwW6z093Gjow5brPT3caOjDtFzL595BnZ-HrsQVf8sEMURKwSXmCbJVnTCCREzsxKU&_nc_ohc=fIQ254y-v7MAX-B3y0I&_nc_ht=scontent-cgk1-1.xx&oh=3d5c56726b1435156384dfa6b2a64d4c&oe=5FF22777" class="img-fluid" width="500" height="500">
            <p>Manusia yang tidak bisa membedakan mana mana udara dan mana oksigen di waktu yang bersamaan</p>
         
          </div>
          <div class="col-sm-4">
            <img src="https://scontent-cgk1-1.xx.fbcdn.net/v/t1.0-9/67670755_967272800276515_1741107358714560512_o.jpg?_nc_cat=102&ccb=2&_nc_sid=8bfeb9&_nc_eui2=AeE6vww6CZ4vs4v7z15pdqEAVgpze5dp4xVWCnN7l2njFQtHJLLMARxHx9g6vfTwTzhyxpMwSG8RNHW1yjeS4BrE&_nc_ohc=iU6HQP0qNmwAX_KDJLR&_nc_ht=scontent-cgk1-1.xx&oh=f72de1a95c618d7dfa325ac75c829ce4&oe=5FF38C56" class="img-fluid" width="500" height="500">
            <p>Sahabat pertama yang Telah Sukses setelah menyelesaikan masa-masa SMA dan telah menjadi Polisi di daerah Cimahi bandung</p>
          
          </div>
          <div class="col-sm-4">
            <img src="https://scontent-cgk1-1.xx.fbcdn.net/v/t1.0-9/12079224_180006039003199_5954696631768167846_n.jpg?_nc_cat=110&ccb=2&_nc_sid=19026a&_nc_eui2=AeEiA7YRe7IhuGG-nHbDR_VtUbJwovynN-VRsnCi_Kc35Wyx4Y2685OaHZIMNLGDfZR7GLGtTawso5WDwrgM78sz&_nc_ohc=x2fkUo8-zRkAX9umUdR&_nc_ht=scontent-cgk1-1.xx&oh=44aa7118bf46d57dfa83dbf6af8c78ef&oe=5FF29068" class="img-fluid"  width="500" height="500">      
            <p>Ini foto saya ketika berumur 10 thn yang sudah siap untuk menerima Yesus menjadi Juruslamat Saya Pribadi melalui babtisan kudus</p>
            
          </div>
        </div>
    </div>
      <div class="jumbotron text-center" style="margin-top: 20px; margin-bottom:0">
        <p>Created by Noel Nikodemus Sabaton Pandiangan.MTA</p>
        <p>©FTI UNAI 2020</p>
      </div>
    
</body>
</html>
