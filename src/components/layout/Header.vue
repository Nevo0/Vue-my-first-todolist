<template>
  <div class="header">
    <h1>Todo List</h1>
    <div id="nav">
      <router-link to="/">AppS</router-link>|
      <router-link to="/about">About</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

 <style scoped>
.header {
  text-align: center;
  background: #333;
  color: #fff;
  padding: 10px;
}
.header a {
  color: #fff;
  padding-right: 5px;
  text-decoration: none;
}
</style>
 