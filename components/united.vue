<template>
    <div class="united">
        <div class="content">
            <div class="left-side">
                <span class="left-side-text">
                    تكمن قوة التحالفات في توحيد الجهود والخبرات لتحقيق أهداف مشتركة. وفي هذا الإطار، نحرص في وثير للعقارات على بناء شراكات استراتيجية مع جهات متميزة لتعزيز توجهاتنا وتحقيق تطلعاتنا. تلك التحالفات تسهم في تعزيز مدى تأثيرنا وتوسيع نطاق عملنا.

                </span>
            </div>
            <div class="right-side">
                <span class="right-side-text">
                    التحالفات
                </span>
            </div>
        </div>

        <!------->

        <v-container>
            <v-row class="mt-10" style="height: fit-content;">
                <!-- col1 -->
            <v-col class="d-flex" xl="2" lg="2" md="4" sm="6" cols="6">
                <img src="~/assets/img/naga.jpg" class="w-100" alt="">
            </v-col>
                <!-- col1 -->
            <v-col class="d-flex" xl="2" lg="2" md="4" sm="6" cols="6">
              <img src="~/assets/img/asayl.png"  class="w-100"  alt="">
            </v-col>
            <!-- col2 -->
            <v-col class="d-flex" xl="2" lg="2" md="4" sm="6" cols="6">
                <img src="~/assets/img/roshen.png" class="w-100"  alt="">
            </v-col>
            <!-- col3 -->
            <v-col class="d-flex" xl="2" lg="2" md="4" sm="6" cols="6">
                <img src="~/assets/img/wafy.png" class="w-100" alt="">
            </v-col>
            <!-- col4 -->
            <v-col class="d-flex" xl="2" lg="2" md="4" sm="6" cols="6">
                <img src="~/assets/img/sheaon.png" class="w-100" alt="">

            </v-col>
            <!-- col5 -->
            <v-col class="d-flex" xl="2" lg="2" md="4" sm="6" cols="6">
                <img src="~/assets/img/watana.png" class="w-100" alt="">

            </v-col>
            
            </v-row>
        </v-container>
    </div>
</template>

<script>
    export default {
        data(){
            return{
                x:window.matchMedia("(max-width:1425px)"),
            }
        }
        
    }
</script>

<style lang="scss" scoped>
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
.united{
    overflow-x: hidden !important;
    overflow-y: hidden !important;
    max-width: 100% !important;
    background-color: whitesmoke;
    height: fit-content;
    .content{
        padding: 0 11% 0 10%;
        margin-top: 15%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
        height: fit-content;
        .left-side{
            width: 40%;
            @include fonts();
            text-align: right;
            direction: rtl;
            font-weight: 400;
            color:#8F8F8F;
            span{
                position: relative;
                &::before{
                    content: '';
                    width: 2px;
                    height: 100%;
                    position: absolute;
                    background-color:#1C95D3;
                    right: -15px
;
                }
            }
        }
        .right-side{
            width: 40%;
            height: 100%;
            text-align: right;
            direction: rtl;
            @include fonts();
            font-weight: 700;
            font-size: 200%;
            
        }
    }

}
@media (max-width:450px) {

    .united{

        .content{
        flex-wrap: wrap;
        flex-direction: column-reverse;
        .left-side , .right-side{
            display: flex;
            width: 100%;
            justify-content: center;
            align-items: center;
        }
        .right-side{
            margin-bottom: 50px;
        }
        
    }

    }
  
    
}
</style>