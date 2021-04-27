<template>
  <div class="container">
    <!-- <section>
      <div class="wrap">
        <logo />
        <h1 class="title">Liam Broadbent</h1>
        <h4 class="subtitle">Site Coming Soon!</h4>
        <div class="links">
          <a href="https://www.linkedin.com/in/liambroadbent/" class="btn red bg">
            Connect
          </a>
        </div>
      </div>
      <nuxt-link to="/about">
        <img class="one" src="/images/rounded-stripes.svg" />
      </nuxt-link>
      <nuxt-link to="/contact">
        <img class="two" src="/images/rounded-stripes.svg" />
      </nuxt-link>
    </section> -->
    <section id="new">

        <h1>test</h1>

    </section>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo,
  },
  data() {
    return {
      title: 'New - Liam Broadbent - Website coming soon!',
    }
  },
  head() {
    return {
      title: this.title,
      meta: [
        // hid is used as unique identifier. Do not use `vmid` for it as it will not work
        {
          hid: 'description',
          name: 'description',
          content:
            'A Holding page, I use various parts of the site as a sandbox to test various technologies out',
        },
      ],
    }
  },
}
</script>

<style lang="scss" scoped>
@import 'assets/css/scss';
.container {
  flex-direction: column;
}

#new {
  padding: 10rem;
  width:1200px;
  flex: 1 1 auto;
  background-color: #fff;
}
</style>
