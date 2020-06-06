<template>
  <div class="container">
    <section>
      <!-- <logo /> -->
      <h1 class="title">Liam Broadbent</h1>
      <h4 class="subtitle">Site Coming Soon</h4>
      <div class="links">
        <a href="#" class="btn red bg">Link 1</a>
      </div>
    </section>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style lang="scss" scoped>
@import 'assets/css/setup/variables';
h1{
  margin: 2rem 0 0 0;
  text-transform: uppercase;
}
h4{
  font-weight: 100;
  text-transform: uppercase;
}
.links{
  margin-top: 3rem
}

section{
  padding:10%;
  background-color: #fff;
  box-shadow:$boxshadow1;
  // border-radius: 5rem;
}

</style>
