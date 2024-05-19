# Coffee-landing-page
A simple coffee shop landing page using only HTML and CSS.

###HTML CODE
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Coffee Landing Page</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <!-- Nav -->
  <nav>
    <h1 class="logo">Logo</h1>
    <ul>
      <li><a href="">Home</a></li>
      <li><a href="">About</a></li>
      <li><a href="">Menu</a></li>
      <li><a href="">Contact</a></li>
    </ul>
  </nav>

  <!-- Header -->

  <header class="header">
    <h1 class="main-heading">START YOUR DAY</h1>
    <h1 class="primary-heading">WITH OUR COFFEE</h1>
    <button class="main-btn">SHOP NOW</button>
  </header>

  <!-- Our story -->
<hr>
  <section id="our-story">
    <div class="img-container">
      <div class="img"></div>
    </div>

    <div class="section-content">
      <div class="title-style">
        <span class="line"></span>
        <h1 class="title">Our Story</h1>
      </div>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic, maiores perferendis ipsam in, omnis, dolore
        libero doloribus sunt earum alias aliquid cumque culpa corrupti perspiciatis facilis rerum cum et harum minima
        quo. Non delectus, voluptatem impedit ratione animi maiores odit eveniet voluptatum vel? Labore eveniet
        cupiditate consectetur iste. Numquam, quaerat eaque. Qui, inventore. Quia dicta perferendis asperiores sapiente
        numquam unde iusto ipsa adipisci, laudantium quisquam quidem reiciendis qui optio. Tempora eos placeat quam
        ducimus ipsam, odio, labore sapiente voluptate rem qui ullam obcaecati maxime numquam ratione tenetur id et
        quidem corporis quo expedita sequi dolorum, autem praesentium harum. Officiis, ab!
      </p>
      <button>Learn More</button>
    </div>
  </section>

  <hr>
  <!-- Coffee Container -->
  <section class="coffee-container">
    <div class="content-section">
      <div class="title-style">
        <h1 class="title-two">
          Perfect place <br>
          To Enjoy Your <br>
          Coffee
        </h1>
      </div>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia, accusamus. Odio obcaecati ducimus amet tempore
        laudantium. Odit quibusdam, hic, eum quos alias, doloremque unde expedita nam perferendis asperiores quaerat
        quis debitis dolorem? Velit voluptatibus facere aspernatur illo illum exercitationem cum, quas labore aliquid
        sed facilis nostrum quasi animi quae maiores.
      </p>
      <button style="margin-top: 20px;">Learn More</button>
    </div>

    <sention class="img-container">
      <img src="coffee_start_ur_day-removebg-preview.png" class="img-2" />
    </sention>
  </section>


  <!-- Products -->
  <hr>
  <section class="Products">
    <h1 class="title title-three">Products</h1>

    <section class="cards">
      <div class="card">
        <div class="card-img img-one"></div>
        <div class="card-title">
          <h1>Mocha</h1>
        </div>
        <div class="items">
          <p>Espresso</p>
          <p>Chocolate</p>
          <p>Steamed Milk</p>
        </div>
      </div>
      <div class="card">
        <div class="card-img img-two"></div>
        <div class="card-title">
          <h1>Mocha</h1>
        </div>
        <div class="items">
          <p>Espresso</p>
          <p>Chocolate</p>
          <p>Steamed Milk</p>
        </div>
      </div>
      <div class="card">
        <div class="card-img img-three"></div>
        <div class="card-title">
          <h1>Mocha</h1>
        </div>
        <div class="items">
          <p>Espresso</p>
          <p>Chocolate</p>
          <p>Steamed Milk</p>
        </div>
      </div>
    </section>
  </section>

  <!-- Products End -->

  <!-- Footer Start -->

  <!-- <hr> -->
  <footer>
    <div class="container"> <!--span is used below here (before us) to give only that word a perticular color-->
      <h1 class="heading-info">About <span>Us</span></h1>
      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Asperiores impedit corporis, at neque quaerat enim
        consectetur omnis excepturi deserunt unde, soluta quia nesciunt repudiandae iusto consequuntur magni obcaecati
        nisi ullam! </p>
    </div>
    <div class="container">
      <h1 class="heading-info">Contact <span>Us</span></h1>
      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Asperiores impedit corporis, at neque quaerat enim
        consectetur omnis excepturi deserunt unde, soluta quia nesciunt repudiandae iusto consequuntur magni obcaecati
        nisi ullam! </p>
    </div>
    <div class="container">
      <h1 class="heading-info">Opening <span>Hours</span></h1>
      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Asperiores impedit corporis, at neque quaerat enim
        consectetur omnis excepturi deserunt unde, soluta quia nesciunt repudiandae iusto consequuntur magni obcaecati
        nisi ullam! </p>
    </div>

    <!-- <hr class="hr-two"> -->
    <p class="para">
      Copyright @ 2024 Asfi Ahmed | Provided by <span>Asfi Ahmed</span>
    </p>
  </footer>

</body>

</html>


###CSS CODE

@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,700;1,700&display=swap');

:root {
    --main-color: #deab5f;
    --primary-color: #312e2e;
}

/* Utility styles */

button {
    padding: 10px 30px;
    background: var(--main-color);
    border: none;
    cursor: pointer;
}

/* Resets */

* {
    padding: 0 ;
    margin: 0;
    box-sizing:border-box;
}

body {
    background-color: black;
}

/* Navigation */

nav {
    display: flex;
    justify-content: space-around;
    align-items: center;
    color: #fff;
    font-family: sans-serif;
    padding-top: 15px;
    padding-bottom: 15px;
}

li {
    display: inline;
    list-style: none;
}

li a {
    color: white;
    text-decoration: none;
    margin-left: 40px;
    padding-bottom: 10px;
}

li a:hover {
    border-bottom: 2px solid var(--main-color);
}
/* navigation ends */

/* Header Start */

.logo {
    background-image: url(coffee-logo-design_636083-191.jpg);
    background-position: center;
    background-size: cover;
    position: cover;
    height: 50px;
    width: 50px;
}

.header {
background: url(coffee-bg1.jpg);
background-color: #ffffff21;
background-blend-mode: color;
background-position: center;
background-size: cover;
height: 100vh;
font-family: 'Playfair Display' , serif;

font-weight: normal;

/* Flexbox */
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
color: white;
position: relative;
text-align: center;
}

.main-heading {
    position: absolute;
    top: 14rem;
    font-size: 4rem;
    word-spacing: 10px;
    margin-bottom: -40px;
    min-width: 100px;
}

.primary-heading {
    position: absolute;
    bottom: 22rem;
    font-size: 4rem;
    word-spacing: 10px;
    margin-bottom: -40px;
    min-width: 100px;
}

.main-btn {
    position: absolute;
    bottom: 20rem;
    padding: 10px 30px;
    margin-top: 20px;
    background: transparent;
    background: var(--main-color);
    transform: translateY(60px);
}

/* our story strats */
#our-story {
    height: 100vh;
    margin-top: 15%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    align-items: center;

    color: white;
}

.img {
    width: 100vh;
    height: 400px;
    background: url(barista\ our\ story.jpg);
    background-position: bottom; /*without bg position and cover style, it will mess up the image and look weird. try by comment out the bg pos and cover style*/
    background-size: cover;
}

.title-style {
    display: flex;
    align-items: center;
}

.title {
    font-family: 'Playfair Display' , serif;
    font-size: 4rem;
    color: #fff;
    transform: translateX(-100px);

}

.line {
    width: 100px;
    height: 2px;
    background-color:var(--main-color);
    transform: translateX(-120px);
    /* transform: translateY(10px); */
}

.section-content p {

max-width: 500px;
color: #fff;
font-family: sans-serif;
line-height: 20px;
margin: 20px 0;

}

/* our story ends */

/* Coffee Start */

.coffee-container {
    display: flex;
    flex-wrap: wrap ;
    justify-content: center;
    align-items: center;
    margin-top: 10rem;
}


.img-2 {
    width: 100vh;
    height: 500px;
}

.title-two {
    font-family: 'Playfair Display' , serif;
    font-size: 3rem;
    color: #fff;

}

.content-section p {
    max-width: 700px;
    margin-top: 20px;
    font-family: sans-serif;
    color: #fff;

}

/* Coffee start End */

/* Products */

.products {
    margin-top: 5rem;
}

.title-three {
    display: flex;                   /* if u wnat to make the title center u have to
        `                                use dis[lay flex and then justify content space around and align items center. 
                                         this works because the title is part of a section which will allow u to use display flex.
                                        to be noted, this only works only if ur title is in a section (Maybe there are other suitable or proper explanation but i dont know about it.)*/
    justify-content: space-around;
    align-items: center;
    font-size: 4rem;
    margin-left: 10rem;
    margin-top: 10rem;
    margin-bottom: 10rem;
}

.cards {
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
}

.card {
    border: 2px solid var(--main-color) ;
    padding: 0 20px;
    height: 400px;
    width: 300px;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    border-radius: 5px;
    position: relative;
    margin-bottom: 4rem ;
}

.card-img {
    width: 100px;         /*make sure that u do not change the height and width.
                            because it will mess up the aesthetics. u can try by changing the
                            height and width to see the effects!*/
    height: 100px;
    position: absolute;
    top: -60px;
}

.img-one {
    background: url(mocha\ bg\ removed.png);
    background-position: center;
    background-size: cover;
}

.img-two {
    background: url(espresson\ bg\ removed.png);
    background-position: center;
    background-size: cover;
}

.img-three {
    background: url(americano-removebg-preview.png);
    background-position: center;
    background-size: cover;
}

.card-title {
    color: #fff;
    font-family: sans-serif;
    margin-top: 50px;
}

.card .items p{
    color: #fff;
    margin: 20px 0;
    font-family: sans-serif;

}

/* Products End */

/* Footer Starts */

footer {
    height: 50vh;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    color: #fff;
    font-family: sans-serif;
}

footer .container {
    margin: 38px;
    max-width: 300px;
    text-align: center;
}

footer .heading-info {
    margin-bottom: 20px;
}

footer p {
    line-height: 25px;
}

span {
    color: var(--main-color);
}

hr {
    margin-bottom: 20px;
    border: var(--main-color);
    width: 500px;
    margin: 0 auto;
}

.para {
    color: #fff;
    font-family: sans-serif;
    text-align: center;
    margin-top: 20px;
}

/* Project End */

/* Project responsiveness */

@media only screen and (max-width: 768px) {
    .main-headings, .primary-heading {
        font-size: 0.5rem;
    }
    #our-story {
        text-align: center;
    }

    #our-story .title {
        transform: translateX(50px);
    }

    #our-story .line {
        display: none;
    }

    .content-section {
        text-align: center;
    }

    #our-story .img-container .img {
        width: 70%;
        text-align: center;
        margin: 0 auto;
    }

    .coffee-container .img-container {
        margin-top: 5rem;
        width: 50%;
    }

    .title {
        margin: 0 auto;
    }
    .title-two {
        margin: 0 auto;
    }

    .title-three {
        display: none;
    }

    .para {
        display: none;
    }
}
