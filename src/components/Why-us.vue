<template>
  <div class="additional-contents">
    <div class="grid-containers">
      <div class="grid-items">
        <div class="content-container">
          <h3>Why choose <span>Scissors</span></h3>
          <p>Scissors is the hub of everything that has to do with your
             link management. We shorten your URLs, allow you to create custom ones
              for your personal, business, or event usage. Our swift QR code creation, 
              management, and usage tracking with advanced analytics for all of these are second to none.</p>
        </div>
      </div>
      <div class="grid-items">
        <div class="content-container">
          <img src="@/assets/images/small-vector.png" alt="Image 5" class="image-col">
          <h4>URL Shortening</h4>
          <p class="content-text">Scissor allows you to shorten URLs of your<br>
            business, events. Shorten your URL at scale,<br> URL redirects.</p>
        </div>
      </div>
      <div class="grid-items">
        <div class="content-container">
          <img src="@/assets/images/edit1.png" alt="Image 5" class="image-col">
          <h4>Custom URLs</h4>
          <p class="content-text">With Scissors, you can create custom URLs with 
            the length you want! A solution for social media and businesses.</p>
        </div>
      </div>
    </div>
  </div>

  <div class="additional-contents-two">
    <div class="grid-containers">
      <div class="grid-items">
        <div class="content-container">
          <!-- Empty grid item -->
        </div>
      </div>
      <div class="grid-items">
        <div class="content-container">
          <img src="@/assets/images/grid.png" alt="Image 5" class="image-col">
          <h4>QR Codes</h4>
          <p class="content-text">Generate QR codes for your business and events. Bring your audience and customers 
            to your doorstep with this scan-and-go solution.</p>
        </div>
      </div>
      <div class="grid-items">
        <div class="content-container">
          <img src="@/assets/images/activity.png" alt="Image 5" class="image-col">
          <h4>Data Analytics</h4>
          <p class="content-text">Receive data on the usage of either your shortened URL, custom URLs, 
            or generated QR codes. Embedded tools to monitor progress.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.additional-contents {
  position: absolute;
  top: 1220px;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 50px 80px;
}

.additional-contents-two {
  position: absolute;
  top: 1500px;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 50px 80px;
}

.grid-containers {
  display: grid;
  grid-template-columns: repeat(3, 380px);
  grid-gap:40px;
}

.grid-items {
  padding: 10px;
  text-align: center;
  border-radius: 10px;
}

.content-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

h3 {
  font-family: 'Gilroy-Bold';
  font-size: 35px;
  line-height: 32px;
  color: #141414;
  margin: 20px 4px;
}

h4 {
  font-family: 'Gilroy-SemiBold';
  font-size: 32px;
  line-height: 28px;
  color: #141414;
  font-weight: 600;
  margin-top:12px;
}

.image-col {
  width: 30px;
  height: 30px;
  margin-top:14px;
  background: rgba(50, 132, 255, 0.13);
  border-radius:100px;
}

.image-col img {
  width: 30%;
  height: 30%;
  object-fit: cover;
}

p {
  display: block;
  width: 340px;
  margin: 0 auto;
  padding: 30px;
  font-family: 'Gilroy-Medium';
  font-size: 16px;
  line-height: 24px;
  color: #141414;
  text-align: left;
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 10px; 
}

.content-text p{
   margin-bottom:50px;
}
</style>

