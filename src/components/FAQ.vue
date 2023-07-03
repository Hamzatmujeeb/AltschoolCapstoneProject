<template>
  <!-- FAQs -->
  <div class="faqs">
    <div class="wrapper9">
      <!--<img class="faq_image" src="@/assets/images/Line 70.png" alt="FAQ Image">-->
      <h2>FAQs</h2>
      <ul class="accordian">
        <li>
          <input type="radio" name="accordian" id="first" checked>
          <label for="first">How does URL shortening work?</label>
          <div class="content">
            <p>
              URL shortening works by taking a long URL and creating a shorter,
               condensed version that redirects to the original URL. When a user clicks on
                the shortened link, they are redirected to the intended destination.
            </p>
          </div>
        </li>

        <li>
          <input type="radio" name="accordian" id="second">
          <label for="second">Is it necessary to create an account to use the URL shortening service?</label>
          <div class="content">
            <p>
              URL shortening works by taking a long URL and creating a
               shorter, condensed version that redirects to the original URL. 
               When a user clicks on the shortened link, they are redirected to the intended destination.
            </p>
          </div>
        </li>

        <li>
          <input type="radio" name="accordian" id="third">
          <label for="third">Are the shortened links permanent? Will they expire?</label>
          <div class="content">
            <p>
              URL shortening works by taking a long URL and creating a shorter, 
              condensed version that redirects to the original URL. When a user clicks on the 
              shortened link, they are redirected to the intended destination.
            </p>
          </div>
        </li>

        <li>
          <input type="radio" name="accordian" id="fourth">
          <label for="fourth">Can I customize the shortened URLs to reflect my brand or content?</label>
          <div class="content">
            <p>
              URL shortening works by taking a long URL and creating a shorter, 
              condensed version that redirects to the original URL. When a user 
              clicks on the shortened link, they are redirected to the 
              intended destination.
            </p>
          </div>
        </li>

        <li>
          <input type="radio" name="accordian" id="fifth">
          <label for="fifth">Can I track the performance of my shortened URLs?</label>
          <div class="content">
            <p>
              URL shortening works by taking a long URL and creating a 
              shorter, condensed version that redirects to the original URL. When 
              a user clicks on the shortened link, they are redirected to the intended destination.
            </p>
          </div>
        </li>

        <li>
          <input type="radio" name="accordian" id="sixth">
          <label for="sixth">How secure is the URL shortening service? 
            Are the shortened links protected against spam or malicious activity?</label>
          <div class="content">
            <p>
              URL shortening works by taking a long URL and creating 
              a shorter, condensed version that redirects to the original URL.
               When a user clicks on the shortened link, they are redirected to the intended destination.
            </p>
          </div>
        </li>

        <li>
          <input type="radio" name="accordian" id="seventh">
          <label for="seventh">What is a QR code and what can it do?</label>
          <div class="content">
            <p>
              URL shortening works by taking a long URL and creating
               a shorter, condensed version that redirects to the original URL.
                When a user clicks on the shortened link, they are redirected to the intended destination.
            </p>
            </div>
        </li>

        <li>
          <input type="radio" name="accordian" id="eight">
          <label for="eight">Is there an API available for integrating the URL
             shortening service into my own applications or websites?</label>
          <div class="content">
            <p>
              URL shortening works by taking a long URL and creating a 
              shorter, condensed version that redirects to the original URL.
               When a user clicks on the shortened link, they are redirected to the intended destination.
            </p>
            </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<style>
  /* FAQs */
  .faqs {
    position: absolute;
    top: 3320px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    margin-top: 50px;
  }

  .faqs h2 {
    font-family: gilroy-bold;
    font-size: 46px;
    display: flex;
    align-items: center;
  }

  /*.faq_image {
    width:20px;
    height:10px;
    margin:auto;
  }*/

  .accordian {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin-top: 30px;
    padding: 0;
    list-style: none;
  }

  .wrapper9 {
    padding-top: 40px;
    align-items: center;
    justify-content: center;
    display: flex;
    flex-direction: column;
  }

  .accordian li {
    flex: 0 0 50%;
    margin-bottom: 20px;
    padding: 10px;
  }

  .accordian li label {
    padding: 10px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    font-family: gilroy-medium;
    font-size: 16px;
    font-weight: 600;
    cursor: pointer;
  }

  .accordian label::after {
    content: '+';
    font-size: 1.5em;
    transform: rotate(90deg);
    transition: transform 0.3s ease-in-out;
  }

  .accordian .content {
    padding: 0 10px;
    line-height: 22px;
    max-height: 0;
    overflow: hidden;
    font-family: gilroy-medium;
    font-size: 14px;
    transition: max-height 0.5s;
    border-bottom: 2px solid RGB(230 236 241);
  }

  .accordian li:hover .content {
    max-height: 400px;
  }

  .accordian input[type="radio"] {
    display: none;
  }

  /* Add additional styles as needed */

 /* Media Queries */
 @media only screen and (max-width: 180px) {
    /* Styles for Android phone */
    .faqs {
      top: 100px;
      margin-top: 30px;
    }
    .faqs h2 {
      font-size: 14px;
      justify-content:right;
    }
    .accordian li {
      flex-basis: 100%;
      justify-content: left;
    }
    .accordian .content {
      font-size: 10px;
      margin-left:70px;
    }
    /* Additional styles for other elements on phone */
  }

  @media only screen and (min-width: 451px) and (max-width: 468px) {
    /* Styles for Android tablet */
    .faqs {
      top: 150px;
      margin-top: 40px;
    }
    .faqs h2 {
      font-size: 32px;
    }
    .accordian li {
      flex-basis: 50%;
    }
    .accordian .content {
      font-size: 14px;
    }
    /* Additional styles for other elements on tablet */
  }
</style>