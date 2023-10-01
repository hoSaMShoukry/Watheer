<template>
  <div class="all">
    <svg class="first-svg" width="453" height="431" viewBox="0 0 453 431" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M123.496 430.306H176.955C189.812 284.394 308.91 176.737 452.369 164.549V117.153C282.18 117.153 123.496 262.389 123.496 430.306Z" fill="url(#paint0_linear_1_240)"/>
<path d="M249.363 430.306H300.791C304.175 351.764 370.152 288.118 452.709 283.717V240.722C344.1 240.722 249.363 327.05 249.363 430.306Z" fill="url(#paint1_linear_1_240)"/>
<path d="M0 430.306H51.4286C52.1053 221.763 225.677 45.7202 452.707 47.0744V0.693909C195.903 0.693909 0 190.617 0 430.306Z" fill="url(#paint2_linear_1_240)"/>
<defs>
<linearGradient id="paint0_linear_1_240" x1="287.932" y1="117.153" x2="287.932" y2="430.306" gradientUnits="userSpaceOnUse">
<stop stop-color="#1C95D3" stop-opacity="0.04"/>
<stop offset="1" stop-color="white" stop-opacity="0"/>
</linearGradient>
<linearGradient id="paint1_linear_1_240" x1="351.036" y1="240.722" x2="351.036" y2="430.306" gradientUnits="userSpaceOnUse">
<stop stop-color="#1C95D3" stop-opacity="0.04"/>
<stop offset="1" stop-color="white" stop-opacity="0"/>
</linearGradient>
<linearGradient id="paint2_linear_1_240" x1="226.354" y1="0.693909" x2="226.354" y2="430.306" gradientUnits="userSpaceOnUse">
<stop stop-color="#1C95D3" stop-opacity="0.04"/>
<stop offset="1" stop-color="white" stop-opacity="0"/>
</linearGradient>
</defs>
</svg>
    <Myheader/>
   <Aboutatheer/>
   <Advertise/>
   <Management/>
   <Ahmed/>
   <Khaled/>
   <Sucsessparteners/>
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
    top: 40%;

  }
}
</style>