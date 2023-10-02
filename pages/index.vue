<template>
  <div class="all">
    <LineSvgFirstSvg class="first-svg"/>
    <Myheader/>
   <Aboutatheer/>
   <Advertise/>
   <Management/>
   <Ahmed/>
   <Khaled/>
   <Sucsessparteners/>
   <United/>
<Footer/>
  </div>
  
</template>

<script>
import Myheader from '~/components/myheader.vue';

export default {
    setup() {
        return {};
    },
    components: { Myheader }
}
</script>

<style lang="scss" scoped>
html{
  scroll-behavior: smooth;
}
.all{
  position: relative;
  .first-svg{
        position: absolute;
    right: 0;
    top: 12%;

  }
}
</style>