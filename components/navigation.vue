<template>
<div class="navigation">

<v-layout>
  <v-app-bar height="70" style="background-color: transparent;">
    <div class="parent-header w-100 h-100">
    <div class="skew-header">
      <v-app-bar-nav-icon @click="drawer = !drawer" color="white" width="large" :class="x.matches ? 'd-inline-block' : 'd-none'"  style="position: absolute;right: 0;"></v-app-bar-nav-icon>
      <v-list :class="x.matches ? 'd-none' : ''"  class="header-list">
        <v-list-item>
          <v-btn href="#main" class="list-btn" variant="text">
            <a href="#main" class="font-bold  text-h6 list-etem">الرئيسية</a>
            <v-icon></v-icon>
          </v-btn>
        </v-list-item>
        <v-list-item>
          <v-btn href="#corona" class="list-btn" variant="text">
            <a href="#corona" class="font-bold text-h6  list-etem">احصائيات كورونا</a>
            
            <v-icon></v-icon>
          </v-btn>
        </v-list-item>
        <v-list-item>
          <v-btn href="#deparments" class="list-btn" variant="text">
            <a href="#deparments" class="font-bold text-h6  list-etem">  الاقسام</a>
           
            <v-icon></v-icon>
          </v-btn>
        </v-list-item>
        <v-list-item>
          <v-btn href="#whous" class="list-btn" variant="text">
            <a href="#whous" class="font-bold text-h6  list-etem">من نحن</a>
            
            <v-icon></v-icon>
          </v-btn>
        </v-list-item>
        <v-list-item>
          <v-btn href="#callus" class="list-btn" variant="text">
            <a href="#callus" class="font-bold text-h6  list-etem"> اتصل بنا</a>
           
            <v-icon></v-icon>
          </v-btn>
        </v-list-item>
      </v-list>
    </div>
  </div>
  </v-app-bar>
  <!--start navigation drawer-->
  <v-navigation-drawer
   v-model="drawer" temporary=""
   image="https://e0.pxfuel.com/wallpapers/815/325/desktop-wallpaper-background-for-hospital-website-tip.jpg"
   >
   <v-list density="compact" nav>
            <v-list-item value="home" class="mt-10 text-black">
                <v-btn href="#main" class="font-weight-bold ml-10 nav-btn text-h6" width="150" color="error"  variant="flat" style="border-radius: 20px;">
                    <a href="#main" class="mr-2">الرئيسية</a>
                    <v-icon>mdi-home</v-icon>
                </v-btn>
            </v-list-item>
            <v-list-item value="corona" class="mt-5">
                <v-btn href="#corona" class="font-weight-bold ml-4 text-h6" color="red-darken-4" variant="flat" width="180" style="border-radius: 20px;">
                    <a href="#corona" class="mr-2">احصائيات كورونا </a>
                    <v-icon>mdi-virus</v-icon>
                </v-btn>
            </v-list-item>
            <v-list-item value="dpt" class="mt-5">
                <v-btn href="#deparments" class="font-weight-bold ml-10 text-h6" width="150" color="red-darken-4" variant="flat" style="border-radius: 20px;">
                    <a href="#deparments" class="mr-2">الاقسام </a>
                    <v-icon>mdi-diversify</v-icon>
                </v-btn>
            </v-list-item>
            <v-list-item value="about" class="mt-5">
                <v-btn href="#whous" class="font-weight-bold text-h6 ml-10" variant="flat" width="150" color="error" style="border-radius: 20px;">
                    <a href="#whous" class="mr-2">من نحن</a>
                    <v-icon>mdi-help-circle</v-icon>
                </v-btn>
            </v-list-item>
            <v-list-item value="callus" class="mt-5">
                <v-btn href="#callus" class="font-weight-bold ml-10 text-h6" color="red-darken-4" width="150" variant="flat" style="border-radius: 20px;">
                    <a href="#callus" class=" mr-2">اتصل بنا </a>
                    <v-icon>mdi-phone</v-icon>
                </v-btn>
            </v-list-item>
          </v-list>
   
  </v-navigation-drawer>
  <!--end navigation drawer-->
</v-layout>
 
  
 
  </div>
  
<div>

</div>
 
</template>

<script>

export default{
    data(){
      return{
        drawer:false,
        x:window.matchMedia("(max-width: 890px)"),
        drawer:false,
      }
    }
}
</script>

<style lang="scss" scoped>
.navigation{
 .parent-header{
  background-image: url(https://e0.pxfuel.com/wallpapers/815/325/desktop-wallpaper-background-for-hospital-website-tip.jpg);
  display: flex;
  padding: 15px;
  background-color: rgb(6, 6, 85);
  height: 70.9px;
  .skew-header {
    background: rgb(119, 7, 125);
    display: flex;
    justify-content: flex-end;
    top:10px;
    height : 50px;
    width : 80%;
    opacity: 0.6;
    margin : 10px auto;
    position: absolute;
    right: 0px;
    &:first-child:before{
      content:'';
    position: absolute;
    top:0;
    right:100%;
    width:0;
    height:0;
    border:25.6px solid rgb(119, 7, 125);
    border-top-color:transparent;
    border-left-color:transparent;
    }

    &::nth-child(2){
      &::after{
        height:0;
        position: absolute;
    top:0;
    left:100%;
    width:0;
    
    content:'';
    border:50px solid blue;
    border-bottom-color:transparent;
    border-right-color:transparent;
        
      }
    }
    .header-list{
      direction: rtl;
display: flex;
background-color: transparent;
color: white;
font-weight: bold;
 overflow: hidden;  
      .list-btn{
        transition: 0.5s;
       &:hover{
        scale: 1.1;
       
  a{
    color: rgb(0, 255, 30);
  }
       }
      }
      .list-etem{
        color: whitesmoke;
      }
      
}
    
}
 }
    
}
html {
  scroll-behavior: smooth;
}
</style>