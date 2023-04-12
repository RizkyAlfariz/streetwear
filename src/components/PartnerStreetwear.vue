<template>
  <!-- Partner Logo Section Begin -->
  <div class="partner-logo">
    <div class="container">
      <carousel class="logo-carousel" :items="5" :nav="false" :autoplay="true" :dots="false" :loop="true">
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/stoneisland-logo.png" alt="" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/cpcompany-logo.png" alt="" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/adidas-logo.png" alt="" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/marshalartist-logo.png" alt="" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/ellese-logo.png" alt="" />
          </div>
        </div>
      </carousel>
    </div>
  </div>
  <!-- Partner Logo Section End -->
</template>

<script>
import carousel from 'vue-owl-carousel';

export default {
    name: 'PartnerStreetwear',
    components: {
        carousel,
    }
    
};
</script>

<style>
.logo-item .tablecell-inner img {
    width: 50%;
    aspect-ratio: 5/2;
    object-fit: contain;
}
</style>