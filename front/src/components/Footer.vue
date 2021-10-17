<template>
  <div>
    <footer class="foot">
  	    <p>© All rights reserved by webcampnavi.</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
footer{
    position: absolute;/*←絶対位置*/
    bottom: 0; /*下に固定*/
}


.foot{
    width: 100%;
    color: white;
    background-color: rgb(50, 67, 70);
    text-align: center;
}

</style>