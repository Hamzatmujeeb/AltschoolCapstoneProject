<template>
    <div class="custom-div">
      <img src="@/assets/images/Vector-trim.png" alt="Your Image" class="custom-image">
      <img src="@/assets/images/Vector-trim2.png" alt="Right Image" class="custom-image right-image">
      <form class="custom-form">
        <div class="input-container">
          <input type="text" placeholder="Paste URL here..." class="first-input">
        </div>
        <div class="input-container">
          <input type="text" placeholder="Type Alias here" class="second-input">
          <select class="custom-select">
            <option value="option1">Choose Domain</option>
            <option value="option2">Option 2</option>
            <option value="option3">Option 3</option>
          </select>
        </div>
        <button class="submit-button">
          Trim URL
          <img src="@/assets/images/magic wand.png" alt="Right Image" class="right-image-btn">
        </button>
        <p class="terms-text">By clicking TrimURL, I agree to the <b>Terms of Service</b>,<br> <b>Privacy Policy</b>, and Use of Cookies.</p>
      </form>
    </div>
  </template>
  
  <style scoped>
  .custom-div {
    position: absolute;
    top: 2900px;
    bottom: 0;
    width: 1499px;
    height: 443px;
    background: var(--linear-gradient, linear-gradient(180deg, #1E3448 99.99%, rgba(30, 52, 72, 0.00) 100%));
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .custom-image {
    position: absolute;
    left: 0;
    top: 0;
    width: 450px; /* Adjust the width according to your image size */
    height: 360px; /* Maintain aspect ratio */
  }
  
  .right-image {
    position: absolute;
    left:1038px; /* Adjust the right position according to your needs */
    top:50%; /* Adjust the top position according to your needs */
    transform: translateY(-30%); /* Center the image vertically */
  }
  
  .custom-form {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background-color: #fff;
    padding: 50px;
    border-radius: 12px;
    background: #FFF;
  }
  
  .input-container {
    display: flex;
    gap: 10px;
    margin-bottom: 20px;
    width: 400px; /* Updated width */
  }
  
  .first-input {
    width: 100%;
    height: 55px;
    padding: 8px 12px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    gap: 10px;
    border-radius: 12px;
    border: 2px solid var(--primary-100, #3284FF);
    color: var(--primary-100, #3284FF);
    font-size: 12px;
    font-family: Gilroy-Medium;
    line-height: 18px;
  }
  
  .first-input::placeholder {
    color: var(--primary-100, #3284FF);
  }
  
  .second-input,
  .custom-select {
    width: 392px;
    height: 55px;
    padding: 8px 12px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    gap: 10px;
    border-radius: 12px;
    border: 2px solid var(--primary-100, #3284FF);
    color: var(--primary-100, #3284FF);
    font-size: 12px;
    font-family: Gilroy-Medium;
    line-height: 18px;
  }
  
  .second-input::placeholder,
  .custom-select {
    color: var(--primary-100, #3284FF);
  }
  
  .custom-form input,
  .custom-form select {
    width: 100%;
    height: 100%;
    padding: 15px;
    color: var(--primary-100, #3284FF);
    font-size: 12px;
    font-family: Gilroy-Medium;
    line-height: 18px;
  }
  
  .submit-button {
    position: relative;
    width: 400px; /* Updated width */
    height: 40px;
    background-color: var(--primary-300-base, #0065FE);
    color: var(--neutral-white, #FFF);
    font-size: 14px;
    font-family: Gilroy-SemiBold;
    line-height: 12px;
    border-radius: 100px;
    border: none;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .right-image-btn{
    width:26px;
    height:26px; /* Maintain aspect ratio */
    margin-left:20px; /* Add some spacing between the text and image */
  }
  
  .terms-text {
    margin-top:25px;
    font-size: 16px;
    color: #4991FF;
    font-family: Gilroy-Medium;
    line-height: 20px;
  }
  </style>
  