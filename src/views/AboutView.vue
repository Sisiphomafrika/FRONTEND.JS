<template>
  <div class="about">
    <div class="row justify-content-center m-5">
      <div class="col-7">
        <h1>ABOUT US!</h1>
          <p class="lead">"At SunPower Innovations, we are dedicated to transforming the future of energy through sustainable solar solutions. With a relentless focus on innovation and efficiency, we strive to harness the power of the sun to create a greener, more sustainable world. Our comprehensive range of services includes everything from residential solar panel installations to large-scale commercial projects. We pride ourselves on delivering top-notch craftsmanship and personalized service to every client, ensuring that their transition to solar energy is seamless and hassle-free. At SunPower Innovations, we believe that by working together, we can build a brighter, cleaner future for generations to come.".</p>
  
          <h2>OUR MISSION</h2>
          <p class="lead">Our mission at SunPower Innovations is to revolutionize the way the world uses energy by providing reliable, affordable, and sustainable solar solutions. We believe that by harnessing the power of the sun, we can create a cleaner, greener planet for future generations.</p>

          <h3>WHY CHOOSE US?</h3>
          <p class="lead">At SunPower Innovations, we are committed to excellence in everything we do. Here are a few reasons to choose us for your solar energy needs.</p>
      </div>
    </div>
  </div>
</template>


<style scoped>

.about{
background-image: url('https://i.ibb.co/88HdN9X/bill-mead-wma-P3-Tl80ww-unsplash.jpg');
background-size: cover;
size: 100px;
padding-bottom:600px;
padding-top: 20px;
text-align: center;

}

h1 {
  color: hsl(0, 14%, 87%);
  font-size: 2.5rem;
  margin-bottom: 20px;
}

h2 {
  color: hwb(0 87% 9%);
  font-size: 2rem;
  margin-bottom: 10px;
}

.lead {
  font-size: 1.2rem;
  line-height: 1.6;
}

/* Media query for smaller screens */
@media (max-width: 768px) {
  h1 {
    font-size: 2rem;
  }

  h2 {
    font-size: 1.8rem;
  }

  .lead {
  font-size: 1.2rem;
  line-height: 1.6;
  color: hwb(0 100% 0%); /* Custom text color */
}
}
</style>

