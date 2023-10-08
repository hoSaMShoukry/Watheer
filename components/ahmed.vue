<template>
    <div class="ahmed" id="our-project">
               <v-container>
        <v-row justify="between">
            <v-col xl="6" lg="6" md="6" :sm="x.matches ? '12' : '6'" :cols="x.matches ? '12' : '6'">
                <div class="text">
                    <div class="header-text">
                    <span v-motion-slide-visible-right style="transition: 1.1s;">
                        كلمة رئيس مجلس الإدارة
                    </span>
                </div>
                <div class="body-text" v-motion-slide-visible-left style="transition: 1.1s;">
                    <span>
                        مرحبًا بكم في عالم وثير للعقارات، حيث تتجسد رؤيتنا وتحقق أحلامنا. نحن هنا لنشق طريقًا جديدًا في صناعة التطوير العقاري، من خلال التميز والابتكار والالتزام بالجودة. 
في هذا الرحلة المثيرة، نحمل معنا فريقًا من الخبراء والمبدعين، الذين يمثلون عمق الخبرة والحماسة لدينا. بدعمهم وعزمهم، نطمح لبناء مشاريع لا تقل إثراءً عن قيمنا ومبادئنا. 
تجمعنا في وثير رؤية واحدة: تحويل الأحلام إلى واقع، وخلق بيئات تجمع بين الحداثة والاستدامة، وتلبي تطلعات الأجيال الحالية والمستقبلية. نحن نسعى ليس فقط لبناء مشاريع، بل لنصنع مستقبلًا أفضل.


                    </span>
                </div>
                <div class="footer-text">
                    <span v-motion-slide-visible-top style="transition: 1.1s;">
                        أشكر كل من شارك في هذا الرحلة، من موظفينا وشركائنا وعملائنا. دعونا نعمل معًا نحو تحقيق النجاحات وصناعة تأثير إيجابي يمتد للأجيال القادمة.

                    </span>
                </div>
                </div>
              
            </v-col>
            <v-col :class="x.matches? 'd-block':''" xl="4" lg="4" md="5" :sm="x.matches ? '12' :'6'" cols="12">
                <div class="img" v-motion-roll-visible-top style="transition: 1.1s;">
                    <svg class="svg" width="116" height="111" viewBox="0 0 116 111" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M32.2856 110.494H45.0777C48.3845 72.9664 79.016 45.2775 116 42.1429V29.9529C72.4894 29.9529 32.2856 66.436 32.2856 110.494Z" fill="#0654DC"/>
                    <path d="M64.1354 110.495H76.8405C77.7107 90.294 94.6798 73.9244 116 72.7925V61.7344C87.9792 61.7344 63.4392 84.1989 64.1354 110.495Z" fill="#0654DC"/>
                    <path d="M0.000213623 110.494H12.7923C12.8793 56.858 57.5212 11.6676 115.912 11.9289V0C42.5536 0 0.000213623 48.5861 0.000213623 110.494Z" fill="#0654DC"/>
                    </svg>

                </div>
            </v-col>
        </v-row>
    </v-container>
    </div>
    
</template>

<script>
    export default {
        data(){
            return{
                x:window.matchMedia("(max-width:750px)")
            }
        }, 
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
.ahmed{
    display: flex;
    align-items: center;
    
    max-width: 100% !important;
overflow-x: hidden !important;
overflow-y: hidden !important;
height:100vh ;
    .header-text , .body-text , .footer-text{
    @include fonts();
}
.text{
    .header-text{
    width: 100%;
    display: flex;
    justify-content: flex-end;
    span{
        direction: rtl;
        font-weight: 500;
        font-size: 130%;
        padding-left: 15px;
        padding-right: 15px;
        padding-top: 5px;
        padding-bottom: 7px;
        display: inline-block;
        background-color:#1C355C;
        color: #ffffff;

    }

}
.body-text , .footer-text{
    color: #8F8F8F;
font-weight: 400;
line-height: 26.8px;
font-size: 16px;
display: flex;
justify-content: flex-end;
span{
    display: inline-block;
        text-align: right;
        direction: rtl;
}
}
.body-text{
    margin-top: 4vh;
}
.footer-text{
    margin-top: 5vh;
}
}

.img{
    display: flex;
    justify-content: center;
    position: relative;
    align-items: flex-end;
    background: url(assets/img/ahmed2.jpg);
    width: 100%;
    height: 100%;
   background-size: contain;
   background-attachment: scroll;
   background-repeat: no-repeat;
   background-position: center center;
   image-rendering: crisp-edges;
   image-rendering: -moz-crisp-edges;          /* Firefox */
   image-rendering: -o-crisp-edges;            /* Opera */
   image-rendering: -webkit-optimize-contrast; /* Webkit (non-standard naming)*/
   -ms-interpolation-mode: nearest-neighbor;   /* IE (non-standard property) */
   .svg{
   position: relative;
   top:50px;
}
 
}
}
@media (max-width:1910px) {
    .ahmed{
        .img{
        margin-top: 25px;
        .svg{
            top: 10;
        }
        }
    }
    
}
@media screen and (max-width:1279px) {
    .ahmed{
        .img{     
     .svg{
        top: 0;
     }   

        }
    }

   
}

@media (max-width:1115px) {
    .ahmed{
        .img{
          
          margin-left: 30px;
           

        }
    }

   

    }

    .text{
        margin-right: 600px;
       width: 110%;
       height: 100%;
       margin-top: 40px;
    }
@media (max-width:1000px) {
    .ahmed{
        .img{
            margin-left: 0px !important;
        }
    }
    
}

@media screen and (max-width:961px) {
    .ahmed{
        .img{
           // background-color: red;
            background-position: center bottom;
           bottom: 90px;
            margin-left:40px !important;
            padding-right: 50px;
           width: 90% !important;
           height: 90%;
           .svg{
    top: 30px;   
       width: 100px;
   }
        }
    }

    .text{
        margin-right: 600px;
       width: 110%;
       height: 100%;
    margin-bottom: 85px;
    }
   
    
}
@media (max-width:960px) {
    .ahmed{
        .img{
            bottom: 30px ;
            width: 90%;
           height: 90%; 
        }
    }
    
}
@media (max-width:949px) {
    .ahmed{
        .img{
            bottom: 50px;
        }
    }
    
}
@media (max-width:910px) {

     .ahmed{
        .img{
            bottom: 60px;
        }
     }


    
}
@media (max-width:870px) {
    .ahmed{
        .img{
            bottom: 100px;
        }
    }
    
}

@media screen and (max-width:836px) {
    .ahmed{
        .img{
           bottom: 90px;
        
        }
    }
    
}

@media (max-width:800px) {
    .ahmed{
        .img{
            bottom: 100px;
        }
    }
    
}
@media (max-width:750px) {
    .ahmed{
        height: fit-content;
        justify-content: center;
        .text{
       max-width: 90vw;
    }
        .img{
            top: -50px;
            max-width: 90vw !important;
            height: 60vh;
          //  background-color: red;
            background-size: contain;
            background-position: center bottom;
           
            .svg{

                top: 50px !important;
            }
        }
    }
}

@media (max-width:540px) {
    .ahmed{
        .img{
            max-width: 75vw !important;
            
        }
    }
    
}
@media (max-width:450px) {
    .ahmed{
        .img{
        top: -140px !important;
            .svg{
                max-width: 80px;
            }
        }
    }
    
}
@media (max-width:400px) {
    .ahmed{
        .text{
            .body-text , .footer-text{
                font-size: 14px;
            }
        }
        .img{
            top: -200px !important;
            max-width:70vw !important ;
            .svg{
                max-width: 70px;
            }
        }
    }
    
}


@media (max-width:350px) {
    .ahmed{
        .text{
            .header-text{
                font-size: 13px;
            }
            .body-text , .footer-text{
                font-size: 12px;
            }
        }
        .img{
            top: -250px !important;
            max-width:67vw !important ;
            .svg{
                max-width: 50px;
            }
        }
    }
    
}

</style>