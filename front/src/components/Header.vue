<template>
  <div class="hello">
    <ul>
      <li class="top">SCHEDULE</li>
      <div class="menu">
        <li><a href="">App</a></li>
        <li><a href="">Contact</a></li>
        <li><a href="">Jeneral</a></li>
      </div>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.top {
  text-align: left;
  position: absolute;
  left:  50px;
  font-size: 150%;
}

.menu {
  list-style-type: none;
  padding: 0;
  text-align: right;
}
li {
  display: inline-block;
  margin: 0 10px;
  padding: 30px
}
a {
  color: #ebf4f0;
}
.hello {
  background-color: rgb(35, 213, 240);
}

</style>
