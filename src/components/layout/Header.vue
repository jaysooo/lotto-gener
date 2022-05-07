<template>
  <div class="topnav">
    <div class="menu-left">
      <router-link :to="{name:'home'}" exact>Home</router-link>
    </div>

    <div class="menu-right">
      <a href="#" @click.prevent="toggleNav">Toggle Nav</a>
      <a href="#" @click.prevent="toggleAside">Toggle Aside</a>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.topnav {
    background-color:gray;
    display: float;
    overflow:hidden;
}

.topnav .menu-right {
margin-left: auto;
}
.topnav a {
    float: left;
    display: block;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 14px;
    border-radius: 0.25em;
    margin-right: .25rem;
    font-weight: bold;
  }
  /* Change the color of links on hover */
  .topnav a:hover {
    background-color: #ddd;
    color: black;
  }
  /* Add a color to the active/current link */
  .topnav a.active {
    background-color: #4CAF50;
    color: white;
  }
</style>