<template>
    <div class="ahmed">
               <v-container>
        <v-row justify="between">
            
            <v-col xl="4" lg="4" md="5" sm="6" cols="12">
                <div class="img" v-motion-roll-visible-left style="transition: 1.1s;">
                    <svg class="svg" width="116" height="111" viewBox="0 0 116 111" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M83.7145 110.494H70.9224C67.6156 72.9664 36.9841 45.2775 6.10352e-05 42.1429V29.9529C43.5107 29.9529 83.7145 66.436 83.7145 110.494Z" fill="#0654DC"/>
<path d="M51.8647 110.495H39.1596C38.2894 90.294 21.3203 73.9244 6.10352e-05 72.7925V61.7344C28.0209 61.7344 52.5609 84.1989 51.8647 110.495Z" fill="#0654DC"/>
<path d="M116 110.494H103.208C103.121 56.858 58.4788 11.6676 0.0875702 11.9289V0C73.4465 0 116 48.5861 116 110.494Z" fill="#0654DC"/>
</svg>


                </div>
            </v-col>
            <v-col xl="6" lg="6" md="6" sm="6" cols="12">
                <div class="text">
                    <div class="header-text">
                    <span v-motion-roll-visible-bottom style="transition: 1.1s;">
                        كلمة العضو المنتدب 
                    </span>
                </div>
                <div class="body-text" v-motion-roll-visible-top style="transition: 1.1s;">
                    <span>
                        من خلال رؤية استراتيجية وروح ريادية، يسعدني أن أرحب بكم في عالم وثير للعقارات. نحن هنا لنكون نقطة تحول في صناعة التطوير العقاري، ولنبني مجتمعات مستدامة ومبتكرة تتجاوز التوقعات.

                    </span>
                </div>
                <div class="footer-text">
                    <span v-motion-roll-visible-bottom style="transition: 1.1s;">
                        في وثير، نؤمن بقوة الابتكار والتفرد، ونسعى جاهدين لتحقيق أعلى مستويات الجودة في جميع جوانب عملنا. مع فريقنا المتميز من الخبراء والمهنيين، نعمل بتفاني وعزم لتحقيق نجاحات مستدامة وبناء علاقات تعتمد على الثقة والشفافية.
نحن نفخر بمساهمتنا في تشكيل مستقبل المدن وتحسين جودة الحياة للأجيال الحالية والمقبلة. إن الالتزام بالاستدامة والمسؤولية الاجتماعية جزء لا يتجزأ من هويتنا، ونعمل جاهدين لتحقيق توازن بين النجاح الاقتصادي وتحقيق الفائدة الاجتماعية.
شكرًا لكم على دعمكم وثقتكم، ومعًا سنستمر في تحقيق الإنجازات وخدمة المجتمع بأفضل طريقة ممكنة
                    </span>
                </div>
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
html{
  scroll-behavior: smooth !important;
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
   // align-items: center;
    max-width: 100% !important;
    overflow-x: hidden !important;
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

}

.img{
    display: flex;
    justify-content: center;
    position: relative;
    align-items: flex-end;
    background: url(assets/img/khaled2.jpg);
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
            margin-left:-20px !important ;
           width: 120%;
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
@media (max-width:1000px) {
    .ahmed{
        .text{
            width: 105%;
        }
    }
    
}
@media (max-width:960px) {
    .ahmed{
        height: fit-content !important;
        overflow-y: hidden;
        .text{
            width: 90%;
        }
        .img{
            margin-top: 75px;
            margin-left:20px !important;
           width: 90%;
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
@media (max-width:801px) {
    .ahmed{
        .img{
            margin-top: 75px;
            margin-left:50px ;
            padding-right: 50px;
           width: 95% !important;
           height: 75%;
                
       
        }
    }

    .text{
        margin-right: 600px;
       width: 110%;
       height: 100%;
    margin-bottom: 85px;
    }

}

@media (max-width:730px) {
    .ahmed{
        .img{
            margin: 100px;
            width: 100% !important;
            height: 70% !important;
            right: 15px;
        }
    }
    
}


@media (max-width: 660px) {
    .ahmed{
        height: fit-content;
        .img{
            height: 60% !important;
            margin-top: 150px;
        }
    }
    
}
@media (max-width:599px) {
    .ahmed{
        height: fit-content;
        justify-content: center;
        .text{
       width: 90vw !important;
    }
        .img{
            width: 80% !important;
            background-size: 100% 100%;
            background-position: center;
            height: 70vh !important;
            left: 3.5vw;
            top: -10vh;    
        }
    }
}
@media (max-width:500px) {
    .ahmed{
        .img{
            width: 80% !important;
             right: 1vw !important;
        }
    }
    
}
@media (max-width: 451px) {
    .ahmed{
        .img{
            width: 100%;
            height: 60vh !important;
            left: 4vw !important;
            background-size: 100% 100%;
        }
    }
    
}
@media (max-width:420px) {
    .ahmed{
        .img{
            right: 12vw;
        }
    }
    
}
@media (max-width:400px) {
    .ahmed{
        .img{
            right: 13vw;
        }
    }
    
}
@media (max-width:361px) {
    .ahmed{
        .img{
            width: 80vw !important;
            height: 50vh !important;
        left:1vw !important;
        }
    }
    
}
@media (max-width: 351px) {
    .ahmed{
        .img{
            height: 50vh !important;
            right: 15vw;
        }
    }
    
}
@media (max-width: 320px) {
    .ahmed{
        .img{
        
            right: 16vw;
        }
    }
    
}
@media (max-width: 301px) {
    .ahmed{
        .img{
            width: 82vw !important;
            height: 48vh !important;
            left: 1vw !important;
        }
    }
    
}
</style>