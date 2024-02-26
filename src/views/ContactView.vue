<template>
    <div class="container">
      <div class="row">
        <div class="col-md-6 offset-md-3">
          <h2>Contact Us</h2>
          <form @submit.prevent="submitForm">
            <div class="mb-3">
              <label for="name" class="form-label">Name</label>
              <input type="text" class="form-control" id="name" v-model="name" required>
            </div>
            <div class="mb-3">
              <label for="email" class="form-label">Email</label>
              <input type="email" class="form-control" id="email" v-model="email" required>
            </div>
            <div class="mb-3">
              <label for="message" class="form-label">Message</label>
              <textarea class="form-control" id="message" v-model="message" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
          </form>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        name: '',
        email: '',
        message: ''
      };
    },
    methods: {
      submitForm() {
       
        console.log('Name:', this.name);
        console.log('Email:', this.email);
        console.log('Message:', this.message);
        
        // Reset form fields after submission
        this.name = '';
        this.email = '';
        this.message = '';
      }
    }
  };
  </script>
  
  <style>
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
  