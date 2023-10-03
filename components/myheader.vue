<template>
    <div class="header">
<v-layout>
    <v-app-bar class="navbar" flat="" color="#FFFFF">
        <v-btn class="callus" color="#0654DC" variant="flat"><span class="callus-text">اتصل بنا  </span></v-btn>
        <span class="search-icon"></span> 
        <v-list :class="x.matches ? 'd-none' : 'd-flex'" class="header-list">
            <v-list-item href="#main" class="header-list-items">الرئيسية</v-list-item>
            <v-list-item href="#about" class="header-list-items">عن وثير</v-list-item>
            <v-list-item href="#advertis" class="header-list-items">المركز الاعلامى</v-list-item>
            <v-list-item href="#our-project" class="header-list-items">مشاريعنا</v-list-item>
            <v-list-item href="#our-subs" class="header-list-items">قطاعتنا</v-list-item>
            <v-list-item href="#services" class="header-list-items">خدماتنا</v-list-item>
            <v-list-item href="#joinus" class="header-list-items">انضم الينا</v-list-item>
            
        </v-list> 
        <div :class="x.matches ? 'd-none' : 'd-flex'" class="img">
<svg width="69" height="49" viewBox="0 0 69 49" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M37.1242 49H31.4513C29.9849 32.3578 16.401 20.0788 0 18.6887V13.2829C19.2953 13.2829 37.1242 29.4618 37.1242 49Z" fill="#1C355C"/>
<path d="M23 49H17.3658C16.9799 40.0418 9.4547 32.7825 0 32.2805V27.3767C12.4262 27.3767 23.3087 37.3389 23 49Z" fill="#1C355C"/>
<path d="M51.4413 49H45.7684C45.7298 25.2143 25.9329 5.17415 0.0385742 5.28999V0C32.5705 0 51.4413 21.5461 51.4413 49Z" fill="#1C355C"/>
<path d="M31.4514 49H37.5487C39.0151 32.3578 52.599 20.0788 68.9614 18.6887V13.2829C49.5503 13.2829 31.4514 29.8479 31.4514 49Z" fill="#1C95D3"/>
<path d="M45.8071 49H51.6728C52.0587 40.0418 59.5839 32.7825 69 32.2805V27.3767C56.6124 27.3767 45.8071 37.223 45.8071 49Z" fill="#1C95D3"/>
<path d="M17.3658 49H23.2316C23.3087 25.2143 43.1057 5.13554 69 5.28999V0C39.7097 0 17.3658 21.6619 17.3658 49Z" fill="#1C95D3"/>
</svg>
<span class="img-text">
    وثير للتطوير العقارى
</span>
        </div>      
<v-spacer></v-spacer>
<v-app-bar-nav-icon :class="x.matches ? 'd-inline-block' : 'd-none'" @click="drawer = !drawer" class="mt-11 pr-16"></v-app-bar-nav-icon>
    </v-app-bar>
    <v-navigation-drawer v-model="drawer" temporary="">
    <v-list class="drawer">
        <div class="d-flex mr-10" style="flex-wrap: wrap; width: 150px;justify-content: center;">
            <svg width="69" height="49" viewBox="0 0 69 49" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M37.1242 49H31.4513C29.9849 32.3578 16.401 20.0788 0 18.6887V13.2829C19.2953 13.2829 37.1242 29.4618 37.1242 49Z" fill="#1C355C"/>
<path d="M23 49H17.3658C16.9799 40.0418 9.4547 32.7825 0 32.2805V27.3767C12.4262 27.3767 23.3087 37.3389 23 49Z" fill="#1C355C"/>
<path d="M51.4413 49H45.7684C45.7298 25.2143 25.9329 5.17415 0.0385742 5.28999V0C32.5705 0 51.4413 21.5461 51.4413 49Z" fill="#1C355C"/>
<path d="M31.4514 49H37.5487C39.0151 32.3578 52.599 20.0788 68.9614 18.6887V13.2829C49.5503 13.2829 31.4514 29.8479 31.4514 49Z" fill="#1C95D3"/>
<path d="M45.8071 49H51.6728C52.0587 40.0418 59.5839 32.7825 69 32.2805V27.3767C56.6124 27.3767 45.8071 37.223 45.8071 49Z" fill="#1C95D3"/>
<path d="M17.3658 49H23.2316C23.3087 25.2143 43.1057 5.13554 69 5.28999V0C39.7097 0 17.3658 21.6619 17.3658 49Z" fill="#1C95D3"/>
</svg>
<span class="drawer-list">
    وثير للتطوير العقارى
</span>
        </div>  
        <v-list-item href="#main" class="drawer-list">الرئيسية</v-list-item>
        <v-list-item href="#about" class="drawer-list">عن وثير</v-list-item>
        <v-list-item href="#advertis" class="drawer-list">المركز الاعلامى</v-list-item>
        <v-list-item href="#our-project" class="drawer-list">مشاريعنا</v-list-item>
        <v-list-item href="#our-subs" class="drawer-list">قطاعتنا</v-list-item>
        <v-list-item href="#services" class="drawer-list">خدماتنا</v-list-item>
        <v-list-item href="#joinus" class="drawer-list">انضم الينا</v-list-item>
    </v-list>
    </v-navigation-drawer>
</v-layout>
    </div>
</template>

<script>
export default {
    data() {
    return{
    x:window.matchMedia("(max-width: 867px)"),
    drawer:false
         
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
.header{
    .navbar{
    height: 113px;
    position: relative;
}
.callus{
    width: 136px;
    height: 50px;
    margin-top:31px ;
    margin-left:8.5%;
    border-radius: 0;
    .callus-text{
       color: white;
        font-weight: 500;
        font-size: 100%;
        line-height: 28.8px;
       @include fonts()
       
    }
}
.search-icon{
    position: relative;
    border: 2px solid #0654DC;
    width: 19px;
    height: 19px;
    margin-top: 35px;
    margin-left: 5%;
    border-radius: 50%;
    &:hover{
        cursor: pointer;
    }
    &::before{
content: '';
position: absolute;
width: 2px;
height: 6px;
background-color: #0654DC;
rotate: -50deg;
right: -3px;
bottom: -2px;

    }
}
.header-list{
    width: 50vw;
    padding-right: 100px;
    flex-wrap: wrap;
    display: flex;
    font-weight: 700;
    margin-top: 35px;
    margin-left: 5%;
    font-size: 100%;
    overflow-x: hidden;
    direction: rtl;
    @include fonts();
.header-list-items{
    transition: 0.4s;
    cursor: pointer;
    &:hover{
        scale: 1.1;
        color: #0654DC;
    }
}    
}
.img{
    position: absolute;
    width: 160px;
    justify-content: center;
    flex-wrap: wrap;
 display: flex;
  margin-top: 50px;
  right: 82px;  
  .img-text{
    display: inline-block;
    @include fonts();
    font-size: 12px;
    font-weight: 700;
    
  }
}
.drawer{
    display: flex;
    width: 100%;
    flex-direction: column;
    align-items: end;
    margin-top: 50px;
    padding-right: 20px;
    .drawer-list{
        transition: 0.3s;
        cursor: pointer;
        &:hover{
            scale: 1.1;
            color: #0654DC;
        }
 font-weight: 700;
@include fonts();
    }
}
}
@media (max-width:1246px) 
{
    .header{
        .img{
            right: 60px;
        }
    }
}
@media (max-width: 1120px) {
    .header{
        .img{
            right: 45px;
        }
    }
}
@media (max-width: 977px) {
    .header{
        .img{
            right: 35px;
        }
    }
}
@media(max-width: 550px) {
    .header{
        .navbar{
            .callus{
                width: 100px;
                font-size: 12px;
            }
        }
    }
}

</style>