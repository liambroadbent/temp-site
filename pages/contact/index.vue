<template>
  <div class="container">
    <div class="form">
      <h1>Contact Page</h1>
      <iframe
        src="https://docs.google.com/forms/d/e/1FAIpQLSff9TbIUcv3JYzu0D7ZGo_dm_-x8Lbx9hTaYszWSacAKuWywQ/viewform?embedded=true"
        width="640"
        height="440"
        frameborder="0"
        marginheight="0"
        marginwidth="0"
        >Loading…</iframe
      >
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'Contact Liam Broadbent!',
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
  h1{
    margin-bottom: 5rem;
  }

  .form {
    padding:10rem;
    min-height:50vw;
  flex-direction: column;
    background: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
  }
}
</style>