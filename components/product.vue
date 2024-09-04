<script setup>
</script>

<template>
  <div>
    <NuxtLink to="/detail">
      <div class="image-wrap">
        <img src="~/assets/images/png/product-img.png" alt="" />
      </div>
      <h2 class="product-title">EUTOUR E030</h2>
      <div class="product-price-wrap">
        <span>600 uzs</span>
        <span>150 uzs / oyiga</span>
      </div>
    </NuxtLink>
  </div>
</template>

<style lang="sass" scoped>
.image-wrap
    width: fit-content
    background: #272727
    padding: 10px
    border-radius: 12px
    @media screen and (max-width: 750px)
        img
            width: 100%
.product-title
    color: #fff
    font-weight: 500
    font-size: 24px
    padding: 20px 0
    @media screen and (max-width: 750px)
        padding: 10px 0
        font-size: 18px
.product-price-wrap
    display: flex
    align-items: center
    gap: 20px
    span
        &:first-child
            font-weight: 600
            font-size: 20px
            color: #fff
            @media screen and (max-width: 750px)
                font-size: 16px
        &:last-child
            padding: 8px
            background: #292929
            color: #fff
            border-radius: 6px
</style>