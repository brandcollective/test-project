<template>
  <section class="container">
    <div>
      <h1 class="title">
        Test Project
      </h1>
      <h2 class="subtitle">
        Our users are shown below!
      </h2>
      <!-- Add your user list component here-->
      <div>
        <h2 class="subtitle">
          Create an account.
        </h2>
        <!-- Add your component form for creating a new user here here -->
      </div>
    </div>
  </section>
</template>

<script>
import axios from 'axios'
import { log } from 'util';

export default {
  components: {
  },
  data: function () {
    return {
    }
  },
  methods: {
  },
  created: async function () {
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.customers {
  padding-top: 15px;
  padding-bottom: 15px;
}

button {
  margin-top: 15px;
}
ul {
  padding: 0;
  margin: 0;
}
li {
  list-style-type: none;
  border-bottom: 1px solid grey;
  padding: 5px;
  margin: 10px;
}
li:hover {
  cursor: pointer;
}
</style>
