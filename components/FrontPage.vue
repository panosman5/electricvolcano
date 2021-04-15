<template>
<div>
  <img src="@/assets/images/etna.jpg" alt="" width="100%">
  <div id="content">
      <h1 style="text">ELECTRIC VOLCANO</h1>
      <a class="button"><NuxtLink to="/About">Learn More</NuxtLink></a>
  </div>
</div>
</template>

<script>
export default {

}
</script>

<style>
/* body {
  background-image: url("@/assets/images/etna.jpg");
  background-size: cover;
} */
#content {
   
  position: fixed;
  top: 50%;
  left: 50%;
  /* bring your own prefixes */
  transform: translate(-50%, -50%);
    text-align: center;
}

h1 {
    font-size: 40px;
    color: white;
}
</style>