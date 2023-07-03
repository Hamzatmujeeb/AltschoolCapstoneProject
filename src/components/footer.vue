<template>
  <footer>
    <div class="footer-wrapper">
      <div class="grid-container">
        <div class="grid-item">
          <div class="footer-logo">
            <img src="@/assets/images/footer-vector.png" alt="Footer Vector">
            <img src="@/assets/images/footer-line-logo.png" alt="Footer Line Logo">
            <img src="@/assets/images/footer-logo.png" alt="Footer Logo">
          </div>
          <div class="icon">
            <a href="#"><img src="@/assets/images/twitter-icon.png" alt="Twitter Icon"></a>
            <a href="#"><img src="@/assets/images/instagram.png" alt="Instagram Icon"></a>
            <a href="#"><img src="@/assets/images/in-icon.png" alt="LinkedIn Icon"></a>
            <a href="#"><img src="@/assets/images/facebook-icon.png" alt="Facebook Icon"></a>
          </div>
        </div>
        <div class="grid-item">
          <h3>Why Scissors?</h3>
          <p>Scissor 101</p>
          <p>Integration & API</p>
          <p>Pricing</p>
        </div>
        <div class="grid-item">
          <h3>Solution</h3>
          <p>Social Media</p>
          <p>Digital Marketing</p>
          <p>Customer Services</p>
          <p>For Developers</p>
        </div>
        <div class="grid-item">
          <h3>Products</h3>
          <p>Link Management</p>
          <p>QR Codes</p>
          <p>Link-in-bio</p>
        </div>
        <div class="grid-item">
          <h3>Company</h3>
          <p>About Scissors</p>
          <p>Careers</p>
          <p>Partners</p>
          <p>Press</p>
          <p>Contact</p>
          <p>Reviews</p>
        </div>
      </div>
      <div class="grid-container grid-container-two">
        <div class="grid-item">
          <!-- Empty -->
        </div>
        <div class="grid-item">
          <h3>Resources</h3>
          <p>Blog</p>
          <p>Resources Library</p>
          <p>App Connections</p>
          <p>Support</p>
          <p>Trust Center</p>
          <p>Browser Extension</p>
          <p>Mobile App</p>
        </div>
        <div class="grid-item">
          <h3>Features</h3>
          <p>Branded Links</p>
          <p>Mobile Links</p>
          <p>Campaign Management</p>
          <p>& Developer</p>
          <p>Analytics</p>
          <p>QR Generation</p>
        </div>
        <div class="grid-item">
          <h3>Legal</h3>
          <p>Privacy Policy</p>
          <p>Cookie Policy</p>
          <p>Terms of Service</p>
          <p>Acceptable Use Policy</p>
          <p>Code of Conduct</p>
        </div>
        <div class="grid-item">
          <!-- Empty -->
        </div>
      </div>
    </div>
    <h4>Terms of Service | Security | Scissors 2023</h4>
    <div class="footer-images">
      <img src="@/assets/images/Vector-footer.png" alt="Left Image" class="left-image">
      <img src="@/assets/images/Vector-footer2.png" alt="Right Image" class="right-image">
    </div>
  </footer>
</template>

<style>
  footer {
    position: absolute;
    top: 4900px;
    background: var(--neutral-white, #FFF);
    width: 1499px;
    height: 681px;
    overflow: hidden; /* Hide overflowing content */
  }

  .grid-container {
    display: grid;
    grid-template-columns: repeat(5, minmax(0, 1fr)); /* Adjust the column size */
    grid-gap: 10px; /* Adjust the gap between grid items */
  }

  .grid-container-two {
    margin-top: -92px;
    grid-gap: 2px; /* Adjust the gap between grid items */
  }

  .grid-item {
    border: none;
    padding: 10px;
    margin: 2px; /* Reduce the margin between the grid items */
  }

  .footer-logo img {
    margin-right: 10px;
    margin-top: 20px;
  }

  .icon img {
    margin-right: 13px;
    margin-top: 50px;
  }

  h3 {
    color: var(--neutral-900, #071827); /* Set the text color */
    font-size: 24px; /* Adjust the font size as needed */
    font-family: Gilroy-Bold; /* Set the font family */
    line-height: 24px; /* Adjust the line height as needed */
  }

  .grid-item p {
    display: -webkit-box; /* Display <p> elements as blocks */
    color: var(--neutral-800, #112232);
    font-size: 16px;
    font-family: Gilroy-Medium;
    font-style: normal;
    font-weight: 400;
    line-height: 24px;
    margin-left: 90px; /* Reset margin for the <p> tags */
    padding: 0; /* Reset padding */
  }

  h4 {
    color: var(--neutral-800, #112232);
    font-size: 14px;
    font-family: Gilroy-Medium;
    font-style: normal;
    font-weight: 400;
    line-height: 20px;
    text-align: right;
    margin-right: 50px; /* Align the <h4> element to the right */
    margin-top: -30px;
  }

  .footer-images {
    position: absolute;
    bottom: 0;
    left: 20px;
    right: 0;
    display: flex;
    justify-content: space-between;
  }

  .left-image,
  .right-image {
    width: 100px;
    height: 100px;
  }
</style>
