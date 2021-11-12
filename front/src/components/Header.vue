<template>
  <div id="header">
      <div>
          <h2>Schedule</h2>
      </div>
      <div class="menu-list">
          <ul>
              <li><a href="#">All</a></li>
              <li><a href="#">自習タスク</a></li>
              <li><a href="#">テスト予定</a></li>
              <li><a href="#">TOEFL</a></li>
              <li><a href="#">もくもく会</a></li>
          </ul>
      </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  a {
      text-decoration: none;
  }
  #header {
      display: flex;
      justify-content: space-between;
  }
  
  #header ul {
      display: flex;
      list-style-type: none;
  }
  
  #header li {
      padding: 10px;
  }
</style>
