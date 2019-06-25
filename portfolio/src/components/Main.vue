<template>
  <div class="main">
    <h1>{{ msg }}</h1>
    <p>
      Welcome! This website is in progress!
    </p>
    <h3>Projects</h3>
    <ul>
      <li>
        link1
      </li>
      <li>
        link2
      </li>
      <li>
        link3
      </li>
    </ul>
    <h3>Organizations</h3>
    <ul>
      <li>
        Women in Computer Science
      </li>
      <li>
        Engineering Design Team
      </li>
      <li>
        Society of Hispanic Engineers
      </li>
    </ul>
    <h3>Classes</h3>
    <ul>
      <li>
        Human Augmentics
      </li>
      <li>
        Video Game Design and Development
      </li>
      <li>
        Wearable Technology
      </li>
      <li>
        Artificial Intelligence
      </li>
    </ul>
  </div>

</template>

<script>
export default {
  name: "Main",
  props: {
    msg: String
  }
};
</script>


<!-- CSS begins -->
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
