<template>
    <span id="advertis"></span>
    <div class="management mt-40">
     <div class="management-elements">
        <div class="management-header">
      <div class="management-seat">
        
        <span v-motion-slide-visible-right style="transition: 1.1s;">مجلس الإدارة</span>
      </div>
      <div class="management-description">
        <span v-motion-slide-visible-left style="transition: 1.1s;">
            يضمّ فريق الإدارة في وثير مجموعة متميزة من الخبراء، الذين يمثلون العامل الرئيسي وراء إنجازاتنا وتقدمنا.

        </span>
      </div>
        </div>
        <div class="management-body">
            <v-container>
             <v-row class="mt-10">
                <!--first col-->
                <v-col xl="3" lg="3" md="4" sm="4" :cols="x.matches ? '12' : '6'">
                   <v-card class="card" v-motion-slide-visible-left style="transition: 1.1s;">
                    <img src="~/assets/img/salem.jpg" alt="">
                   </v-card>
                   <div class="card-info">
                    <span>سالم الدوسرى</span>
                    <div class="card-info-icon">
                        <span class="mr-2 card-info-iconi">العضو المنتدب</span>
                        <span>
                       
                        <svg class="mt-2 card-info-iconii" width="11" height="10" viewBox="0 0 11 10" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M0.930664 9.54681H2.56566C2.95889 5.09851 6.60141 1.81647 10.989 1.44492V0C5.78392 0 0.930664 4.42765 0.930664 9.54681Z" fill="white"/>
                        <path d="M4.78009 9.54678H6.353C6.45648 7.15234 8.47436 5.21201 10.9993 5.07784V3.76709C7.67755 3.76709 4.78009 6.39891 4.78009 9.54678Z" fill="white"/>
                        </svg>

                        </span>
                       

                    </div>
                   </div>
                </v-col>
                <!--second col-->
                <v-col xl="3" lg="3" md="4" sm="4" :cols="x.matches ? '12' : '6'">
                    <v-card class="card" v-motion-slide-visible-right style="transition: 1.1s;">
                    <img src="~/assets/img/khaled.jpg" alt="">
                   </v-card>
                   <div class="card-info">
                    <span>خالد القحطانى</span>
                    <div class="card-info-icon">
                        <span class="mr-2 card-info-iconi">المستشار القانونى</span>
                        <span>
                       
                        <svg class="mt-2 card-info-iconii" width="11" height="10" viewBox="0 0 11 10" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M0.930664 9.54681H2.56566C2.95889 5.09851 6.60141 1.81647 10.989 1.44492V0C5.78392 0 0.930664 4.42765 0.930664 9.54681Z" fill="white"/>
                        <path d="M4.78009 9.54678H6.353C6.45648 7.15234 8.47436 5.21201 10.9993 5.07784V3.76709C7.67755 3.76709 4.78009 6.39891 4.78009 9.54678Z" fill="white"/>
                        </svg>

                        </span>
                       

                    </div>
                   </div>
                </v-col>
                <!--third col-->
                <v-col xl="3" lg="3" md="4" sm="4" :cols="x.matches ? '12' : '6'">
                    <v-card class="card" v-motion-slide-visible-bottom style="transition: 1.1s;">
                    <img src="~/assets/img/saeed.jpg" alt="">
                   </v-card>
                   <div class="card-info">
                    <span>سعيد الشمرى</span>
                    <div class="card-info-icon">
                        <span class="mr-2 card-info-iconi">نائب رئيس مجلس الإدارة</span>
                        <span>
                       
                        <svg class="mt-2 card-info-iconii" width="11" height="10" viewBox="0 0 11 10" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M0.930664 9.54681H2.56566C2.95889 5.09851 6.60141 1.81647 10.989 1.44492V0C5.78392 0 0.930664 4.42765 0.930664 9.54681Z" fill="white"/>
                        <path d="M4.78009 9.54678H6.353C6.45648 7.15234 8.47436 5.21201 10.9993 5.07784V3.76709C7.67755 3.76709 4.78009 6.39891 4.78009 9.54678Z" fill="white"/>
                        </svg>

                        </span>
                       

                    </div>
                   </div>
                </v-col>
                <!--fourth col-->
                <v-col xl="3" lg="3" md="4" sm="4" :cols="x.matches ? '12' : '6'">
                    <v-card class="card" v-motion-slide-visible-top style="transition: 1.1s;">
                    <img src="~/assets/img/ahmed.jpg" alt="">
                   </v-card>
                   <div class="card-info">
                    <span>أحمد الدوسرى</span>
                    <div class="card-info-icon">
                        <span class="mr-2 card-info-iconi">رئيس مجلس الإدارة</span>
                        <span>
                       
                        <svg class="mt-2 card-info-iconii" width="11" height="10" viewBox="0 0 11 10" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M0.930664 9.54681H2.56566C2.95889 5.09851 6.60141 1.81647 10.989 1.44492V0C5.78392 0 0.930664 4.42765 0.930664 9.54681Z" fill="white"/>
                        <path d="M4.78009 9.54678H6.353C6.45648 7.15234 8.47436 5.21201 10.9993 5.07784V3.76709C7.67755 3.76709 4.78009 6.39891 4.78009 9.54678Z" fill="white"/>
                        </svg>

                        </span>
                       

                    </div>
                   </div>
                </v-col>
             </v-row>
            </v-container>
            
        </div>
     </div>
    </div>
</template>

<script>
    export default {
        data(){
            return{
                x: window.matchMedia("(max-width: 400px)")

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
.management{
    background-color: #0654DC;
    height: fit-content;
    padding-bottom: 50px;
    .management-header{
        .management-seat{
            display: flex;
            justify-content: center;
            span{
                @include fonts();
                font-size: 200%;
                color: #ffff;
                direction: rtl;
                padding-top: 40px;
                font-weight: 700;
            }

        }
        .management-description{
            display: flex;
            justify-content: center;
            span{
                @include fonts();
                color: #ffff;
                display: inline-block;
                font-size: 120%;
                padding-top: 10px;
                font-weight: 400;
                direction: rtl;
                width: 40%;
                text-align: center;
                line-height: 40.2px;

            }
        }
    }
    .management-body{
        .card{
            height: 409px;
@include fonts();
img{
    width: 100%;
    height: 100%;
}
        }
        .card-info{
            @include fonts();
            display: block;
            justify-content: flex-end;
            span{
                @include fonts();
                font-size: 105%;
                display:block;
                text-align: right;
                color: #ffffff;
                font-weight: 500;
                font-size: 110%;
            }
            .card-info-icon{
                display: flex;
                justify-content: flex-end;
                flex-wrap: nowrap;
                width: 100%;
                .card-info-iconi , .card-info-iconii{
                    color: #ffffff;
                    font-weight: 500;
                    font-size: 90%;
                }
               
            }

        }
    }
}
@media (max-width:1080px) {
    .management{
        .management-header{
            .management-description{
                span{
                    width: 90%;

                }
            }
        }
    }
    
}
</style>