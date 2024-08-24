<template>
  <main>
    <div class="container">
      <div class="img"></div>
      <div class="summary">
        <h2>Order Summary</h2>
        <div class="music-text">
          <p>You can now listen to millions of songs, audiobooks, and podcasts on any device anywhere you like!</p>
        </div>


      </div>
      <div class="payment-plan">
        <div class="music-image"></div>

        <div class="payment-text">
          <div class="plan-text">
            <p class="annual">Annual Plan</p>
            <p>$59.99/year</p>
          </div>
          <div class="change-div">
            <a href="">Change</a>
          </div>
        </div>
      </div>

      <div class="payment-button"> Proceed to Payment</div>
      <div class="cancel-button"> Cancel Order</div>
    </div>
  </main>
</template>

<style scoped>
main {
  background-color: hsl(225, 100%, 94%);
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100vw;
  height: 100vh;
  background-image: url("/images/pattern-background-desktop.svg");
  background-repeat: no-repeat;
  background-size: contain;
  background-position-y: -100px;
}

.container {
  width: 350px;
  height: 600px;
  background-color: white;
  border-radius: 20px;

}

.img {
  width: 100%;
  background-color: white;
  height: 35%;
  background-image: url("/images/illustration-hero.svg");
  background-repeat: no-repeat;
  background-size: cover;
  border-top-left-radius: 20px;
  border-top-right-radius: 20px;
}

.summary {
  text-align: center;
  padding: 20px;
}

h2 {
  color: hsl(223, 47%, 23%);
  font-size: 25px;
  font-weight: 900;

}

.music-text {
  padding-left: 30px;
  padding-right: 30px;
}

.payment-plan {
  height: 80px;
  width: 300px;
  background-color: hsl(225, 100%, 98%);
  margin-left: auto;
  margin-right: auto;
  border-radius: 10px;
  padding: 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 20px;
}

.annual {
  color: hsl(223, 47%, 23%);
  font-weight: 900;
}

.music-image {
  width: 50px;
  height: 50px;
  background-repeat: no-repeat;
  background-image: url("/images/icon-music.svg");
  background-color: hsl(225, 100%, 94%);
  border-radius: 50%;
  padding: 10px;
}

p {
  font-size: 16px;

}

.payment-text {
  display: flex;
  flex-grow: 1;
  align-items: center;
  justify-content: space-between;
}


a {
  color: hsl(245, 75%, 52%);
  font-size: 15px;
  font-weight: 700;
}

.payment-button {
  background-color: hsl(245, 75%, 52%);
  width: 300px;
  height: 40px;
  border-radius: 10px;
  margin-top: 20px;
  margin-left: auto;
  margin-right: auto;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-weight: 700;
  box-shadow: 0 10px 10px hsl(225, 100%, 94%);
}

.cancel-button {
  background-color: white;
  width: 100px;
  height: 40px;
  border-radius: 10px;
  margin-left: auto;
  margin-right: auto;
  margin-top: 15px;
  margin-bottom: 0px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: hsl(223, 47%, 23%);
  font-weight: 700;
}

.cancel-button:hover {
  cursor: pointer;
}

a:hover {
  cursor: pointer;
  color: hsl(224, 23%, 55%);
  text-decoration: none;
}

.payment-button:hover {
  cursor: pointer;
  background-color: hsl(224, 23%, 55%);
}

</style>