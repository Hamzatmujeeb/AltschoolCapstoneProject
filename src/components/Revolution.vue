<template>
    <div class="custom-div">
      <img src="@/assets/images/Vector-trim.png" alt="Your Image" class="custom-image">
      <img src="@/assets/images/Vector-trim2.png" alt="Right Image" class="custom-image right-image">
      <h2>Revolutionizing Link Optimization</h2>
      <button class="custom-button">Get Started</button>
    </div>
  </template>
  
  <style scoped>
  .custom-div {
    position: absolute;
    top: 4400px;
    bottom: 0;
    width: 1499px;
    height: 413px;
    background: var(--linear-gradient, linear-gradient(180deg, #1E3448 99.99%, rgba(30, 52, 72, 0.00) 100%));
    display: flex;
    flex-direction: column;
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
    left: 1038px; /* Adjust the right position according to your needs */
    top:40%; /* Adjust the top position according to your needs */
    transform: translateY(-30%); /* Center the image vertically */
  }
  
  h2 {
    display: flex;
    width: 806px;
    height: 57px;
    flex-direction: column;
    color: #FFF;
    text-align: center;
    font-size: 40px;
    font-family: Gilroy-Bold;
    line-height: 48px;
  }
  
  .custom-button {
  margin-top: 20px;
  display: flex;
  width: 200px;
  height: 48px;
  padding: 12px 24px;
  justify-content: center;
  align-items: center;
  gap: 10px;
  border-radius: 100px;
  background: var(--primary-400, #005AE2);
  color: #FFF;
  font-size: 18px;
  font-weight: bold;
  border: none;
  cursor: pointer;
}

  
  </style>
  