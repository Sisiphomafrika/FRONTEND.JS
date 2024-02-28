<template class="container">
  <div class="Home" >
    <div class="row">
      <h2 class="display-2 mb-4">WELCOME TO <br>SUNPOWER INNOVATIONS</h2>
    </div>
    <div class="row">
      <p class="lead"> where we're dedicated to providing innovative solutions for a sustainable future. Explore our range of cutting-edge products and services designed to help you save money and reduce your carbon footprint. Join us in our mission to create a cleaner, greener world for generations to come. Together, we can make a difference!".</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeView',
  components: {
  }
}
</script>

<style scoped>

*,
::before,
::after {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Times New Roman', Times, serif;
}

.Home{
  background-image: url('https://i.ibb.co/wsQR7tH/mariana-proenca-m-G8sgwk-Mh-CY-unsplash.jpg'); /* Path to your background image */
background-size: cover;
size: 100px;
padding-bottom:600px;
padding-top: 20px;
}
h1 {
  color: #333;
  font-size: 2.5rem;
  margin-bottom: 20px;
}

h2 {
  color: #333;
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
    font-size: 1rem;
  }
}
</style>
