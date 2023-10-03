<template>
  <div class="about-atheer h-screen" id="main">
    <v-row>
    <v-col  :cols="x.matches ? '12' : '7'">
<div class="atheer-img" v-motion-pop style="transition: 1s;">
  <svg width="25%" class="atheer-img-svg" height="126" viewBox="0 0 132 126" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M36.7387 125.735H51.2953C55.0582 83.0307 89.9147 51.5227 132 47.9558V34.0843C82.4879 34.0843 36.7387 75.5996 36.7387 125.735Z" fill="#0654DC"/>
<path d="M72.9816 125.735H87.4391C88.4294 102.748 107.739 84.1208 132 82.8327V70.2493C100.114 70.2493 72.1894 95.8124 72.9816 125.735Z" fill="#0654DC"/>
<path d="M-0.000198364 125.735H14.5564C14.6554 64.7005 65.4548 13.277 131.9 13.5742V0C48.4226 0 -0.000198364 55.2877 -0.000198364 125.735Z" fill="#0654DC"/>
</svg>

</div>
    </v-col>
    <v-col :cols="x.matches ? '12' : '4'">
        <div class="mt-60 w-100 d-block about-atheer-text" style="position: relative;transition: 1s;" v-motion-slide-right >
           <div class="about-atheer-text1">
            <span class="main">   الرئيسية /  </span>
             &nbsp;
            <span class="about">عن وثير</span>
          </div>
          <hr style="position: absolute; top: -50px; right: -20px; width: 140%;"/>            
           <div class="about-atheer-text2">
            <div class="about-atheer-text2-svg">
              <svg width="87" height="19" viewBox="0 0 87 19" fill="none" xmlns="http://www.w3.org/2000/svg">
<line x1="87" y1="10.5" x2="61" y2="10.5" stroke="#0654DC"/>
<path d="M7.91125 12.36V14H5.43125C5.43125 15.0933 5.13792 15.9333 4.55125 16.52C3.96458 17.1067 3.13792 17.4 2.07125 17.4C1.43125 17.4 0.937917 17.3467 0.59125 17.24L1.11125 15.72H1.55125C2.93792 15.72 3.63125 15.1333 3.63125 13.96V7.96C3.63125 7.69333 3.75125 7.49333 3.99125 7.36L5.43125 6.88V12.36H7.91125ZM13.8756 12.36V14H7.11563V12.36H9.63562L9.59562 7.56C9.59562 7.26667 9.75562 7.05333 10.0756 6.92L11.5156 6.32V12.36H13.8756ZM9.91562 17.16C9.91562 17.2667 9.88896 17.32 9.83562 17.32H8.15562C8.10229 17.32 8.07563 17.2667 8.07563 17.16V15.52C8.07563 15.4667 8.10229 15.44 8.15562 15.44H9.83562C9.88896 15.44 9.91562 15.4667 9.91562 15.52V17.16ZM12.4756 17.16C12.4756 17.2667 12.449 17.32 12.3956 17.32H10.7156C10.6623 17.32 10.6356 17.2667 10.6356 17.16V15.52C10.6356 15.4667 10.6623 15.44 10.7156 15.44H12.3956C12.449 15.44 12.4756 15.4667 12.4756 15.52V17.16ZM13.0688 12.36H15.5887L15.5487 7.56C15.5487 7.26667 15.7087 7.05333 16.0287 6.92L17.4688 6.32V14H13.0688V12.36ZM15.1087 2.56C15.0021 2.56 14.9488 2.53333 14.9488 2.48V0.8C14.9488 0.746667 15.0021 0.72 15.1087 0.72H16.7487C16.8021 0.72 16.8287 0.746667 16.8287 0.8V2.48C16.8287 2.53333 16.8021 2.56 16.7487 2.56H15.1087ZM15.5487 5.08C15.5487 5.18667 15.5221 5.24 15.4688 5.24H13.7887C13.7354 5.24 13.7087 5.18667 13.7087 5.08V3.44C13.7087 3.38667 13.7354 3.36 13.7887 3.36H15.4688C15.5221 3.36 15.5487 3.38667 15.5487 3.44V5.08ZM18.1087 5.08C18.1087 5.18667 18.0821 5.24 18.0287 5.24H16.3487C16.2954 5.24 16.2687 5.18667 16.2687 5.08V3.44C16.2687 3.38667 16.2954 3.36 16.3487 3.36H18.0287C18.0821 3.36 18.1087 3.38667 18.1087 3.44V5.08ZM25.6256 6.6V14.04C25.6256 15.1067 25.3323 15.9333 24.7456 16.52C24.159 17.1067 23.3323 17.4 22.2656 17.4C21.6256 17.4 21.1323 17.3467 20.7856 17.24L21.3056 15.72H21.7456C23.079 15.72 23.7723 15.1467 23.8256 14H22.4656C21.3456 14 20.5056 13.6133 19.9456 12.84C19.3856 12.2 19.1056 11.36 19.1056 10.32C19.1056 9.25333 19.3856 8.38667 19.9456 7.72C20.239 7.34667 20.599 7.06667 21.0256 6.88C21.479 6.66667 21.959 6.56 22.4656 6.56L25.6256 6.6ZM23.8256 8.28H22.4656C21.959 8.28 21.5723 8.48 21.3056 8.88C21.0123 9.33333 20.8656 9.81333 20.8656 10.32C20.8656 10.9067 21.0123 11.4 21.3056 11.8C21.6256 12.1733 22.0123 12.36 22.4656 12.36H23.8256V8.28ZM42.7075 14H39.7875C39.7342 14.8533 39.6275 15.5333 39.4675 16.04C39.3075 16.5733 39.0408 17.0133 38.6675 17.36C38.3208 17.7333 37.8408 18.0133 37.2275 18.2C36.6142 18.3867 35.9475 18.48 35.2275 18.48C34.5075 18.48 33.8408 18.3733 33.2275 18.16C32.6142 17.9733 32.1208 17.68 31.7475 17.28C31.1075 16.56 30.7875 15.5333 30.7875 14.2C30.7875 13.08 31.0408 11.84 31.5475 10.48L33.2275 10.52C32.7475 11.6667 32.5075 12.88 32.5075 14.16C32.5075 15.1467 32.6808 15.8267 33.0275 16.2C33.1875 16.4133 33.4542 16.5733 33.8275 16.68C34.2008 16.8133 34.6142 16.88 35.0675 16.88C35.5208 16.88 35.9608 16.8133 36.3875 16.68C36.8142 16.5733 37.1342 16.4133 37.3475 16.2C37.5608 15.96 37.7075 15.6533 37.7875 15.28C37.8675 14.9067 37.9075 14.4133 37.9075 13.8L37.8675 12.44V10.32C37.8675 10.0267 38.0275 9.81333 38.3475 9.68L39.7875 9.08V11.08V12.36H42.7075V14ZM34.0675 8.28C33.9608 8.28 33.9075 8.25333 33.9075 8.2V6.52C33.9075 6.46667 33.9608 6.44 34.0675 6.44H35.7075C35.7608 6.44 35.7875 6.46667 35.7875 6.52V8.2C35.7875 8.25333 35.7608 8.28 35.7075 8.28H34.0675ZM41.9125 12.36H44.7125C44.3658 11.1333 44.1925 10.0667 44.1925 9.16C44.1925 8.22667 44.4058 7.53333 44.8325 7.08C45.2858 6.62667 45.9925 6.4 46.9525 6.4C47.6458 6.4 48.4725 6.52 49.4325 6.76L49.1525 8.52C48.2725 8.25333 47.5525 8.12 46.9925 8.12C46.2458 8.12 45.8725 8.44 45.8725 9.08C45.8725 9.53333 46.0458 10.2133 46.3925 11.12C46.5525 11.5467 46.7258 11.84 46.9125 12C47.1258 12.16 47.4325 12.2667 47.8325 12.32C48.2592 12.3467 49.0458 12.36 50.1925 12.36V14H41.9125V12.36Z" fill="#0654DC"/>
</svg>
</div>
  
<div class="about-atheer-text2-i">
  <p>
    تمثل وثير جوهر الإتقان العمراني بفضل تبنيها لمزايا التخطيط الحضري

  </p>
</div>
<div class="about-atheer-text2-ii">
  <p>
    تعكس وثير تجسيد الإتقان العمراني الذي ينبغي أن يتميز به أي مجتمع متقدم. من خلال اعتمادها لمزايا التخطيط الحضري، أصبحت وثير مدينة تتسم بتوازنٍ استدامي بين البنية التحتية المتطورة والبيئة المحيطة.
  </p>
</div>
           </div>
        </div>
       

    </v-col>
  </v-row>
  </div>
  
    
</template>

<script>

export default {
  data(){
    return{
      x: window.matchMedia("(max-width: 650px)")
    }
  }
  
}
</script>

<style lang="scss" scoped>
html{
  scroll-behavior: smooth;
}
@import url(https://db.onlinewebfonts.com/c/fd33d5c7a5d5f34c2a7e0fec0af20b8d?family=PNU+Medium);
@mixin fonts(){
    font-family: "PNU Medium";
    src: url("https://db.onlinewebfonts.com/t/fd33d5c7a5d5f34c2a7e0fec0af20b8d.eot");
    src: url("https://db.onlinewebfonts.com/t/fd33d5c7a5d5f34c2a7e0fec0af20b8d.eot?#iefix")format("embedded-opentype"),
    url("https://db.onlinewebfonts.com/t/fd33d5c7a5d5f34c2a7e0fec0af20b8d.woff2")format("woff2"),
    url("https://db.onlinewebfonts.com/t/fd33d5c7a5d5f34c2a7e0fec0af20b8d.woff")format("woff"),
    url("https://db.onlinewebfonts.com/t/fd33d5c7a5d5f34c2a7e0fec0af20b8d.ttf")format("truetype"),
    url("https://db.onlinewebfonts.com/t/fd33d5c7a5d5f34c2a7e0fec0af20b8d.svg#PNU Medium")format("svg");
    
}

body {
    overflow-x: hidden !important;
}
.about-atheer{
  .first-svg{
    position: absolute;
    background-color: red;
    right: 0;
}
max-width: 100% !important;
overflow-x: hidden !important;
  .atheer-img{
  width: 47vw;
  height: 80vh;
background: url(~/assets/img/aboutatheer.jpg);
background-size: 100% 100%;
background-attachment: scroll;
background-repeat: no-repeat;
image-rendering: crisp-edges;
 image-rendering: -moz-crisp-edges;          /* Firefox */
 image-rendering: -o-crisp-edges;            /* Opera */
 image-rendering: -webkit-optimize-contrast; /* Webkit (non-standard naming)*/
 -ms-interpolation-mode: nearest-neighbor;   /* IE (non-standard property) */
position: relative;
.atheer-img-svg{
  position: absolute;
  width: 132px;
  height: 125.74px;
  bottom: -30px;
  right: -40px;

}
 
}
  .about-atheer-text{
    .about-atheer-text1{
      @include fonts();
      position: absolute;
      right: -20px;
      top: -100px;
      .main{
        color: #8F8F8F;
        font-weight: 400;
        font-size: 14px;
      }
     .about{
      @include fonts();
      color: #1C95D3;
      font-size: 14px;
      font-weight: bold;
     }
    }
    .about-atheer-text2{
    position: relative;
    direction: rtl;
    }
    .about-atheer-text2-svg{
      position: absolute;
      top: 5px;
      right: -25px;
      
    }
    .about-atheer-text2-i{
      @include fonts();
position: absolute;
top: 50px;
right: -25px;
font-size: 210%;
font-weight: 700;

    }
    .about-atheer-text2-ii{
      @include fonts();
      position: absolute;
      color:#8F8F8F;
      top: 180px;
      font-weight: 400;
      right: -25px;
    }
  }
}
@media (max-width: 1378px) {
  .about-atheer-text{
    .about-atheer-text2-ii{
      top:225px !important;
    }
  }
}
@media (max-width:900px) {
  .about-atheer-text{
.about-atheer-text2-i{
  font-size: 150% !important;
}
.about-atheer-text2-ii{
  top: 190px !important;
}
  }
  
}
/************************ */
@media (max-width:650px) {
.about-atheer{
  height: fit-content !important;
  overflow-y: hidden !important;
  .atheer-img{
    width: 100%;
    background-size: 90% 100% !important;
    background-position: center center;
    .atheer-img-svg{
      width: 100px;
right: 10px;
    }
  }
  display: block;
  text-align: right;
  .about-atheer-text{
    display: inline-block !important;
   width: 70% !important;
   margin-right: 20px;
position: relative;
bottom: 100px;
right: 20px;
padding-bottom: 200px;   
  }
}
  
}
@media (max-width:450px) {
  .about-atheer{
    padding-bottom: 40px !important;
  }
  
}
@media (max-width:290px) {
  .about-atheer{
    padding-bottom: 50px !important;
  }
  
}
</style>