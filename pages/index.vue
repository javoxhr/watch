<script setup>
const quantity = ref(0);
</script>

<template>
  <div>
    <div class="hero">
      <div class="container">
        <div class="hero-wrapper">
          <div class="hero__left">
            <img src="~/assets/images/png/detail-main-image.png" alt="" />
          </div>
          <div class="hero__right">
            <div class="hero-right__text-wrapper">
              <div class="images images-media">
                <div class="image-box"></div>
                <div class="image-box"></div>
                <div class="image-box"></div>
                <div class="image-box"></div>
              </div>
              <h2 class="product-title">
                EUTOUR Magnetic Eng yaxshi yog'och soatlar E031
              </h2>
              <span class="date-delivery"
                >Buyurtmangiz 2-9-sentyabrgacha yetkaziladi</span
              >
              <div class="price-wrap">
                <span class="price">600 000 <span>uzs</span></span>
                <span class="ras">150 uzs / oyiga</span>
              </div>
              <div class="add-quantity">
                <button @click="quantity > 0 ? quantity-- : ''">-</button>
                <span class="quantity">{{ quantity }}</span>
                <button @click="quantity += 1">+</button>
              </div>
              <span class="linie"></span>
              <div class="images">
                <div class="image-box"></div>
                <div class="image-box"></div>
                <div class="image-box"></div>
                <div class="image-box"></div>
              </div>
              <div class="hero-right-btns">
                <button>Batafsil ma’limot olish</button>
                <button>Buyurtmani rasmiylashtirish</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="character">
      <div class="container">
        <div class="character-wrapper">
          <div class="character__left">
            <h2>Xarakteristikasi</h2>
            <div class="character__left-wrapper">
              <nav>
                <ul>
                  <li><span>Model raqami</span><span>E031A-M1</span></li>
                  <li><span>Rangi</span><span>Qora</span></li>
                  <li><span>Harakat</span><span>RONDA Quartz-M1</span></li>
                  <li>
                    <span>Batareya</span
                    ><span>920 tugmali hujayra (45 oy)</span>
                  </li>
                  <li><span>Suvga chidamliligi</span><span>3ATM</span></li>
                  <li><span>Koson materiali:</span><span>mis (PVD)</span></li>
                  <li><span>Dial</span><span>Tabiiy yog'och </span></li>
                  <li><span>Koson diametri</span><span>40mm</span></li>
                  <li><span>Band uzunligi</span><span>Moslashuvchan </span></li>
                </ul>
              </nav>
            </div>
          </div>
          <div class="character__right">
            <h2>Ta’rifi</h2>
            <div class="character__right-wrapper">
              <div class="charcter-item">
                <h3>Tabiiy yog'och material</h3>
                <p>
                  58% mis qotishmasidan va tabiiy qizil sandal daraxtidan
                  tayyorlangan har bir magnitli yog'och soat qo'lda
                  ehtiyotkorlik bilan ishlangan. Ushbu soatlarning har bir
                  detalidan ularning ter va donoligini his qilishingiz mumkin.
                  Ularning barchasi toksik bo'lmagan va hipoalerjenikdir.
                </p>
              </div>

              <div class="charcter-item">
                <h3>Og'ir yuk komponentlari</h3>
                <p>
                  Shveytsariyalik RONDA kvarts harakati bilan jihozlangan bu
                  yog'och soatlar bardoshli va har bir harakatingiz uchun aniq
                  vaqtni ushlab turishi mumkin. Batareyaning ishlash muddati 45
                  oygacha.
                </p>
              </div>

              <div class="charcter-item">
                <h3>Moslashtirilgan yog'och soat tasmasi</h3>
                <p>
                  Yog'ochdan yasalgan magnit soatlar yog'ochning tabiiy
                  go'zalligini saqlaydigan, bo'yoq va kimyoviy moddalarsiz,
                  nafis ishlangan EUTOUR yog'och bantlari bilan birga keladi.
                  Har bir guruh noyob bo'lib, nafislik va estetikani taqdim
                  etadi. O'lchamlarni sozlash uchun professional vositalar
                  taqdim etiladi, bu esa soat bandini oson sozlash imkonini
                  beradi.
                </p>
              </div>

              <div class="charcter-item">
                <h3>3ATM suv o'tkazmaydigan jism</h3>
                <p>
                  30 metrgacha (3ATM) suvga chidamliligi bilan bu soatlar ter,
                  yomg'ir yoki suvning chayqalishiga bardosh bera oladi. Biroq,
                  ular suzish, dush olish, sho'ng'in qilish yoki snorkeling
                  uchun mos emas.
                </p>
              </div>
            </div>
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
.images-media
    margin-top: -20px !important
    padding-bottom: 20px
    display: none !important
    @media screen and (max-width: 1300px)
        display: flex !important
.hero
    &-wrapper
        display: flex
        align-items: flex-start
        gap: 50px
        padding: 80px 0
        @media screen and (max-width: 1300px)
            flex-direction: column
            align-items: center
        @media screen and (max-width: 700px)
            padding: 30px 0
    &__left
        width: fit-content
        background: #272727
        padding: 64px 60px
        border-radius: 12px
        @media screen and (max-width: 750px)
            padding: 30px
        img
            @media screen and (max-width: 750px)
                width: 100%
    &__right
        .product-title
            width: 100%
            max-width: 612px
            line-height: 38px
            font-weight: 400
            font-size: 30px
            color: #F5F5F5
            font-family: sans-serif
            @media screen and (max-width: 750px)
                width: 100%
                font-size: 20px
        .date-delivery
            color: #E59046
            font-weight: 300
            font-size: 16px
            font-family: sans-serif
            padding: 10px 0
            display: block
            @media screen and (max-width: 750px)
                font-size: 14px
        .price
            font-family: sans-serif
            font-weight: 400
            font-size: 30px
            color: #fff
            display: flex
            align-items: center
            gap: 10px
            span
                font-size: 20px
                color: #CCCCCC
                font-family: sans-serif
        .ras
            padding: 6px 10px
            background: #292929
            color: #fff
            font-family: sans-serif
            font-weight: 400
            font-size: 16px
            border-radius: 6px
        .price-wrap
            display: flex
            align-items: center
            gap: 20px
            @media screen and (max-width: 750px)
                margin-top: 10px
        .add-quantity
            width: fit-content
            display: flex
            align-items: center
            gap: 30px
            background: #2D2D2D
            padding: 10px 14px
            border-radius: 12px
            border: 1px solid #868686
            margin-top: 29px
            @media screen and (max-width: 750px)
                span
                    font-size: 20px !important
                button
                    font-size: 20px !important
            span
                font-weight: 400
                font-size: 25px
                color: #fff
                font-weight: 700
            button
                border: none
                background: none
                color: #fff
                font-family: sans-serif
                font-weight: 400
                font-size: 30px
                cursor: pointer
        .images
            width: 100%
            display: flex
            align-items: center
            gap: 20px
            margin-top: 30px
            @media screen and (max-width: 1300px)
                display: none
            .image-box
                width: 138px
                height: 137px
                background: #272727
                border-radius: 4px
                @media screen and (max-width: 750px)
                    width: 100%
                    height: 80px
                &:first-child
                    border: 1px solid #E59046
        .linie
            width: 100%
            height: 2px
            background: #727272
            margin-top: 30px
            display: block
            @media screen and (max-width: 1300px)
                display: none
        .hero-right-btns
            display: flex
            flex-direction: column
            gap: 20px
            margin-top: 60px
            @media screen and (max-width: 750px)
                margin-top: 30px
            button
                width: 100%
                padding: 18px 0
                font-weight: 300
                font-size: 16px
                background: none
                color: #FFFFFF
                border: 1px solid #BBBBBB
                border-radius: 8px
                cursor: pointer
                transition: all .5s ease
                height: 60px
                @media screen and (max-width: 750px)
                    font-size: 14px
                    padding: 14px 0
                &:last-child
                    background: #E59046
            button:hover
                background: #E59046
                border: #E59046
.character
  &-wrapper
    display: flex
    justify-content: space-between
    @media screen and (max-width: 1300px)
      flex-direction: column
      align-items: center
      gap: 30px
  &__left
    width: 595px
    @media screen and (max-width: 700px)
      width: 100%
      h2
        font-size: 30px !important
    h2
      font-weight: 400
      font-size: 40px
      font-family: sans-serif
      color: #fff
    &-wrapper
      margin-top: 24px
      nav
        ul
          display: flex
          flex-direction: column
          gap: 15px
          li
            width: 100%
            display: flex
            align-items: center
            justify-content: space-between
            span
              font-weight: 400
              font-size: 16px
              color: #909090
              font-family: sans-serif
              &:first-child
                color: #BCBCBC
                font-size: 17px
  &__right
    @media screen and (max-width: 700px)
      h2
        font-size: 30px !important
    h2
      font-weight: 400
      font-size: 40px
      font-family: sans-serif
      color: #fff
    &-wrapper
      margin-top: 20px
      .charcter-item
        h3
          font-family: sans-serif
          font-weight: 400
          font-size: 16px
          color: #BCBCBC
        p
          width: 100%
          max-width: 610px
          font-family: sans-serif
          font-weight: 300
          font-size: 14px
          line-height: 24px
          color: #909090
          padding: 10px 0

.information
  margin-top: 50px
  &-wrapper
    display: flex
    flex-direction: column
    align-items: center
    h2
      font-weight: 500
      font-size: 40px
      color: #fff
      text-align: center
      @media screen and (max-width: 750px)
        font-size: 24px
  .information-items
    display: flex
    flex-direction: column
    gap: 10px
    margin-top: 70px
    @media screen and (max-width: 750px)
      margin-top: 30px
    .first-inf
      width: 100%
      max-width: 819px
      background: #202020
      padding: 18px 20px
      border-radius: 12px
      &__header
        display: flex
        align-items: center
        justify-content: space-between
        @media screen and (max-width: 750px)
          align-items: flex-end
        h3
          color: #fff
          font-weight: 400
          font-size: 20px
          @media screen and (max-width: 750px)
            font-size: 16px
        img
          @media screen and (max-width: 750px)
            width: 18px   
      ul
        display: flex
        flex-direction: column
        gap: 5px
        margin-top: 17px
        li
          font-weight: 300
          font-size: 16px
          color: #B9B9B9
          @media screen and (max-width: 750px)
            font-size: 14px 
    .nxt-item
      width: 100%
      max-width: 819px
      background: #202020
      display: flex
      align-items: flex-end
      justify-content: space-between
      padding: 17px 20px
      border-radius: 12px
      h3
        color: #fff
        font-weight: 400
        font-size: 19px
        @media screen and (max-width: 750px)
          font-size: 16px
      img
        @media screen and (max-width: 750px)
          width: 18px
          height: 18px    
      img
        cursor: pointer

.form-box
  margin-top: 180px
  @media screen and (max-width: 700px)
    margin-top: 60px
  h2
    color: #fff
    font-weight: 500
    font-size: 35px
    @media screen and (max-width: 750px)
      font-size: 23px
  &__wrapper
    display: flex
    gap: 32px
    padding: 50px 0
    @media screen and (max-width: 1300px)
      flex-direction: column
      align-items: center
    &-left
      background: #1C1C1C
      padding: 40px
      border-radius: 20px
      @media screen and (max-width: 1300px)
        width: 100%
      p
        width: 100%
        max-width: 530px
        color: #fff
        font-weight: 400
        font-size: 18px
        line-height: 27px
        @media screen and (max-width: 750px)
          font-size: 14px
          line-height: 22px
      .inputs
        display: flex
        flex-direction: column
        gap: 20px
        margin-top: 30px
        label
          display: flex
          flex-direction: column
          gap: 10px
          color: #fff
          font-weight: 300
          font-size: 13px
          input
            width: 100%
            max-width: 530px
            padding: 16px 15px
            border-radius: 8px
            border: none
            background: #303030
            color: #fff
          textarea
            width: 100%
            height: 80px
            max-width: 530px
            background: #303030
            padding: 16px
            color: #fff
            border-radius: 8px
            border: none
            resize: none
        button
          width: 100%
          max-width: 530px
          font-weight: 600
          font-size: 16px
          color: #fff
          padding: 19px
          background: #E59046
          border: none
          cursor: pointer
          border-radius: 8px
    &-right
      @media screen and (max-width: 1300px)
        width: 100%
        display: none

      @media screen and (max-width: 750px)
        display: block
        img
          height: 300px !important  
      img
        width: 100%
        height: 539px
        object-fit: cover
        border-radius: 20px                            
</style>