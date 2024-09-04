<script setup>
</script>

<template>
    <div>
        <div class="cart">
            <div class="container">
                <h2 class="cart-title">Mahsulot yetib borishi uchun ma’lumotlaringizni to‘g‘ri to‘ldiring</h2>
                <div class="cart-wrapper">
                    <div class="cart-left">
                        <div class="cart-left-img-wrap">
                            <img src="~/assets/images/png/detail-main-image.png" alt="">
                        </div>
                        <div class="cart-left-text-wrapper">
                            <h2>EUTOUR Magnetic Eng yaxshi yog'och soatlar E031</h2>
                            <span>600 000 uzs</span>
                        </div>
                    </div>
                    <div class="cart-right">
                        <div class="cart-right-wrapper">
                            <label>
                                <span>Ism familiyangiz</span>
                                <input type="text">
                            </label>
                            <label>
                                <span>Telefon raqamingiz</span>
                                <input type="text">
                            </label>
                            <label>
                                <span>Viloyatingiz</span>
                                <input type="text">
                            </label>
                            <label>
                                <span>To‘liq manzilingizni yozing</span>
                                <textarea placeholder="to'liq manzildi shuerga yozing"></textarea>
                            </label>
                            <button class="purchase">Yuborish</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="sass" scoped>
.cart-right
    width: 100%
    margin-top: 30px
.cart-wrapper
    display: flex
    align-items: flex-start
    gap: 30px
.purchase
    color: #fff
    background: #E59046
    cursor: pointer
    border: none
    border-radius: 8px
    padding: 19px
    font-weight: 600
    font-size: 16px
.cart-left
    margin-top: 30px
.cart
    position: fixed
    top: 0
    width: 100%
    background: #505050
    padding: 20px
    .cart-title
        width: 100%
        max-width: 610px
        line-height: 49px
        font-weight: 600
        font-size: 36px
        color: #fff
    .cart-left-img-wrap
        width: fit-content
        background: #272727
        padding: 27px
        border-radius: 16px
    .cart-left-text-wrapper
        display: flex
        align-items: flex-end
        padding: 20px 0
        h2
            font-weight: 400
            font-size: 30px
            width: 100%
            max-width: 400px
            color: #fff
        span
            font-weight: 400
            font-size: 30px
            color: #CCCCCC 

.cart-right-wrapper
    width: 100%
    display: flex
    flex-direction: column
    gap: 30px
    background: #1C1C1C
    padding: 25px
    border-radius: 16px
    label
        display: flex
        flex-direction: column
        gap: 12px
        input
            padding: 18px
            background: #303030
            border: none
            border-radius: 8px
        textarea
            padding: 18px
            background: #303030
            border: none
            resize: none
            border-radius: 8px   
        span
            font-weight: 400
            font-size: 16px
            color: #B0B3B9                             
</style>