<script setup>
</script>

<template>
  <div>
    <div class="hero">
      <div class="container">
        <div class="hero-wrapper">
          <div class="media-hero">
            <img src="~/assets/images/png/media-hero.png" alt="" />
          </div>
          <div class="hero-text-wrapper">
            <h2>EUTOUR E030</h2>
            <h3>Erkaklar uchun Magnit Sport soatlari</h3>
            <div class="hero-price-wrapper">
              <span>600 uzs</span>
              <span>150 uzs / oyiga</span>
            </div>
            <div class="hero-btns">
              <button>Batafsil</button>
              <button>Buyurtma berish</button>
            </div>
          </div>
          <div class="hero-img">
            <div class="hero-images">
              <img src="~/assets/images/png/watch-hero-left.png" alt="" />
              <img src="~/assets/images/png/watch-hero-center.png" alt="" />
              <img src="~/assets/images/png/watch-hero-right.png" alt="" />
            </div>
          </div>
          <div class="imgs">
            <div class="all-hero-img-wrapper">
              <div class="hero-images">
                <img src="~/assets/images/png/watch-hero-left.png" alt="" />
                <img src="~/assets/images/png/watch-hero-center.png" alt="" />
                <img src="~/assets/images/png/watch-hero-right.png" alt="" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="prdoucts">
      <div class="container">
        <h2 class="products-title">Mahsulotlarimiz</h2>
        <div class="products-wrapper">
          <product v-for="item in 3" :key="item" />
        </div>
      </div>
    </div>
    <div class="banner">
      <div class="container">
        <div class="banner-wrapper">
          <div class="banner-text-wrapper">
            <h2>Xizmatlarimiz</h2>
            <p>
              Bizdan soat xarid qilganingizda, qoʻshimchasiga o‘z logotipingizni
              tushurishingiz yoki ismingizni yozdirsangiz boʻladi.
            </p>
          </div>
          <div class="banner-img">
            <img src="~/assets/images/jpg/banner.jpg" alt="" />
          </div>
          <button class="buy-btn">Buyurtma berish</button>
        </div>
      </div>
    </div>
    <div class="about">
      <div class="container">
        <h2 class="about-title">Biz haqimizda</h2>
        <div class="about-wrapper">
          <div class="about-left">
            <img src="~/assets/images/jpg/about-img.jpg" alt="" />
          </div>
          <div class="about-right">
            <p>
              “Watch Tailor”ga xush kelibsiz! Bizning soatlarimiz nafaqat vaqtni
              ko‘rsatadi, balki sizning unutilmas onlaringizda ham hamrohlik
              qiladi.
            </p>
            <p>
              Bizning maqsadimiz — har bir mijozimizning ehtiyojlariga mos,
              individual soat dizaynlarini yaratish. Bu O‘zbekistonda noyob
              taklif bo‘lib, faqat bizda soatingizni o‘zingiz uchun individual
              dizaynda qildira olasiz. Har bir soat o‘ziga xos bo‘lib, sizning
              imidjingizga yangicha koʻrinish qo‘shadi.
            </p>
            <p>
              Watch Tailor — yangi va o‘ziga xos soatlar dizayni bilan mashhur
              bo‘lgan brend. Biz “EUTOUR” brendidan ilhomlanib, mijozlar uchun
              soatlar yaratamiz. Farqimiz shundaki, “EUTOUR”da siz uchun maxsus
              dizayn xizmatlari yo‘q, ammo bizda individual tarzda soatingizni
              ismingiz yoki logotipingiz bilan shaxsiylashtirish imkoniyatiga
              ega boʻlasiz.
            </p>
            <p>
              “Watch Tailor”ga xush kelibsiz! Bizning soatlarimiz nafaqat vaqtni
              ko‘rsatadi, balki sizning unutilmas onlaringizda ham hamrohlik
              qiladi.
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="busin">
      <div class="container">
        <div class="busin-wrapper">
          <div class="busin-items-wrapper">
            <div class="busin-item">
              <span>8+</span>
              <h3>Tajriba biznesda</h3>
            </div>
            <div class="busin-item">
              <span>200+</span>
              <h3>Mijozlar</h3>
            </div>
            <div class="busin-item">
              <span>8+</span>
              <h3>Loyihalar</h3>
            </div>
            <div class="busin-item">
              <span>100%</span>
              <h3>Mijozlar roziligi</h3>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="services">
      <div class="container">
        <h2 class="services-title">Nima uchun bizni tanlashingiz kerak?</h2>
        <div class="services-wrapper">
          <div class="services-cards-wrapper">
            <div class="serivces-card">
              <img src="~/assets/images/png/round-services.png" alt="" />
              <h2>Individual</h2>
              <span
                >Xarid qilgan soatingizga ism yoki logotipingizni tushirib
                beramiz.</span
              >
            </div>
            <div class="serivces-card">
              <img src="~/assets/images/png/round-services.png" alt="" />
              <h2>Individual</h2>
              <span
                >Xarid qilgan soatingizga ism yoki logotipingizni tushirib
                beramiz.</span
              >
            </div>
            <div class="serivces-card">
              <img src="~/assets/images/png/round-services.png" alt="" />
              <h2>Individual</h2>
              <span
                >Xarid qilgan soatingizga ism yoki logotipingizni tushirib
                beramiz.</span
              >
            </div>
            <div class="serivces-card">
              <img src="~/assets/images/png/round-services.png" alt="" />
              <h2>Individual</h2>
              <span
                >Xarid qilgan soatingizga ism yoki logotipingizni tushirib
                beramiz.</span
              >
            </div>
            <div class="serivces-card">
              <img src="~/assets/images/png/round-services.png" alt="" />
              <h2>Individual</h2>
              <span
                >Xarid qilgan soatingizga ism yoki logotipingizni tushirib
                beramiz.</span
              >
            </div>
            <div class="serivces-card">
              <img src="~/assets/images/png/round-services.png" alt="" />
              <h2>Individual</h2>
              <span
                >Xarid qilgan soatingizga ism yoki logotipingizni tushirib
                beramiz.</span
              >
            </div>
            <div class="serivces-card">
              <img src="~/assets/images/png/round-services.png" alt="" />
              <h2>Individual</h2>
              <span
                >Xarid qilgan soatingizga ism yoki logotipingizni tushirib
                beramiz.</span
              >
            </div>
            <div class="serivces-card">
              <img src="~/assets/images/png/round-services.png" alt="" />
              <h2>Individual</h2>
              <span
                >Xarid qilgan soatingizga ism yoki logotipingizni tushirib
                beramiz.</span
              >
            </div>
          </div>
          <div class="services-btn-wrp">
            <button class="buy-btn-services">Buyurtma berish</button>
          </div>
        </div>
      </div>
    </div>
    <div class="clients-message">
      <div class="container">
        <h2 class="services-title">Mijozlar fikri</h2>
        <div class="client-message-wrapper">
          <div class="client-message-item">
            <div class="client-item-header">
              <img src="~/assets/images/jpg/rating-image.jpg" alt="" />
              <h2>EUTOUR E030</h2>
            </div>
            <span>
              Nasiya savdo orqali soat xarid qildim, juda qulay, yetkazib berish
              ham tekin ekan.
            </span>
            <div class="profil">
              <span></span>
              <span>Farrux</span>
            </div>
          </div>

          <div class="client-message-item">
            <div class="client-item-header">
              <img src="~/assets/images/jpg/rating-image.jpg" alt="" />
              <h2>EUTOUR E030</h2>
            </div>
            <span>
              Nasiya savdo orqali soat xarid qildim, juda qulay, yetkazib berish
              ham tekin ekan.
            </span>
            <div class="profil">
              <span></span>
              <span>Muhammad Yusuf</span>
            </div>
          </div>

          <div class="client-message-item">
            <div class="client-item-header">
              <img src="~/assets/images/jpg/rating-image.jpg" alt="" />
              <h2>EUTOUR E030</h2>
            </div>
            <span>
              Nasiya savdo orqali soat xarid qildim, juda qulay, yetkazib berish
              ham tekin ekan.
            </span>
            <div class="profil">
              <span></span>
              <span>Samandar</span>
            </div>
          </div>

          <div class="client-message-item">
            <div class="client-item-header">
              <img src="~/assets/images/jpg/rating-image.jpg" alt="" />
              <h2>EUTOUR E030</h2>
            </div>
            <span>
              Nasiya savdo orqali soat xarid qildim, juda qulay, yetkazib berish
              ham tekin ekan.
            </span>
            <div class="profil">
              <span></span>
              <span>Aziz</span>
            </div>
          </div>

          <div class="client-message-item">
            <div class="client-item-header">
              <img src="~/assets/images/jpg/rating-image.jpg" alt="" />
              <h2>EUTOUR E030</h2>
            </div>
            <span>
              Nasiya savdo orqali soat xarid qildim, juda qulay, yetkazib berish
              ham tekin ekan.
            </span>
            <div class="profil">
              <span></span>
              <span>Aziz</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="style">
      <div class="container">
        <div class="style-wrapper">
          <div class="style-left">
            <img src="~/assets/images/jpg/black-watch.jpg" alt="" />
          </div>
          <div class="style-right">
            <h2>
              Hoziroq o‘z stilingizni yarating va qolganlardan ajralib turing!
            </h2>
            <button>Buyurtma berish</button>
          </div>
        </div>
      </div>
    </div>
    <div class="information">
      <div class="container">
        <div class="information-wrapper">
          <h2>Tez-tez berildigan savollar</h2>
          <div class="information-items">
            <div class="first-inf">
              <div class="first-inf__header">
                <h3>Soatlarni qanday buyurtma qilsam bo ‘ladi?</h3>
                <img src="~/assets/images/png/minus.png" alt="">
              </div>
              <ul>
                <li>1. Oʻzingizga yoqqan soatni tanlab,  shaxsiy maʼlumotlaringizni kiriting. Tez orada siz bilan bogʼlanamiz.</li>
                <li>2. Soatlarni saytdagi telefon raqamimizga aloqaga chiqib, buyurtma berishingiz mumkin.</li>
              </ul>
            </div>

            <div class="nxt-item">
              <h3>Soat sotib olsam dostavkaga ham alohida to‘lov qilamanmi?</h3>
              <img src="~/assets/images/png/pluse.png">
            </div>
            
            <div class="nxt-item">
              <h3>Buyurtmam necha kunda keladi?</h3>
              <img src="~/assets/images/png/pluse.png">

            </div>

            <div class="nxt-item">
              <h3>Buyurtmam vaqtida kelmasa nima bo‘ladi?</h3>
              <img src="~/assets/images/png/pluse.png">
            </div>

            <div class="nxt-item">
              <h3>Agar buyurtmam yoqmasa qaytarib bersam bo‘ladimi?</h3>
              <img src="~/assets/images/png/pluse.png">
            </div>

            <div class="nxt-item">
              <h3>Dizaynga qildirish pullimi?</h3>
              <img src="~/assets/images/png/pluse.png">
            </div>

            <div class="nxt-item">
              <h3>Qanday bonuslar mavjud?</h3>
              <img src="~/assets/images/png/pluse.png">
            </div>

            <div class="nxt-item">
              <h3>Bo‘lib to‘lashga ham soat sotib olsam bo‘ladimi?</h3>
              <img src="~/assets/images/png/pluse.png">
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="form-box">
      <div class="container">
        <h2>Aloqa</h2>
        <div class="form-box__wrapper">
          <div class="form-box__wrapper-left">
            <p>
              Talab yoki takliflaringiz bo‘lsa, maʼlumotlaringizni qoldiring. Tez orada siz bilan bog‘lanamiz.
            </p>
            <div class="inputs">
              <label>
                Ismingiz
                <input type="text">
              </label>
              <label>
                Telefon raqamingiz
                <input type="text">
              </label>
              <label>
                Xabaringizni yozing
                <textarea placeholder="xabar kriting"></textarea>
              </label>
              <button>Yuborish</button>
            </div>
          </div>
          <div class="form-box__wrapper-right">
            <img src="~/assets/images/png/map.png">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="sass" scoped>
.style-left
  @media screen and (max-width: 750px)
    img
      width: 100%
.style-wrapper
  display: flex
  padding: 30px 0
  @media screen and (max-width: 1300px)
    flex-direction: column
    align-items: center
    justify-content: center
.style-right
  display: flex
  align-items: flex-start
  flex-direction: column
  background: #1C1C1C
  justify-content: center
  padding: 0 60px
  height: 600px
  @media screen and (max-width: 1300px)
    height: 400px
    padding: 0 34px
.style-right
    h2
        width: 100%
        max-width: 542px
        font-weight: 600
        font-size: 44px
        color: #fff
        line-height: 59px
        @media screen and (max-width: 1300px)
          font-size: 35px
        @media screen and (max-width: 750px)
          font-size: 25px
          line-height: 32px 
          text-align: center 
    button
      padding: 13px 30px
      font-weight: 600px
      font-size: 20px
      color: #fff
      border-radius: 8px
      background: #E59046
      margin-top: 20px 
      cursor: pointer
      border: none
      @media screen and (max-width: 750px)
        width: 100%
        font-size: 17px   
.clients-message
    padding: 30px 0 60px
.client-message-wrapper
    display: grid
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr
    gap: 20px
    overflow-x: auto
    overflow-y: hidden
    margin-top: 30px
    &::-webkit-scrollbar
        display: none
    .client-message-item
        width: 399px
        background: #242424
        padding: 20px 20px 5px
        height: 410px
        border-radius: 16px
        .client-item-header
            display: flex
            align-items: center
            gap: 10px
            h2
                font-weight: 500
                font-size: 24px
                color: #fff
                @media screen and (max-width: 750px)
                    font-size: 18px
            img
                border-radius: 10px
        span
            width: 100%
            max-width: 375px
            color: #fff
            font-weight: 300
            font-size: 16px
            line-height: 28px
            margin-top: 30px
            display: block
.profil
    width: 100%
    height: 100%
    display: flex
    align-items: center
    gap: 17px
    margin-top: auto
    span
        &:first-child
            width: 40px
            height: 35px
            border-radius: 50%
            background: #FF7A7A
            display: flex
.services
    margin-top: 60px
.services-btn-wrp
    display: flex
    align-items: center
    justify-content: center
    padding: 40px 0
.buy-btn-services
    font-weight: 600
    font-size: 18px
    color: #fff
    padding: 15px 30px
    background: #E59046
    border-radius: 8px
    cursor: pointer
    @media screen and (max-width: 750px)
        width: 100%
        font-size: 16px
        padding: 13px 22px
.services-title
    font-weight: 400
    font-size: 40px
    color: #fff
    padding: 20px 0
    @media screen and (max-width: 750px)
        font-size: 22px
.services-cards-wrapper
    display: grid
    grid-template-columns: 1fr 1fr 1fr 1fr
    gap: 50px
    margin-top: 25px
    @media screen and (max-width: 1300px)
        grid-template-columns: 1fr 1fr 1fr
    @media screen and (max-width: 850px)
        grid-template-columns: 1fr 1fr
    @media screen and (max-width: 570px)
        grid-template-columns: 1fr

    .serivces-card
        background: #242424
        display: flex
        align-items: center
        flex-direction: column
        gap: 13px
        padding: 20px
        border-radius: 12px
        h2
            font-weight: 400
            font-size: 20px
            color: #fff
        span
            width: 100%
            max-width: 295px
            font-weight: 300
            font-sizi: 14px
            line-height: 20px
            text-align: center
            color: #d1cece
.busin-items-wrapper
    display: flex
    aligh-items: center
    justify-content: space-between
    padding: 20px 0
    @media screen and (max-width: 1300px)
        flex-direction: column
        align-items: center
        gap: 20px
    .busin-item
        width: 295px
        color: #fff
        background: #242424
        display: flex
        flex-direction: column
        align-items: center
        gap: 10px
        padding: 30px 67px
        border-radius: 16px
        @media screen and (max-width: 400px)
            width: 100%
        span
            font-weight: 400
            font-size: 50px
            color: #F0F0F0
            @media screen and (max-width: 750px)
                font-size: 30px
        h3
            font-weight: 400
            font-size: 20px
            color: #B1B1B1
            @media screen and (max-width: 750px)
                font-size: 16px
.about-wrapper
    display: flex
    align-items: flex-start
    gap: 20px
    margin-top: 35px
    padding: 30px 0
    @media screen and (max-width: 1300px)
        flex-direction: column
        align-items: center
        text-align: center
    @media screen and (max-width: 750px)
        margin-top: 0
.about-right
    display: flex
    flex-direction: column
    gap: 20px
    padding: 30px 40px
    background: #1C1C1C
    border-radius: 16px
    p
        font-weight: 300
        font-size: 18px
        line-height: 28px
        color: #FFFFFF
        width: 100%
        max-width: 700px
        @media screen and (max-width: 750px)
            font-size: 16px
.about-left
    img
        border-radius: 25px
        @media screen and (max-width: 611px)
            width: 100%
.about-title
    font-weight: 500
    font-size: 40px
    color: #fff
    @media screen and (max-width: 750px)
        font-size: 25px
.buy-btn
    width: 100%
    font-weight: 600
    padding: 15px
    border: none
    font-size: 14px
    cursor: pointer
    border-radius: 8px
    color: #fff
    background: #E59046
    display: none
    @media screen and (max-width: 750px)
        display: block
.banner
    margin-top: 30px
    padding-bottom: 80px
    @media screen and (max-width: 750px)
        padding-bottom: 40px
.banner-img
    padding: 20px 0
    img
        width: 100%
        border-radius: 20px
.banner-text-wrapper
    h2
        font-weight: 500
        font-size: 40px
        color: #fff
        @media screen and (max-width: 750px)
            font-size: 24px
    p
        width: 100%
        max-width: 607px
        font-weight: 300
        font-size: 16px
        color: #fff
        line-height: 20px
        padding: 20px 0
        @media screen and (max-width: 750px)
            font-size: 14px
.products-wrapper
    display: flex
    align-items: center
    justify-content: space-between
    padding: 40px 0
    @media screen and (max-width: 1200px)
        flex-direction: column
        gap: 40px
.products-title
    font-weight: 400
    font-size: 40px
    color: #fff
    padding: 30px 0
    @media screen and (max-width: 650px)
        font-size: 30px
        padding: 10px 0
.hero-img
    display: none
    @media screen and (max-width: 1300px)
        display: block
.imgs
    position: relative
.all-hero-img-wrapper
    position: absolute
    top: -430px
    right: 870px
    @media screen and (max-width: 1300px)
        display: none

.media-hero
    display: none
    align-items: center
    @media screen and (max-width: 900px)
        display: flex
.hero
    padding: 100px 0
    position: relative
    @media screen and (max-width: 900px)
        padding: 50px 0 40px

.hero-wrapper
    display: block
    flex-direction: column
    align-items: center
    justify-content: center
    gap: 20px
    @media screen and (max-width: 1300px)
        display: flex
.hero-text-wrapper
    margin-top: 50px
    @media screen and (max-width: 1300px)
        margin-top: 620px

    @media screen and (max-width: 900px)
        margin-top: 80px
    @media screen and (max-width: 700px)
        width: 100%

    h2
        font-weight: 500
        font-size: 60px
        color: #FFFFFF
        @media screen and (max-width: 700px)
            font-size: 30px

    h3
        font-weight: 400
        font-size: 20px
        color: #FFFFFF
        padding: 10px 0
        @media screen and (max-width: 700px)
            font-size: 16px

    .hero-price-wrapper
        display: flex
        align-items: center
        gap: 20px
        padding: 30px 0
        @media screen and (max-width: 700px)
            padding: 20px 0
        span
            &:first-child
                font-weight: 600
                font-size: 30px
                color: #fff
                @media screen and (max-width: 700px)
                    font-size: 20px

            &:last-child
                padding: 10px 15px
                color: #D4D4D4
                background: #4D4D4D
                border-radius: 6px
                @media screen and (max-width: 700px)
                    font-size: 14px

    .hero-btns
        display: flex
        align-items: center
        gap: 20px
        margin-top: 20px
        @media screen and (max-width: 700px)
            flex-direction: column
        button
            font-weight: 600
            font-size: 20px
            color: #fff
            padding: 16px 20px
            background: none
            border-radius: 6px
            border: 1px solid #BBBBBB
            cursor: pointer
            @media screen and (max-width: 700px)
                width: 100%
                font-size: 16px
                padding: 13px 16px
            &:last-child
                border: none
                background: #E59046

.hero-images
    display: flex
    position: relative
    @media screen and (max-width: 1300px)
        position: absolute
        right: 1100px
        top: 60px
    @media screen and (max-width: 1210px)
        right: 1040px
    @media screen and (max-width: 1100px)
        right: 1000px
    @media screen and (max-width: 1000px)
        right: 960px
    @media screen and (max-width: 900px)
        display: none

    img
        &:nth-child(1)
            position: absolute
            left: 0
            top: 30px

        &:nth-child(2)
            position: absolute
            left: 200px

        &:nth-child(3)
            position: absolute
            left: 550px
            top: 30px
</style>
