<template>
  <div>
    <nuxt />
    <footer>
      <ul>
        <li>
          <nuxt-link to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/about">About</nuxt-link>
        </li>
        <!-- <li>
          <nuxt-link to="/projects">Projects</nuxt-link>
        </li> -->
        <li>
          <nuxt-link to="/contact">Contact</nuxt-link>
        </li>
      </ul>
    </footer>
  </div>
</template>

<style lang="scss" scoped>
@import 'assets/css/scss';
div {
  @include gradient($darkblue, $blue, horizontal);
  z-index: 1;
}
footer {
  min-height: 20vh;
  position: relative;
  z-index: 999;
  padding: 10%;
  background-color: #2c2c2c;
  ul {
    display: flex;
    justify-content: space-between;
    li {
      display: flex;
      align-items: center;
      a {
        border-bottom: 1px solid white;
        color: white;
        padding-bottom: 0.25em;
        text-decoration: none;
        font-size: 2rem;
          background-position: bottom;
          background-repeat: repeat-x;

        &:hover {
          background-image: url("data:image/svg+xml;charset=utf8,%3Csvg id='squiggle-link' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' xmlns:ev='http://www.w3.org/2001/xml-events' viewBox='0 0 20 4'%3E%3Cstyle type='text/css'%3E.squiggle{animation:shift .3s linear infinite;}@keyframes shift {from {transform:translateX(0);}to {transform:translateX(-20px);}}%3C/style%3E%3Cpath fill='none' stroke='%23fff' stroke-width='2' class='squiggle' d='M0,3.5 c 5,0,5,-3,10,-3 s 5,3,10,3 c 5,0,5,-3,10,-3 s 5,3,10,3'/%3E%3C/svg%3E");
          background-position: bottom;
          background-repeat: repeat-x;
          background-size: 20%;
          border-bottom: 0;
          // padding-bottom: 0.3em;
          text-decoration: none;
        }
      }
    }
  }
}
</style>
