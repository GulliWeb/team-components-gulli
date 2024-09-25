<script>
export default {
  data() {
    return {
      
    }
  }
}
</script>

<template>
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
          <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner bg-black">
          <div class="carousel-item active">
            <div class="carousel-card">
                <div class="title">High level of efficiency and scientific teaching methods</div>
                <p class="text">
                  I am free t learn at my own pace, follow my own schedule and choose the subject I want to learn from the syllabus. Great study portal for people like me.	
                </p>
                <div class="img-wrapper d-flex justify-content-start align-items-center">
                  <img src="../assets/img/testimonial-avata-02.jpg" alt="testimonial-avatar-01">
                  <div class="carousel-img-content d-flex">
                    <h6 class="img-title">Mina Hollace</h6>
                    <p class="img-text">/ Freelancer</p>
                </div>
                </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="carousel-card">
              <div class="title">High level of efficiency and scientific teaching methods</div>
              <p class="carousel-text">					I am free to learn at my own pace, follow my own schedule and choose the subject I want to learn from the syllabus. Great study portal for people like me.				</p>
              <div class="carousel-img">
                  <img src="../assets/img/testimonial-avata-01.jpg" alt="testimonial-avatar-01">
                  <h3 class="img-title">Mina Hollace</h3>
                  <p class="img-text">/ Freelancer</p>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="carousel-card">
              <div class="title">High level of efficiency and scientific teaching methods</div>
              <p class="text">					I am free to learn at my own pace, follow my own schedule and choose the subject I want to learn from the syllabus. Great study portal for people like me.				</p>
              <img src="../assets/img/testimonial-avata-03.jpg" alt="testimonial-avatar-01">
              <div class="img-content">
                  <h3 class="img-title">Mina Hollace</h3>
                  <p class="img-text">/ Freelancer</p>
              </div>
            </div>
          </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>
      
</template>

<style lang="scss" scoped>
// CARD CAROUSEL
.carousel-card{
    width: 700px;
    height: 350px;
    border: 1px solid black;
    padding: 40px 50px;
}

.carousel-card .title{
  font-size: 20px;
  color: #3F3A64;
}

.carousel-card .text{
  margin-top: 15px;
  font-size: 18px;
  font-weight: 500;
  color: #696969;
}

.carousel-card img{
  height: 70px;
  width: 70px;
  max-width: 100%;
  border-radius: 50%;
}

.carousel-img-content{
  margin-left: 25px;
  flex-direction: column;
  align-items: start;
}

.carousel-card .carousel-img-content .img-title{
  font-size: 15px;
  color: #3F3A64;
  text-transform: uppercase;
  letter-spacing: 1px;
}

.carousel-card .carousel-img-content .img-text{
  font-size: 14px;
  color: #7e7e7e;
}
</style>