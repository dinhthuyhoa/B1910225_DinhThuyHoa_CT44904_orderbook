<script>
import AppHeader from "@/components/AppHeader.vue";
import AppFooter from "@/components/AppFooter.vue";
import Login from "@/components/Login.vue";
import Home from "@/views/Home.vue";
export default {
  components: {
    AppHeader,
    AppFooter,
    Login,
    Home,
  },
};
</script>

<template>
  <div id="app" >
    <!-- <Login /> -->
    <div >
      <div>
        <AppHeader />
      </div>    
      <div class="container " >
        <router-view />
      </div>
      <div>
        <AppFooter />
      </div>
    </div>
  </div>
</template>

<style>
.page {
  max-width: 400px;
  margin: auto;
}

.hidden {
  display: none;
}
</style>
