<template>
 <div class="container">
      <header id="nav1" class="navbar navbar-expand-lg fixed-top">
        <div class="container-fluid">
            <label>Your Region:</label> 
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              
              <li class="nav-item dropdown">
                <a id="drop" class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Gauteng
                </a>
                </li>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Freestate</a></li>
                  <li><a class="dropdown-item" href="#">Eastern Cape</a></li>
                  <li><a class="dropdown-item" href="#">Gauteng</a></li>
                  <li><a class="dropdown-item" href="#">Mpumalanga</a></li>
                  <li><a class="dropdown-item" href="#">Kwazulu/natla</a></li>
                  <li><a class="dropdown-item" href="#">Western Cape</a></li>
                </ul>
            </ul>
            <ul id="lgsg" class="navbar-nav me-auto mb-2 mb-lg-0">
                <li><a href="#">LOG IN</a></li> |
                <li><a href="#">SIGN UP</a></li>
            </ul>
        </div>
    </header>
      <nav class="navbar navbar-expand-lg">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"><img id="logo" src="https://i.postimg.cc/yYFHzQN8/picknpay.png" alt="Logo"> </a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            
            <form class="d-flex" role="search">
              <input id="searchbar" class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            </form>
            <button id="btn">
                <i class="fa-solid fa-file-lines"></i>Online Orders
            </button>
            <button id="btn2">
                <i class="fa-solid fa-heart"></i>Favourites & Lists
            </button>
            <div id="order">
              <i class="fa-solid fa-truck"></i>
              <p>Book</p>
            </div>
            <div id="order2">
              <i class="fa-solid fa-cart-shopping"></i>
              <p>Trolley</p>
            </div>
            
          </div>
        </div>
      </nav>
      <nav>
          <ul>

              <li id="link" class="nav-item dropdown"><a id="link2" class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">Shop by Aisle</a></li>
              <li id="link">Specials</li>
              <li id="link" class="nav-item dropdown"><a id="link2" class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">Winter</a></li>
              <li id="link">Recipes</li>
              <li id="link" class="nav-item dropdown"><a id="link2" class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">Smart Shopper</a></li>
              <li id="link">Pick n Pay asap!</li>
              <li id="link">In-Store Catalogues</li>
              <li id="link">Feed The Nation</li>
          </ul>
      </nav>
      <div id="party">
        <p>There are no more party packs left today. 😲 Come back tomorrow for another FREE party pack! Hurry, daily limits apply. Valid 1 - 7 Aug 2022.</p>
      </div>
      <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://i.postimg.cc/DfCV90xv/Birthday-Homepage-Header.gif" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="https://i.postimg.cc/G3gNMNp9/OLS-Party-Pack-HP-Banner-Nivea-Always-On-4-Days.jpg" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="https://i.postimg.cc/xjG8Mvjs/OLS-Homepage-Banner-Desktop-1.jpg" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="https://i.postimg.cc/Mp29N8JZ/Same-Day-Delivery-Desktop01.jpg" class="d-block w-100" alt="...">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      <hr>
      <button>Book A Delivery</button>
      <button>Shop SpecialS</button>
      <button>Clothing</button>
      <button>Competitions</button>
      <button>Track My Orders</button>
      <button>PnP Moblie</button>

      <h1>Shop Our Top Sellers</h1>

        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
      <button id="shop-now">
        Shop Now>
      </button>
      <h1>Top Online Deals</h1>

        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
      <button id="shop-now">
        Shop Now>
      </button>
      <h1>Lights On - Load Shedding Esstentials</h1>

        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
      <button id="shop-now">
        Shop Now>
      </button>
      <h1>Crafted Collect For Any Occasion</h1>

        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
      <button id="shop-now">
        Shop Now>
      </button>
      <h1>House & Home Savings</h1>

        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
      <button id="shop-now">
        Shop Now>
      </button>
      <h1>For The Ultimate Cheese Board</h1>

        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
        <div class="card">
          <img src="https://picsum.photos/id/237/200/300" alt="...">
        </div>
      <button id="shop-now">
        Shop Now>
      </button>
    <h1>Inspiration From Pnp</h1>
    <div class="card">
      <img id="inspiration" src="https://i.postimg.cc/QM2fcGNW/Winter-Drinks-Homepage.jpg" alt="...">
    </div>
    <div class="card">
      <img id="inspiration" src="https://i.postimg.cc/W1K8PLkf/Cook-In-Homepage.jpg" alt="...">
    </div>
    <div class="card">
      <img id="inspiration" src="https://i.postimg.cc/Pf387bZS/Bakery-Homepage.jpg" alt="...">
    </div>
    <div class="card">
      <img id="inspiration" src="https://i.postimg.cc/gk78xy2x/Breakfast-Homepage.jpg" alt="...">
    </div>
    <div class="container">
      <img id="poster" src="https://i.postimg.cc/sfNvmjd8/HOMEPAGE-SPECIALS-1160-X300-NO-PINK-Desktop.jpg" alt="...">
      <img id="poster" src="https://i.postimg.cc/QC9Nw7Gz/hmpg-banner-1160x300.jpg" alt="">
    </div>
    
    <h1>Reasons Top Shop With Us</h1>
    <div id="card" class="row">
      <div class="col-md-4">
        <i id="reason" class="fa-solid fa-truck"></i>
        <h5>Scheduled same-day delivery</h5>
        <p>Order before 10 AM & get your groceries delivered in the afternoon.</p>
        <a id="option" href="#">Book a slot></a>
      </div>
      <div class="col-md-4">
        <i id="reason" class="fa-solid fa-motorcycle"></i>
        <h5>On-demand delivery</h5>
        <p>Get the Pick n Pay asap! app for some-day delivery in as little as 60 minutes.</p>
        <a id="option" href="#">Download app></a>
      </div>
      <div class="col-md-4">
        <i id="reason" class="fa-solid fa-store"></i>
        <h5>Click n Collect</h5>
        <p>Order online and collect at your nearest store for free.</p>
        <a id="option" href="#">Book a slot></a>
      </div>
    </div>
    <div id="card" class="row">
      <div class="col-md-4">
        <i id="reason" class="fa-solid fa-address-card"></i>
       <h5>Smart Shopper loyalty</h5> 
       <p>Collect and pay with your points.</p>
       <a id="option" href="#">More info></a> 
      </div>
      <div class="col-md-4">
        <i id="reason" class="fa-solid fa-box-open"></i>
        <h5>Shop your favourites</h5>
        <p>Order your most loved products in just a few seconds.</p>
        <a id="option" href="#">Shop Favourites></a>
      </div>
      <div class="col-md-4">
        <i id="reason" class="fa-solid fa-medal"></i>
        <h5>Guaranteed fresh</h5>
        <p>We pick only the freshest groceries.</p>
        <a id="option" href="#">Shop Fresh></a>
      </div>
    </div>
    </div>
    <footer>
      <div class="container">
        <div class="row">
          <div class="col-md-2">
            <img id="logo2" src="https://i.postimg.cc/V60XJLVM/PicknPay.png" alt="">
          </div>
          <div class="col-md-10">
            <ul id="links">
              <li id="leader" class="nav-item dropdown"><a id="link3" class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">Company</a></li>
              <li class="nav-item dropdown"><a id="link3" class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">Useful</a></li>
              <li class="nav-item dropdown"><a id="link3" class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">Mobile & Money</a></li>
              <li class="nav-item dropdown"><a id="link3" class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">Help</a></li>
              </ul>
          </div>
        
        </div>
      <hr>
        <div id="last" class="row">
          <div class="col-md-3">
           <h5>Showing Our New Shopping App</h5>
           <img id="store" src="https://i.postimg.cc/rw7GG42s/App-Store.png" alt="">
           <img id="store" src="https://i.postimg.cc/gJSf44z8/Google-Play.png" alt="">
           <img id="store" src="https://i.postimg.cc/d3cS5XM7/App-Gallery.png" alt=""> 
          </div>
          <div class="col-md-6">
            <strong><p class="text-center">&copy;2022 Pick n Pay All Rights Reserved</p></strong> 
            <p class="text-center">Privacy Portal | Copyright | Returns Policy | CPA | Customer Communication</p>
          </div>
          <div class="col-md-3">
           <h5>Follow Us On:</h5> 
           <i class="fa-brands fa-facebook"></i>
           <i class="fa-brands fa-twitter"></i>
           <i class="fa-brands fa-youtube"></i>
           <i class="fa-brands fa-pinterest"></i>
           <i class="fa-brands fa-instagram"></i>
          </div>
        </div>
      </div>
    </footer>
</template>

<style>
*{
    margin: 0;
    padding: 0;
}



#nav1{
    background-color:#B9154A;
    color: white;
}

#drop{
    color: white; 
    text-decoration:underline;
}

#lgsg{
    padding-left: 900px;
    gap: 10px;
}
#searchbar{
    width: 450px;
}

#btn{
    width: 180px;
    margin-left: 20px;
    background-color: rgb(41, 41, 112);
    color: white;
    height: 37px;
}
#btn2{
    width: 180px;
    background-color: rgb(41, 41, 112);
    color: white;
    height: 37px;
    margin-left: 10px;
}

#order{
    margin-left: 50px ;
}
#order2{
    margin-left: 30px;
}

label{
    color: white;
}
a{
    color: white;
}
a:hover{
    color: #d6265e;
}

li nav-item dropdown{
    color: white;
}

#logo{
    width: 100%;
    height: 50px;
}
#logo2{
    margin-top: 15px;
    width: 100;
    height: 50px;
}

img{
    width: 100%;
    height: auto;
    width: 250px;
    height: 250px;
}

li{
    display: inline;
    gap: 10px;
}

.card{
    width: 300px;
    gap: 5px;
    display: inline;
}

footer{
    background-color:#B9154A;
    color: white;
}

#store{
    width: 90px;
    height: 30px;
}

#reason{
    font-size:70px;
    color: blue;
}

#link{
    padding-left: 50px;
    font-weight: 500;
    color: rgb(71, 71, 71);
}

#link2{
    display: inline;
}

#party{
    background-color: yellow; 
    height:50px; 
    padding-top: 10px;
    padding-left: 100px;
    margin-bottom: 10px;
}

button{
    width: 170px;
    height: 37px;
    margin-left: 30px;
}

#inspiration{
    width: 310px;
    margin-left: 5px;
    margin-bottom: 10px;
    height: 200px;
}

#poster{
    width: 100%;
}

#option{
    text-decoration: underline;
    color:#B9154A;
}

#card{
    height: 200px;
}

#shop-now{
    margin-left: 500px;
    margin-top: 10px;
}

#leader{
    margin-left: 50px;
}

#link3{
    display: inline;
    margin-left: 50px;
}

#links{
    margin-top: 30px;
}

#last{
    height: 100px;
}

.carousel-control-prev-icon{
    margin-top: 200px; 
    margin-right: 100px;
}

.carousel-control-next-icon{
    margin-top: 200px; 
    margin-left: 100px;
}
</style>