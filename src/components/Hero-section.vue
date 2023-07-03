<script>

</script>

<template>
   <div id="app">
     <header>
       <div class="logo-nav">
       <div class="logo-container">
         <a href="#"><img class="logo" src="@/assets/images/SCISSOR.png" alt="Logo 1"></a>
         <a href="#"><img class="logo-2 logo" src="@/assets/images/Vector1.png" alt="Logo 1"></a>
         <a href="#"><img class="logo" src="@/assets/images/blue-vector.png" alt="Logo 2"></a>
       </div>
         <nav>
           <ul>
             <li><a href="#">MyURL</a></li>
             <li><a href="#">Features</a></li>
             <li><a href="#">Pricing</a></li>
             <li><a href="#">Analytics</a></li>
             <li><a href="#">FAQs </a></li>
             <li><a href="#"><span>Log in</span></a></li>
             <li class="margin-li"><button class="try-free-button"><span>Try for Free</span></button></li>
           </ul>
         </nav>
       </div>
       <h2 class="header-text">Optimize Your Online Experience with Our Advanced <span>URL Shortening</span> Solution</h2>
       <div class="blue-line"></div>
       <p class="additional-text">
         Personalize your to align with your brand identity.<br>
         Utilize custom slugs, branded links, and domain customization options<br>
         to reinforce your brand presence and enhance user engagement.
       </p>
       <div class="cta-container">
         <a href="#" class="sign-up-button">Sign Up</a>
         <p class="learn-more-text"><a href="#">Learn More</a></p>
       </div>
      <div class="image-container">
       <img src="@/assets/images/Vector-triangle.png" alt="Image" class="image">
    </div>
    <div class="container">
    <div class="image-row">
      <img src="@/assets/images/vector-ring.png" alt="Image 1" class="image-col">
      <img src="@/assets/images/vector-ring.png" alt="Image 2" class="image-col">
      <img src="@/assets/images/vector-ring.png" alt="Image 3" class="image-col">
      <img src="@/assets/images/Line 7.png" alt="Image 4" class="arrow-image">
      <img src="@/assets/images/vector-ring.png" alt="Image 5" class="image-col">
    </div>
    <p class="container-text">Seamlessly transform your long URLs
       into <b>concise</b> and <b>shareable links</b> with just a few clicks.</p>
    <!-- Other content goes here -->
   </div>
  <div class="hero-images">
   <img class="image-hero" src="@/assets/images/Rectangle 9.png" alt="Image 4">
   <img class="image-hero" src="@/assets/images/Vector-line.png" alt="Image 5">
 </div>
 <div class="additional-content">
  <div class="grid-container">
    <div class="grid-item">
      <h4>One Stop. <br>Four <span>Possibilities.</span> </h4>
    </div>
    <div class="grid-item">
      <h4>3M</h4>
      <p class="grid-text">Active users</p>
    </div>
    <div class="grid-item">
      <h4>60M</h4>
      <p class="grid-text">Links & QR codes created</p>
    </div>
    <div class="grid-item">
      <h4>1B</h4>
      <p class="grid-text">Clicked & Scanned connections</p>
    </div>
    <div class="grid-item">
      <h4>300k</h4>
      <p class="grid-text">App Integrations</p>
    </div>
  </div>
</div>

  </header>
 </div>
</template>
 
 <style>
  /* Apply background image to the header */
   body {
     background-image: url("@/assets/images/bg aurora.png");
     background-repeat: no-repeat;
     background-size: cover;
     background-position: center;
     overflow-x: hidden;
   }
   /* CSS for the header */
   header {
     background-color:none;
     padding: 20px;
     display: flex;
     flex-direction: column;
     align-items: center;
     position: relative;
   }
 
   .logo-nav {
     display: flex;
     align-items: center;
     justify-content: flex-start;
   }
 
   /* CSS for the logos */
 
    .logo-container{
       position: absolute;
       left:10%;
    } 

   .logo {
     width: 50px;
     height: 30px;
     margin-right: 10px;
   }

   .logo-2{
      width: 5px;
      height: 27px;
   }
 
   /* CSS for the navbar */
   nav {
     margin-left: 100px;
   }
 
   ul {
     list-style-type: none;
     margin-left:250px;
     padding: 0;
     display: flex;
     justify-content: space-between;
   }
 
   li {
     margin-right: 45px;
     list-style: none;
   }
  
   li span{
       color:#0065FE;
   }

/* CSS for the margin between specific li elements */
   .marginli {
     margin-left: 90px;
   }

   /* CSS for the links within the navbar */
   nav li a {
     width: 76px;
     height: 22px;
     font-family: 'Gilroy-Medium', sans-serif;
     font-size: 18px;
     line-height: 21px;
     color: #141414;
     text-decoration: none;
   }
/* CSS for the button */
  .try-free-button {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    border: none;
    padding: 12px 24px;
    margin:-10px 100px;
    gap: 10px;
    width: 142px;
    height: 39px;
    background: #0065FE;
    border-radius: 100px;
    flex: none;
    order: 1;
    flex-grow: 0;
}

/* CSS for the button text */
.try-free-button span {
  font-family: 'Gilroy-SemiBold', sans-serif;
  font-size: 16px;
  line-height: 12px;
  color: #FFFFFF;
  flex: none;
  order: 0;
  flex-grow: 0;
}


   
   /* CSS for the header text */
   .header-text {
     width: 948px;
     height: 200px;
     font-family: 'Gilroy-Bold', sans-serif;
     font-size: 48px;
     line-height: 96px;
     text-align: center;
     color: #141414;
     margin-top: 50px;
   }

   span{
      color: #005AE2;
   }
 
    /* CSS for the blue line */
    .blue-line {
      position: absolute;
      width: 103.63px;
      height: 8.91px;
      left:712px;
      top: 313.9px;
  /* Primary/400 */
     background: #005AE2;
     transform: rotate(-10.82deg);
   }

   /* CSS for the additional text */
   .additional-text {
     width: 781px;
     height: 105px;
     font-family: 'Gilroy-Medium', sans-serif;
     font-size: 18px;
     line-height: 28px;
     text-align: center;
     color: #141414;
     margin-top: 10px;
   }

  
   /* CSS for the CTA container */
   .cta-container {
     display: flex;
     align-items: center;
     justify-content: center;
     margin-top: 20px;
   }
 
     /* CSS for the Sign Up button */
     .sign-up-button {
     display: flex;
     flex-direction: row;
     justify-content: center;
     align-items: center;
     padding: 12px 14px;
     background-color: #0065FE;
     color: #FFFFFF;
     font-family: 'Gilroy-SemiBold';
     font-size: 16px;
     line-height: 12px;
     text-decoration: none;
     border-radius: 90px;
     flex: none;
     order: 0;
     flex-grow: 0;
     margin-right: 10px;
     gap: 10px;
     width: 102px;
     height: 24px;
   }
 
    /* CSS for the Learn More text */
   .learn-more-text {
     font-family: 'Gilroy-SemiBold', sans-serif;
     font-size: 18px;
     line-height: 19px;
     color:#005AE2;
     margin-left:70px;
     font-weight:700;
   }

   .learn-more-text a{
      text-decoration: none;
   }

     /* CSS for the container */
    
   .image-container {
      position: absolute;
      left:430px;
      top: 130%;
      transform: translateY(-50%);
}

  .image {
     width: 238.55px;
     height: 221.2px;
     object-fit: cover;
 }


  /* CSS for the container */
  .container {
    position: absolute;
    left: 52%;
    top:130%;
    transform: translate(-50%, -50%);
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    padding: 40px 60px;
    gap: 16px;
    width: 504px;
    height: 224px;
    background: rgba(254, 254, 254, 0.1);
    border: 0.5px solid #005AE2;
    backdrop-filter: blur(106px);
    border-radius: 24px;
}

/* CSS for the image row */
.image-row {
   display: flex;
   justify-content:space-between;
   position: absolute;
   left: 4.17%;
   right: 4.17%;
   top: 20.17%;
   bottom: 29.17%;
}

/* CSS for the images */
.image-col {
  width: 80px;
  height: 80px;
}

.arrow-image{
  width: 40px;
  height: 0px;
}

.container-text {
  width: 384px;
  height: 48px;
  font-family: 'Gilroy-Medium', sans-serif;
  font-size: 16px;
  line-height: 24px;
  text-align: center;
  color: #141414;
  flex: none;
  order: 1;
  align-self: stretch;
  flex-grow: 0;
  margin-top:86px;
}

.hero-images {
   position: absolute;
   position: absolute;
   left: 0px;
   top: 931px;
}

.image-hero {
  width: 1440px;
  height: 93px;
  position: relative;
}

.image-hero:nth-child(2) {
  position: absolute;
  top: 60%;
  left: 50%;
  width: 956px;
  height: 49px;
  transform: translate(-50%, -50%);
}
.additional-content {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 50px 140px;
    gap: 90px;
    position: absolute;
    width: 100%;
    max-width: 1350px;
    height: 80px;
    left: 50%;
    transform: translateX(-50%);
    top: 1025px;
    background: #F9FBFD;
  }

  .grid-container {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-gap:4px; /* Reduce the gap between grid items */
  }

  .grid-item {
    padding: 10px;
    text-align: center;
  }

  .grid-item:nth-child(1) {
    margin-right: -50px;
  }

  .grid-item h4 {
    font-family: 'Gilroy-SemiBold';
    font-size: 30px;
    line-height: 40px;
    text-align: left;
    color: #141414;
    font-weight: 800;
    padding-top: 30px;
    margin-left: 90px;
    margin-bottom: 0;
  }

  .grid-item h4 szpan {
    color: #005AE2;
    font-size: 38px;
  }

  .grid-item p {
    color: var(--text-color-main-text, #141414);
    font-size: 16px;
    font-family: Gilroy-Medium;
    font-style: normal;
    font-weight: 400;
     line-height: 24px;
    text-align: left;
    margin-left: 20px;
    margin-top: 5px; /* Adjust the top margin to align under h4 */
  }


  /* CSS styles for desktop */
  /* ... existing CSS code ... */

  /* CSS styles for tablet */
  @media (max-width: 600px) {
  body {
    width: 280px;
    height: 480px;
    /* Add other tablet-specific styles here */
  }
}

   

  /* CSS styles for phone */
  @media (max-width: 280px) {
    body {
      /* Example phone-specific styles */
     /* CSS for the logos */
     .logo-container {
      left: 5%;
    }

    /* CSS for the navbar */
    nav {
      margin-left: 50px;
    }

    /* CSS for the margin between specific li elements */
    .marginli {
      margin-left: 50px;
    }

    /* CSS for the container */
    .container {
      width: 80%;
      left: 50%;
      top: 80%;
      transform: translate(-50%, -50%);
    }

    /* CSS for the image row */
    .image-row {
      flex-wrap: wrap;
    }

    /* CSS for the images */
    .image-col {
      width: 30%;
    }

    .container-text {
      width: 100%;
    }

    .hero-images {
      top: 130%;
    }

    .image-hero:nth-child(2) {
      width: 80%;
      height: auto;
      transform: translate(-50%, -50%);
    }

    .additional-content {
      width: 100%;
      padding: 30px;
      top: 1400px;
    }

    .grid-container {
      grid-template-columns: repeat(2, 1fr);
      grid-gap: 20px;
    }
  }

    /* CSS for the logos */
    .logo-container {
      left: 2%;
    }

    /* CSS for the navbar */
    nav {
      margin-left: 20px;
    }

    /* CSS for the margin between specific li elements */
    .marginli {
      margin-left: 20px;
    }

    /* CSS for the container */
    .container {
      width: 90%;
      padding: 20px;
      left: 50%;
      top: 80%;
      transform: translate(-50%, -50%);
    }

    /* CSS for the image row */
    .image-row {
      flex-wrap: wrap;
    }

    /* CSS for the images */
    .image-col {
      width: 45%;
    }

    .container-text {
      width: 100%;
    }

    .hero-images {
      top: 160%;
    }

    .image-hero:nth-child(2) {
      width: 100%;
      height: auto;
      transform: translate(-50%, -50%);
    }

    .additional-content {
      width: 100%;
      padding: 20px;
      top: 1800px;
    }

    .grid-container {
      grid-template-columns: repeat(1, 1fr);
      grid-gap: 10px;
    }
  }

 </style>
 
 <!--<link href="https://fonts.googleapis.com/css2?family=Gilroy:wght@700&display=swap" rel="stylesheet">-->
 
 