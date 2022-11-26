<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ShopE🛒</title>
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css">
<style>
     *{
      margin: 0;
      padding: 0;
    }
    .navbar{
        background-color:slategray;
        position: sticky;
        position: -webkit-sticky;
        top:0px;
        height: 80px;
        
    }
    .navbar-brand{
        margin: 0px;
        color:wheat;
        font-size: 40px;
        font-style: oblique;
        padding:50px
    }
    .navbar-brand:hover{
        color: wheat;
    }
    .nav-link{
        color:white;
        
        margin-left: 20px;
    }
    .nav-item{
        position: right;
    }
    .form-control{
        border-color: #ffa31a;
        
    }
    .btn{
        background-color: #ffcc80;
    }
    .btn:hover{
        background-color: #ffd699;
    }
    *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    footer{
          position: relative;
          bottom: 0;
          left: 0;
          right: 0;
          background: #111;
          height: auto;
          width: 100vw;
          padding-top: 40px;
          color: #fff;
      }
      .footer-content h3{
    font-size: 2.1rem;
    font-weight: 500;
    text-transform: capitalize;
    line-height: 3rem;
}
.footer-content p{
    max-width: 500px;
    margin: 10px auto;
    line-height: 28px;
    font-size: 14px;
    color: #cacdd2;
}
.socials{
    list-style: none;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 1rem 0 3rem 0;
}

.socials li{
    margin: 0 10px;
}
.socials a{
    text-decoration: none;
    color: #fff;
    border: 1.1px solid white;
    padding: 5px;
    border-radius: 50%;
}

.socials a i{
    font-size: 1.1rem;
    width: 20px;
    transition: color .4s ease;
}

.socials a:hover i{
    color: aqua;
}



.footer-bottom p{
   float: left;
   font-size: 14px;
   word-spacing: 2px;
   text-transform: capitalize;
}
.footer-bottom p a{
  color:#44bae8;
  font-size: 16px;
  text-decoration: none;
}
.footer-bottom span{
    text-transform: uppercase;
    opacity: .4;
    font-weight: 200;
}

    .container{
      max-width: 1170px;
      margin: auto;
    }
    ul{
      list-style: none;
    }
    .footer-content{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    text-align: center;
}
    
    .anchor{
      text-decoration: none;
      color: white;
    }
    .saad{
      display: inline-block;
      background-color: blue;
      width: 100%;
    }
    .list{
      display: inline-block;
    }
    .m1{
      display: inline-block;
      margin-left: 10px;
      margin-right: 80px;
      margin-top: 20px;
      font-size: 20px;
    }
    .m1:hover{
      background-color: #ffd699;
    }
    .anchor1{
      text-decoration: none;
      color: white;
    }
    .products{
      width: 300x;
      height: 300px;
      padding-left: 55px;
    }

    .anchor2{
      text-decoration: none;
      color: black;
      width: 30px;
    }
    .products1{
      width:420px;
      border: groove;
      border-radius: 25px;
      height: auto;
      margin-top: 30px;
      margin-left: 450px;
      padding-left: 10px;
     
      background-color: white;
    }
  
    .heading{
      margin-left: 490px;
      font-size: 33px;
      font: italic;
      padding-left: 5px;
     padding-top: 15px; 
     padding-bottom: 0px;
    }

            body{
              background-color: slategray;
            }
            .gallery1{
                color: black;
                text-decoration: none;
            }
            .gallery2{
                color: hotpink;
                text-decoration: none;
            }
            .gallery1:hover{
                color: blue;
            }
            .gallery2:hover{
                color: blue;
            }
   

    
    

</style>
</head>
<body>

    <nav class="navbar sticky-top navbar-expand-lg ">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"><img src="images/logo.png" alt="" width="50" height="40">
            ShopE</a>
         
          

            <form class="d-flex">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">🔎</button>
            </form>
            <ul class="navbar-nav m-lg-left">
                <li class="nav-item ">
                  <a class="nav-link active" aria-current="page" href="#">Home</a>
                </li>
             
                <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                    🛒
                  </a>
                  <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                    <li><a class="dropdown-item" href="#">My Cart</a></li>
                    <li><a class="dropdown-item" href="#">Wishlist</a></li>
                    <li><hr class="dropdown-divider"></li>
                    <li><a class="dropdown-item" href="#">Help?</a></li>
                  </ul>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="aboutus.html" target="_new">About us</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="signup.html" target="_new"> Sign Up</a>
                </li>
              </ul>
          </div>
        </div>
      </nav>
      
      <div class="saad">
        <ul class="list">
          <li class="m1">
            <a href=""class="anchor1">Electronics</a>
          </li>
          <li class="m1">
            <a href="accessories.html" class="anchor1">Accessories</a>
          </li>
          <li class="m1">
             <a href="clothing.html" class="anchor1"> Clothing</a>
          </li>
          <li class="m1">
            <a href="furniture.html" class="anchor1"> Furniture</a>
         </li>
         <li class="m1">
          <a href="home appliances.html" class="anchor1">Home Appliances</a>
      </div>
      <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <br>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="img1.jpg" width="100%" height="600px"  alt="...">
            <div class="carousel-caption d-none d-md-block">
                <a href="clothing.html" class="gallery1"> <h5 class="gallery1">Grab upto 30% offer on latest products </h5></a>
                <a href="clothing.html" class="gallery1"> <p class="gallry1"> Fashion for men and women</p></a>
              
            </div>
          </div>
          <div class="carousel-item">
            <img src="i.webp" width="100%" height="600px" alt="...">
            <div class="carousel-caption d-none d-md-block">
                <a href="shope .html" class="gallery2"> <h5 class="gallery2"> Electronic devices up for grabs</h5> </a>
            </div>
          </div>
          <div class="carousel-item">
            <img src="R (2).jpg" width="100%" height="600px">
            <div class="carousel-caption d-none d-md-block">
                <a href="furniture.html" class="gallery1"><h5 class="gallery1">Furniture at lowest prices </h5></a>
              <p>Some representative placeholder content for the third slide.</p>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      <h1 class="heading">
        Recommended for you
      </h1>
      <div class="products1">
        <a class="anchor2" target="_new" href="https://www.amazon.in/dp/B09X7SXPKC/ref=cm_sw_r_apa_i_dl_5868EN7TJVA3M6QDKZ5T_0"><img class="products" src="images/Product1.jpg" alt=""> <p class="productp">Acer Nitro 5 Gaming Laptop/ 11th Gen Intel Core i5-11400H Processor 6 core/ 15.6"(39.6cms) FHD 144 Hz Display (8GB/512GB SSD/GTX 1650 Graphics/Windows...</p></a>
      </div> <div class="products1">
        <a class="anchor2" target="_new" href="https://www.amazon.in/dp/B08WHTPNVZ/ref=cm_sw_r_apa_i_GPE66XC45F0B8WPB7A18_2"><img class="products" src="images/product2.jpg" alt=""> <p class="productp">boAt Immortal IM-200 7.1 Wired Over Ear Headphones Channel USB Gaming Headphone with RGB Breathing LEDs & 50mm Drivers with mic (Active Black)</p></a>
       
      </div>
      <div class="products1">
        <a class="anchor2" target="_new" href="https://www.amazon.in/dp/B09NYKZ7M8/ref=cm_sw_r_apa_i_XA1XZ2T7EQQRZXWQ80T8_0"><img class="products" src="images/product3.jpg" alt=""> <p class="productp">boAt Airdopes 181 Bluetooth Truly Wireless in Ear Earbuds with Mic, ENx, Tech, Beast, Mode (Low Latency Upto 60ms) for Gaming, ASAP, Charge, 20H Playtime, Bluetooth v5.2, IPX4 & IWP (Carbon Black)</p></a>

      </div>
      <div class="products1">
        <a class="anchor2" target="_new" href="https://www.amazon.in/dp/B094NTVMVS/ref=cm_sw_r_apa_i_F9QBMBK4V543QD734C9V_0?_encoding=UTF8&psc=1"><img class="products" src="images/product4.jpg" alt=""> <p class="productp">Croma 20 Litres Solo Microwave Oven (CRAM2026, Black)</p></a>

      </div><br><br>

      <footer>
        <div class="footer-content">
          
            <h3>ShopE</h3>
      </div>
  
      <ul class="socials">
        <li><a href="#"><i class="fab fa-facebook"></i></a></li>
        <li><a href="#"><i class="fab fa-twitter"></i></a></li>
        <li><a href="#"><i class="fab fa-github"></i></a></li>
        <li><a href="#"><i class="fab fa-youtube"></i></a></li>
       
     </ul>
  
   <p>copyright &copy;2022 <a href="#">ShopE</a>  </p>
      </footer>

      


    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>

</body>
</html>



    
