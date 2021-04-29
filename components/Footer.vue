<template>
<v-app id="app">
    <v-main>
        <v-sheet
        max-width="100%"
        max-height="100%"
        class="Footer-color"
        >
            <v-container>
                <v-row>
                    <v-col cols="12 py-15">
                        <v-row>
                            <v-col 
                            cols="4"
                            >
                            <p class="white--text text-lg-h5 text-md-h6 text-sm-h4 font-weight-light"><strong>Panday Digital</strong><br>
                                One Global Place,<br>
                                Level 10-1,<br>
                                25th street & 5th Avenue,<br>
                                Bonifacio Global City,<br>
                                Taguig City, 1632 Philippines</p>
                            </v-col>
                            <v-col 
                            cols="4"
                            >
                                <p class="white--text text-lg-h5 text-md-h6 text-sm-h4 font-weight-light">
                                    <b>Business Hours</b><br>
                                    Monday – Saturday<br>
                                    8:00AM – 8:00PM<br><br>

                                    +63 (977) 366-8544<br>
                                    info@digitalmarketingmanila.com
                                </p>
                            </v-col>
                            <v-col cols="4">
                                <p class="white--text text-lg-h5 text-md-h6 text-sm-h4 font-weight-light"><b>Connect to Us!</b></p>
                                    <v-row>
                                        <v-col cols="3">
                                        </v-col>
                                        <v-col cols="3">                             
                                        </v-col>
                                        <v-col cols="3">                                          
                                        </v-col>
                                        <v-col cols="12 d-flex">
                                            <v-img
                                            class="mr-2"
                                            :src="require(`~/assets/resources/fb.png`)"
                                            max-height="50px"
                                            max-width="50px"
                                            >
                                                
                                            </v-img>      
                                            <v-img
                                            class="mr-2"
                                            :src="require(`~/assets/resources/twitter.png`)"
                                            max-height="50px"
                                            max-width="50px"
                                            >

                                            </v-img>   
                                            <v-img
                                            class="mr-2"
                                            :src="require(`~/assets/resources/in.png`)"
                                            max-height="50px"
                                            max-width="50px"
                                            >
                                                
                                            </v-img>                                                                                                                                   
                                        </v-col>
                                    </v-row>
                            </v-col>
                        </v-row>
                    </v-col>
                    <v-col cols="12  pt-10">
                        <div class="container">
                            <v-row>
                                <v-col cols="3" class="center px-0"> 
                                    <p class="text-subtitle-2 white--text font-weight-light text-lg-h5 text-md-h6 text-sm-h4">©2021 Panday Digital. All Rights Reserved.</p>
                                </v-col>
                                <v-col cols="6 " class=" center"> 
                                    <div class="d-block text-center ma-auto">
                                        <h1>PANDAY DIGITAL</h1>
                                        <p class="white--text text-lg-h5 text-md-h6 text-sm-h4 font-weight-light">we build you digital pressence
                                        </p>
                                    </div>
                                </v-col>
                                <v-col cols="3" class="center"> 
                                    <span><NuxtLink to="/" class="white--text text-lg-h5 text-md-h6 text-sm-h4 font-weight-regular">Privacy Policy</NuxtLink ></span>
                                    <span class="text-lg-h5 text-md-h6 text-sm-h4 font-weight-regular">|</span>
                                    <span class="white--text text-lg-h5 text-md-h6 text-sm-h4 font-weight-regular"><NuxtLink to="/" class="white--text"
                                    
                                    >Terms & Conditions</NuxtLink ></span>
                                </v-col>                                        
                            </v-row>
                        </div>
                    </v-col>
                </v-row>
            </v-container>
        </v-sheet>
    </v-main>
</v-app>
</template>

<script>
export default {

}
</script>

<style>
.Footer-color.v-sheet {
    background-color: #1b75bb !important;
    border-color: #FFFFFF !important;
    color: rgb(255 255 255) !important;
}
#app .v-application--wrap{
    min-height: 100% !important;
    
}p {
    color:#FFFFFF;
}
</style>