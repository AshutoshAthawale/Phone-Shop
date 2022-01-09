# Phone-Shop

<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Phone Shop</title>

   <!-- font awesome cdn link  -->
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

   <link rel="stylesheet" href="https://unpkg.com/swiper@7/swiper-bundle.min.css" />

   <!-- custom css file link  -->
   <link rel="stylesheet" href="Style.css">

</head>
<body>

<!-- header section starts-->

<div id="menu-btn" class="fas fa-bars"></div>

<header class="header">

   <a href="#" class="logo">Phone Shop</a>

   <nav class="navbar">
      <a href="#banner">Home</a>
      <a href="#products">products</a>
   <!--   <a href="#reviews">reviews</a> -->
      <a href="#contact">contact</a>
   </nav>

   <div class="share">
      <a href="https://www.facebook.com/ashutosh.at.18" class="fab fa-facebook-f"></a>
      <a href="#" class="fab fa-twitter"></a>
      <a href="https://www.instagram.com/_ashutosh_athawale_/" class="fab fa-instagram"></a>
      <a href="https://www.linkedin.com/mwlite/in/ashutosh-athawale-673552214" class="fab fa-linkedin"></a>
   </div>

   <p class="credit"> &copy; copyright @ 2022 by mr.Ashutosh Athawale</p>

</header>

<!-- header section ends-->

<!-- banner section starts  -->

<section class="banner" id="banner">

   <div class="content">
      <span>upto 10% off on</span>
      <h3>All Types Of Phones</h3>
      <p>Looking for a mobile phone? <br>
          It is our constant endeavour to understand your needs and to help you find the product best suited for You!</p>
      <a href="#" class="btn">shop now</a>
   </div>

   <div class="image">
        <img src="images/phones.jpg" alt="">
   </div>

</section>

<!-- banner section ends -->

<!-- prodcuts section starts  -->

<section class="products" id="products">

   <h1 class="heading"> our <span>products</span> </h1>

   <div class="swiper products-slider">

      <div class="swiper-wrapper">

         <div class="swiper-slide slide">
            <img src="images/m21.jpg" alt="">
            <h3>Samsung Galaxy M21</h3>
            <div class="btn" data-product="product-1">see details</div>
        <br><p>slide to see more</p>
         </div>

         <div class="swiper-slide slide">
            <img src="images/one plus.webp" alt="">
            <h3>OnePlus Nord CE 5G</h3>
            <div class="btn" data-product="product-2">see details</div>
         </div>

         <div class="swiper-slide slide">
            <img src="images/redmi.jpg" alt="">
            <h3>Redmi Note 10 Lite</h3>
            <div class="btn" data-product="product-3">see details</div>
         </div>

         <div class="swiper-slide slide">
            <img src="images/techno.webp" alt="">
            <h3>Tecno Spark 8T</h3>
            <div class="btn" data-product="product-4">see details</div>
         </div>

         <div class="swiper-slide slide">
            <img src="images/oppo.webp" alt="">
            <h3>OPPO F17 Pro</h3>
            <div class="btn" data-product="product-5">see details</div>
         </div>

         <div class="swiper-slide slide">
            <img src="images/vivo.jpg" alt="">
            <h3>Vivo Y72 5G</h3>
            <div class="btn" data-product="product-6">see details</div>
         </div>

      </div>

   </div>

</section>

<!-- prodcuts section ends -->

<!-- product preview section starts  -->

<section class="products-preview-container">

   <div class="product-preview" data-target="product-1">
      <div class="fas fa-times"></div>
      <div class="image">
         <img src="images/m21.jpg" alt="">
      </div>
      <div class="content">
         <h3>Samsung Galaxy M21</h3>
         <p>Samsung Galaxy M21 2021 Edition - Charcoal black, 6GB RAM, 128GB Storage - FHD+ sAMOLED</p>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">₹15,499</div>
         <a href="#" class="btn">buy now</a>
      </div>
   </div>

   <div class="product-preview" data-target="product-2">
      <div class="fas fa-times"></div>
      <div class="image">
         <img src="images/one plus.webp" alt="">
      </div>
      <div class="content">
         <h3>OnePlus Nord CE 5G</h3>
         <p>OnePlus Nord CE 5G (Charcoal Ink, 8GB RAM, 128GB Storage)!</p>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">₹24,999.00</div>
         <a href="#" class="btn">buy now</a>
      </div>
   </div>

   <div class="product-preview" data-target="product-3">
      <div class="fas fa-times"></div>
      <div class="image">
         <img src="images/redmi.jpg" alt="">
      </div>
      <div class="content">
         <h3>Redmi Note 10 Lite</h3>
         <p>Redmi Note 10 Lite (Glacier White, 4GB RAM, 64GB Storage) | Alexa Built-in</p>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">₹12,999.00</div>
         <a href="#" class="btn">buy now</a>
      </div>
   </div>

   <div class="product-preview" data-target="product-4">
      <div class="fas fa-times"></div>
      <div class="image">
         <img src="images/techno.webp" alt="">
      </div>
      <div class="content">
         <h3>Tecno Spark 8T</h3>
         <p>Tecno Spark 8T (Atlantic Blue,4GB RAM, 64GB Storage)| 50MP AI Camera | 6.6" FHD+Display | 5000mAh</p>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">₹9,499.00</div>
         <a href="#" class="btn">buy now</a>
      </div>
   </div>

   <div class="product-preview" data-target="product-5">
      <div class="fas fa-times"></div>
      <div class="image">
         <img src="images/oppo.webp" alt="">
      </div>
      <div class="content">
         <h3>OPPO F17 Pro</h3>
         <p>OPPO F17 Pro (Matte Black, 8GB RAM, 128GB Storage)</p>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">₹22,999.00</div>
         <a href="#" class="btn">buy now</a>
      </div>
   </div>

   <div class="product-preview" data-target="product-6">
      <div class="fas fa-times"></div>
      <div class="image">
         <img src="images/vivo.jpg" alt="">
      </div>
      <div class="content">
         <h3>Vivo Y72 5G</h3>
         <p>Vivo Y72 5G (Slate Gray, 8GB RAM, 128GB Storage)</p>
         <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star-half-alt"></i>
            <span>( 250 )</span>
         </div>
         <div class="price">₹20,990.00</div>
         <a href="#" class="btn">buy now</a>
      </div>
   </div>

</section>




<!-- product preview section ends -->

<!-- services section starts  -->

<section class="service">

   <div class="box">
      <i class="fas fa-shipping-fast"></i>
      <p>free delivery</p>
   </div>

   <div class="box">
      <i class="fas fa-redo"></i>
      <p>10 days return</p>
   </div>

   <div class="box">
      <i class="fas fa-headset"></i>
      <p>24/7 support</p>
   </div>

</section>

<!-- services section ends -->

<!-- reviews section starts  -->

<!-- <section class="reviews" id="reviews">

   <h1 class="heading"> clients <span>reviews</span> </h1>

   <div class="swiper reviews-slider">

      <div class="swiper-wrapper">

         <div class="swiper-slide slide">
            <i class="fas fa-quote-right"></i>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Incidunt laudantium est quam eveniet perferendis cum reprehenderit aperiam nesciunt soluta optio?</p>
            <img src="images/pic-1.png" alt="">
            <h3>john deo</h3>
         </div>

         <div class="swiper-slide slide">
            <i class="fas fa-quote-right"></i>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Incidunt laudantium est quam eveniet perferendis cum reprehenderit aperiam nesciunt soluta optio?</p>
            <img src="images/pic-2.png" alt="">
            <h3>john deo</h3>
         </div>

         <div class="swiper-slide slide">
            <i class="fas fa-quote-right"></i>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Incidunt laudantium est quam eveniet perferendis cum reprehenderit aperiam nesciunt soluta optio?</p>
            <img src="images/pic-3.png" alt="">
            <h3>john deo</h3>
         </div>

         <div class="swiper-slide slide">
            <i class="fas fa-quote-right"></i>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Incidunt laudantium est quam eveniet perferendis cum reprehenderit aperiam nesciunt soluta optio?</p>
            <img src="images/pic-4.png" alt="">
            <h3>john deo</h3>
         </div>

         <div class="swiper-slide slide">
            <i class="fas fa-quote-right"></i>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Incidunt laudantium est quam eveniet perferendis cum reprehenderit aperiam nesciunt soluta optio?</p>
            <img src="images/pic-5.png" alt="">
            <h3>john deo</h3>
         </div>

         <div class="swiper-slide slide">
            <i class="fas fa-quote-right"></i>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Incidunt laudantium est quam eveniet perferendis cum reprehenderit aperiam nesciunt soluta optio?</p>
            <img src="images/pic-6.png" alt="">
            <h3>john deo</h3>
         </div>
         
      </div>

   </div>

</section> -->

<!-- reviews section ends -->

<!-- contact section starts  -->

<section class="contact" id="contact">

   <h1 class="heading"> <span>contact</span> us </h1>

   <div class="row">

      <form action="">
         <input type="text" placeholder="name" class="box">
         <input type="email" placeholder="email" class="box">
         <input type="number" placeholder="phone" class="box">
         <textarea name="" class="box" placeholder="message" id="" cols="30" rows="10"></textarea>
         <input type="submit" value="send message" class="btn">
      </form>

      <div class="contact-info">
         <h3>do you have any questions?</h3>
         <p class="grapgh">You can contact me </p>
         <div class="icons">
            <i class="fas fa-map"></i>
            <div class="info">
               <p>Amravati, Maharashtra, 
                 <br>India - 444604</p>
            </div>
         </div>
         <div class="icons">
            <i class="fas fa-envelope"></i>
            <div class="info">
               <p>ashutosh111athawale@gmail.com</p>
            </div>
         </div>
         <div class="icons">
            <i class="fas fa-phone"></i>
            <div class="info">
               <p>7798340090</p>
               <p>9284682557</p>
            </div>
         </div>
         <div class="share">
            <a href="https://www.facebook.com/ashutosh.at.18" class="fab fa-facebook-f"></a>
            <a href="#" class="fab fa-twitter"></a>
            <a href="https://www.instagram.com/_ashutosh_athawale_/" class="fab fa-instagram"></a>
            <a href="https://www.linkedin.com/mwlite/in/ashutosh-athawale-673552214" class="fab fa-linkedin"></a>
         </div>
      </div>

   </div>

</section>

<!-- contact section ends -->







<script src="https://unpkg.com/swiper@7/swiper-bundle.min.js"></script>

<!-- custom js file link  -->
<script src="javascript.js"></script>

</body>
</html>
