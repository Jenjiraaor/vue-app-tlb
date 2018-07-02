<template>
  <div>
    <nuxt-link to="/table"><center>Hello jenjira->click.</center></nuxt-link><br>
    <router-link :to="{ path: '/Login'}" replace><center>Register</center></router-link><br>
    <router-link :to="{ path: '/Login'}" push><center>Register</center></router-link><br>
  </div>
</template>
<script>
export default {
  data() {
    return {
      id: 1,
    }
  },
}
</script>