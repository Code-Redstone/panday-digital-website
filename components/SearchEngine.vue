<template>
    <v-container>
        <v-row>
            <v-col class="Text-center"  cols="12" >
                <div class="div text-center">
                <h3 class="white--text font-weight-regular text-h5 mb-5">SEARCH ENGINE & SOCIAL MEDIA OPTIMIZATION</h3>
                <h2  class="white--text text-h3 font-weight-bold py-5"> Our Digital Marketing Services</h2>
                </div>
            </v-col>            
            <v-col class="text-center" cols="4" sm="12" md="6" lg="3" xl="3" v-for="digital in digital_services " :key="digital.id" >
                <v-card
                class="pa-11 Digital-Services Services-Font rounded-xl"
                outlined
                color="rgb(255 255 255 / 9%)"
                >
                <v-img
                    class="mb-2" 
                    :src="digital.img"
                    max-height="100%"
                    max-width="100%"
                ></v-img>
                <h3 class="mb-5 px-1 white--text text-center Services-Font text-xl-h4 text-lg-h6 text-md-h6 text-sm-h4 pt-5">{{digital.discription}}</h3>
                </v-card>
            </v-col>
        </v-row>
    </v-container>
</template>

<script>
export default {
    name:'SearchEngine',
    data() {
        return{
            digital_services: [
          {
            id: 1,
            img:'/_nuxt/assets/resources/web.png',
            discription:'WEBSITE DESIGN MANAGEMENT',
          },
          {
            id: 2,
            img:'/_nuxt/assets/resources/Ads.png',
            discription:'PAY PER CLICK ADVERTISING',
          },
          {
            id: 3,
            img:'/_nuxt/assets/resources/seo.png',
            discription:'SEARCH ENGINE OPTIMIZATION',
          },
          {
            id: 4,
            img:'/_nuxt/assets/resources/Socialmediamarketing.png',
            discription:'SOCIAL MEDIA MARKETING',
          },
        ],
        }
    }
}
</script>

<style>

</style>