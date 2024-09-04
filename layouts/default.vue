<script setup>
const menu = ref(-100)
</script>

<template>
  <div class="site-body">
    <div class="menu-open" :style="{'right': menu + '%'}">
      <button @click="menu = -100" class="close-menu-btn">
        <svg
          fill="none"
          height="23"
          viewBox="0 0 16 16"
          width="23"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            clip-rule="evenodd"
            d="M8 16C12.4183 16 16 12.4183 16 8C16 3.58172 12.4183 0 8 0C3.58172 0 0 3.58172 0 8C0 12.4183 3.58172 16 8 16ZM4.29289 5.70711L6.58579 8L4.29289 10.2929L5.70711 11.7071L8 9.41421L10.2929 11.7071L11.7071 10.2929L9.41421 8L11.7071 5.70711L10.2929 4.29289L8 6.58579L5.70711 4.29289L4.29289 5.70711Z"
            fill="#E59046"
            fill-rule="evenodd"
          />
        </svg>
      </button>
      <div class="header-wrapper-list menu-list">
        <nav>
          <ul>
            <li><NuxtLink to="/">Bosh sahifa</NuxtLink></li>
            <li><NuxtLink to="/">Katalog</NuxtLink></li>
            <li><NuxtLink to="/">Biz haqimizda</NuxtLink></li>
            <li><NuxtLink to="/">Ko’p beriladigan savollar</NuxtLink></li>
            <li><NuxtLink to="/">Fikrlar</NuxtLink></li>
            <li><NuxtLink to="/">Aloqa</NuxtLink></li>
          </ul>
        </nav>
      </div>
    </div>
    <header>
      <div class="container">
        <div class="header-wrapper">
          <div class="site-logo">
            <NuxtLink to="/">
              <img src="~/assets/images/svg/logo.svg" alt="" />
            </NuxtLink>
          </div>
          <div class="menu-header">
            <span><img src="~/assets/images/svg/call.svg" alt="" /></span>
            <span @click="menu = 0"><img src="~/assets/images/svg/menu.svg" alt="" /></span>
          </div>
          <div class="header-wrapper-list">
            <nav>
              <ul>
                <li><NuxtLink to="/">Bosh sahifa</NuxtLink></li>
                <li><NuxtLink to="/">Katalog</NuxtLink></li>
                <li><NuxtLink to="/">Biz haqimizda</NuxtLink></li>
                <li><NuxtLink to="/">Ko’p beriladigan savollar</NuxtLink></li>
                <li><NuxtLink to="/">Fikrlar</NuxtLink></li>
                <li><NuxtLink to="/">Aloqa</NuxtLink></li>
              </ul>
            </nav>
          </div>
          <div class="site-number">
            <a href="#">
              <img src="~/assets/images/svg/call.svg" alt="" />
              <span>971351721</span>
            </a>
          </div>
          <div class="header-wrapper__icons">
            <a href="#"
              ><img src="~/assets/images/svg/telegram.svg" alt=""
            /></a>
            <a href="#"><img src="~/assets/images/svg/youtube.svg" alt="" /></a>
            <a href="#"
              ><img src="~/assets/images/svg/instagram.svg" alt=""
            /></a>
          </div>
        </div>
      </div>
    </header>
    <NuxtPage />
    <footer>
      <div class="container">
        <div class="footer-wrapper">
          <div class="footer-logo">
            <NuxtLink>
              <img src="~/assets/images/svg/logo.svg">
            </NuxtLink>
          </div>
          <nav>
            <ul>
              <li><NuxtLink to="/">Bosh sahifa</NuxtLink></li>
              <li><NuxtLink to="/">Katalog</NuxtLink></li>
              <li><NuxtLink to="/">Biz haqimizda</NuxtLink></li>
              <li><NuxtLink to="/">Ko’p beriladigan savollar</NuxtLink></li>
              <li><NuxtLink to="/">Fikrlar</NuxtLink></li>
              <li><NuxtLink to="/">Aloqa</NuxtLink></li>
            </ul>
          </nav>
          <div class="footer-contact">
            <button><img src="~/assets/images/svg/call.svg">971351721</button>
          </div>

          <div class="footer-icons">
            <a href="#"><img src="~/assets/images/svg/telegram.svg"></a>
            <a href="#"><img src="~/assets/images/svg/youtube.svg"></a>
            <a href="#"><img src="~/assets/images/svg/instagram.svg"></a>
          </div>
        </div>
        <div class="footer-bottom">
          <span></span>
          <h5>Copyright Fargenius Software Group © 2023-2024. All Rights Reserved.</h5>
        </div>
      </div>
    </footer>
  </div>
</template>

<style lang="sass" scoped>
.site-body
  background: linear-gradient(180deg, #5D5D5D -4.75%, #040404 112.56%)
  animation: site-anim 1s forwards

@keyframes site-anim
  from
    opacity: 0
  to
    opacity: 1

.close-menu-btn
  border-radius: 50%
  border: none
  display: flex
  align-items: center
  justify-content: center
  position: absolute
  right: 20px
  cursor: pointer
.menu-header
  display: none
  align-items: center
  gap: 10px
  @media screen and (max-width: 1300px)
    display: flex
  span
    padding: 8px
    background: #4A4A4A
    border-radius: 6px
    cursor: pointer
.menu-open
  width: 300px
  position: fixed
  z-index: 10
  right: 0
  height: 100%
  background: #272727
  border-left: 3px solid #E59046
  padding: 20px
  transition: all .4s ease
.menu-list
  margin-top: 40px
  nav
    ul
      display: flex
      flex-direction: column
      gap: 20px 
      *
        color: #fff
        font-family: sans-serif

footer
  .container
    display: grid
    grid-template-rows: 1fr auto
    @media screen and (max-width: 8129px)
     height: 20vh
    @media screen and (max-width: 1600px)
      height: 30vh
    @media screen and (max-width: 1300px)
      height: 100%  
         

.footer-wrapper
  display: flex
  align-items: center
  justify-content: space-between
  @media screen and (max-width: 1300px)
    flex-direction: column
    gap: 30px
  nav
    ul
      display: flex
      align-items: center
      gap: 40px
      @media screen and (max-width: 1300px)
        flex-direction: column
      li
        *
          font-weight: 300
          font-size: 16px
          color: #D6D6D6
  .footer-contact
    button
      border: none
      background: #363636
      color: #fff
      display: flex
      align-items: center
      gap: 10px
      font-weight: 400
      font-size: 16px
      padding: 10px 15px
      border-radius: 6px 
  .footer-icons
    display: flex
    align-items: center
    gap: 5px
    a
      width: 44px
      height: 44px
      border-radius: 50%
      background: #363636
      display: flex
      align-items: center
      justify-content: center

.footer-bottom
  span
    width: 100%
    height: 2px
    background: #333333
    display: block
    margin-top: 40px 
  h5
    color: #fff
    padding: 30px 0
    text-align: center                       
</style>