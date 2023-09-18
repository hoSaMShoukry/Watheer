<template>
    <div class="w-100 pt-16 corona-group text-center mt-3 mb-10" id="corona">
        <span class="d-inline-block pt-5 text-h4 font-weight-bold text-error" v-motion-pop-visible style="transition: 0.7s;">إحصائيات فيروس كورونا لعام 2023</span>
        <v-container>
          <v-row justify="center" class="mt-10">
                <v-col lg="4" xl="6" md="12" sm="12" cols="12">
        <Corona2/>
    </v-col>
    <div class="spacer px-20"></div>
    <v-col lg="5" xl="5" md="12" sm="12" cols="12">
        <Corona1/>
    </v-col>
          
    
   </v-row>
        </v-container>
       
    </div>
   
</template>
<style lang="scss" scoped>
.corona-group{
    image-rendering: crisp-edges;
 image-rendering: -moz-crisp-edges;          /* Firefox */
 image-rendering: -o-crisp-edges;            /* Opera */
 image-rendering: -webkit-optimize-contrast; /* Webkit (non-standard naming)*/
 -ms-interpolation-mode: nearest-neighbor;   /* IE (non-standard property) */
    background-image: url(https://img.freepik.com/free-vector/medical-background-with-abstract-virus-cells-global-pandemic_1048-12124.jpg);
    background-attachment:fixed;
  background-repeat: no-repeat;
  background-size: 100% 100%; 
  transition: 0.5s;
  -webkit-transition: 0.5s;
  -moz-transition: 0.5s;
  -ms-transition: 0.5s;
  -o-transition: 0.5s;
  height: 100%;
  width: 100%;
}
html{
  scroll-behavior: smooth;
}
</style>

