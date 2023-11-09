<script setup>
import HelloWorld from './components/HelloWorld.vue'
import ButtonWorld from './components/ButtonWorld.vue';

</script>

<template>
      <nav>
        <p>Home</p>
      <router-link to="/about" >About</router-link>
      <router-link to="/contact" >Contact</router-link>
   
    </nav>
  <div>

 <!-- <ButtonWorld text="Login" secondProps="Manish" :arrayOfNumbers="[1,2,3]" /> -->
 <!-- <ButtonWorld text="Login" secondProps="Manish"  /> -->
 <!-- <ButtonWorld text="Register" secondProps="abc" />
 <ButtonWorld  /> -->
 <router-view />
 <footer>
      <p>This is footer</p>

    </footer>
  
  </div>
  <!-- <HelloWorld  /> -->
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
