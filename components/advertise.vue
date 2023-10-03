<template>
    <div class="advertis">
        <v-container>
    <v-row>
        <!--start vision col-->
        <v-col xl="6" lg="6" md="6" sm="6" cols="12" >
            <v-card variant="flat" class="card" v-motion-roll-visible-top style="transition: 1.2s;">
                <div class="main-card">
                    <!--card head-->
                <div class="card-head">
                     <!--vison text-->
                     <span class="vision-text d-inline-block" id="about">
                        الرؤية
                    </span>
                  <!--vison text-->
                    <!--vision icon-->
                    <svg class="card-icon" width="42" height="19" viewBox="0 0 42 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M21.42 18.707H24.6237C25.3943 9.99055 32.5318 3.55939 41.1293 2.83133V0C30.9299 0 21.42 8.67601 21.42 18.707Z" fill="#0654DC"/>
                    <path d="M28.9629 18.707H32.045C32.2478 14.0151 36.2019 10.213 41.1495 9.95013V7.38171C34.6405 7.38171 28.9629 12.5388 28.9629 18.707Z" fill="#0654DC"/>
                    <path d="M19.7296 18.707H16.5258C15.7553 9.99055 8.61777 3.55939 0.0202751 2.83133V0C10.2197 0 19.7296 8.67601 19.7296 18.707Z" fill="#0654DC"/>
                    <path d="M12.1867 18.707H9.10454C8.90177 14.0151 4.94773 10.213 0.000114441 9.95013V7.38171C6.50907 7.38171 12.1867 12.5388 12.1867 18.707Z" fill="#0654DC"/>
                    </svg>
                      <!--vision icon-->
                   
                </div>
                <div class="card-body">
                    <div class="hr-parent">
                        <hr class="hr-child">

                    </div>
                <div class="card-body-text">
                    <p>
                        {{ data[0].vison }}
                    </p>
                
                </div>
                </div>
            </div>
            </v-card>
            
        </v-col>
        <!--end vision col-->

        <!--start about col-->
        
            <v-col xl="6" lg="6" md="6" sm="6" cols="12" >
            <v-card variant="flat" class="card" v-motion-roll-visible-right style="transition: 1.2s;">
                <div class="main-card">
                    <!--card head-->
                <div class="card-head">
                     <!--vison text-->
                     <span class="vision-text d-inline-block">
                        نبذة
                    </span>
                  <!--vison text-->
                    <!--vision icon-->
                    <svg class="card-icon" width="42" height="19" viewBox="0 0 42 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M21.42 18.707H24.6237C25.3943 9.99055 32.5318 3.55939 41.1293 2.83133V0C30.9299 0 21.42 8.67601 21.42 18.707Z" fill="#0654DC"/>
                    <path d="M28.9629 18.707H32.045C32.2478 14.0151 36.2019 10.213 41.1495 9.95013V7.38171C34.6405 7.38171 28.9629 12.5388 28.9629 18.707Z" fill="#0654DC"/>
                    <path d="M19.7296 18.707H16.5258C15.7553 9.99055 8.61777 3.55939 0.0202751 2.83133V0C10.2197 0 19.7296 8.67601 19.7296 18.707Z" fill="#0654DC"/>
                    <path d="M12.1867 18.707H9.10454C8.90177 14.0151 4.94773 10.213 0.000114441 9.95013V7.38171C6.50907 7.38171 12.1867 12.5388 12.1867 18.707Z" fill="#0654DC"/>
                    </svg>
                      <!--vision icon-->
                   
                </div>
                <div class="card-body">
                    <div class="hr-parent">
                        <hr class="hr-child">

                    </div>
                    <div class="card-body-text">
                    <p>
                        {{ data[1].about }}
                    </p>
                
                </div>
                </div>
            </div>
            </v-card>
            
        </v-col>
        <!--end about col-->
        <!--start bahavior col-->
        <v-col xl="6" lg="6" md="6" sm="6" cols="12" >
            <v-card variant="flat"  class="card" v-motion-roll-visible-left style="transition: 1.2s;">
                <div class="main-card">
                    <!--card head-->
                <div class="card-head">
                     <!--vison text-->
                     <span class="vision-text d-inline-block">
                        القيم
                    </span>
                  <!--vison text-->
                    <!--vision icon-->
                    <svg class="card-icon" width="42" height="19" viewBox="0 0 42 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M21.42 18.707H24.6237C25.3943 9.99055 32.5318 3.55939 41.1293 2.83133V0C30.9299 0 21.42 8.67601 21.42 18.707Z" fill="#0654DC"/>
                    <path d="M28.9629 18.707H32.045C32.2478 14.0151 36.2019 10.213 41.1495 9.95013V7.38171C34.6405 7.38171 28.9629 12.5388 28.9629 18.707Z" fill="#0654DC"/>
                    <path d="M19.7296 18.707H16.5258C15.7553 9.99055 8.61777 3.55939 0.0202751 2.83133V0C10.2197 0 19.7296 8.67601 19.7296 18.707Z" fill="#0654DC"/>
                    <path d="M12.1867 18.707H9.10454C8.90177 14.0151 4.94773 10.213 0.000114441 9.95013V7.38171C6.50907 7.38171 12.1867 12.5388 12.1867 18.707Z" fill="#0654DC"/>
                    </svg>
                      <!--vision icon-->
                   
                </div>
                <div class="card-body">
                    <div class="hr-parent">
                        <hr class="hr-child">

                    </div>
                    <div class="card-body-text">
                    <p>
                        {{ data[2].behavior }}
                    </p>
                
                </div>
                </div>
            </div>
            </v-card>
            

        </v-col>
        <!--end bahavior col-->
        <!--start goals col-->
        <v-col xl="6" lg="6" md="6" sm="6" cols="12" >
            <v-card variant="flat" class="card" v-motion-roll-visible-bottom style="transition: 1.2s;">
                <div class="main-card">
                    <!--card head-->
                <div class="card-head">
                     <!--vison text-->
                     <span class="vision-text d-inline-block">
                        الأهداف
                    </span>
                  <!--vison text-->
                    <!--vision icon-->
                    <svg class="card-icon" width="42" height="19" viewBox="0 0 42 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M21.42 18.707H24.6237C25.3943 9.99055 32.5318 3.55939 41.1293 2.83133V0C30.9299 0 21.42 8.67601 21.42 18.707Z" fill="#0654DC"/>
                    <path d="M28.9629 18.707H32.045C32.2478 14.0151 36.2019 10.213 41.1495 9.95013V7.38171C34.6405 7.38171 28.9629 12.5388 28.9629 18.707Z" fill="#0654DC"/>
                    <path d="M19.7296 18.707H16.5258C15.7553 9.99055 8.61777 3.55939 0.0202751 2.83133V0C10.2197 0 19.7296 8.67601 19.7296 18.707Z" fill="#0654DC"/>
                    <path d="M12.1867 18.707H9.10454C8.90177 14.0151 4.94773 10.213 0.000114441 9.95013V7.38171C6.50907 7.38171 12.1867 12.5388 12.1867 18.707Z" fill="#0654DC"/>
                    </svg>
                      <!--vision icon-->
                   
                </div>
                <div class="card-body">

                    <div class="hr-parent">
                        <hr class="hr-child">

                    </div>
                    <div class="card-body-text">
                    <p>
                        {{ data[3].goals }}
                    </p>
                
                </div>
                </div>
            </div>
            </v-card>
        </v-col>
        <!--end goals col-->
    </v-row>
   </v-container>
    </div>
  
</template>

<script>
    export default {
        data(){
            return{
                data:[{
                    vison:'نسعى في وثير للعقارات أن نكون رائدين في تحقيق التميز في صناعة التطوير العقاري والإنشاءات. نطمح إلى بناء مستقبل مبهرج يجمع بين الابتكار والجودة والاستدامة. رؤيتنا هي خلق مشاريع عقارية استثنائية تلهم الحياة وتعزز البيئات الحضرية. '
                },
                {
                    about:'شركة وثير للعقارات هي إحدى الشركات الرائدة في مجال التطوير العقاري والإنشاءات، وهي تتخذ من الخليج العربي مقرًا لها. تعمل الشركة على تحقيق مشاريع عقارية متميزة تجمع بين الجودة العالية والتصميم المبتكر، مما يجعلها تستحق مكانة مميزة في صناعة العقارات.'
                },
                {
                    behavior:'نسعى في وثير للعقارات أن نكون رائدين في تحقيق التميز في صناعة التطوير العقاري والإنشاءات. نطمح إلى بناء مستقبل مبهرج يجمع بين الابتكار والجودة والاستدامة. رؤيتنا هي خلق مشاريع عقارية استثنائية تلهم الحياة وتعزز البيئات الحضرية. '
                },
                {
                    goals:'في وثير للعقارات، نتطلع إلى تحقيق تميز رائد في مجال التطوير العقاري والإنشاءات. نسعى جاهدين لتقديم تصميمات وحلول إبداعية تلبي تطلعات واحتياجات عملائنا، مع الالتزام الدائم بأعلى مستويات الجودة والتفوق في تنفيذ مشاريعنا. نؤمن بأهمية الاستدامة والمسؤولية الاجتماعية.'
                },
            ]
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

.advertis{
    max-width: 100% !important;
    overflow-x: hidden !important;
    overflow-y: hidden;
    .card{
        width: 100%;
        height: 323px;
    .main-card{
        .card-head{
            display: flex;
            justify-content: flex-end;
            padding-right:50px ;
            padding-top: 20px;
           span{
            @include fonts();
            margin-right: 10px;
            font-weight: 700;
            font-size: 200%;
           }
           .card-icon{
            margin-top: 15px;
           }
        }
        .card-body{
.hr-parent{
    display: flex;
    justify-content: center;
    .hr-child{
        display: inline-block;
        width: 80%;
        margin-top: 15px;

    }
}
            .card-body-text{
                display: flex;
                justify-content: center;
                text-align: right;
                 
                p{
                @include fonts();
                margin-top: 20px;
                display: inline-block;
                width: 80%;
                font-size: 102%;
                font-weight: 400;
                direction: rtl;
                color: #8F8F8F;
                right: 74px;
               
                }
                
            }
        }
    }
}
}

</style>