<template>
  <div class="all">
    <LineSvgFirstSvg class="first-svg"/>
    <LineSvgSecondSvg class="second-svg"/>
    <LineSvgThirdSvg class="third-svg"/>
    <Myheader/>
   <Aboutatheer/>
   <Advertise/>
   <Management/>
   <Ahmed/>
   <Khaled/>
   <Sucsessparteners/>
   <United/>
<Footer/>
<Callus/>
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

<style lang="scss">
html{
  scroll-behavior: smooth !important;
}
body{
  overflow-x: hidden;
}
.all{
  max-width: 100% !important;
  overflow-x: hidden !important;
  position: relative;
  .first-svg{
        position: absolute;
    right: 0;
    top: 10%;

  }
  .second-svg{
    position: absolute;
    left: -60px;
    top:40%;
  }
  .third-svg{
    position: absolute;
    right: -3px;
    top:78%;
    
  }
}
</style>