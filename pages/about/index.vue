<template>
    <div class="container">
      <section>
        <div class="wrap">
          <h1>Hi, my name is Liam Broadbent</h1>
          <h3>I am a creative designer/developer</h3>
          <p>Focused on developing brands that convert.</p>

        </div>
      </section>
    </div>
</template>

<script>
export default {
  data () {
    return {
      title: 'About Liam Broadbent'
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

h1{
  text-align: left;
  margin-bottom: 3rem;
}
h3{
  text-align: left;
  margin-bottom: 3rem;
}
p{
  text-align: left;
}

</style>