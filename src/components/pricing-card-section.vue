<template>
  <section>
  <h2 class="pricing-title">A <span>Price Perfect</span> for Your Needs</h2>
  <p class="pricing-text">From catering for your personal, business, event, socials needs, you can be<br>
    rest assured we have you in mind in our pricing.</p>
  <div class="pricing-container">
    <div class="pricing-card">
      <h4 class="pricing-subtitle">basic</h4>
      <h2 class="pricing-price">Free</h2>
      <h5 class="pricing-description">Free plan for all users</h5>
      <div class="pricing-feature">
        <img src="@/assets/images/check-circle.png" alt="Feature Image 1">
        <p class="pricing-features">Basic Link Analytics</p>
      </div>
      <div class="pricing-feature">
        <img src="@/assets/images/check-circle.png" alt="Feature Image 1">
        <p class="pricing-features">Customizable Short Links</p>
      </div>
      <div class="pricing-feature">
        <img src="@/assets/images/check-circle.png" alt="Feature Image 1">
        <p class="pricing-features">Customizable Short Links</p>
      </div>
      <div class="pricing-feature">
        <img src="@/assets/images/check-circle.png" alt="Feature Image 1">
        <p class="pricing-features">Ad-supported</p>
      </div>
    </div>

    <div class="pricing-card second-column">
      <h4 class="pricing-subtitle">Professional</h4>
      <h2 class="pricing-price">$15/month</h2>
      <h5 class="pricing-description">Ideal for business creators</h5>
      <div class="pricing-feature">
        <img src="@/assets/images/check-circle.png" alt="Feature Image 1">
        <p class="pricing-features">Enhanced Link Analytics</p>
      </div>
      <div class="pricing-feature">
        <img src="@/assets/images/check-circle.png" alt="Feature Image 1">
        <p class="pricing-features">Enhanced Link Analytics</p>
      </div>
      <div class="pricing-feature">
        <img src="@/assets/images/check-circle.png" alt="Feature Image 1">
        <p class="pricing-features">Advanced Link Customization</p>
      </div>
      <div class="pricing-feature">
        <img src="@/assets/images/check-circle.png" alt="Feature Image 1">
        <p class="pricing-features">Ad-free Experience</p>
      </div>
    </div>

    <div class="pricing-card">
      <h4 class="pricing-subtitle">Teams</h4>
      <h2 class="pricing-price">$25/month</h2>
      <h5 class="pricing-description">Share with up to 10 users</h5>
      <div class="pricing-feature">
        <img src="@/assets/images/check-circle.png" alt="Feature Image 1">
        <p class="pricing-features">Team Collaboration</p>
      </div>
      <div class="pricing-feature">
        <img src="@/assets/images/check-circle.png" alt="Feature Image 1">
        <p class="pricing-features">User Roles and Permissions</p>
      </div>
      <div class="pricing-feature">
        <img src="@/assets/images/check-circle.png" alt="Feature Image 1">
        <p class="pricing-features">User Roles and Permissions</p>
      </div>
      <div class="pricing-feature">
        <img src="@/assets/images/check-circle.png" alt="Feature Image 1">
        <p class="pricing-features">Dedicated Account Manager</p>
      </div>
    </div>
  </div>
  <div class="pricing-buttons">
      <button class="pricing-button">Get Custom Pricing</button>
      <button class="pricing-button">Select Pricing</button>
    </div>
</section>

</template>
  
  <style scoped>
  section {
    position: absolute;
    top: 1910px;
    left: 50%;
    transform: translateX(-50%);
  }
  
  .pricing-container {
    display: flex;
    justify-content: center;
    padding: 15px;
  }
  
  .pricing-card {
    width: 379px;
    height: 495px;
    flex-shrink: 0;
    border-radius: 10px;
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
    background-color: #ffffff;
    padding: 24px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  
  .second-column {
  display: inline-flex;
  border-radius: 12px;
  padding-top: 19px;
  padding-bottom: 70px;
  background: var(--linear-gradient, linear-gradient(160deg, #1E3448 99.99%, rgba(30, 52, 72, 0.00) 80%));
  /* Drop shadow */
  box-shadow: 0px 4px 8px 0px rgba(0, 0, 0, 0.05);
}

.second-column h4,
.second-column h2,
.second-column h5,
.second-column p {
  color: #fff;
}
  
  .pricing-title {
    font-size: 40px;
    font-weight: bold;
    color: #141414;
    text-align: center;
    font-family: Gilroy-Bold;
    line-height: 48px;
    margin-bottom: 12px;
  }
  
  span {
    color: rgba(0, 90, 226, 1);
  }
  
  .pricing-text {
    color: var(--text-color-main-text, #141414);
    text-align: center;
    font-size: 16px;
    font-family: Gilroy-large;
    line-height: 24px;
    font-weight: 700;
  }
  
  .pricing-subtitle {
    color: var(--text-color-main-text, #141414);
    text-align: center;
    font-size: 24px;
    font-family: Gilroy-Medium;
    line-height: 32px;
    margin: 20px;
  }
  
  .pricing-price {
    font-size: 48px;
    font-weight: bold;
    color: #141414;
    margin-bottom: 12px;
  }
  
  .pricing-description {
    color: var(--text-color-main-text, #141414);
    text-align: center;
    margin-left: 10px;
    font-size: 20px;
    font-family: Gilroy-Medium;
    line-height: 32px;
  }
  
  .pricing-feature {
    display: flex;
    align-items: center;
    margin-bottom: 12px;
  }

  .pricing-feature img {
    display: block; /* Change display to block */
    width: 16px;
    height: 16px;
    margin-right: 8px;
  }

  .pricing-features {
    display: block; /* Change display to block */
    color: var(--text-color-main-text, #141414);
    font-size: 14px;
    font-family: Gilroy-Medium;
    line-height: 10px;
  }

/* Existing styles */

.pricing-buttons {
  display: flex;
  justify-content: center;
  margin-top: 40px;
}

.pricing-button {
  display: flex;
  width: 200px;
  height: 48px;
  padding: 12px 24px;
  margin: 10px;
  justify-content: center;
  align-items: center;
  gap: 10px;
  background-color: #005AE2;
  color: #ffffff;
  border: none;
  border-radius: 6px;
  font-size: 16px;
  font-weight: bold;
  cursor: pointer;
}

.pricing-button:first-child {
  background-color: #ffffff;
  border-radius: 100px;
  border: 1px solid var(--primary-300-base, #0065FE);
  color: var(--primary-300-base, #0065FE);
  font-size: 16px;
  font-family: Gilroy-SemiBold;
  line-height: 12px;
}

.pricing-button:nth-child(2) {
  border-radius: 100px;
  background: var(--primary-300-base, #0065FE);
  color: var(--neutral-white, #FFF);
  font-size: 16px;
  font-family: Gilroy-SemiBold;
  line-height: 12px;
}

  </style>
  