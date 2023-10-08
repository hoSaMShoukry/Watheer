<template>
    <div class="partenrs" id="our-subs">
<div class="success-partenrs">
    <div class="success-partenrs-header d-block text-center" v-motion-fade-visible style="transition: 1.1s;">
        <span class="d-inline-block">
            شركاء النجاح
            <svg class="svg-header" width="178" height="11" viewBox="0 0 178 11" fill="none" xmlns="http://www.w3.org/2000/svg">
        <rect width="178" height="11" fill="#1C95D3"/>
         </svg>
        </span>
    </div>
    <div class="success-partenrs-body">
   
        <v-row justify="center"> 
                <v-col xl="3" lg="2" md="2" sm="5" :cols="z.matches ? '12' : '6'"> 
                <div class="parent-svg" v-motion-slide-visible-bottom style="transition: 1.1s;">
                    <img src="~/assets/img/iscan.png" class="w-75 img" alt="">
                  <LineSvg :class="z.matches ? 'd-none' : ''"/>
                </div>               
            </v-col>
            <!--second-col-->
            <v-col xl="3" lg="2" md="2" sm="5" :cols="z.matches ? '12' : '6'"> 
                <div class="parent-svg" v-motion-slide-visible-top style="transition: 1.1s;">
                    <img src="~/assets/img/immar.png" :class="y.matches ? 'pl-5 w-75 img immar' : 'w-75 img immar'" alt="">
                    <LineSvg :class="x.matches ? 'd-none' : ''"/>
                </div>               
            </v-col>
            <!--third col-->
            <v-col xl="3" lg="2" md="2" sm="5" :cols="z.matches ? '12' : '6'"> 
                <div class="parent-svg" v-motion-slide-visible-right style="transition: 1.1s;">
                    <img src="~/assets/img/iqarat.png" class="w-75 img" alt="">
                    <LineSvg  :class="z.matches ? 'd-none' : ''"/>
                </div>               
            </v-col>
            <!--fourth col-->
            <v-col xl="3" lg="2" md="2" sm="5" :cols="z.matches ? '12' : '6'"> 
                <div class="parent-svg" v-motion-slide-visible-left style="transition: 1.1s;">
                    <img src="~/assets/img/iqarya.png" :class="y.matches ? 'pl-5 w-75 img iqarya' : 'w-75 img iqarya'">
                </div>               
            </v-col>
        </v-row>
     
       
      
    </div>
   


</div>
    </div>
</template>

<script>
import LineSvg from './lineSvg/line-svg.vue';

    export default {
        data(){
            return{
                x:window.matchMedia("(max-width:959px)"),
                y:window.matchMedia("(max-width:600px)"),
                z:window.matchMedia("(max-width:450px)"),
            }
        }
        ,
    components: { LineSvg }
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
.partenrs{
    width: 100%;
    max-width: 100% !important;
    overflow-x: hidden !important;
    overflow-y: hidden;
    height: fit-content;    
.success-partenrs{
    background-color: #0654DC;
    height: fit-content;
    .success-partenrs-header{
    padding-top: 10px;
    span{
@include fonts();
    padding-top: 20px;
color: #FFFFFF;
font-size: 200%;
font-weight: 500;

    }
.svg-header{
    position: relative;
    top: -15px;
    opacity: 0.7;
    z-index: -1;
}
}
.success-partenrs-body{
    margin-top: 50px;
    padding-bottom: 50px;
    .parent-svg{
        display: grid;
        grid-template-columns: auto auto;
        .img{
            margin-top: 25px;
        }
    }

}
}


}

@media (max-width:1170px) {
    .partenrs{
        .success-partenrs{
            .success-partenrs-body{
                .parent-svg{
                    .img{
                        margin-top: 29px;
                    }
                }
            }
        }
    }
    
}
@media (max-width:1100px) {
    .partenrs{
        .success-partenrs{
            .success-partenrs-body{
                .parent-svg{
                    .img{
                        margin-top: 35px;
                    }
                }
            }
        }
    }
    
}
@media (max-width:959px) {
    .partenrs{
        .success-partenrs{
            .success-partenrs-body{
                padding-left:16vw;
                .parent-svg{
                    .img{
                        margin-top: 18px;
                    }
                }
            }
        }
    }

    
}
@media (max-width:959px) {
    .partenrs{
        .success-partenrs{
            .success-partenrs-body{
                padding-left:16vw;
                .parent-svg{
                    .img{
                        margin-top: 18px;
                    }
                }
            }
        }
    }
}

@media (max-width:830px) {
    .partenrs{
        .success-partenrs{
            .success-partenrs-body{
                padding-left:13vw;
            }
        }
    }

    
}

@media (max-width:800px) {
    .partenrs{
        .success-partenrs{
            .success-partenrs-body{
                padding-left:10vw; 
            }
        }
    }
}

@media (max-width: 700px) {
    .partenrs{
        .success-partenrs{
            .success-partenrs-body{
                padding-left: 7vw;
            }
        }
    }
    
}

@media (max-width: 600px) {
    .partenrs{
        .success-partenrs{
            .success-partenrs-body{
                padding-left: 11vw;
                .parent-svg{
                    .img{
                        margin-top: 25px;
                    }
                }
            }
        }
    }
    
}

@media (max-width: 550px) {
    .partenrs{
        .success-partenrs{
            .success-partenrs-body{
                padding-left: 8vw;
                .parent-svg{
                    .img{
                        margin-top: 25px;
                        &.immar{
                            margin-top: 33px;
                        }
                    }
                }
            }
        }
    }
    
}

@media (max-width:450px) {

    .partenrs{
        .success-partenrs{
            .success-partenrs-body{
                padding-left: 30vw;
                overflow-y: hidden;
                .parent-svg{
                    .img{
                        margin-top: 25px;
                        &.immar{
                            margin-left: -15px;
                        }
                        &.iqarya{
                            margin-left: -15px;
                        }
                    }
                }
            }
        }
    }
    
}

</style>