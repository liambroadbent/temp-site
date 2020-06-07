<template>
  <div class="container">
    <h1>Contact Page</h1>
  </div>
</template>

<script>
export default {
  data () {
    return {
      title: 'Contact Liam Broadbent!'
    }
  },
  head () {
    return {
      title: this.title,
      meta: [
        { hid: 'description', name: 'description', content: 'A Holding page, I use various parts of the site as a sandbox to test various technologies out' }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
@import 'assets/css/scss';

</style>