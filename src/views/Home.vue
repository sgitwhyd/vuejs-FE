<template>
 
 <div>
  <div class="container">
  <div class="row">
    <div class="col-lg-6  align-self-center">
      <img width="590px" src="../assets/Destination-pana.png" alt="content-pic">
    </div>
     <div class="col-md-5 ml-5 title">
        <h4 class="title-text">BEST 2020 TRAVEL AGENT</h4>
        <h1>Plan, Order & Pay in Comfort</h1>
        <p>Traveling should be fun and stress free. 
            Our service is ready 24 hours to help you 
            create the most amazing travel experience.
          </p>
     </div>
  </div>
 </div>
  <div class="container">
    <h1 class="title-content">Why Choose Us ?</h1>
    <div class="row mt-5 ">
      <div class="col-sm-3 feature">
        <img width="150px" height="150px" src="../assets/technology.png" alt="">
        <div>
              <h4>All in One Trip Package</h4>
        <p>Transportation, accommodation, 
          tickets, and visa applications 
          are included in one package.</p>
        </div>
      </div>
      <div class="col-sm-3 feature">
        <img width="150px" height="150px" src="../assets/24-hours.png" alt="">
        <div>
            <h4>24 Hours Full Service</h4>
        <p>Our service is ready to serve you 
          for 24 hours, 7 days a week, 
          and 365 days a year. </p>
        </div>
      </div>
      <div class="col-sm-3 feature">
        <img width="150px" height="150px"  src="../assets/best-price.png" alt="">
        <div>
          <h4>Best Price Best Experience</h4>
        <p>Various great offers to give you 
            the best price for your own desired travel experience.</p>
        </div>
      </div>
       <div class="col-sm-3 feature">
        <img width="170px" height="150px"  src="../assets/City-driver-pana.png" alt="">
        <div>
          <h4>Best Price Best Experience</h4>
        <p>Various great offers to give you 
            the best price for your own desired travel experience.</p>
        </div>
      </div>
    </div>
 </div>
 </div>


</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
export default {
  name: 'Home',
  components: {
     
  }
}
</script>

<style scoped>

.title-content {
  font-size: 50px;
}

.title {
  margin-top: 70px;
}

.title .title-text {
  color: #F8B70C;
  font-size: 28px;
}

.title h1 {
  font-weight: bold;
  font-size: 65px;
  margin-top: 40px;
}

.feature h4 {
  text-align: center;
  font-weight: bold;
  font-size: 28px;
  margin-top: 30px;
}

.feature p {
  font-size: 18px;
  line-height: 30px;
  margin-top: 10px;
  text-align: center;
}

.feature img {
  margin-left: 50px;
}


</style>
