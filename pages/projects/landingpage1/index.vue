<template>
  <div class="container">
      <header>
          <a class="logo" href="#">ArtHole</a>
          <div class="navs">
              <nav>
                  <ul>
                      <li>
                          <a href="#" class="link">Services</a>
                          <a href="#" class="link">Work</a>
                          <a href="#" class="link">Agency</a>
                          <a href="#" class="link">News</a>
                          <a href="#" class="link">Contact</a>
                      </li>
                  </ul>
              </nav>
              <ul class="socials">
                  <li><a href="#" class="link">Instagram</a></li>
                  <li><a href="#" class="link">Twitter</a></li>
                  <li><a href="#" class="link">LinkedIn</a></li>
              </ul>
          </div>
        </header>  
      <div class="cover">
          <div class="wrap">
              <h1>Creative Agency</h1>
              <h2>For businesses and brands</h2>
              <a href="#">CTA</a>
          </div>
      </div>
      <div class="part one">
          <div class="wrap">
              <h2>Beatuiful solutions come at&nbsp;a&nbsp;price.</h2>
              <h3>ArtHole is a branding agency that makes a impression</h3>
          </div>
          <div class="img">

          </div>
      </div>
      <div class="part two">
          <div class="card one">
              <h4>Title goes here</h4>
              <div class="img one"></div>
              <h5>bit of text goes here</h5>
          </div>
          <div class="card two">
              <h4>Title goes here</h4>
              <div class="img two"></div>
              <h5>bit of text goes here</h5>
          </div>
          <div class="card three">
              <h4>Title goes here</h4>
              <div class="img three"></div>
              <h5>bit of text goes here</h5>
          </div>
      </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'Landing Page 1'
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
            'combination of a few cool landing page ideas ive seen'
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
@import 'assets/css/scss';
.container{
    background-color: #fff;
    background-image: none;
    height:100%;
    width:100%;
    flex-direction:column;
}

header{
    display: flex;
    justify-content: space-between;
    position: absolute;
    width: 100%;
    top:0;
    left:0%;
    padding:3rem;
    .logo{
        color:white;
        font-size: 2rem;
    }
    .navs{
        display:flex;
        nav{
            ul{

                li{
                    margin-left:2rem;
                }
            }     
        }
        ul{
            display: flex;
            li{
                margin-left:1rem;
                font-size: 1rem;
                a{
                    color:white;
                }
            }
        }
    }
}
.cover{
    height:100vh;
    width:100%;
    flex-direction:column;
    background: url('https://images.unsplash.com/photo-1596295228890-6f9115cd9c2c?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80');
    display: flex;
    justify-content: center;
    align-items: flex-start;
    .wrap{
        display: flex;
        padding-left: 5vw;
        justify-content: flex-start;
        align-items: flex-start;
        flex-direction: column;
        h1{
            color:white;
        }
        h2{
            color:white;
        }
    }
}

.part{
    height: 100vh;
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding:5vw;

    &.one{
        text-align: left;
        .wrap{
            width: 65%;
            h2{
                color:black;
                font-size: 7rem;
                line-height: 1.35;
                font-weight: 900;
            }
            h3{
                color:black;
                margin-top: 3rem;
                font-size: 3rem;
                width: 70%;
                line-height: 1.35;
            }
        }
        .img{
            height:300px;
            width:30%;
            background-image: url('https://images.unsplash.com/photo-1596272983839-ce0e5a1f5485?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=701&q=80');
        }
    }
    &.two{

        .card{
            border-top:1px solid red;
            text-align: left;
            width: 30%;
            padding-top: 3rem;

            h5{
                margin-top: 1rem;
                font-weight: normal;
            }
            .img{
                margin-top: 3rem;
                height:300px;
                width:100%;
                background-size: cover;
                &.one{
                    background-image: url('https://images.unsplash.com/photo-1595943350274-58503f7f6237?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60');
                }
                &.two{
                    background-image: url('https://images.unsplash.com/photo-1595502999951-de4d6e15bae4?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60');
                }
                &.three{
                    background-image: url('https://images.unsplash.com/photo-1595878715977-2e8f8df18ea8?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60');
                }
            }
        }
    }
}
</style>