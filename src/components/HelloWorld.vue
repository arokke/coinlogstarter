<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>A take on personal finance</p>
    <h3>Status</h3>
    <br />

    <div class="container">
      <!-- Content here -->
      <div class="progress">
        <div
          class="progress-bar"
          role="progressbar"
          style="width: 100%"
          aria-valuenow="100"
          aria-valuemin="0"
          aria-valuemax="100"
        >
          Domain name acquired!
        </div>
      </div>
      <br />
            <div class="progress">
        <div
          class="progress-bar"
          role="progressbar"
          style="width: 100%"
          aria-valuenow="100"
          aria-valuemin="0"
          aria-valuemax="100"
        >
          Data model Completed!
        </div>
      </div>
      <br />
      <div class="progress">
        <div
          class="progress-bar"
          role="progressbar"
          style="width: 100%"
          aria-valuenow="100"
          aria-valuemin="0"
          aria-valuemax="100"
        >
          Back-end Completed!
        </div>
      </div>
      <br />
      <div class="progress">
        <div
          class="progress-bar"
          role="progressbar"
          style="width: 40%"
          aria-valuenow="40"
          aria-valuemin="0"
          aria-valuemax="100"
        >
          Front-end 40%
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}

a {
  color: #42b983;
}
</style>
