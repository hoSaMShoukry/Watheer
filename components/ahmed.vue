<template>
    <div class="ahmed">
               <v-container>
        <v-row justify="between">
            <v-col xl="6" lg="6" md="6" sm="6" cols="12">
                <div class="text">
                    <div class="header-text">
                    <span>
                        كلمة رئيس مجلس الإدارة
                    </span>
                </div>
                <div class="body-text">
                    <span>
                        مرحبًا بكم في عالم وثير للعقارات، حيث تتجسد رؤيتنا وتحقق أحلامنا. نحن هنا لنشق طريقًا جديدًا في صناعة التطوير العقاري، من خلال التميز والابتكار والالتزام بالجودة. 
في هذا الرحلة المثيرة، نحمل معنا فريقًا من الخبراء والمبدعين، الذين يمثلون عمق الخبرة والحماسة لدينا. بدعمهم وعزمهم، نطمح لبناء مشاريع لا تقل إثراءً عن قيمنا ومبادئنا. 
تجمعنا في وثير رؤية واحدة: تحويل الأحلام إلى واقع، وخلق بيئات تجمع بين الحداثة والاستدامة، وتلبي تطلعات الأجيال الحالية والمستقبلية. نحن نسعى ليس فقط لبناء مشاريع، بل لنصنع مستقبلًا أفضل.


                    </span>
                </div>
                <div class="footer-text">
                    <span>
                        أشكر كل من شارك في هذا الرحلة، من موظفينا وشركائنا وعملائنا. دعونا نعمل معًا نحو تحقيق النجاحات وصناعة تأثير إيجابي يمتد للأجيال القادمة.

                    </span>
                </div>
                </div>
              
            </v-col>
            <v-col xl="4" lg="4" md="5" sm="6" cols="12">
                <div class="img">
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
    width: 110%;
    height: 130%;
    position: relative;
    top: -40px;
    background-size: 100% 100%;
background-attachment: scroll;
background-repeat: no-repeat;
image-rendering: crisp-edges;
 image-rendering: -moz-crisp-edges;          /* Firefox */
 image-rendering: -o-crisp-edges;            /* Opera */
 image-rendering: -webkit-optimize-contrast; /* Webkit (non-standard naming)*/
 -ms-interpolation-mode: nearest-neighbor;   /* IE (non-standard property) */
 .svg{
    display: inline-block;
    position: absolute;
    bottom: -50px;
    
 }
}
}
@media (max-width:1279px) {
    .ahmed{
        .img{
            margin-top: 35px;
            margin-left:60px;
           width: 110%;
           height: 100%;
           

        }
    }

    .text{
       width: 100%;
       height: 100%;
    }
}

@media (max-width:1115px) {
    .ahmed{
        .img{
          
          margin-left: 30px;
           

        }
    }

   
}

@media (max-width:1279px) {
    .ahmed{
        .img{
            margin-top: 35px;
            margin-left:60px ;
           width: 90%;
           height: 115%;
           

        }
    }

    .text{
        margin-right: 600px;
       width: 110%;
       height: 100%;
       margin-top: 40px;
    }
}

@media (max-width:960px) {
    .ahmed{
        .img{
            margin-top: 35px;
            margin-left:50px ;
            padding-right: 50px;
           width: 80%;
           height: 90%;
                
       
        }
    }

    .text{
        margin-right: 600px;
       width: 110%;
       height: 100%;
    margin-bottom: 85px;
    }
    
}
@media (max-width:800px) {
    .ahmed{
        .img{
            margin-top: 75px;
            margin-left:50px ;
            padding-right: 50px;
           width: 80%;
           height: 80%;
                
       
        }
    }

    .text{
        margin-right: 600px;
       width: 110%;
       height: 100%;
    margin-bottom: 85px;
    }

}

@media (max-width:599px) {
    .ahmed{
        height: fit-content;
        justify-content: center;
        .text{
       max-width: 90vw;
    }
        .img{
            width: 90%;
            background-size: 70% 100%;
            background-position: center;
            height: 70vh;
            right: 2vw;
            top: -10vh;    
        }
    }
}
@media (max-width: 451px) {
    .ahmed{
        .img{
            width: 100%;
            background-size: 100% 100%;
            right: 11vw;
        }
    }
    
}
@media (max-width: 351px) {
    .ahmed{
        .img{
        
            right: 14vw;
        }
    }
    
}
@media (max-width: 301px) {
    .ahmed{
        .img{
        
            right: 16vw;
        }
    }
    
}
</style>