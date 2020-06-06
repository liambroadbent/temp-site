<template>
  <div class="container">
    <section>
      <logo />
      <h1 class="title">Liam Broadbent</h1>
      <h4 class="subtitle">Site Coming Soon</h4>
      <div class="links">
        <a href="https://www.linkedin.com/in/liambroadbent/" class="btn red bg"> <?xml version="1.0" encoding="utf-8"?>
          <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
            width="24px" height="24px" viewBox="0 0 24 24" enable-background="new 0 0 24 24" xml:space="preserve">
            <g>
              <path fill-rule="evenodd" clip-rule="evenodd" fill="#FEFEFE" d="M13.435,10.107c0.098-0.107,0.138-0.139,0.164-0.179
                c1.35-1.969,3.276-2.548,5.525-2.202c2.599,0.4,4.26,2.219,4.685,5.001c0.101,0.659,0.151,1.322,0.15,1.989
                c-0.002,2.771-0.007,5.541,0.006,8.312c0.003,0.312-0.075,0.403-0.395,0.399c-1.451-0.017-2.904-0.017-4.355,0
                c-0.317,0.004-0.399-0.087-0.396-0.398c0.011-2.585,0.007-5.169,0.005-7.753c-0.002-0.587-0.042-1.17-0.207-1.738
                c-0.528-1.825-2.604-2.465-4.082-1.251c-0.799,0.655-1.111,1.52-1.104,2.541c0.014,2.437,0.003,4.874,0.003,7.312
                c0,0.32-0.017,0.642,0.007,0.959c0.02,0.276-0.094,0.329-0.344,0.328c-1.478-0.01-2.957-0.011-4.435,0
                c-0.269,0.002-0.365-0.053-0.362-0.348c0.021-2.197,0.03-4.396,0.031-6.592c0-2.704-0.005-5.408-0.024-8.112
                c-0.002-0.296,0.06-0.383,0.366-0.38c1.479,0.017,2.957,0.014,4.435,0.002c0.267-0.002,0.341,0.078,0.332,0.336
                C13.421,8.891,13.435,9.448,13.435,10.107z"/>
              <path fill-rule="evenodd" clip-rule="evenodd" fill="#FEFEFE" d="M5.488,15.714c0,2.437-0.006,4.873,0.006,7.31
                c0.001,0.302-0.06,0.41-0.39,0.406c-1.464-0.02-2.929-0.017-4.394-0.004c-0.272,0.002-0.363-0.065-0.363-0.352
                c0.007-4.913,0.006-9.826-0.001-14.739c0-0.256,0.062-0.341,0.331-0.339C2.167,8.009,3.659,8.011,5.15,7.995
                c0.298-0.003,0.345,0.105,0.343,0.369C5.484,10.813,5.488,13.264,5.488,15.714z"/>
              <path fill-rule="evenodd" clip-rule="evenodd" fill="#FEFEFE" d="M2.959,0.57c1.965,0.002,3.242,1.559,2.776,3.384
                C5.383,5.332,3.958,6.125,2.313,5.858C0.565,5.574-0.41,3.869,0.235,2.221C0.637,1.191,1.666,0.568,2.959,0.57z"/>
          </g>
          </svg>
          Connect
        </a>
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
