<template>
  <div class="container">
    <div class="title">
      <h1>Projects</h1>
    </div>
    <div class="body">
      <h3>My Projects</h3>
      <ul>
        <li>BMR Calculator</li>
        <li>Other</li>
        <li>Other</li>
      </ul>
      <p>I plan to fill the page out more, make each project a card with a link offsite?</p>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'Various Projects - Liam Broadbent'
    }
  },
  head() {
    return {
      title: this.title,
      meta: [
        {
          hid: 'description',
          name: 'description',
          content:
            'A Holding page, I use various parts of the site as a sandbox to test various technologies out'
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
</style>