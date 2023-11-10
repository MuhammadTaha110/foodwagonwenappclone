# foodwagonwenappclone


#INDEX.HTML
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style.css">

  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js">

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"
    integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<body>

  <!--Header-->

  <div class="container">

    <div class="row header">
      <div class=" logo_div">
        <img class="logo" src="imgs/logo.png" alt="Logo">
      </div>

      <div class="search_span_1 ">
        <span>Deleiver to: </span><i class="fa-solid fa-location-dot icon_color"></i><span><span class="norm_span">
            Current location</span></span><span> Karachi, Pakistan</span>
      </div>

      <div class="search_span_2 ">
        <i class="fa-solid fa-magnifying-glass icon_color"></i><span> Search Food</span>
      </div>


      <div class="button_div ">
        <button class="btn btn-light login_button"><i class="fa-solid fa-user"></i>&nbsp;&nbsp;Login</button>
      </div>
    </div>
  </div>


  <!--Search_Div-->



  <div class="searchdiv">
    <div class="searchheading">
      <h1>Are you starving?</h1>
      <p>Within a few clicks, find meals that are accessible near you</p>

      <div class="searchimage">
        <img src="imgs/Image.png" alt="Poster">
      </div>
    </div>



    <div class="searchdiv_searchbar">
      <div class="searchdiv_searchbar_innerdiv">
        <i class="fa-solid fa-motorcycle"></i>
        Deleivery
      </div>
      <div class="searchdiv_searchbar_innerdiv_pickup">
        <i class="fa-solid fa-bag-shopping"></i>
        Pick Up
      </div>
      <div class="searchdiv_searchbar_innerdiv_searchbar">
        <i class="fa-solid fa-location-dot"></i>
        <form>
          <input class="searchdiv_searchbar_innerdiv_searchbar_form" type="text" placeholder="Enter Your Address">
        </form>
      </div>
      <button class="searchdiv_searchbar_innerdiv_searchbar_button">
        <i class="fa-solid fa-magnifying-glass"></i>
        <span>Find Food</span>
      </button>
    </div>
  </div>

  <!--Card_Div-->

  <div class="container">

    <div class="row cardDivMain">
      <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">

        <div class="sale_tag">
          <div class="num">
            15
          </div>
          <div class="off">
            <div class="per">%</div>
            <div class="offin">Off</div>
          </div>
        </div>

        <img class="cardDiv_img" src="imgs/CardDeal (1).png" alt="Card1">
        <h6 class="cardTittle">Grey Vage</h6>
        <p class="cardDays">6 Days Remaining</p>
      </div>
      <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">

        <div class="sale_tag">
          <div class="num">
            10
          </div>
          <div class="off">
            <div class="per">%</div>
            <div class="offin">Off</div>
          </div>
        </div>

        <img class="cardDiv_img" src="imgs/CardDeal (4).png" alt="Card1">
        <h6 class="cardTittle">Grey Vage</h6>
        <p class="cardDays">6 Days Remaining</p>
      </div>
      <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">

        <div class="sale_tag">
          <div class="num">
            25
          </div>
          <div class="off">
            <div class="per">%</div>
            <div class="offin">Off</div>
          </div>
        </div>

        <img class="cardDiv_img" src="imgs/CardDeal (2).png" alt="Card1">
        <h6 class="cardTittle">Grey Vage</h6>
        <p class="cardDays">6 Days Remaining</p>
      </div>
      <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">

        <div class="sale_tag">
          <div class="num">
            20
          </div>
          <div class="off">
            <div class="per">%</div>
            <div class="offin">Off</div>
          </div>
        </div>

        <img class="cardDiv_img" src="imgs/CardDeal (3).png" alt="Card1">
        <h6 class="cardTittle">Grey Vage</h6>
        <p class="cardDays">6 Days Remaining</p>
      </div>
    </div>
  </div>

  <!--About-->

  <div class="about">
    <div class="container">

      <div class="howWork">
        <h3 class="howWorkHeading">How does it work</h3>
      </div>

      <div class="row aboutDiv">
        <div class="col-md-6 col-lg-3 col-sm-6">
          <img class="aboutIcons" src="imgs/icon (3).png" alt="icon">
          <h6 class="abooutTittle">Select Location</h6>
          <p>Choose the location where your food will be deleivered</p>
        </div>

        <div class="col-md-6 col-lg-3 col-sm-6">
          <img class="aboutIcons" src="imgs/icon (4).png" alt="icon">
          <h6 class="abooutTittle">Choose Order</h6>
          <p>Check over hundreds of menus to pick your favorite food</p>
        </div>

        <div class="col-md-6 col-lg-3 col-sm-6">
          <img class="aboutIcons" src="imgs/icon (1).png" alt="icon">
          <h6 class="abooutTittle">Pay Advance</h6>
          <p>It's quick, safe, and simple. Select several methods of payment</p>
        </div>

        <div class="col-md-6 col-lg-3 col-sm-6">
          <img class="aboutIcons" src="imgs/icon (2).png" alt="icon">
          <h6 class="abooutTittle"><br>Enjoy Meals</h6>
          <p>Food is made and delivered directly to your home.</p>
        </div>
      </div>

    </div>
  </div>

  <!--Popular Items Section-->

  <div class="container">

    <div class="row cardDivMain3">

      <div class="popularItems">
        <h3 class="popularItemsHeading">Popular Items</h3>
      </div>

      <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
        <img class="cardDiv_img" src="imgs/PopularItems (4).png" alt="Card1">
        <h6 class="cardTittle">Cheese Burger</h6>
        <h6 class="cardLocation">
          <i class="fa-solid fa-location-dot icon_color"></i> Burger Arena
        </h6>
        <h6 class="cardTittlePrice">3.88$</h6>
        <div class="buttonDiv">
          <button class="btn btn-warning orderNowBtn">
            <h5 class="orderNowBtnTxt">Order Now</h5>
          </button>
        </div>
      </div>

      <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
        <img class="cardDiv_img" src="imgs/PopularItems (1).png" alt="Card1">
        <h6 class="cardTittle">Toffe's Cake</h6>
        <h6 class="cardLocation">
          <i class="fa-solid fa-location-dot icon_color"></i>
          Top Stick
        </h6>
        <h6 class="cardTittlePrice">4.00$</h6>
        <div class="buttonDiv">
          <button class="btn btn-warning orderNowBtn">
            <h5 class="orderNowBtnTxt">Order Now</h5>
          </button>
        </div>

      </div>

      <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
        <img class="cardDiv_img" src="imgs/PopularItems (2).png" alt="Card1">
        <h6 class="cardTittle">Dancake</h6>
        <h6 class="cardLocation">
          <i class="fa-solid fa-location-dot icon_color"></i>
          Cake World
        </h6>
        <h6 class="cardTittlePrice">1.99$</h6>
        <div class="buttonDiv">
          <button class="btn btn-warning orderNowBtn">
            <h5 class="orderNowBtnTxt">Order Now</h5>
          </button>
        </div>

      </div>

      <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
        <img class="cardDiv_img" src="imgs/PopularItems (3).png" alt="Card1">
        <h6 class="cardTittle">Crispy Sandwitch</h6>
        <h6 class="cardLocation">
          <i class="fa-solid fa-location-dot icon_color"></i>
          FastFood Dine
        </h6>
        <h6 class="cardTittlePrice">3.00$</h6>
        <div class="buttonDiv">
          <button class="btn btn-warning orderNowBtn">
            <h5 class="orderNowBtnTxt">Order Now</h5>
          </button>
        </div>
      </div>

      <!--Featured Products Section-->

      <div class="container">

        <div class="row cardDivMain">

          <div class="popularItems">
            <h3 class="popularItemsHeading">Featured Restaurants</h3>
          </div>

          <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
            <img class="cardDiv_img" src="imgs/featured (2).png" alt="Card1">
            <div class="outerDiv">
              <div class="resLogo">
                <img src="imgs/Restaruant Logo.png" alt="Food World Logo">
              </div>
              <h6 class="cardTittle2">Food World</h6>
              <h6 class="cardStar">
                <i class="fa-solid fa-star"></i> 46
              </h6>
              <p class="openNow">Open Now</p>
            </div>
          </div>

          <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
            <img class="cardDiv_img" src="imgs/featured (3).png" alt="Card1">
            <div class="outerDiv">
              <div class="resLogo">
                <img src="imgs/RestaurantsLogo (3).png" alt="Pizza Hub Logo">
              </div>
              <h6 class="cardTittle2">Pizza Hub</h6>
              <h6 class="cardStar">
                <i class="fa-solid fa-star"></i> 48
              </h6>
              <p class="openTomorrow">Open Tomorrow</p>
            </div>

          </div>

          <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
            <img class="cardDiv_img" src="imgs/featured (1).png" alt="Card1">
            <div class="outerDiv">
              <div class="resLogo">
                <img src="imgs/RestaurantsLogo (2).png" alt="Dunkin Donuts Logo">
              </div>
              <h6 class="cardTittle2">Donuts Hut</h6>
              <h6 class="cardStar">
                <i class="fa-solid fa-star"></i> 46
              </h6>
              <p class="openNow">Open Now</p>
            </div>

          </div>

          <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
            <img class="cardDiv_img" src="imgs/featured.png " alt="Card1">

            <div class="outerDiv">
              <div class="resLogo">
                <img src="imgs/RestaurantsLogo.png" alt="Subway Logo">
              </div>
              <h6 class="cardTittle2">Soft Cream</h6>
              <h6 class="cardStar">
                <i class="fa-solid fa-star"></i> 50
              </h6>
              <p class="openNow">Open Now</p>
            </div>
          </div>

        </div>


        <div class="row cardDivMain">

          <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
            <img class="cardDiv_img" src="imgs/food.png" alt="Card1">
            <div class="outerDiv">
              <div class="resLogo">
                <img src="imgs/RestaurantsLogo (1).png" alt="Ruby Tuesday Logo">
              </div>
              <h6 class="cardTittle3">Ruby Tuesday</h6>
              <h6 class="cardStar">
                <i class="fa-solid fa-star"></i> 46
              </h6>
              <p class="openTomorrow">Open Tomorrow</p>
              
            </div>
          </div>

          <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
            <img class="cardDiv_img" src="imgs/food (3).png" alt="Card1">
            <div class="outerDiv">
              <div class="resLogo">
                <img src="imgs/Restaruant Logo (2).png" alt="KFC Logo">
              </div>
              <h6 class="cardTittle5">Karachi Food Center</h6>
              <h6 class="cardStar">
                <i class="fa-solid fa-star"></i> 50
              </h6>
              <p class="openNow">Open Now</p>
            </div>

          </div>

          <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
            <img class="cardDiv_img" src="imgs/food (4).png" alt="Card1">
            <div class="outerDiv">
              <div class="resLogo">
                <img src="imgs/RestaurantsLogo (4).png" alt="Red Square Logos">
              </div>
              <h6 class="cardTittle2">Red Square</h6>
              <h6 class="cardStar">
                <i class="fa-solid fa-star"></i> 42
              </h6>
              <p class="openTomorrow">Open Tomorrow</p>
            </div>

          </div>

          <div class="col-md-6 col-lg-3 col-sm-6 cardDiv">
            <img class="cardDiv_img" src="imgs/food (2).png " alt="Card1">

            <div class="outerDiv">
              <div class="resLogo">
                <img src="imgs/Restaruant Logo (1).png" alt="Taco Bell Logo">
              </div>
              <h6 class="cardTittle4">Taco Bell</h6>
              <h6 class="cardStar">
                <i class="fa-solid fa-star"></i> 46
              </h6>
              <p class="openNow">Open Now</p>
            </div>
          </div>

        </div>

        <div class="buttonDiv2">
          <button class="btn btn-warning viewAllBtn">
            <h5 class="viewAllBtnTxt">View All ></h5>
          </button>
        </div>          
      </div>
    </div>


    <div class="">
      <div class="container">

        <div class="row cardDivMainSBF1">

        <div class="col-md-4 col-lg-2 col-sm-4 searchByFood">
          <img src="imgs/searchByFood (1).png" alt="Burger Image">
          <h6 class="searchByFoodTxt">Burger</h6>
        </div>

        <div class="col-md-4 col-lg-2 col-sm-4 searchByFood">
          <img src="imgs/searchByFood (2).png" alt="">
          <h6 class="searchByFoodTxt">Pizza</h6>

        </div>

        <div class="col-md-4 col-lg-2 col-sm-4 searchByFood">
          <img src="imgs/searchByFood (3).png" alt="">
          <h6 class="searchByFoodTxt">Steak</h6>

        </div>

        <div class="col-md-4 col-lg-2 col-sm-4 searchByFood">
          <img src="imgs/searchByFood (4).png" alt="">
          <h6 class="searchByFoodTxt">Chowmein</h6>

        </div>

        <div class="col-md-4 col-lg-2 col-sm-4 searchByFood">
          <img src="imgs/searchByFood (5).png" alt="">
          <h6 class="searchByFoodTxt">Sub-Sandwitches</h6>

        </div>

        <div class="col-md-4 col-lg-2 col-sm-4 searchByFood">
          <img src="imgs/searchByFood (6).png" alt="">
          <h6 class="searchByFoodTxt">Noodles</h6>

        </div>
        </div>

        <div class="row cardDivMainSBF">
          <div class="col-md-4 col-lg-4 col-sm-4 searchByFood">
            <h4 class="searchByFoodTxt2">Search By Food</h4>
  
          </div>

          <div class="col-md-4 col-lg-4 col-sm-4 searchByFood">
            <div class="searchByFoodTxt3OuterDiv2">
            <h4 class="searchByFoodTxt3"><</h4>
          </div>
  
          </div>

          <div class="col-md-4 col-lg-4 col-sm-4 searchByFood">
          <div class="searchByFoodTxt3OuterDiv">
            <h4 class="searchByFoodTxt3">></h4>
          </div>
  
          </div>
        </div>

        

      </div>
</body>



</html>


#STYLE.CSS

:root {
    --font_color: #FFA833;
    --div_colr: #FFA833;
    --bg_colr: #ffffff;
}
 @font-face {
    font-family: Source Serif pro;
    src: url(fonts/SourceSansPro-Bold.ttf);
 }

 @font-face {
    font-family: Source Serif Regular;
    src: url(fonts/SourceSansPro-Regular.ttf);
 }

 @font-face {
    font-family: Source Serif Bold;
    src: url(fonts/SourceSansPro-Bold.ttf);
 }


body{
    width: 100%;
}


.header .logo {
    width: 150px;
    height: 30px;
    margin-top: 10px;

}

.header .login_button {
   margin-top: 10;
   font-family: 'Source Serif Pro';
   color: var(--font_color);
   background-color: var(--bg_colr);
   box-shadow: rgba(255,190,26,255) 0px 3px 8px;
}

.header .login_button:hover{
    background-color: var(--font_color);
    color: var(--bg_colr);
}

.header .search_span_1{
    font-family: 'Source Serif Pro';
    width: 50%;
    margin-top: 10px;
    text-align: center;
}

.header .search_span_2{
    font-family: 'Source Serif Pro';
    width: 15%;
    margin-top: 10px;
}


.header .logo_div{
    width: 20%;
}

.header .button_div{
    width: 15%;
}

.header .search_span_1 .norm_span{
    font-family: 'Source Serif Regular';
}

.header .search_span_1 .icon_color,
.header .search_span_2 .icon_color{
    color: var(--font_color);
}

.searchdiv{
    background-image: url(imgs/Group\ 1\ 1.png);
    width: 100%;
    height: 420px;
    position: relative;
    margin-top: 12px;
}

.searchheading{
    position: absolute;
    top: 100px;
    left: 100px;
}

.searchheading h1{
    font-size: 55px;
    font-family: Source Serif Pro;
    color: #ffffff;
}

.searchheading p{
    font-size: 15px;
    font-family: Source Serif Regular;
}

.searchdiv_searchbar{
    background-color: #ffffff;
    width: 580px;
    height: 150px;
    border-radius: 15px;
    position: absolute;
    top: 210px;
    left: 95px;
}

.searchdiv_searchbar_innerdiv{
    background-color: #fce4d4;
    width: 140px;
    height: 40px;
    border-radius: 8px;
    position: absolute;
    top: 20px;
    left: 20px;
    font-family: Source Serif Pro;
    font-size: 20px;
    color: #F17228;
}

.searchdiv_searchbar_innerdiv i{
    margin-left: 12px;
    margin-top: 8px;
}

.searchdiv_searchbar_innerdiv_pickup{
    width: 140px;
    height: 40px;
    border-radius: 8px;
    position: absolute;
    top: 20px;
    left: 180px;
    font-family: Source Serif Pro;
    font-size: 20px;
    color: #757575;
}

.searchdiv_searchbar_innerdiv_pickup i{
    margin-left: 12px;
    margin-top: 8px;
}

.searchdiv_searchbar_innerdiv_searchbar{
    width: 380px;
    height: 50px;
    border-radius: 8px;
    position: absolute;
    top: 80px;
    left: 20px;
    font-family: Source Serif Regular;
    font-size: 18px;
    color: #757575;
    background-color: #F5F5F5;
}

.searchdiv_searchbar_innerdiv_searchbar i{
    margin-left: 25px;
    margin-top: 13px;
    color: #FF7474;
    font-size: 25px;
}

.searchdiv_searchbar_innerdiv_searchbar_form{
    background-color: #F5F5F5;
    border: none;
    position: absolute;
    top: 5px;
    width: 320px;
    height: 40px;
    left: 60px;
}

.searchdiv_searchbar_innerdiv_searchbar span{
    margin-left: 10px;
}

.searchdiv_searchbar_innerdiv_searchbar_button{
    width: 150px;
    height: 55px;
    border-radius: 8px;
    position: absolute;
    top: 78px;
    left: 420px;
    font-family: Source Serif Pro;
    font-size: 18px;
    color: #757575;
    background-image: linear-gradient(to right, #FF7A7A, #F65900);
    border: none;
}

.searchdiv_searchbar_innerdiv_searchbar_button i{
    color: #F5F5F5;
    font-size: 15px;
}

.searchdiv_searchbar_innerdiv_searchbar_button span{
    margin-left: 10px;
    color: #F5F5F5;
}



.searchimage img{
    width: 470px;
    height: 370px;
    position: absolute;
    margin-left: 470px;
    margin-top: -160px;
}

.cardDiv_img{
    margin-top: 50px;
    width: 230px;
    height: 190px;
    border-radius: 16px;
    
}

.cardTittle{
    margin-top: 15px;
    font-family: Source Serif Pro;
    font-weight: bolder; 
}

.cardDays{ 
    background: #fce4d4;
    text-align: center;
    font-weight: 700;
    color: #F17228;
    width: 160px;
    height: 28px;
    border-radius: 5px;
    
}

.cardDiv{
   
    width: 100%;
    position: relative;
   
}

.cardDivMain{
    width: 100%;
}

.cardDivMain2{
    width: 100%;
    top: 150px;
    position: static;
}

.cardDiv .sale_tag{
    position: absolute;
    top: 175px;
    background-color: #FFA833;
    height: 65px;
    width: 100px;
    border-top-right-radius: 32px;
    border-bottom-left-radius: 16px;

}

.cardDiv .sale_tag .num{
    color: #F5F5F5;
    font-size: 50px;
    font-family: Source Serif Regular;
    font-weight: 600;
    margin-left: 5px;
    margin-top: -5px;
}

.cardDiv .sale_tag .off{
    font-family: Source Serif Regular;
    
    margin-top: -60px;
    margin-left: 60px;
    color: #F5F5F5;

}

.cardDiv .sale_tag .per{
    margin-top: -10px;
    font-size: 25px;
}

.cardDiv .sale_tag .off .offin{
    font-size: 18px;
    margin-top: -16px;
}


/*About Section*/

.howWork{
margin-top: 0px;
height: 80px;
position: relative;
}

.howWork .howWorkHeading{
    font-family:Source Serif Pro;
    text-align: center;
    color:#F17228;
    position: absolute;
    top: 15px;
    left: 360px;
}

.about{
    margin-top: 20px;
    width: 100%;
    height: 350px;
    background-image: linear-gradient(180deg,#FFCE6738,#FDEDCA00);

}

.aboutDiv{
    text-align: center;
}

.abooutTittle{
    margin-top: -35px;
    font-family: Source Serif Pro;
    font-weight: bolder;
}


/*Popular Items section*/

.popularItems .popularItemsHeading{
    font-family:Source Serif Pro;
    text-align: center;
    margin-top: 50px;

}

.cardLocation{
    margin-top: -5px;
    font-family: Source Serif Pro;
    font-weight: bolder;
    color: #FFA833; 
}

.cardTittlePrice{
    margin-top: -5px;
    font-family: Source Serif Bold;
    font-weight: bolder; 
}

.cardDivMain3{
    width: 100%;
    top: 0px;
    position: static;
    display: flex;
    margin-bottom: 50px;
}

.buttonDiv .orderNowBtn{
    width: 95%;
    height: 30px;
    text-align: center;
    font-family: Source Serif Pro;
    color: #F5F5F5;
    margin-left: auto;
    margin-right: auto;
   background-color: #F17228;
    border-radius: 3px;
    position: relative;

}

.orderNowBtnTxt{
    font-size:medium;
    position: absolute;
    top: 4px;
    left: 60px;
}

.cardTittle2, .cardTittle3, .cardTittle4, .cardTittle5{
    margin-top: 15px;
    font-family: Source Serif Pro;
    font-weight: bolder; 
    margin-left: 60px;

}

.cardStar{
    margin-top: -5px;
    margin-left: 60px;
    font-family: Source Serif Pro;
    font-weight: bolder;
    color: #FFA833; 
}

.outerDiv{
    position: relative;
}
.resLogo{
    width: 50px;
    height: 50px;
    border-radius: 5px;
    margin-left: auto;
    display: flex;
    flex-direction: column;
    position: absolute;
}

.openTomorrow{ 
    background: #fce4d4;
    text-align: center;
    font-weight: 700;
    color: #F17228;
    width: 150px;
    height: 28px;
    border-radius: 5px;
    margin-top: 30px
    
}

.openNow{ 
    background: #79B93C33;
    text-align: center;
    font-weight: 700;
    color: #79B93C;
    width: 110px;
    height: 28px;
    border-radius: 5px;
    margin-top: 30px
    
}
.viwAllBtnDiv{
    margin-left: auto;
    margin-right: auto;
}

.viewAllBtn{
    position: relative;
    width: 120px;
    height: 40px;
    text-align: center;
    border-radius: 5px;
    margin-right: auto;

}

.viewAllBtnTxt{
    font-family: Source Serif Pro;
    color: #F5F5F5;
    position: absolute;
    font-size: medium;
    top: 9px;
    left: 28px;
}

.buttonDiv2{
    margin-top: 20px;
    margin-right: auto;
    margin-left: auto;
    width: 120px;
    position: relative;
   
}

.buttonDiv2 .viewAllBtn{
    
    width: 120px;
    height: 40px;
    text-align: center;
    font-family: Source Serif Pro;
    margin-left: auto;
    margin-right: auto;
    background: linear-gradient(97.86deg, #FFBA26 -8.95%, #FF9A0E 109.24%);
    border-radius: 8px;
    position: relative;
}



/*Featued Product Section*/
.featuredItems{
    margin-top: 50px;
}

.cardDivMainSBF1{
    width: 100%;
    margin-bottom: 20px;
}

.searchByFood img{
    width: 130px;
    height: 130px;
    border-radius: 50%;
    margin-top: 20px;
    margin-bottom: 20px;
}
.searchByFoodTxtDiv{
    width: 50px;
}

.searchByFoodTxt{
    font-family: Source Serif Pro;
    text-align: center;
}

.searchByFoodTxt2{
    margin-top: 20px;
    font-family: Source Serif Pro;
    text-align: left;
}

.cardDivMainSBF{
    width: 100%;
    display: flex;
    position: relative;
}

.searchByFoodTxt2{
    font-family: Source Serif Pro;
    text-align: left;
}
.searchByFoodTxt3OuterDiv{
    width: 50px;
    height: 50px;
    margin-right: auto;
    position: absolute;
    left: 800px;
    border-radius: 50%;
    background-color: #FFA833;
}

.searchByFoodTxt3OuterDiv2{
    width: 50px;
    height: 50px;
    margin-right: auto;
    position: absolute;
    left: 740px;
    border-radius: 50%;
    background-color: #FFA833;
}

.searchByFoodTxt3{
    font-family: Source Serif Pro;
    text-align: center;
    margin-top: 10px;
    width: 50px;
    height: 50px;
    color: #F5F5F5;
    
   
}

.arrows{
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background-color: #FF9A0E;
}

/*BreakPoints******************************
****************************************************/


@media (max-width:1100px) {

    

    .searchimage img{
        display: none;
    }

    .searchdiv{
        position: static;
        height: 280px;
    }

    .searchheading{
        position: static;
        display: flex;
        align-items: center;
        flex-direction: column;
    }

    .searchdiv_searchbar{
        position: static;
        display: flex;
        justify-content: center;
        flex-direction: row;
        margin-left: auto;
        margin-right: auto;
        margin-top: 10px;
    }

    .searchdiv_searchbar_innerdiv{
        position: static;
        margin-top: 20px;
       
    }

    .searchdiv_searchbar_innerdiv_pickup{
        position: static;
        margin-top: 20px;
    }

    .searchdiv_searchbar_innerdiv_searchbar{
        margin-top: 80px;
        margin-left: -280px;
        position: static;
    }

    .searchdiv_searchbar_innerdiv_searchbar form{
        margin-top: -30px;
    }

    .searchdiv_searchbar_innerdiv_searchbar_form{
       
        position: static;
        margin-left: 50px;
    }

    .searchdiv_searchbar_innerdiv_searchbar_button{
        position: static;
        margin-top: 78px;
    } 

    .cardDivMain{
        width: 950px;
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
    }

    .cardDivMain2{
        width: 100%;
        position: absolute;
        top: 1550px;
    }

  

    
}

@media (max-width:620px){

    body{
        width: 620px;
    }

    .search_span_1,
    .search_span_2{
        display: none;
    }
    .searchheading h1{
        font-size: 40px;
    }

    .button_div .login_button{
        width: 100px;
        margin-left: 250px;
    }

    .searchdiv_searchbar{
        width: 90%;
    }

    .searchdiv_searchbar_innerdiv{
        width: 100px;
        height: 30px;
        font-size: 15px;
        margin-left: 10px;
    }

    .searchdiv_searchbar_innerdiv_pickup{
        width: 110px;
        height: 25px;
        font-size: 15px;
        margin-left: -10px;
        text-align: center;
    }

    

    .searchdiv_searchbar_innerdiv_searchbar_button{
        width: 120px;
        margin-left: 0px;
    }

    .searchdiv_searchbar_innerdiv_searchbar_form{
        width: 180px;
        margin-left: 60px;
        margin-top: -10px;
    }

    .searchdiv_searchbar_innerdiv_searchbar{
        width: 250px;
        margin-left: -210px;
        margin-right: 10px;

    }

    .cardDivMain{
        width: 100%;
        display: grid;
        flex-wrap: wrap;
    }

     .cardDiv{
       text-align: center;
    }

    .cardDays{
        margin-left: auto;
        margin-right: auto;
    }

    .cardDivMain2{
        width: 100%;
        position: absolute;
        top: 2650px;
    }

    


}

@media (max-width:620px){

    body{
        width: 620px;
    }

    .cardDivMain2{
        width: 100%;
        position: absolute;
        top: 2650px;
    }

    .cardDiv2{
        top: 1250px;
    }

    .about{
        margin-bottom: 250px;
    }

    .cardDivMain3 {
        position:static;
        margin-top: -200px;
    }

      .cardDivMain3 {
        position:static;
        margin-top: -200px;
    }
    
    .howWork .howWorkHeading{
        left: 170px;
    }

    .orderNowBtnTxt{
        font-size:medium;
        position: absolute;
        top: 4px;
        left: 75px;
    }

    .cardTittle2{
        margin-left: -25px;
    
    }
    
    .cardStar{
        margin-left: -65px;
    }
    
    .cardTittle3{
        margin-left: 0px;
    }

    .cardTittle4{
        margin-left: -40px;
    }

    .cardTittle5{
        margin-left: 40px;
    }
}

@media (max-width:360px){

    .header {
        width: 50px;
    }

    .header .login_button {
       margin-left: 200px;
       margin-top: 5px;
     }

    body{
        width: 360px;
    }

    .searchdiv{
        background-color: #FF7A7A;
        width: 360px;
    }

    

.searchheading h1{
    font-size: 35px;
    font-family: Source Serif Pro;
    color: #ffffff;
}

.searchheading p{
    font-size: 12px;
    font-family: Source Serif Regular;
}

.searchdiv_searchbar{
    background-color: #ffffff;
    width: 280px;
    height: 150px;
    border-radius: 15px;
    position: absolute;
    top: 140px;
    left: 38px;
}

.searchdiv_searchbar_innerdiv{
    background-color: #fce4d4;
    width: 130px;
    height: 30px;
    border-radius: 8px;
    position: absolute;
    top: -5px;
    left: 5px;
    font-family: Source Serif Pro;
    font-size: 18px;
    color: #F17228;
}

.searchdiv_searchbar_innerdiv i{
    margin-left: 12px;
    margin-top: 6px;
}

.searchdiv_searchbar_innerdiv_pickup{
    width: 130px;
    height: 30px;
    border-radius: 8px;
    position: absolute;
    top: -8px;
    left: 150px;
    font-family: Source Serif Pro;
    font-size: 18px;
    color: #757575;
}

.searchdiv_searchbar_innerdiv_pickup i{
    margin-left: 12px;
    margin-top: 8px;
}

.searchdiv_searchbar_innerdiv_searchbar{
    width: 60px;
    height: 50px;
    border-radius: 8px;
    position: absolute;
    top: 0px;
    left: -50px;
    font-family: Source Serif Regular;
    font-size: 18px;
    color: #757575;
    background-color: #F5F5F5;
}

.searchdiv_searchbar_innerdiv_searchbar i{
    position: absolute;
    left: 460px;
    top:  -32px;
    color: #FF7474;
    font-size: 25px;
    z-index: 1;
}

.searchdiv_searchbar_innerdiv_searchbar_form{
    background-color: #F5F5F5;
    border: none;
    position: absolute;
    top: -15px;
    width: 240px;
    height: 40px;
    left: 220px;
}

.searchdiv_searchbar_innerdiv_searchbar span{
    margin-left: 10px;
}

.searchdiv_searchbar_innerdiv_searchbar_button{
    width: 140px;
    height: 35px;
    border-radius: 8px;
    position: absolute;
    top: 25px;
    left: 20px;
    font-family: Source Serif Pro;
    font-size: 18px;
    color: #757575;
    background-image: linear-gradient(to right, #FF7A7A, #F65900);
    border: none;
}

.searchdiv_searchbar_innerdiv_searchbar_button i{
    color: #F5F5F5;
    font-size: 15px;
}

.searchdiv_searchbar_innerdiv_searchbar_button span{
    margin-left: 10px;
    color: #F5F5F5;
}


}
