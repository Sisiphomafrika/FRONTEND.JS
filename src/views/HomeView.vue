<template>
  <div class="container">
    <div class="row">
      <h2 class="display-2 mb-4">Home</h2>
    </div>
    <div class="row">
      <p class="lead">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium ratione quam necessitatibus deleniti molestiae delectus excepturi earum quaerat quidem natus minus, ipsa, perferendis reprehenderit quisquam dolore mollitia voluptas officiis. Quidem.</p>
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

.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

.row {
  margin-bottom: 20px;
}

.display-2 {
  color: #333;
}

.lead {
  font-size: 1.2rem;
}
</style>
