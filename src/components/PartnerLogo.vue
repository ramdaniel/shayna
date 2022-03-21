<template>
   <!-- Partner Logo Section Begin -->
    <section class="partner-logo">
        <div class="container">
            <carousel class="logo-carousel" :loop="true" :autoplay="true" :items="5" :dots="false" :nav="false">
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/logo-carousel/logo-1.png" alt="" />
                    </div>
                </div>
                
            </carousel>
                    </div>
    </section>
    <!-- Partner Logo Section End -->
</template>

<script>
import carousel from 'vue-owl-carousel'
export default {
    name:'PartnerLogo',
    component: {
        carousel
    }
}
</script>
<style scoped>

</style>